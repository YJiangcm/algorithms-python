# Algorithms based on Python
使用python编写的部分算法题目整理

## 输入输出流
print(""" """) # 跨行打印字符串 \
print(x, end=' ') # 以空格为间隔输出 \
print('%.2g' % 1111.1111)  # 取2位有效数字，自动转换为科学计数法 \
print("{:0.3f}".format(n)) # 保留小数点后三位 \
print("%.1f %.1f"%(a, b)) # 同时格式化输出a和b

## 有关字母
a.upper() # 转大写字母 \
a.lower() # 转小写字母 \
ord(a) # 字母的ASCII顺序  \
chr(ord(a)+i) # ASCII顺序转字母

## 列表
list[: : -1] # 列表，字符串反转 \
list.reverse() # 反向列表中元素，直接在原列表上的操作 \
list.pop([index=-1]) # 按照元素位置弹出， 默认弹出最后一个元素 \
list.remove(obj) # 删除第一个该元素 \
list.sort(cmp=None, key=None, reverse=False) # 默认按照从小到大排序 \
list.index(obj) # 从列表中找出某个值第一个匹配项的索引位置 \
list.insert(index, obj) # 将对象插入列表 \
list.count(obj) # 统计某个元素在列表中出现的次数 \
list.append(obj) # 在列表末尾添加新的对象 \
list.extend(seq) # 在列表末尾一次性追加另一个序列中的多个值（用新列表扩展原来的列表）

## 字符串
string.count(str, beg=0, end=len(string)) # 返回 str 在 string 里面出现的次数，如果 beg 或者 end 指定则返回指定范围内 str 出现的次数\
string.find(str, beg=0, end=len(string)) # 检测 str 是否包含在 string 中，如果 beg 和 end 指定范围，则检查是否包含在指定范围内，如果是返回开始的索引值，否则返回-1\
string.replace(str1, str2,  num=string.count(str1)) # 把 string 中的 str1 替换成 str2,如果 num 指定，则替换不超过 num 次\
max(str) #  返回字符串 str 中最大的字母\
min(str) #  返回字符串 str 中最小的字母

## math包
math.floor(x) # 向下取整 \
math.ceil(x) # 向上取整 \
math.sqrt(x) # 求算术平方根 \
math.exp(x) \
math.log(x) \
math.sin(x)
