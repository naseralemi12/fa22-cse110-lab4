1. line 12 will print 3. since i is declared using val, its scope extends outside the for block and after the for loop ends, its value will be the value of the last i at the last iteration.
2. line 13 will print 150. since discountedPrice is declared inside for loop block with var. its scope extends outside the for block and after the for loop ends, its value will be 150 as in the last iteration 300 * (1 - 0.5) = 150.
3. line 14 will print 150. since is declared withing the block of the function so it is also accessable inside the loop and after the loop because its declared withv var.
4. the funtion returns the array of discounted which has 50,100,150 as its elements.
5. line 12 doesnt print anything because i has scope within the for loop block becuase its declared with let.
6. it will cause an error becuase discountedPrince is scoped within the for loop block only because its declared with let.
7. line 14 will print 150. finalprice is declared wiht let outside the for loop block and so when its updated inside the for loop block it keeps the updated data even after the loop block.
8. it will return the array discounted with elements 50,100,150. the scope of the array is the whole function when its updated inside the for loop block, it keeps the updated data even after the loop block.
9. line 11 wont print anything because i has scope within the the for loop not the whole function.
10. 3 will bd printed. we havent changed the value of length since declaration so no error will be generated.
11. the array of discounted with elements 50,100,150 will be returned. const doesnt make its elements unchangable so the elements have been comfortablely changed by the function before return.
12. A. student.name
    B. student['grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]
13. A. '32' since integers map to their exact string representation
    B. 