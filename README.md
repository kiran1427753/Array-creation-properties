# Array-creation-properties
import numpy as np

arr1 = np.array([[1,2],[3,4]])

arr2 = np.array([[5,6],[7,8]])

print("Original 1D Array:", arr1D)

print("Shape:", arr1D.shape)

print("Size:", arr1D.size)

print("Data Type:", arr1D.dtype)

print("no.of dimensions:",arr1D.ndim)

print("identity matrix:",np.identity(6))

print("identity like matrix:",np.eye(6,4))

O/P:

Original 1D Array: [1 2 3 4 5]

Shape: (5,)

Size: 5

Data Type: int32

no.of dimensions: 1
identity matrix: [[1. 0. 0. 0. 0. 0.]

[0. 1. 0. 0. 0. 0.]

[0. 0. 1. 0. 0. 0.]

[0. 0. 0. 1. 0. 0.]

[0. 0. 0. 0. 1. 0.]

[0. 0. 0. 0. 0. 1.]]

identity like matrix: [[1. 0. 0. 0.]

[0. 1. 0. 0.]

[0. 0. 1. 0.]

[0. 0. 0. 1.]

[0. 0. 0. 0.]

[0. 0. 0. 0.]]
