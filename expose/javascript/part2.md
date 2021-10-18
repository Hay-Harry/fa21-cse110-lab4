1. 3 will be printed. Var is function scope, so when the for loop end, var contain prices.length, which is 3
2. 150 will be printed. discountedPrice is var and within its function scope, so it will contain the result of line 7, which is 150 when loop ended
3. 150 will be printed. finalPrice is var and within its function scope, so it will contain the result of line 8, which is 150 when loop ended
4. [50,100,150] ,discounted is an array that contain all finalPrice
5. error. At line 12, let i is out of its block scope. 
6. error. At line 13, let discountedPrice is out of its block scope. 
7. 150 will be printed. At line 14, let finalPrice is within its block scope
8. [50,100,150] , let discounted is an array that contain the finalPrice of each items and it is within its block scope.
9. error. let i is out of its block scope
10. 3 if the code didn't stop at line 7 for trying to change the a const. Const has block scope, so line 12 is within its scope.
11. If the code didn't stop at line 7 for error of changing a const, the code will return an empty array.
12. 
A. student['name'];\
B. student['Grad Year'];\
C. student.greeting();\
D. student['Favorite Teacher']['name'];\
E. student['courseLoad'][0];\
13.  
A. '32' ;integer map to string, so '3' + '2'\
B. 1 ;string map to integer, 3 - 2\
C. 3 ;null map to 0, 3 + 0\
D. '3null' ; null is now string 'null'\
E. 4 ; true map to 1, 1 + 3\
F. 0 ; both false and null map to 0\
G. '3undefined' ; undefined is now a string\
H. NaN ; you can not subtract undefined\
14. 
A. true ; '2' convert to number 2\
B. false ; string comparison\
C. true ; '2' convert to number 2\
D. false ; comparing different type\
E. false ; true map to 1\
F. true ; Boolean(2) is true\
15. == will convert type, === does not convert type
16. see part2-question16.js
17. [2,4,6] : array[1,2,3], and function doSomething passed to modifyArry. In modifyArray, it loop through the array, call function "doSomething(array[i])" and push the returned value into newArr. Return array newArr at the end. doSomething multiple a number by 2, so in the end, newArr contain [2,4,6].
18. see part2-question18.js
19. 1432