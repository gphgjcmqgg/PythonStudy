# PythonStudy

Python学习

python
a=0
exit()

## pip管理

pip list     列出匹配管理的包有哪些
pip install 包名
pip install 包名==版本号
pip uninstall 包名
pip -V  查看版本
pip freeze > requirements.txt   将项目依赖的包输出到指定的requirements.txt
pip install -r requirements.txt 使用pip安装requirements.txt中依赖的文件

Python (解释器+lib+pip)组成
***.py（windows） ---> 源文件 ---> Linux安装python3
-- 执行源代码
python *.py

## python环境变量

D:\Program Files\Python\Python38
D:\Program Files\Python\Python38\Scripts

升级pip
python -m pip install --upgrade pip
pip安装包的路径
D:\Program Files\Python\Python38\Lib\site-packages

## python变量

python是弱类型的,赋什么值就是什么类型
money = 99.9
money = '9.9元'
money = 9
count = 5
person = '小明'

### type(变量名) 返回该变量的类型

print(money, type(money))

## print的使用

print(name,age,gender)  # sep默认的分割是空格
print(name,age,gender,sep='-')
print('AAA', end='')  # 取消默认换行
print('BBB', end='')
print('CCC', end='')
print(r'hello\py\thon')   # r''    原样输出字符串

## 转义字符

\n和\r都是特殊控制符，都是来自于老式电传打字机的功能
\n是newline开个新行
\r是carriage return，打印头回到行首。如果没有\n就直接\r那么这行就会被覆盖打印了
\r的功能就是让光标回到行首，覆盖之前的内容。

