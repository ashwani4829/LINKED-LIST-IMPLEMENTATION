# Singly Linked List in C

**Author:** Ashwani Dwivedi
**Intern ID:** CT04DG1794
**Company:** CODTECH IT SOLUTIONS
**Mentor:** Neela Santosh
**Domain:** C Programming
**Duration:** 4 Weeks

---

## Overview

A menu-driven C program demonstrating key operations on a singly linked list using dynamic memory allocation.

---

## Features

* Insert at beginning, end, or after a value
* Delete by value
* Traverse and display list
* Free memory on exit
* Input validation and error handling

---

## Technologies Used

* C Language
* `stdio.h`, `stdlib.h`

---

## File Structure

```
singly_linked_list.c   # Source code  
README.md              # Documentation  
```

---

## Compile & Run

```bash
gcc linked_list.c -o linkedlist
./linkedlist
```

---

## Example

```
Add 10 at beginning → 10 -> NULL  
Add 20 at end → 10 -> 20 -> NULL  
Add 15 after 10 → 10 -> 15 -> 20 -> NULL  
Delete 15 → 10 -> 20 -> NULL
```

---

## What I Learned

* Using `malloc()` and `free()` for dynamic memory
* Pointer-based data structures
* Modular function-based C code
* Preventing memory leaks and handling input safely