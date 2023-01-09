# Class Notes Week 8
https://www.jgrasp.org/eclipse_plugin.html#install 

debugger and shows data structures

## Linked Lists
- shows how things are linked
- one think in a list points to another thing in a list

![IMG_8469](https://user-images.githubusercontent.com/102199778/194918953-4d42e66b-dad7-4049-bcc1-620ac7180507.jpg)


## Big-O Complexity 
<img width="825" alt="Screen Shot 2022-10-10 at 11 52 39 AM" src="https://user-images.githubusercontent.com/102199778/194916608-7f9f12dd-7977-43fd-aa09-2827a0d31da9.png">

https://www.bigocheatsheet.com

- memory or CPU
    - inite space
    - limited in computation 
- O of 1
    - constant 
- O(n)
    - grows linearly with input size
    - 1 sec to process 1 string
    - 2 sec to process 2 strings
- O(n)^2
    - space required grows exponentially 
    - not good


<img width="597" alt="Screen Shot 2022-10-10 at 12 03 48 PM" src="https://user-images.githubusercontent.com/102199778/194918656-6a6c83c8-00de-44e5-9537-256441b4743a.png">

## Array vs ArrayList
- both are data structures
- ArrayLists use Arrays
- ArrayLists offers more functionality

### Array
- static in size

### ArrayList
- dynamic in size
- can not have primitive data types
- Type safety is ensured with use of generics
- expand by 1.5 * current size of the array

## Collection Interface
- Collection is a bad of objects

https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collections.html 

## List Interface
Example: 
![IMG_8471](https://user-images.githubusercontent.com/102199778/194920104-f848d534-738a-42a5-9fc3-215ad43fa180.jpg)

- ordered collection
- duplicates
- Java API: List interface

## Single vs Double Linked Lists
- double allows going forward and backwards 

## When to use linked list
- best used when adding and removing items frequently

## Why linked lists are useful
- when adding and removing items a new array does not have to be reallocated when the bounds are reached

## Collection vs Collections
- Collection interface
    - the root of the JCF hierarchy
- Collections class
    - provides many static methods

### How this works with linked list
- LinkedList class is a member of the Collections Framework
- LinkedList implements the Collection Interface 
