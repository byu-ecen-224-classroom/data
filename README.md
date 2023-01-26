# Data

## Experience Summary

### How many hours did it take to complete assignment?
[Put answer here]

### What did you enjoy about this lab?
[Put answer here]

### What were the major challenges you had with this lab? Try to be as detailed as possible.
[Put answer here]

## Lab Specific Tasks

### A Simple C Program
1. What are the specific types of comments that exist in the C programming language? Do some research, is there a third type that exists? If there is what is it and how is it used?

[Put answer here]

2. What is a compiler directive? When do they get used? 

[Put answer here]

3. Define the following compiler directives and when they are used: `#define`, `#if`, `#else`, `#endif`.

[Put answer here]

4. Investigate other compiler directives that exist in C. Name two more and explain what they do and when they are used.

[Put answer here]

5. What is the `main()` function and why is it important in C programming?

[Put answer here]

6. What is a return value? Why are they used?

[Put answer here]

7. Why does the `main()` function have a return value? Where can you access the return value of the `main()` function?

[Put answer here]

8. Create a simple program in your lab repository on the Pi Z2W named `simple.c`. Your program should output something to the terminal and include all of the components found in this section. It must also include two different functions with different return value data types.

[Simple C Program](./simple.c)

9. Compile the program above in `gcc`. Make sure the executable is named `simple.bin` and that its assenbly code is available as well. You made need to do some aditional research to accomplish this. Remember: `man` and Google are your friends.

[Simple Assembly](./simple.s)

[Simple Binary](./simple.bin)

10. Look at one of the commands in your `simple.s` file. Google it and try to figure out what it means and report your findings below.

[Put answer here]

### Data Types

11. Read the the `stdint.h` `man` page. You'll find that a lot of extra info about standard C libraries are available there. List below the all the different types this library provides.

[Put answer here]

12. Create a new file called `data.c`. This program should do the following. For each requirement, place a comment next to or above it so I know you have completed the required step:
    - Print out the hex equivalent of the `unsigned int`: 3735928559
    - Create a function that takes in a `uint8_t` as a parameter and prints `char` equivalent. Use it at least 3 times in your `main()`.
    - Use the `printf()` function at least once that has multiple inline replacements.
    - Use at least 5 different replacement types in 5 different `printf()` statements.
    - Use some replacements in `printf()` in unexpected ways (i.e. pass a `char` to replace a `%d`, or something similar). Your program must compile. In a comment next to or above this statement, explain the behavior and why you think it works that way.

[Data C](./data.c)

13. Compile `data.c` into a binary called `data_sol.bin`.

[Data Binary](./data_sol.bin)

### Miscellaneous Questions
The following questions will require some research outside of this lab.

14. What is the biggest number an `int` can hold?

[Put answer here]

15. Which is bigger, a `double` or a `float`?

[Put answer here]

16. Arrange the following in order of size: `int`, `double`, `long long`, `short`, `float`, `uint32_t`, `signed short`

[Put answer here]
