# Binary Search Trees

In this assignment you'll be completing the imperative binary search tree implementation started/outlined in the lecture videos M07-L03. For the purposes of this assignment, the tree you develop will not store duplicated items. All methods are to be recusive unless otherwise specified.

## Initial Setup

Create a class `BinarySearchTree` that is parameterized by a generic type parameter, `T` that `extends Comparable<T>`. 
Next you'll need a `Node` class that stores both the data for a given node in the tree as well as its left and right children. Your `BinarySearchTree` class should maintain a field, `Node root`, that stores a reference to the root of the tree as well as a constructor that takes no parameters and initializes the `root` to null.

### Required Operations

Your binary search tree class should export the following (`public`) methods: 

#### `insert(x)`

This method takes a piece of data `x` of type `T` and adds it to the tree as outlined in lecture (returns nothing). 
Throw an `IllegalArgumentException` if `data` already exists in the tree.

#### `delete(x)`

This method takes a piece of data `x` of type `T` and deletes it from the tree using the approach outlined in lecture. The method should return nothing. Throw an `IllegalArgumentException` if the data doesn't exist within the tree. 

#### `contains(x)`

Returns `true` only if `data` exists in the tree; `false` otherwise.

#### `toString()`

Your class should provide a toString method that recursively renders the tree using a pre-order traversal (you can use a helper method if needed to accomplish this).

#### `partition(data)`

This method takes no formal parameters but should return an arraylist containing all items in the tree that are >= to `data`

### Unit Testing

Your tests should cover all the methods described above. I won't prescribe a fixed number other than to say that they should convince you that the they are working. 

## Handin

When you are ready to submit (or simply want to 'checkin' your work for the day), open the terminal, cd to the project directory, make a commit by typing:

> git commit -am "message goes here"

then follow this up with a

> git push origin main
