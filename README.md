# ShoppingList App – List ADT Assignment

## Overview

This project implements a simple **Shopping List application** in Java using a custom **List Abstract Data Type (ADT)**.  
The goal of the assignment is to demonstrate:

- Programming to an **interface**, not an implementation
- Maintaining a list in **sorted order** using a custom comparison
- Using **iterators** to traverse a list
- Hiding data structure details (array vs. linked) behind a List ADT abstraction

The application allows users to add grocery items, view the current shopping list, and “shop” items one by one in sorted aisle order.

---

## Learning Objectives

This assignment demonstrates the ability to:

- Explain how a **List ADT** differs from a generic collection or set
- Use `ListInterface<T>` to build an application without relying on concrete data structures
- Maintain sorted order using a custom `Comparable` implementation
- Traverse a list using an **iterator**
- Switch between different list implementations with minimal code changes

---

## Design and Architecture

### Programming to an Interface

The core data structure is declared using the interface type:

```java
ListInterface<ShoppingItem> shoppingList;