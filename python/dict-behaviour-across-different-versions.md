# Python dicts behavior across different versions

The CPython implementation of Python 3.6 retains the order
in which the items are inserted. So the items in the dict
would be iterated in the same order as they inserted.
In 3.7 this became a Python language feature.
