# Learn about HTML 
 I decide to use this repository to record my way of learn html

### The basic and background 

a type of standard language to create web page
**H**yper**T**ext **M**arkup **L**anguage 超文本语言

不是编程语言，是标记语言



.html and .htm no difference 

![image.png](https://flowus.cn/preview/317b0043-4ac0-49ff-802f-131fda47076f)



meta 元数据 charset 编码格式 中文网页注意使用<utf-8> 有些浏览器默认的<gbk>格式

#### tell the type <!DOCTYPE html>

![image.png](https://flowus.cn/preview/33ae7b8d-f09a-40b0-bdc8-74d7412ab9a0)



#### The basic code of html

```HTML
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title> Hello World </title>  //声明title 中间的内容  '/' 这个斜杠
</head>
  
<body>
  <h1> The first title </h1>
  <p> content </p>
</body>
  
  
</html>

```




#### SoftWare to code

I choose the VS , beacuse it's my first software when I touch the code and the firste code language is C++.

I hope I can keep up in this way.



#### basic knowlege 

Html tile 

<h1>   </h1>

<h2>   </h2> 

it like the shortcuts

Html paragraph 

<p>   </p>



Html link 

**<**a href="http://github.com"**>** this is a link **</a>**

add target="_blank" the new link will open in the new window

targer="_top" the new link will open in the current window

add id


```HTML
<a id="tips"> 跳转到这  </a>

<!--注意我们引用id要加#-->
<a href="#tips">这里设置的链接会跳转到我们设置的id处   </a>
```






```HTML
<a href="http://github.com">
  <img border="0" src="  " alt="github.com"  width="32"  height="32" </a>
```


Html pictures 
<img decoding="async" src="/images/logo.png" width="258" height="39" />

Html  insensitive to case 



wrap(换行)

<br />

horizontal line
<hr>

note 

<!-- explanation  -- >



Text formatting

Bold(加粗) <b> </b> <strong> </strong>
amplify(放大) <big> </big>
italic(斜体)<em> </em> <i></i>

下标<sub> </sub>

上标<sup></sup>



<pre> </pre> 我输入多少空格就显示多少空格，不会过滤掉
引用句<q></q>



![image.png](https://flowus.cn/preview/8036a46c-5746-4d8e-9d40-4012e03e20a9)











#### The attribute of Html

eg: <a href="      .com " > title </a>

引用属性值，必用单引号的时候

eg:name='John **"ShotGun"** Nelon '

|attribute|
|-|
|class|
|id|
|style|
|title|



#### HTML Head

**<style>
<head>
<tile>
<base> define the basic link 
<link>  define a conection about file and external resources 
<script>**


<meta>

define the keywords for search engineer

<meta name="keywords"  content="xxxxxxx">
define the description 

<meta name="description" content="xxxxxx">

define the author
<meta name="author" content="">

refresh the web page every 30 mintues

<meta http-equiv="refresh" content="30">

<script> use for load the script file 



#### Html CSS

how to use it ?

use style attribute in html 

use<style > in head

use external CSS



eg:<p style="color:blue;margin-left:20px;"> this is a paragraph </p>



eg:define a backoground color

<body style="background-color:yellow;">

<h2 style="background-color:red;">  this is a title </h2>

<p style="background-color:green;">this is a paragraph </p>

</body>
This example is so ugly 

![image.png](https://flowus.cn/preview/257b4bf9-2b62-42c2-a967-c760d0fbf6fd)

Change the font-family(字体) color and font-size 
style="font-family:verdana;"

style="font-family:arial;color:red;font-size:20px;"

text-align（文本对齐）style="text-align:center;

**Internal CSS**

<head>

<style type="text/css">

body{backgroud-color:yellow;}

p{color:blue;}

</style}

</head}
**external CSS**

<head>

<link rel="stylesheet" type="text/css" href="mystyle.css">

</head>



#### Html pictures

```HTML
<img src="name" alt="name" width="" height="" >
<!--gif and static is the same method-->

```


src is meaning source 

alt is a prefab. When we can't show the picture ,it can be the text in the alt .

It's good for the user only use the text to browse the web page.



#### Html <table>

tr table row

td table data 

th table header



Let us to write a two rows and three columns table


```HTML
<table>
  <thead>
    <tr>
      <th>columns 1 </th>
      <th>columns 2 </th>
      <th>columns 3 </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1,1</td>
      <td>1,2</td>
      <td>1,3</td>
    </tr>
    <tr>
      <td>2,1</td>
      <td>2,2</td>
      <td>2,3</td>
    </tr>
        <tr>
      <td>3,1</td>
      <td>3,2</td>
      <td>3,3</td>
    </tr>
  </tbody>
</table>
```




#### Html tabulation

disorder and order 

**disorder**

<ul>

<li>Coffee</li>

<li>Milk</li>

</ul>

**order**

<ol>

<li></li>

<li></li>

</ol>

**HTML customize tabulation**

```HTML
<dl>
  <dt>Coffee</dt>
  <dd>--black hot drink></dd>
  <dt>Milk</dt>
  <dd>--white cold drink</dd>
</dl>
```



```HTML
<ol type="A">
  <li>Apples</li>
  <li>Apples</li>
  <li>Apples</li>
  <li>Apples</li>
</ol>
```



