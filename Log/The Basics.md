# The Basics

***

## 导入Numpy库
```
import numpy as np    # 导入numpy包定义别名为np
```

## 基本属性

### arange
```
print(np.arange(10))
# arange -> ndarray ：生成一个类似于C语言的一维数组
```
### array
```
print(np.array([1,2,3,4,5,6,7,8,9]))
# array -> ndarray ：生成一个类似于C语言的一维数组

print(np.array([[1,2,3], [4,5,6], [7,8,9]]))
# array -> ndarray ：生成一个类似于C语言的多维数组
```
### shape
```
print(np.arange(10).shape)
print(np.array([[1,2,3], [4,5,6], [7,8,9]]).shape)
# shape -> int ：返回当前矩阵的维度和元素个数
```
### ndim
```
print(np.arange(10).ndim)
print(np.array([[1,2,3,4], [5,6,7,8]]).ndim)
# ndim -> int ：返回当前矩阵的维度
```
### size
```
print(np.arange(10).size)
print(np.array([[1,2,3], [4,5,6], [7,8,9]]).size)
# size -> int ：返回矩阵的元素总数
```
### dtype
```
print(np.arange(10).dtype)
print(np.array([[1,2,3], [4,5,6], [7,8,9]]).dtype)
# dtype -> object ：返回矩阵中元素类型的对象
```
### itemsize
```
print(np.arange(10).itemsize)
print(np.array([[1,2,3], [4,5,6], [7,8,9]]).itemsize)
# itemsize -> int ：返回矩阵中每个元素的大小（以字节为单位）
```
### data
```
print(np.arange(10).data)
print(np.array([[1,2,3], [4,5,6], [7,8,9]]).data)
# itemsize -> boject ：返回矩阵的实际元素的缓冲区
```
