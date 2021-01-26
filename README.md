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

### Binary

### Dynamic Programming

### Graphs

### Heaps

### LinkedLists

### Matrixes

### Queues

### Sorting

### Searching

### Stacks

### Strings

### Trees



