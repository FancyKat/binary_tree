# binary_tree

```python
    Example
                  8
                 / \
                3   10
               / \    \
              1   6    14
                 / \   /
                4   7 13
    >>> t = BinarySearchTree().insert(8, 3, 6, 1, 10, 14, 13, 4, 7)
    >>> print(" ".join(repr(i.value) for i in t.traversal_tree()))
    8 3 1 6 4 7 10 14 13
    >>> print(" ".join(repr(i.value) for i in t.traversal_tree(postorder)))
    1 4 7 6 3 13 14 10 8
    >>> BinarySearchTree().search(6)
    Traceback (most recent call last):
    ...
    IndexError: Warning: Tree is empty! please use another.
    """
```python
