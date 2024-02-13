# Introduction To Data Structure

- [Go to Index][index]
- [Previous][previous]
- [Next][next]

[index]: ../Index.md
[next]: ../Data%20Structures/Linear_Data_Structure/1.Array.md
[previous]: ../Index.md

## Introduction :
- "Computer Science" can be defined as the "Study of Data", "its representation" and "transformation".
- "A Structured Datatype" which may be combination or collection of "basic data types" with a "set of properties" and "legal operations" that may be performed on it is called "Abstract Data Type (ADT)".
- Depending upon the Application, the DataType has to be given to how the data is to be stored so that there is "efficient storage" , "Convienient and Faster Retrieval" and "Manipulation ", is called Time and Space consideration.

## Some Important Concepts :
1. **Data Type** :
    - DataType is "a term" used to describe the "information type" that can be processed by the Computer.
    - e.g. int , char, float etc.
    - Some programming languages allows to combine built-in DataTypes.
    - e.g. Structures and Unions in C language.

2. **Data Object** :
    - Data Object refers to a "set of Elements(D)" which may be finite or infinite.
    - If set is infinite, we have to "devise some mechanism to represent that set" in memory since availabile memory is limited.

3. **Data Structure**:
    - Data Structure consist of "data objects", "their properties" and the "set of legal operations" which may be applied to the element of the data objects.
    
        _Definition_: 
        - A Data Structure is a set of Domain 'D', a designated domain " 'd' belongs to 'D'" , a set of function 'F' and a set of axioms 'A'.
        - A triple( D, F, A) denotes the Data Structure.
        - This defination is also called Abstract Data Types
        - Here, 
            D : denotes the Data Objects
            F : denotes the Set of Operations that can carried out on data objects
            A : describe Properties and Rules of operations

## Implementation of a Data Structure:
- A Data Structure may be implemented by using another data structure 'e'.
- Thus an implementation of 'd' is a mapping from 'd' to a set of other data structure 'e'.
- This mapping specifies,
    1. How every objects of 'd' is to be represented by object of 'e'?
    2. Every function of 'd' must be written using functions of data structure 'e'. However, all the operations possible on 'e' may not be valid or may not be allowed for 'd'.
- e.g. For implementation of **Queue** which is sequential Storage of Data following the rule.
    1. Data can only be added to the end of the queue.
    2. Data can be removed only from the front.
    
    

## Hello World Program in C++
```cpp
#include<iostream.h>

int main(int argc, char **argv){
    std::cout<<"Hello world"<<endl;
}
```
