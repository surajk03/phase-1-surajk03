# what is C

> C is a programming language developed at AT and T's Bell Laboratories of USA in 1972. It was designed and written by a man named Dennis Ritchie.

> It is recommended to learn C language before starting any of the programming languages like C++, C#, or Java.

# Getting started with C

> Getting started with C involves:

```
1.Should get to know about what alphabets, digits, and special symbols are used in C.
2.Constructing constants, variables and keyword using these alphabets, digits, and special symbols.
3.These constants, variables and keywords are combined to form instructions.
4.A group of instructions will combine to form a program.
```


## The C character set

> A character denotes any alphabet, digit or special symbol used to represent information.

> The valid alphabets , digits and special symbols allowed in C are:

```
Alphabets - A,B,C,........,X,Y,Z.
          - a,b,c,........,x,y,z.
Digits - 0,1,2,3,4,5,6,7,8,9.
Special symbols - !,@,#,$,%,&,(),{} etc.....
```

## Constants

> C constants are classified two types:

1.Primary constants.
2.Secondary constants.

Primary constants are calssified into:

```
1.Real constant.
2.Integer constant.
3.Character constant - is a single alphabet, single digit, or a single special symbol enclosed with single inverted commas.
```

> Secondary constants are classified into:

```
1.Array.
2.Pointer.
3.Structure.
4.Union etc....
```

## variables

> Variables are the entities which are used to store values that can be changed anytime.

## Key words

> Keywords are the words whose meaning has already been explained to the compiler.
> It is recommended that keywords cannot be used as variable names. 

## Comments

> the way of writing comments in a program:
/*.....*/

Comments are generally written for indicating the purpose of the following program or statement.

> Comments cannot be nested.
> Comment can be split over more than one line such type of comments are called multi line comments.

## main()

> main() is a function that contains set of statements which are enclosed in {}.

## printf()

> printf() is a library function which is used to display the output.
```
%d - used for printing integer values.
%f - used for printing real values.
%c - used for printing charcter values.
```
## scanf()

> scanf() is a library function which is used for recieveing values from the key board.

NOTE: the ampersand(&) before the variables is scanf() is a must, It is an address of operator which gives the location number used by the variable in memory. 

# C instructions

Types of instructions:

1.Type declaration instruction.
2.Arithmetic instruction.
3.Control instruction.

## Type declaration instruction

> This instruction is used to declare the type of variables being used in the program.

> Any variable used in the program must be declared before using it in any statement.
```
Example: int i = 7;
         float a = 1.5;
```

## Arithmetic instruction

> An arithmetic instruction consists of a variable name on the left hand side of = and variable names and constants on the right hand side of =.
> '=' is called as **Assignment Operator**

> the variables and constants appearing on the right hand side of = are connected by arithmetic operators like +, -, *, /.

> The variables and constants together called as **Operands**.

Types of arithmetic statements:

1.Integer mode arithmetic statement: This is an arithmetic operator in which all operands are integer variables or integer constants.
2.Real mode arithmetic statement: This is an arithmetic operator in which all operands are real variables or real constants.
3.Mixed mode arithmetic statement: This is an arithmetic statement in which some operands are integers and some operands are real.

Modulus operator(%): This is used to display the remainder obtained on division of two integer values.

NOTE: The arithmetic instruction is often used for storing character constants in character variables but these character constants represent only their **ASCII** values.

## Integer and Float conversions

> The arithmetic operation between integer and integer always yields an integer result.

> The arithmetic operation between real and real always yeilds a real result.

> The arithmetic operation between integer and real always yeilds a real result. In this operation the integer is promoted to a real and then the operation is performed.

## Type conversion in assignments

> If the type of extension and type of variable on the left hand side of the assignment operator may not be same. In such case the value of the expression is promoted or
  demoted depending on the type of variable on the left hand side of =.
  
## Hierarchy of operations

If we have multiple operators in astatement the we have to follow the following priority order:

**Priority**   **Operators**   **Description**
  
   1st            * / %          multiplication, division, modulus operator.
   2nd            + -            addition, subtraction.
   3rd            =              assignment.
   
## Assosiavity of operators

> When an expression contains two operators of equal priority the tie between them is settled using associativity if operators.

> Associativity of operators in the sense either 1. Left to right associavity.
                                                 2. Right to left associavity.
                                                 
## Control instriction

> The control instructions enable us to specify the order in which the various instructions in a program are to be executed by the computer.

Types of control instructions:
1. Sequence control instruction.
2. Selection or decision control instruction.
3. Repetition or loop control instruction.
4. Case control instruction.

> The sequence control instruction ensures that the instructions are executed in the same order in which they appear in the program.
> decision or case control instruction allow the computer to take a decision as to wchich instruction to be executed next.
> The loop control instruction helps the computer to execute a group of statements repeatedly.
        
