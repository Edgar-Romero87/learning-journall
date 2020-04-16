# **Operators and Loops:** 
 
## **Comparison Operators: Evaluating Conditions**

Comparison operators usually return single values of *true* or *false* 
You can evaluate a situation by comparing one value in the script to what you expect it may be. The result will be a Boolean: **true** or **false**.

### == IS EQUAL TO


### != IS NOT EQUAL


### === STRICT EQUAL TO


### !== STRICT NOT EQUAL TO

### >  GREATER THAN 

### <   LESS THAN 

### >=  GREATER THAN OR EQUAL TO

### <=  LESS THAN OR EQUAL TO

## **LOGICAL OPERATORS**
Logical operatos allow you to compare the resultas of more tha one comparison operator. Logical expresions are evaluated *left* to *right* if the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition. 

### && LOGICAL AND

### || LOGICAL OR

### ! LOGICAL NOT 


## **LOOPS**
loops check a condition. If it returns *true*, a code block will run. Then the condition will be check again and if still returns *true*, the code block will run again. It repeat until the condition returns *false*. there are three common types of loops: 

### FOR 
If you need to run code a specific number of times, use a **for** loop.(Its the most common loop.) In a **for** loop the condition is usually a counter wich is used to tell how many times the loop should run.

### WHILE
If you not know how many times the code should run, you can use a **while** loop. Here the conditions can be something other than a counter, and the code will continue to loop for as long as the condition is **true**.

**Keywords** -you commonly see these two keywords used with loops:
- **Break** -this keyword causes the termination of the loop and tells the interpreter to go on to the next statement of code outside thye loop.(You may also see it used in functions) 
- **Continue** -This keyword tells the interpreter to continue with the current iteration, and then check the condition again.(If it is true, the code runs again.)