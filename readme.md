Data Structure

Types of DS:

Defintions:
1. linear data structure: is a way of organizing data elements sequentially. Think of it like a single-file line to get to the fourth person, you generally have to pass the first three. You can visit every element by starting at the beginning and moving to the end.

Arrays: are the most fundamental linear data structure because they store elements in a continuous block of memory. This "side-by-side" arrangement is what makes them incredibly fast for certain tasks and more restrictive for others. One way to use Arrays if you need to access elements frequently by their position. 

linked list: is more like a scavenger hunt. Each piece of data (called a node) is stored in a random spot in memory, and it contains a "map" (a pointer) telling the computer where to find the next one.

Stacks: is a linear data structure that follows a specific order for adding and removing elements LIFO (Last In, First Out).


Queue: is a linear data structure that follows the FIFO (First In, First Out) principle. It is the exact opposite of a stack.A queue primarily uses two actions to manage data:


2. Non linear Data structure (DS): organize data in a way where an element can be connected to several other elements. This creates a hierarchical or interconnected relationship rather than a straight line.

Trees: is a hierarchical structure where data is organized into nodes connected by edges. It starts with a single "Root" node, and every node can have "Children."

Graphs:are the most versatile non-linear structure. They consist of a finite set of vertices (nodes) and edges (the lines connecting them). Unlike trees, graphs can have cycles—you can start at one node and follow a path back to it.

Heaps: is a specialized tree-based structure that satisfies the "Heap Property.

"Max-Heap: The parent node is always greater than or equal to its children (the largest value is at the root).

Min-Heap: The parent node is always smaller than or equal to its children (the smallest value is at the root)

Heaps are commonly used to implement Priority Queues or for sorting algorithms like Heap Sort.