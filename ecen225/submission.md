<!-- Lab Writup #1 -->
# Lab Writeup #1

Author: Alexis Ivie

Date: May 20th, 2025

<!-- Lab 02: Command Line -->
## Lab 02: Command Line

### Description
In this lab, I learned how to use the Linux command line. I practiced basic commands, moved around folders, and edited files using a text editor in the terminal. I also tried shortcuts and completed a challenge to test what I learned. This lab helped me get comfortable looking for files in the terminal instead of a GUI. I also gained experience looking up solutions online. The lab consisted of a shell challenge allowing me to practice what I learned.

### Usage Instructions
To complete the Shell Challenge, I first uncompressed the challenge.tar.xz file using a terminal command that extracts both the `.tar` and `.xz` layers using the command `tar -xf challenge.tar.xz`.  After extracting, I opened the new folder and followed the instructions in each level. I used basic Linux commands to move through files and directories, change permissions, and solve each task. If I got stuck, I searched online for help. All commands were run directly in the terminal and no GUI's used.

<!-- Lab 03: C Programming -->
## Lab 03: C Programming

### Description
In this lab, we got a feel for how C programs work by writing and running a simple one. We used `gcc` to compile the code and looked at what happens during each step. Like preprocessing, compiling, and linking. We also broke down the basic parts of a C program, like the `main()` function, `printf()`, comments, and how data types and type casting work. It was a good intro to writing C and seeing how it turns into something the computer can run.

### Usage Instructions
To complete this lab, create a file called `data.c` and write a C program that explores how different data types interact with `printf()`. Start by printing the hexadecimal version of the number `3735928559`. Then, write a function that takes a `uint8_t` and prints its character equivalent—make sure to call it at least three times. Use at least five different format specifiers across different `printf()` statements to see how each one behaves. Try combining multiple specifiers in a single print statement, and experiment with using them in unexpected ways (like printing a `char` as a float). When finished, compile your program into an executable named `data`.

<!-- Lab 04 -->
## Lab 04: Data Types & Strings

### Description
In this lab, I got hands-on with how C handles different data types. I learned what happens when integers go beyond their limits, like overflow and underflow, and how the computer deals with mixing different types. Using fixed-size types like `int8_t` and `uint32_t` really helped me see these effects clearly. I also explored how C works with strings and found out why comparing strings with `strcmp()` is necessary instead of just comparing pointers. Overall, this lab helped me understand how data is stored and manipulated in C, and how to avoid common mistakes when working with types.

### Usage Instructions
In this lab, you work through exercises that deepen your understanding of C data types and how they behave. You explore fixed-width integers to see how overflow and underflow happen and experiment with different `printf()` format specifiers to understand how data is displayed. You also practice using string functions carefully, while observing how type casting and integer promotions affect calculations and output. This hands-on approach helps build a solid grasp of key C programming concepts related to data and strings.

<!-- Lab 05: Image -->
## Lab 05: Image

### Description
This lab taught me how to manipulate image data in C by working directly with bitmap files. Since C is not object-oriented, it uses structs to group data, like the Bitmap struct that holds the image’s pixel data, size, and headers. I learned how images are stored as arrays of pixel colors (blue, green, red) and how to use bitmasking to manipulate individual bits. The lab involved writing functions to remove a color channel, convert the image to grayscale, and apply a bitwise OR filter using data from adjacent pixels. It was a deeper dive into pointers, arrays, and bitwise operations — all tied together by working with real image data.

### Usage Instructions
In this lab, you edit an original bitmap image by implementing several image processing functions. First, create a function to remove a specified color channel (red, green, or blue) from the image by setting those color values to zero. Next, write a function to convert the image to grayscale by combining the red, green, and blue values for each pixel using a weighted sum. Finally, implement an OR filter that bitwise ORs each pixel’s color values with the pixels directly above and below it, carefully handling edge cases at the image borders. Use a copy of the original pixel data for reference during the OR operation to avoid compounding changes. After completing these functions, modify the main program to save the edited images so you can visually verify your results.
