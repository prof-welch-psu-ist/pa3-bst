# Binary Search Trees

In this assignment you'll be completing the imperative binary search tree implementation started/outlined in the lecture videos M07-L03. For the purposes of this assignment, the tree you develop will not store duplicated items.

## Initial Setup

Create a class `BinarySearchTree` that is parameterized by a generic type parameter, `T`, that `extends Comparable<T>`. 
Next you'll need a `Node` class that stores the data for the node and it's left and right children. Your `BinarySearchTree` class should maintain a field `Node root;` that 
stores a reference to the root of the tree as well as a constructor that takes no parameters and initializes the `root` to null.

### Required Operations

Your binary search tree class should export the following (`public`) methods: 

#### `insert(x)`

This method takes a piece of data `x` of type `T` and adds it to the tree as outlined in lecture. Throw an `IllegalArgumentException` if `data` already exists in the tree.

#### `delete(x)`

This method takes a piece of data `x` of type `T` and deletes it from the tree using the approach outlined in lecture. The method should return nothing. Throw an `IllegalArgumentException` if the data doesn't exist within the tree. 

#### `contains(x)`

Returns `true` only if `data` exists in the tree; `false` otherwise.


