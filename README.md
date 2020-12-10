# Algorithms based on Python
使用python编写的部分算法题目整理

## 输入输出流
print(""" """) # 跨行打印字符串 \
print(x, end=' ') # 以空格为间隔输出 \
print('%.2g' % 1111.1111)  # 取2位有效数字，自动转换为科学计数法 \
print("{:0.3f}".format(n)) # 保留小数点后三位 \

## 有关字母
a.upper() # 转大写字母 \
a.lower() # 转小写字母 \
ord(a) 

## 列表
list[: : -1] # 列表，字符串反转 \
list.pop() # 按照元素位置弹出， 默认弹出最后一个元素 \
list.remove() # 删除第一个该元素 \
list.sort() # 默认按照从小到大排序

## math包
math.floor(x) # 向下取整 \
math.ceil(x) # 向上取整 \
math.sqrt(x) # 求算术平方根 \
