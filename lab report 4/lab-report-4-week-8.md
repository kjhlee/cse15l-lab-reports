# Lab Report 4

*repo links*
* [My markdown](https://github.com/kjhlee/markdown-parser)
* [Week 7](https://github.com/khiemddang/markdown-parser)


#### Code Snippet 1
This is the expected result: 

```
{`google.com, google.com, ucsd.edu}
```

Test for snippet 1: 
![image](images/snip1.png)

This is the result for running the test in my own impelementation: 
![image](images/res1.png)

This is the result for running the test in my groups week 7 implementation:
![image](images/res7-1.png)


### Code Snippet 2

This is the expected result:
```
{a.com, a.com((, example.com}
```

Test for snippet 2: 
![image](images/snip2.png)

This is the result for running the test in my own impelementation: 
![image](images/res2.png)

This is the result for running the test in my groups week 7 implementation:
![image](images/res7-2.png)


### Code Snippet #3

This is the expected result:

```
{https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule}
```

Test for snippet 2: 
![image](images/snip3.png)

This is the result for running the test in my own impelementation: 
![image](images/res3.png)

This is the result for running the test in my groups week 7 implementation:
![image](images/res7-3.png)


### Questions
1. As of right now I don't believe it would be possible to do it sub 10 lines. If I were to create something to fix fix solution 1 the first thing I would do is to write a check that checks for all back ticks and interior brackets and unless they're in the paranthesis I would ignore them.
2. For code snippet 2 I believe it would be possible to fix it in less than 10 lines. The solution would look something like: 
```
if(backetsIndex + 1 == paranthesisIndex){
    // add it to the list.
}
```
It would look something like this where we check the index of bracket + 1 and if its the same as the paranthesis then we can add it to the list.

3. Code Snippet 3 has some problems that I believe could not be solved in less than 10 lines. The major problems would be traversing through emtpy spaces, I don't really know how I would be able to look for spaces and skip those spaces while also trying to find the links. 


