# Usages

For Loop with Specific Number Row

# ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) JAVA


    Initialization: It is the initial condition which is executed once when the loop starts. Here, we can initialize the variable, or we can use an already initialized variable. It is an optional condition.
    Condition: It is the second condition which is executed each time to test the condition of the loop. It continues execution until the condition is false. It must return boolean value either true or false. It is an optional condition.
    Increment/Decrement: It increments or decrements the variable value. It is an optional condition.
    Statement: The statement of the loop is executed each time until the second condition is false.
<b> SYNTAX </b>
```java
    for(initialization; condition; increment/decrement){    
    //statement or code to be executed    
    }    
```

<b> EXAMPLE FOR LOOP </b>
```java
public class ForExample {  
public static void main(String[] args) {  
    //Code of Java for loop  
    for(int i=1;i<=10;i++){  
        System.out.println(i);  
    }  
}  
}  
```
<a href="https://www.javatpoint.com/java-for-loop">Reference</a>

# ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) PYTHON
<pre>The for loop in Python is used to iterate over a sequence (list, tuple, string) or other iterable objects. Iterating over a sequence is called traversal.</pre>
<b> Syntax of for Loop </b>

```python
for val in sequence:
    loop body
```

<pre>Here, val is the variable that takes the value of the item inside the sequence on each iteration.

Loop continues until we reach the last item in the sequence. The body of for loop is separated from the rest of the code using indentation.</pre>

<b> EXAMPLE FOR LOOP </b>
```python
# Program to find the sum of all numbers stored in a list

# List of numbers
numbers = [6, 5, 3, 8, 4, 2, 5, 4, 11]

# variable to store the sum
sum = 0

# iterate over the list
for val in numbers:
    sum = sum+val

print("The sum is", sum)
```
<a href="https://www.programiz.com/python-programming/for-loop">Reference</a>

# ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) Objective-C 
<b> Syntax of for Loop </b>
```c
for ( ''initializer''; ''conditional expression''; ''loop expression'' )
{
      // statements to be executed
}
```
<prev>The `initializer` typically initializes a counter variable. Traditionally the variable name i is used for this purpose, though any valid variable name will do. For example:</prev>

```c
i = 0;
```
<prev>This sets the counter to be the variable i and sets it to zero.</prev>

# ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) C++

<b>There are 3 types of loops in C++.</b>
  * `for` loop
  *  `while` loop
  *  `do...while` loop
<b> SYNTAX </b>
```c++
for (initialization; condition; update) {
    // body of-loop 
}
```

   <prev> `initialization` - initializes variables and is executed only once
    `condition` - if true, the body of for loop is executed
    `if false`, the for loop is terminated
    `update `- updates the value of initialized variables and again checks the condition </prev>
<b> EXAMPLE FOR LOOP </b>
```c++
#include <iostream>

using namespace std;

int main() {
        for (int i = 1; i <= 5; ++i) {
        cout << i << " ";
    }
    return 0;
}
```
<a href="https://www.programiz.com/cpp-programming/for-loop">Reference</a>
