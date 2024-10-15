The Binary Search Tree has three functions. To start using the BST function, users will first create an instance of the class, by assigning it to a variable, e.g.

new_tree = BinarySearchTree()

Insert 
To insert a new key, use the following format:

new_tree.insert(key, value)

Search
To search for a key, use the following:

result = new_tree.search(key)
print(result)

It will return the value of the key if found. If the key does not exist, it will return "None"

Delete
To delete a key, type:

new_tree.delete(key)

Inorder_traversal
To print all keys and their associated values in sorted order, use:

new_tree.inorder_traversal()
