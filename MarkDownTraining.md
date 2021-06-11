Markdown 練習
======


 標題
======
> # 標題語法有兩種
>   *   ## Setext
>   1.  最高階標題
>   2.  第二階標題
>   *   ## atx
>   


最高階標題
=
> 利用 " = "
>  This is an H1
>  =



第二階標題
=
> 利用 "－"
> 　This is an H2
> 　-



atx標題
=
> 利用 " #"
>  在行首插入1 ~ 6 個 # ，對應到標題 1 到 6
>  # This is an H1
>  ## This is an H2
>  ### This is an H3
>  #### This is an H4
>  ##### This is an H5
>  ###### This is an H6


區塊引言
=
> 利用">"
> 1. 每行前面加上 ">"
> > This is a book.
> > That is another book.
> 
> 2. 整個段落的第一行最前面加上 ">"
>  >This is a book.
> That is another book.
> 
>  3.  階層引言
>  引言內的引言
>  
>  4. 包含其他的 Markdown 語法: 標題、清單、程式碼區塊帶


清單
=
> 1. 有序清單
> 使用數字加英文句點
> 
> 2. 無序清單
> 使用星號、加號或是減號
> 
> 3. 清單中，每項的段落使用"tab"
> * 123
> 
>     123       
> * 456
> * 789



1986\. What a great season.





分隔線
=

***
---

This is an [example](https://tw.yahoo.com/  "yahoo") inline link.

I get 10 times more traffic from [Google] [1] than from [Yahoo] [2] or [MSN] [3].

[1]: http://google.com/                     "Google"
[2]: http://search.yahoo.com/         "Yahoo Serarch"
[3]: http://search.msn.com/            "MSN Search"



強調
=
single asterisks
*single asterisks*
_single asterisks_
**single asterisks**
__single asterisks__


















3.  

# 項目清單 List

目錄
------
+ 準備軟體
+ 常用語法
+ 文檔格式



準備軟體
------
+ 文本編輯器
+ Markdown 檢視器



###  文本編輯器

`記事本、Notpad++、Sublime Text、VSCode、Typora、Vim ...etc`

![text-editor](assets/002/P_20201001_203141.jpg)



程式碼
=
```markdown
### H3 子標題

**01**

內文

```


```
Text - 文字說明
```

```java
// Java Code
System.out.println("Hello Word");
```

```diff
+ System.out.println("Hello Word");
- System.out.println("Hello Word");
```

