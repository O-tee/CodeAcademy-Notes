# 12/17/24

## Notes 
### Object-oriented programming (OOP): 
- is a software development paradigm that encourages sculpting desired entities with properties and methods in named classes to create applications.

### So why learn C++? Among many other things:
- It is fast and flexible.
- It is well-supported.
- It forces you to think in new and creative ways.<br/>

### Structure
![Screenshot 2024-12-17 180045](https://github.com/user-attachments/assets/ce8462ed-e626-4a2c-bc78-afc3be897410)
- std::cout is the “character output stream”. It is pronounced “see-out”.
- << is an operator  that comes right after it.
- "Hello World!\n" is what’s being outputted here. You need double quotes around the text.
  - The \n is a special character that indicates a new line.
- ; is a punctuation that tells the computer that you are at the end of a statement. It is similar to a period in a sentence.

### "#include < iostream >"
- This is known as a pre-processor directive. It instructs the compiler to locate the file that contains code for a library known as iostream. This library contains code that allows for input and output, such as displaying data in the terminal window or reading input from your keyboard. <br/>


![Screenshot 2024-12-17 211521](https://github.com/user-attachments/assets/984ada75-2617-4ffd-9cab-02645381758b)
- Every C++ program must have a function called main(). A function is basically a sequence of instructions for the computer to execute. This main() function houses all of our instructions for our program. This is where we will be writing our code.

### return 0
- The return statement is used to end a function. If the program reaches this statement, returning a value of 0 is an indication to the operating system that the code executed successfully. This line of code is optional.

### Compile and Execute
- Compile: A computer can only understand machine code. A compiler can translate the C++ programs that we write into machine code. You call on the compiler by using the terminal, which is the black panel to the right of the code editor that contains a dollar sign $. To compile a file, you need to type g++ followed by the file name in the terminal and press enter:
  - g++ hello.cpp -> creates a.out
- Execute: To execute the new machine code file, all you need to do is type ./ and the machine code file name in the terminal and press enter. In this case, our compiled file name is a.out. Putting it all together, we end up with the following:
  - ./a.out
 
### Compile to make an output executable with a diff name
- g++ hello.cpp -o hello
- ./hello
