# **DSAproductTable**

Final project for the DS&amp;A course.

#### By:
*Santeri* | *Aryan* | *Sebastian*

## Documentation

### Project Topic:

### Store Inventory

We can use lists stacks and queues for different kind of products, I.e., queues for managinig FIFO products, or stacks for products that don't mind waiting in shelves, and search algorithms to find the products themselves.

### The class HashTable has:

- **Arrays:** Used to create the table in self. table.
- **Linear Search:** Used I.e., in the add function to check if the key already exist.
- **Polymorphims:** Used I.e., in the search function, it acts differently depending on the nature of the object it encounters.
- **Collision Resolving Method:** Chaining collision method, which uses buckets that uses a list of lists for saving objects that share a key.
- **Linear Traversal:** In the show function, we use iteration to go over each linked hashtable and object.
- **Recursive Traversal:** In the simple show function.

### The class Product has:

- **Basic Data Structures:** Implements a basic class structure in Python.
- **Fundamental Algorithms:** The stock() and sell() methods implement basic algorithms for managing stock.

### The class freshProduct has:

- **Data Structures:** It implements a priority queue (heap) using heapq.
- **Algorithms:** It implements operations for stock management like stock() and sell().

### Time complexity and space complexity:

**Collision resolving method, chaining:** 
Uses a complexity of O(n). This method is implemented in the hash function and inherited in every other function called in the class.

**Dynamic Size for space complexity:** 
Chaining allows the hash table to potentially exceed its initial size in terms of the number of stored elements, as the lists can grow as needed to accommodate more entries. Furthermore, it is possible to make the table bigger (when creating it) to have better performance.
