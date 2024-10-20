# Must do patterns before starting with DSA, why?

  - Solving pattern problems helps us to improve our understanding of how loop works, it gives us more control over loops.
  - To get any value from a data structure we need to know how to traverse in a structure whether it's Array, Linked-List, BST, Graphs or dynamic-programming and for that we use loops.
  - It helps in building-up logical thinking and enforce to think critically.
  - Pattern based questions are not often asked by companies until less it is either service based like TCS or product based like Amazon or Flipkart.
  - Patterns based problems plays a significant role in order master Data Structures & Algorithms.

# There are 4 major steps which helps to solve most of the pattern problems.
  Before discussing that, keep in mind drawing a pattern will always need nested loops.

  - Step 1: Focus on the vertical lines a.k.a rows and count the number lines, this will decide the number of iterations the of outer loop.
  - Step 2: Focus on the horizontal lines a.k.a columns count the number lines, this will decide the number of iteration of inner loop, now connect them somehow to the rows.
  - Step 3: Whatever pattern we want to print like symbols '*', letters 'a,b,c,d' or numbers '1,2,3', print them inside the inner loop.
  - # This will not always the case (optional).
  - Step 4: Observe the symmetry (shape) for certain patterns.

# Using these rules, first solve them on a paper and dry run your solve.
  - ## Let's try to a solve basic pattern.
  >> >> `* * * *`  
  >> >> `* * * *`  
  >> >> `* * * *`  
  >> >> `* * * *`  

  - ## Now first focus on the number vertical lines .e.i rows, count them this will help to identify iteration of the outer loop.  
   0. [`* * * *`]  
   1. [`* * * *`]  
   2. [`* * * *`]  
   3. [`* * * *`]  

  - ## So on the above pattern we can see that there are 4 rows and 4 columns in every row.
  >> - ### This means our outer should run 4 times and for each row the inner loop will also run for 4 times