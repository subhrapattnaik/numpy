import numpy as np

arr1 = np.array([[1, 2], [3, 4]])
print(arr1)

arr2 = np.array([[5, 6], [7, 8]])
print(arr2)

#join column wise if axis=0 --display column wise-this is by default
arr3 = np.concatenate((arr1, arr2), axis=0)
print(arr3)


#join row wise if axis=1 --display rowwise
arr4 = np.concatenate((arr1, arr2), axis=1)
print(arr4)




