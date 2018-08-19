---

title:  python--while循环、for循环
categories: Python
tags: [while循环,for循环]

---

### **1、while循环**

#### **while 循环的基本格式**

  1、变量的初始化

  while 条件2:

​      条件满足时候:执行该代码

​      条件满足时候:执行该代码

​      **3****变量的更新**

### **2、while 循环的应用**

#### 1、while循环输出

while循环输出20次我爱你

![](https://raw.githubusercontent.com/voicezyxzyx/voicezyxzyx.github.io/master/images/5.png)

#### 2、while循环输出1-100累加和

\# 1-100之间所有数的和
\# 1变量的初始化
i = 0
sum = 0 #存储和
\# 判断条件
while i <= 100:
    sum += i  # sum = sum +i   求和
    # 变量的更新
    i += 1
print(sum)

3、输出1-100之间偶数的和

\# 1-100之间偶数的和
\# 1变量的初始化
i = 0
sum = 0 #存储和
\# 判断条件
while i <= 100:
    if i % 2 == 0:  # 是否是偶数
        sum += i  # sum = sum +i   求和
    # 变量的更新
    i += 1
print(“1-100之间所有偶数的和%s”%sum)

### **3、while循环嵌套(了解)**

while嵌套的 while里面还有while

While 执行一次  ,里面多次

**While嵌套的基本的格式（了解）**

while 条件1

条件1满足时,执行该代码

条件1满足时,执行该代码

while 条件2：

条件2满足时，执行该代码

外部的while 循环一次，里面的while循环多次

**外边的while 循环一次，里面的while循环多次**

#### **1、使用while循环打印三角形的练习**

![](https://raw.githubusercontent.com/voicezyxzyx/voicezyxzyx.github.io/master/images/6.png)

第一行  1     星星的个数 行数是一样

第二行  2

第三行  3

第四行   4

第五行  5

用一个while 也可以实现

![](https://raw.githubusercontent.com/voicezyxzyx/voicezyxzyx.github.io/master/images/7.png)

#### **2、九九乘法表**

1 * 1 = 1

1 * 2 = 2    2 * 2 =4

1 * 3 =3     2 * 3 =6  3 * 3 =9

前面的数  星星的个数   * 行数     =

![](https://raw.githubusercontent.com/voicezyxzyx/voicezyxzyx.github.io/master/images/8.png)

注意：外层执行一遍，内层执行多次

### 4、for循环

像while循环一样，for可以完成循环功能

python中可以用for循环遍历任何系列的项目,如果一个列表或一个字符串

#### for 循环的基本格式

For  变量  in  数据

​     代码

```
for i in range(0,11):
    print(i,end=" ")
```

### 5、扩展

range(start,stop) 函数可创建一个整数int列表，一般用在 for 循环中。

1. start: 计数从 start 开始。默认是从 0 开始。例如range（5）等价于range（0， 5）
2. stop: 计数到 stop 结束，但不包括 stop。例如：range（0， 5）是[0, 1, 2, 3, 4]没有

例如：

range(5)  ====range(0,5)     ===0,1,2,3,4

range(3,9)   3  4 5 6 7 8

range(1,100)  1 2 3 4...99

### 6、break 和continue作用

注意：break continue 结合 条件判断     满足一定的条件，退出

break 退出的是相关的所有的循环

Continue 退出是当前的循环，进入下一次循环