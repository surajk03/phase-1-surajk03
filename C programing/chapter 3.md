# Loops


> The repetition of some portion of program either a specified number of times or until a particular condition is being satisfied is called loops.

> the repetitive operation is done through a **loop control instruction.**

**Loop control instruction:** the loop control instruction helps the computer to execute group of statements repeatedly.

The three methods by which we can repeat a part of program are:

1. for statement.
2. while statement.
3. do-while statement.


## While loop


The general form of while loop is:

```
while (condition)
     {
       set of statements;
       either increment/decrement;
     }
```     

**Note:**

1. Until the condition is true, the set of statements get executed repeatedly.
2. When the condition becomes false, the set of statements not get executed and the compiler skips the part that is enclosed in parenthesis after the while loop.
3. There must be a statement that makes the condition to be false oherwise the loop will go on executed indefinitely.


## For loop


The general form of for loop is:

```
for (initialize counter; test counter; increment/decrement counter)
{
   set of statements;
}
```

**Note:**

1. In for loop the initialization, testing and incrementation or decrementation are incorporated in the for statement itself.
2. firstly the variable is initialized, then goes to test counter,
3. If the condition is true then the set of statements gets executed followed by incrementation of variable.
4. If the condition evaluates to false then the set of statements not get executed and the compiler skips the part that is enclosed in parenthesis after the for loop.

