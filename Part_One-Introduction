\*

>>Learn C++ Notes - Introduction<<

Disclaimer
  - Most of the notes are based of the material on the Learn C++ site (https://www.learncpp.com/)
  - All notes taken are used for educational purposes and taken with materials that are free to use or have adaptations that are free to use. Please don't sell/distribute these notes for profit.
  - Some notes are from other sources
    - C++ Primer 5th Edition (https://www.amazon.com/Primer-5th-Stanley-B-Lippman/dp/0321714113) or (https://cpp-primer.pages.dev/src/001-contents) ** THIS WILL NOT BE THE CASE UNTIL I GET THROUGH LEARN C++ **
    - Stack Overflow (https://stackoverflow.com/) ** Learn C++ redirects here for some niche topics **
  - Some notes are from my own knowledge, or rather "Common knowledge" in the modern era

Terminology

    Computer Program/Application in C++
        - Set of instructions to preform a task
        - Can be written with multiple languages
          - Some languages are better for certain tasks
          - e.g. C++ is good for applications or faster tasks, Python is good for scripting or simpler tasks

    File Extension
        - A string of characters that comes after the file name
        - e.g. .txt, .cpp, .exe

    Programming
      - Process of writing the program
    
    Compiling
      - Process of converting the program to machine language
      - Done by a compiler
      - First, checks for syntax errors
      - Then, converts the program to machine language
        - Stored in an object file
          Object File
            - A file that contains the machine language code
            - e.g. .o, .obj
        - Three .cpp files will create three object files
        
    Execution
      - Process of running the program

    Debugging
      - Process of finding/fixing errors in the program 
    
    Ascii Characters
      - Characters that are used in the ASCII (American Standard Code for Information Interchange) standard
      - e.g. A, B, C, 1, 2, 3, !, @, #, etc.
      - Ascii art is used in programming to represent mathematical concepts
        - e.g. != means "not equal to"
        - Some programing fonts can convert != to a single character, like Fira Code

    Code Editor
      - A program that allows you to write code
      - e.g. Visual Studio Code, Sublime Text, Notepad++
      - Has features that make writing code easier

        Line Numbering
          - Numbers on the left side of the editor
          - Helps you find a specific line of code

        Syntax highlighting
          - Different colors for different parts of the code
          - e.g. blue for keywords, red for strings

        Fixed-width (monospace) font
          - All characters have the same width
          - Makes the code easier to 
          - codingfont.com and programmingfonts.org have good fonts for coding
          
        Code folding
          - Allows you to hide/show blocks of code
          - e.g. hide a function that you're not working on

        Autocompletion
          - Automatically completes code for you
          - e.g. typing "for" and pressing tab will complete the for loop

        Warnings/Error highlighting
          - Highlights potential issues in the code
          - e.g. using a variable before it's defined

        Plugins
          - Add extra features to the editor
          - e.g. a plugin that allows you to run the code from the editor
          - e.g. Microsoft C++ extension for Visual Studio Code

    Bug
      - An error in the code
      - Coined by Thomas Edison in 1870s
      - Popularized when a moth was found in a computer in 1947, causing a short circuit

    Source code
      - One or more files that contain the instructions written in a programming language

    Programming Languages
        - Languages designed to program
        - Python, C++, Java, JavaScript, etc.

    Syntax
        - Rules for writing code in a programming language
        - Differs between languages
        - If the syntax is incorrect, the program will not run

    Pragmatics
      - How the code is used
        - e.g. how the code is written, how the code is compiled, how the code is executed

    Purpose
      - The reason for writing the program
        - e.g. to solve a problem, to automate a task, to learn a language

    Platform
      - The software environment in which the program runs
        - e.g. Windows, MacOS, Linux
      - The CPU family or instruction set architecture on which the program runs
        - e.g. x86, ARM64
      - The hardware environment on which the program runs
        - e.g. Intel, AMD
      - "PC" usually refers to Windows in a x86 environment

    Machine Language
      - The language that the computer understands
      - An instruction set
          - All possible instructions that the computer can execute
            - Instructions are composed of a sequence of 1s and 0s
              - e.g. 1010101010101010
              - Binary or Binary Code
                  - Each number (1) or (0) in binary is called a bit
            - Interpreted by the CPU to preform tasks
              - e.g. add, subtract, move, jump

    Assembly Language
      - Abriviations, allowing humans to better understand machine language
        - still hard to understand
      - A low-level programming language
      - Requires an Assembler
        - A program that converts assembly language to machine language
      - e.g. mov ax, 5
      - Needs to be remade for each family of CPUs

    High-Level Language
      - A language that is easier to read and write than machine language
      - Requires fewer instructions to preform a task than machine language
      - Higher languages tend to be portable
        - Can be run on multiple platforms

      Compiled Language
        - Requires a compiler
          - After being compiled, the program can be run without the compiler
            - e.g. .exe, .out 
          - A program that converts high-level language to machine language or assembly
          - e.g. g++, clang, msvc
        - A language that is more efficient when converted to machine language before execution
        - e.g. C++, C, Rust
        - Faster than Interpreted Languages

        Process
          - High-Level Language source code
            (What you write)
          - Compiler
            (Converts to machine language)
          - Executable
            (What you run)
          - Hardware
            (What runs the program)
          - Return
            (What the program does)

      Interpreted Language
        - "Scripting" languages
        - Code from these languages is converted to machine language during execution
        - e.g. Python, JavaScript, Ruby
        - Needs to be done everytime the program is run

        Process
          - High-Level Language source code
            (What you write)
          - Interpreter
            (Converts to machine language)
          - Hardware
            (What runs the program)
          - Return
            (What the program does)

      Hybrid Language
        - A language that is efficient when both compiled and interpreted
        - e.g. Java, C#
        - Compiled to bytecode
          - A low-level language that is interpreted by the Java Virtual Machine
        - Interpreted by the Java Virtual Machine
          - A program that converts bytecode to machine language

        Process
          - High-Level Language source code
            (What you write)
          - Compiler
            (Converts to bytecode)
          - Java Virtual Machine or for Common Language Runtime (.NET)
            (Converts to machine language)
          - Hardware
            (What runs the program)
          - Return
            (What the program does)

      Comparism (Generally Speaking)
        - Compiled
          - Preform faster due to optimising and being able to see all code up front compared to looking at it as it runs
          - Generate low level code that does high level ideas
            - Dynamic dispatch
              - The ability to call a function based on the type of an object
              - Polymorphism
                - The ability to use a single interface to represent multiple types
                - e.g. a function that can take multiple types of arguments
            - Inheritance
              - The ability to create a new class from an existing class
          - Generally faster because it's for the program itself not the program + the interpreter
          - Incompatible with dynamic typing
            - Inefficient for the compiler to run (which defeats the purpose of using a compiler)
            - The ability to change the type of a variable
          - Compilers have a longer compile time than an interpreter because they have to convert the entire program
        - Interpreted
          - Start up faster because they don't have to compile the entire program
          - Compatible with dynamic optimizations
            - optimizations that are applied to the program as it runs
              - e.g. Just-In-Time (JIT) compilation
                - A technique that optmizes the method as the program runs
          - Higher memory usage because the interpreter needs to keep more information about the program while running
          - Slower because the interpreter has to spend some CPU time
        - Hybrid
          - The best of both worlds
          - Compiled but initaly interpreted
            - Can find code that's "hot" (used alot) and compile it
              - JS engines will compile pieces of the code
                - This results in a  fast startup that gets faster as the program runs
            - Can preform dynamic optimizations
              - e.g. In-line caching
                - Speeds up the process of looking up a method by caching the result

      Cross-Platform Program
        - A program that can run on multiple platforms
          - e.g. Windows, MacOS, Linux
          - High level language code
            - Compiler for x86
              - x86 executable
            - Compiler for PowerPC
              - PowerPC executable
            - Compiler for MIPS
              - MIPS executable
        - High level languages are more likely to be cross-platform
          - This is because the compiler/interpreter can be written for multiple platforms

      "Languages are not compiled or interpreted"
        - Theoretically, code from any language can be compiled or interpreted
        - Some languages are designed to be compiled or interpreted
        - Futamura projections
          - A theory that states that any program can be compiled or interpreted
          - A program that can convert a program from one language to another
          - A program that can convert a program from one language to itself
  
  Statements
    - A type of instruction to preform a task/action
    - Must have
        - A statement terminator
            - A character that ends a statement
            - e.g. ;
        - A statement body
            - The code that preforms the task
            - e.g. x = 5;
    
    Declaration statements
        - Define a variable, function, class, or namespace

            Variable declarations
                - A statement that defines a variable
                - e.g. int x;

            Function declarations
                - A statement that defines a function
                - e.g. void printHello();

            Class declarations
                - A statement that defines a class
                - e.g. class MyClass;

            Namespace declarations
                - A statement that defines a namespace
                - e.g. namespace MyNamespace;

    Jump statements
        - A statement that changes the flow of the program/order of execution

            Return statements
                - A statement that ends a function
                - e.g. return 5;

            Break statements
                - A statement that ends a loop
                - e.g. break;

            Continue statements
                - A statement that skips the rest of the loop
                - e.g. continue;

            Goto statements (avoid using)
                - A statement that jumps to a label
                - These lead to "spaghetti code" (poor readability/continuity)
                - e.g. goto label;

    Expression statements
        - A statement that preforms an operation/calculation
        - e.g. x = 5;
        - e.g. x = x + 5;

          Assignment statements
              - A statement that assigns a value to a variable
              - e.g. x = 5;

          Arithmetic statements
              - A statement that preforms a mathematical operation
              - e.g. x = x + 5;

          Function call statements
              - A statement that calls a function
              - e.g. printHello();

          Increment/Decrement statements
              - A statement that increases/decreases a variable by 1
              - e.g. x++;

    Compound statements
        - A statement that groups multiple statements
        - e.g. { int x; x = 5; }
            
        Block statements
            - A statement that groups multiple statements
            - e.g. { int x; x = 5; }

        Function body statements
            - A statement that groups multiple statements in a function
            - e.g. void printHello() { std::cout << "Hello, World!" << std::endl; }

    Selection statements (conditionals)
        - A statement that chooses between two or more paths
        - e.g. if (x == 5) { x = 10; }
        
        If statements
            - A statement that chooses between two paths
            - e.g. if (x == 5) { x = 10; }
        
        Else statements
            - A statement that runs if the if statement is false
            - e.g. if (x == 5) { x = 10; } else { x = 0; }
        
        If-Else statements
            - A statement that chooses between two paths
            - e.g. if (x == 5) { x = 10; } else { x = 0; }

        Else-If statements
            - A statement that runs if the if statement is false and a condition is true
            - e.g. if (x == 5) { x = 10; } else if (x == 10) { x = 5; }
        
        Switch statements
            - A statement that chooses between multiple paths
            - e.g. switch (x) { case 5: x = 10; break; case 10: x = 5; break; default: x = 0; break; }

    Iteration statements (loops)
        - A statement that repeats a block of code
        - e.g. for (int i = 0; i < 10; i++) { x = x + 1; }
        
        For Loop
            - A statement that repeats a block of code a specific number of times
            - e.g. for (int i = 0; i < 10; i++) { x = x + 1; }
        
        While Loop
            - A statement that repeats a block of code while a condition is true
            - e.g. while (x < 10) { x = x + 1; }
        
        Do-While Loop
            - A statement that repeats a block of code while a condition is true
            - e.g. do { x = x + 1; } while (x < 10);


    Try blocks (exception handling)
        - A statement that handles errors
        - e.g. try { x = 5 / 0; } catch (int e) { x = 0; }

            Try-Catch blocks
                - A statement that handles errors
                - e.g. try { x = 5 / 0; } catch (int e) { x = 0; }
            
            Try-Catch-Throw blocks
                - A statement that handles errors and throws an error
                - e.g. try { x = 5 / 0; } catch (int e) { x = 0; throw e; }
            
            Try-Catch-Throw-Catch blocks
                - A statement that handles errors, throws an error, and catches the error
                - e.g. try { x = 5 / 0; } catch (int e) { x = 0; throw e; } catch (int e) { x = 0; }

    Null Statements
        - A statement that does nothing
        - e.g. ;
            Empty statements (Useless)
                - A statement that does nothing
                - e.g. ;
            
            Comment statements (Useful)
                - A statement that does nothing but holds information
                - e.g. All the notes are in a multi-line comment
    
  Functions
    - A statement
    - Can be called multiple times
    - Can be called from other functions
    - Can be called from other files

  Main
    - The starting point of a program
    - The first function called
    - Must be defined
    - Must return an integer
    - Must have a return statement
    - Must have a closing bracket
  
  Embedded Systems
      - Which are systems that are built into other systems
      - e.g. a smartwatch

  Object Linking
    - The process of combining object files into an executable
    - Done by a linker
  
  
  Object Linker
    - A program that combines object files into an executable (or other file type)
  
  Packaging
    - The process of combining multiple files into a single file
    - Done by a packager
  
  
  Library Files
    - Files that contain code that can be used in other programs
    - e.g. a file that contains a function that prints "Hello, World!"

    Iostream
      - A common library file that contains code for input/output
      - e.g. std::cout, std::cin

    C++ Standard Library
      - A library that contains code that is commonly used in C++
      - e.g. iostream, string, vector, algorithm
    
    
    String Library
      - A library that contains code for strings
      - e.g. std::string
    
    Vector Library
      - A library that contains code for vectors
      - e.g. std::vector
    
    Algorithm Library
      - A library that contains code for algorithms
      - e.g. std::sort
    
    C Math
      - A library that contains code for math
      - e.g. std::abs, std::pow, std::sqrt
    


  Nomenclature
    - Naming conventions for code or files
    - Allows us to understand the purpose of the code

    Camel Case (Preferred by Micheal in Game Makers Union)
        - First letter is lowercase
        - First letter of each word is uppercase
        - e.g. camelCase
    
    Snake Case
        - All lowercase
        - Words are separated by underscores
        - e.g. snake_case
    
    Pascal Case
        - First letter is uppercase
        - First letter of each word is uppercase
        - e.g. PascalCase
    
    Kebab Case
        - All lowercase
        - Words are separated by hyphens
        - e.g. kebab-case

C++ History

  Standardized by the ISO (International Organization for Standardization) committee in 1998
    - Standards document
      - Provides a set of rules for writing C++ code
        - Ensures that code is portable across compilers and platforms

  Based on C
    - C is a low-level programming language
    - C++ is a high-level programming language based on C
    - C# is a high-level programming language based on C++

  Five Major Updates

    C++11
      - Released in 2011
      - Considered the baseline for modern C++
      - Formal name is ISO/IEC 14882:2011

    C++14
      - Released in 2014
      - Formal name is ISO/IEC 14882:2014

    C++17
      - Released in 2017
      - Formal name is ISO/IEC 14882:2017

    C++20
      - Released in 2020
      - Formal name is ISO/IEC 14882:2020

    C++23
      - Released in 2023
      - Formal name is ISO/IEC 14882:2023
    
    - Future updates are expected to be released every 3 years

  Philosophy
    - Designed to "Trust the Programmer"
      - This allows the programmer to have alot of control over the program
      - This can lead to more bugs

  Uses
    - Video Games
    - Real-Time Systems
    - AI and Neural Networks
    - Embedded Systems

  Popularity
    - Consistently the 2nd or 3rd most popular compiling language
      - Many resources available to learn it
      - Many companies use it
  
Writing in C++

  Process of writing a program

    Define
      - "I need a program that can navigate a maze"
      - "I need a program that can display a clock"

      Design
        - Good solutions
          - Occams razor (simple is more likely to work)
          - Well documented
          - Give errors when issues occur
          - Easy to change or reuse
            - e.g. a function that can be used in multiple places
            - If you write in the least amount of code, it will be hard to read and edit later on if it produces bugs

        Write
          - Write the code in a code editor
          - e.g
            #include <iostream>
            int main()
            {
              std::cout << "Hello, World!" << std::endl;
              return 0;
            }
          - C++ programs can have thousands of files
            - The primary one should be called main.cpp
            - All other files should end in .cpp
            - The .cpp extension indicates that the file contains C++ code

          Compile
            Link Objects

              Test

                Debug/Rewrite
                  - Removing bugs


*/
