# returnCombinationsBacktracking
A backtracking algorithm that returns all the possible combinations of given elements with an optional parameter for the depth of the tree, i.e. the amount of elements that
can be chained together. 

For example: 
In the function "init" at the bottom of the file, you could enter the array [1,2,3] and give init the depth 2. The algorithm then would return:
0: (2) [2, 1]
1: (2) [3, 1]
2: (2) [1, 2]
3: (2) [3, 2]
4: (2) [1, 3]

Notice that the order matters: [2,1] !== [1,2]

If you do not provide a value for the maximum amount of combined elements, all possible combinations will be returned. 

Please note:
This script does not come with a UI. Changes need to be done in the actual TypeScript file. The outcome will be written to console once you've compiled the TypeScript and 
opened the index.html file. Alternatively, after compiling, you could just run the script with 'node js.js'.

