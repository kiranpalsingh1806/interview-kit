# Interview Kit

Prepare for interviews in easier way

- [Interview Kit](#interview-kit)
  - [1. What is Sharding?](#1-what-is-sharding)
  - [2. What is the difference between low level and high level language?](#2-what-is-the-difference-between-low-level-and-high-level-language)
  - [3. What is Kernel?](#3-what-is-kernel)
  - [4. What is Consistent Hashing?](#4-what-is-consistent-hashing)

## 1. What is Sharding?

<details>
  <summary>Answer</summary>

Sharding is a very important concept that helps the system to keep data in different resources according to the sharding process. The word “Shard” means “a small part of a whole“. Hence Sharding means dividing a larger part into smaller parts.  
In DBMS, Sharding is a type of DataBase partitioning in which a large database is divided or partitioned into smaller data and different nodes. These shards are not only smaller, but also faster and hence easily manageable.

</details>

## 2. What is the difference between low level and high level language?

<details>
  <summary>Answer</summary>

Machine Code could probably be considered the lowest level programming language.
Assembly language is at the level of telling the processor what to do. There is still a conversion step towards machine code.

C is a step up from assembler, because you get to specify what you want to do in slightly more abstract terms, but you're still fairly close to the metal.
C++ does everything that C can do but adds the capability to abstract things away into classes.

Java/C# do similar things to C++ in a way, but without the opportunity to do everything you can do in C (like pointer manipulation in Java's case [thanks Joe!]). They have garbage collection though, which you have to do manually in C++.
Python/Ruby are even higher level, and let you forget about a lot of the details that you would need to specify in something like Java or C#.
SQL is even higher level (it's declarative). Just say "Give me all the items in the table sorted by age" and it will work out the most efficient way to carry this out for you.

</details>

## 3. What is Kernel?

<details>
<summary>Answer</summary>
Kernel is central component of an operating system that manages operations of computer and hardware. It basically manages operations of memory and CPU time. It is core component of an operating system. Kernel acts as a bridge between applications and data processing performed at hardware level using inter-process communication and system calls.

Kernel loads first into memory when an operating system is loaded and remains into memory until operating system is shut down again. It is responsible for various tasks such as disk management, task management, and memory management.
</details>

## 4. What is Consistent Hashing?

<details>
<summary>Answer</summary>
Consistent Hashing is a distributed hashing scheme that operates independently of the number of servers or objects in a distributed hash table. It powers many high-traffic dynamic websites and web applications.
</details>

[Read More](https://www.toptal.com/big-data/consistent-hashing)
