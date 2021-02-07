# 基础测试

## 选择题

-[question]:
winddow 控制台中输入：`python -V`，执行结果什么？
-[option]:
A 进入python命令行交互模式  
B 输出python的版本号  
答案: B
简写，等同于python --version


-[question]:
1 byte 等于多少 bit？
-[option]:
A 8  
B 2  
答案: A


-[question]:
一个汉字等于多少个字符？
-[option]:
 A 2个  
 B 与编码有关。一般2~4个  
答案: B

-[question]:
1 byte 等于多少 char
-[option]:  
 A 2
 B 0.5
答案: B


-[question]:
以下说法正确的是？
-[option]:
 A Python 是一种解释型语言  
 B Python 是交互式语言  
 C Python 是面向对象语言  
答案: ABC
Python 是一种解释型语言： 这意味着开发过程中没有了编译这个环节。类似于PHP和Perl语言。  
Python 是交互式语言： 这意味着，您可以在一个 Python 提示符 >>> 后直接执行代码。  
Python 是面向对象语言: 这意味着Python支持面向对象的风格或代码封装在对象的编程技术。  


-[question]:
以下说法正确的是？
-[option]:
A Python 3 源码文件以 UTF-8 编码，所有字符串都是 unicode 字符串
B Python 2 源码文件以 UTF-8 编码，所有字符串都是 unicode 字符串
答案：A


-[question]:  
```
a = 9//10
println(a)
```
以上代码执行结果为？  
-[option]:
A 1  
B 0  
答案：B  
//是整除，向下取整，直接删去小数。  


-[question]:  
`print("\a")`，以下说法正确的是：  
-[option]:
A \是转义符  
B 执行代码，电脑发出闹铃声  
答案：AB  
转义符\表示的\之后的字符是特殊字符，而不是a本身。  

-[question]:  
代码`print( R'a\nb' )`的输出结果为：  
-[option]:  
A a\nb  
B a换行，然后b  
答案：A  
r-string 会忽略字符串中的特殊字符，即转义符\代表的就是它本身，不进行转义  
参考：https://www.runoob.com/python3/python3-string.html  

-[question]:  
`a,b = b,a` 实现了什么功能？  
-[option]:  
A 交换a、b的值  
B 没有任何改变，a = b，b = b  
答案：A  

-[question]:  
`range(10)` 函数执行返回的是什么？
-[option]:  
A 一个列表   
B 一个迭代器对象
C 一个元祖
答案：B  
python 3 中range返回的是迭代器。Python2返回列表，如需迭代器需要使用 xrange










