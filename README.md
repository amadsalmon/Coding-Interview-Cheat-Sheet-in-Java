# Coding Interview Cheat Sheet (in Java)
A list of useful information and code snippets to be well-prepared for your coding interview.

[TOC]

## Types

### String 

### StringBuilder

### Integer

### BigInteger





## Data Structures

### Array

#### HashMap

#### HashSet 

##### Constructors

```java
HashSet<E> hs = new HashSet<E>();
```
```java
// The initial capacity means the number of buckets when hashtable (HashSet internally uses hashtable data structure) is created. The number of buckets will be automatically increased if the current size gets full. 

HashSet<E> hs = new HashSet<E>(int initialCapacity);
```
```java
// The load factor is a measure of how full the HashSet is allowed to get before its capacity is automatically increased. When the number of entries in the hash table exceeds the product of the load factor and the current capacity, the hash table is rehashed (that is, internal data structures are rebuilt) so that the hash table has approximately twice the number of buckets.

HashSet<E> hs = new HashSet<E>(int initialCapacity, float loadFactor);
```
```java
HashSet<E> hs = new HashSet<E>(Collection C);
```

##### Methods
```java
add();
```
```java
remove();
```
```java
contains();
```
```java
size();
```
```java
isEmpty();
```
```java

```

##### Example

```java
// Instantiate an object of HashSet 
HashSet<String> hs = new HashSet<String>(); 

// Elements are added using add() method 
hs.add("A"); // returns 'true'
hs.add("B"); // returns 'true'
hs.add("A"); // returns 'false' as "A" was already in the Set
```




### List
#### LinkedList

#### ArrayList



## Algorithms

### Arrays

#### 



### Binary

-   Test kth bit is set: `num & (1 << k) != 0`.
-   Set kth bit: `num |= (1 << k)`.
-   Turn off kth bit: `num &= ~(1 << k)`.
-   Toggle the kth bit: `num ^= (1 << k)`.
-   To check if a number is a power of 2, `num & num - 1 == 0`.



### Dynamic Programming

### Graphs

### Heaps

### LinkedLists

#### Notes

#### Common approaches

-   Getting the kth from last node - Have two pointers, where one is k nodes ahead of the other. When the node ahead reaches the end, the other node is k nodes behind
-   Detecting cycles - Have two pointers, where one pointer increments twice as much as the other, if the two pointers meet, means that there is a cycle
-   Getting the middle node - Have two pointers, where one pointer increments twice as much as the other. When the faster node reaches the end of the list, the slower node will be at the middle

#### Edge cases

-   Single node
-   Two nodes
-   Linked list has cycle. 
    **Tip:** Clarify with the interviewer whether there can be a cycle in the list. Usually the answer is no

### Matrixes

### Queues

### Sorting

### Searching

### Stacks

### Strings

### Trees



