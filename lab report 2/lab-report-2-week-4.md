# Lab Report 2 Week 4
## Debugging

### _Example 1_
### _Link with no ending parenthesis_
![image](images/file1.png)

### _Symptom_
![image](images/error1.png)

There is an error when trying to run this code due to the fact that the second link is missing a parenthesis. The symptom of this code is shown in our error statement. Because our code never found the missing parenthesis we get an error showing that the parse is running but the closing parenthesis is nowhere to be found.

### _Example 2_
### _Link with only brackets_
![image](images/file2.png)

### _Symptom_
![image](images/error2.png)

This is an interesting error for the code. The failure inducing code is that for the links we don't have parenthesis but actually we have brackets. The error comes from trying to find the start and ending parenthesis. Because we never find it the code ends up inducing a out of memory error. This is also synonymous with the symptom of the code. Our code is trying to read the link of the code but because there is never a parenthesis it is never given.

### _Example 3_
### _Link with only brackets_
![image](images/file3.png)
[Link to error](https://github.com/kjhlee/markdown-parser/commit/90b30cc4d7fa367c22d6e0f3452a330701ef7b96)

### _Symptom_
![image](images/error3.png)