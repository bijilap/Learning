### Numpy

* **numpy.exp**
```
numpy.exp(x[, out]) = <ufunc 'exp'>
```
Calculate the exponential of all elements in the input array.

```
Parameters:	
`x` : array_like
Input values.
Returns:	
out : ndarray
Output array, element-wise exponential of x.
```

* **numpy.sum**

```
numpy.sum(a, axis=None, dtype=None, out=None, keepdims=False)[source]
```

Sum of array elements over a given axis.

```
Parameters:	
a : array_like
Elements to sum.
axis : None or int or tuple of ints, optional
Axis or axes along which a sum is performed. The default (axis = None) is perform a sum over all the dimensions of the input array. axis may be negative, in which case it counts from the last to the first axis.
New in version 1.7.0.
If this is a tuple of ints, a sum is performed on multiple axes, instead of a single axis or all the axes as before.
dtype : dtype, optional
The type of the returned array and of the accumulator in which the elements are summed. By default, the dtype of a is used. An exception is when a has an integer type with less precision than the default platform integer. In that case, the default platform integer is used instead.
out : ndarray, optional
Array into which the output is placed. By default, a new array is created. If out is given, it must be of the appropriate shape (the shape of a with axis removed, i.e., numpy.delete(a.shape, axis)). Its type is preserved. See doc.ufuncs (Section “Output arguments”) for more details.
keepdims : bool, optional
If this is set to True, the axes which are reduced are left in the result as dimensions with size one. With this option, the result will broadcast correctly against the original arr.
Returns:	
sum_along_axis : ndarray
An array with the same shape as a, with the specified axis removed. If a is a 0-d array, or if axis is None, a scalar is returned. If an output array is specified, a reference to out is returned.
```

