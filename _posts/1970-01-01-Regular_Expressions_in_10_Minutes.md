---
layout: default
title: Regular Expressions
category: Regular Expressions
---

什么是正则表达式？

**常用元字符**
|代码 |说明                       |
|-----|---------------------------|
|.    |匹配除换行符以外的任意字符 |
|\w   |匹配字母或数字或下划线     |
|\s   |匹配任意的空白符           |
|\d   |匹配数字                   |
|\b   |匹配单词的开始或结束       |
|^    |匹配字符串的开始           |
|$    |匹配字符串的结束           |

**常用限定符**

|代码/语法 |说明                  |
|----------|----------------------|
|*         |重复零次或更多次      |
|+         |重复一次或更多次      |
|?         |重复零次或一次        |
|{n}       |重复n次               |
|{n,}      |重复n次或更多次       |
|{n,m}     |重复n到m次            |

**常用反义词**
|代码/语法 |说明                                       |
|----------|-------------------------------------------|
|\W        |匹配任意不是字母，数字，下划线，汉字的字符 |
|\S        |匹配任意不是空白符的字符                   |
|\D        |匹配任意非数字的字符                       |
|\B        |匹配不是单词开头或结束的位置               |
|[^x]      |匹配除了x以外的任意字符                    |
|[^aeiou]  |匹配除了aeiou这几个字母以外的任意字符      |

在线测试工具

### 书籍推荐
入门：

《正则表达式必知必会》[勘误表](http://www.ituring.com.cn/book/509)
*Sams Teach Yourself Regular Expressions in 10 Minutes*, [errata](http://www.forta.com/books/errata.cfm?p=30)

深入：
《精通正则表达式》
*Mastering Regular Expression*, errata





