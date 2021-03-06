[Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed/)

[B站视频](https://www.bilibili.com/video/BV1d7411w7hc)

### 命令模式 
蓝色 编辑模式进入命令模式：ESC

### 编辑模式
绿色 命令模式进入编辑模式：Enter

```python
print("hello world!")
```
    hello world!
    
```python
sum(range(101))
```
    5050

```python
1 + 2
```
    3

### 快捷键

shift+enter：运行当前代码块，且光标进入下面的代码块；

ctrl+enter：运行当前代码块，并且光标停留在当前代码块；

dd：删除当前代码块；

b：在下方添加一个空代码块；

a：在上方添加一个空代码块；

m：将编程语言代码块变成Markdown代码块；

y：将Markdown代码块变成编程语言代码块；

shift+m：将当前行与下一行合并；

两行之间相隔一行是通过换行来进行的。

### 添加超链接 

网站设置格式为：[网站名称] + (http://网址)

[python官网地址](http://www.python.org/)
[百度网址](http://www.baidu.com)

渲染图片设置格式为：! + [图片名称] + (http://网址)

![图片](https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1965980779,135999522&fm=26&gp=0.jpg)

### 列出目录格式为：破折号 或者 数字+.

- 第一点
- 第二点
3. 第三
4. 第四


### 渲染公式格式为：在两个$$之间编写公式，公式会居中显示，假如只有一个$之间，则靠左显示

$$z = x + y$$
$$\frac{2}{x + y}$$

### 使用tab键上面的三个飘符号 + python + 三个飘符号，可以在标记中编辑代码显示

```python
if __name__ == "__main__":
```

### 一个井号 + 空格为一级标题；两个井号 + 空格为两级标题；三个井号 + 空格为三级标题；

# 一级标题   
## 二级标题 
### 三级标题 

### 两个星号之间为加粗；一个星号之间为斜体

**加粗**
*斜体* 

### 表格设置方法：
```表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
- 两边加：表示文字居中
- 右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
