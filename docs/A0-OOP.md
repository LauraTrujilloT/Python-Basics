# Appendix 0 : Object Oriented Programming (OOP)
#### Last edit by @lvtrujillot

Python is an OOP! Meaning that almost everything is an object (with properties and methods)... But what exactly is an object? And what's the difference between an object and a Class?

## Python Objects

Basically, objects are collection of data, since they have _variables_ that described them and _methods_, which are nothing but functions that act on those data. Additionally, this collection of data points to a specific location in memory. However, there are a lot of insights about objects but let's keep it simple for now.

So, if almost everything is an object in python... What about numbers? Are they objects as well? 

```python
>> isinstance(1, object)
True
```

The function `isinstance()` is comparing the type of the number 1 with the type `object` and, as we can see, numbers are also objects.

## Python Classes


> To understand more deeply those new concepts, see [Python Data Model](https://docs.python.org/3/reference/datamodel.html)
