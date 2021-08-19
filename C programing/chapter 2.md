# The decision control structure


> Decision control instruction allow the computer to take a decision as to which instruction to be executed next.

Types of decision making instructions:

1. If statement.
2. If else statement.
3. The conditional operators.


## The if statement


The general form of the if satement is:
```
if (condition)
   statement;
```
**Note:**
1. if the condition enclosed in the parenthesis is true then the statement is executed.
2. if the condition enclosed in the parenthesis is not true then the statement is not executed instead the program skips past it.

> we use relational operators for expressing the condition.

> if multiple statements are to be executed when the condition following is satisfied then those staemnets have to be placed within a pair of braces.


## The if else statement


The main purpose of if else statement is:

> we can execute one group of statements if the condition is true and another group of statements if the condition is not true.

The general form of if else satement is:
```
if (condition)
    {
      set of statements;
    }
else
    {
      set of statements;
    }
```    

## Nested if elses


The general form of the nested if elses is:
```
if (condition 1)
    {
      set of statements;
    }
else
    {
      if (condition 2)
          set of statements;
      else
          set of statements;
    }
 ```   

> Logiacal operators: logical operators like &&(and), ||(or), !(not), helps us in making the program less complex.

## else if clause


```
if (condition 1)                                        
    statement 1;                                            if (condition 1)                    
else                                                               statemnet 1;                                          
    {                               **(OR)**                else if (condition 2)    
      if (condition 2)                                             statement 2;
         statement 2;
    }
```    
**Note:**
both mentioned above are true but the 2nd one reduces the indentation of statements.

