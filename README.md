# 第五天和第六天：三种简历
***
* [HTML](#html)
* CSS
  * [style_1.css](#style-1)
  * [style_2.css](#style-2)
  <br>
***
## html
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>简历</title>
	<link rel="stylesheet" type="text/css" href="css/style-2.css" />
</head>
<body>

<div class="box3">
	<h1>简历</h1>
</div>
<h2>基本信息</h2>
<br>

<div class="box1">
	
	<div class="box1_1">姓名：张三</div>
	<div class="box1_2">性别：男</div>
	<div class="box1_3">应聘职位：Web前端工程师</div>
	
</div>
<br>

<h2>联系方式</h2>
<br>

<div class="box1">
	
	<div class="box1_2_1">手机：12345678910</div>
	<div class="box1_2_2">Email：<a href="https://mail.qq.com" target="_blank">1059914928@qq.com</a></div>
	<div class="box1_2_3">个人主页：<a href="https://github.com/kylincat" target="_blank">Github</a></div>
	
</div>
<br>

<h2>能力描述</h2>
<br>

<div class="box2_1">技术能力：</div>
<div class="box2_2">熟练掌握HTML,CSS,JvavScript</div>
<div class="box2_3">综合能力：</div>
<div class="box2_4">良好的沟通，主动积极，努力勤奋</div>
<br>
<br>

<h2>教育经历</h2>
<br>

<div class="box2_1">本科</div>
<div class="box2_2">幻想大学</div>
<div class="box2_3">研究生</div>
<div class="box2_4">幻想大学天堂学院</div>
<br>
<br>

<h2>项目经历</h2>
<br>

<div class="box2_1">小小度</div>
<div class="box2_2">作为前端攻城狮角色参与了ABC组件的开发</div>
<div class="box2_3">SAN&nbsp;Doc</div>
<div class="box2_4">作为文档攻城狮参与了SAN&nbsp;Coc编写</div>
<br>
<br>

</body>
</html>
```
***
### style-1
```
.box1 {
    height: 25px;
    width: 100%;
    position: relative;
    top:0px;
    left:0px;
    
    padding:0;
    margin:0;

}
.box1_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2 {
    height: 25px;
    width: 20%;
    position: relative;
    left:268px;
    top:-28px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_3 {
    height: 25px;
    width: 20%;
    position: relative;
    left:537px;
    top:-55px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}


.box2_1 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_2 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_3 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:20px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_4 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:20px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
a:link {color:blue;}
a:visited {color:purple;}
a：hover {color:green;}
a:active {color:red;}
```
***
## style-2
```

.box1 {
    height: 25px;
    width: 80%;
    position: relative;
    top:0px;
    left:260px;
    border;
    padding:0;
    margin:0;

}
.box1_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:0px;
    top:-867px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2 {
    height: 25px;
    width: 20%;
    position: relative;
    left:268px;
    top:-867px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_3 {
    height: 25px;
    width: 25%;
    position: relative;
    left:537px;
    top:-867px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:0px;
    top:-727px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_2 {
    height: 25px;
    width: 30%;
    position: relative;
    left:268px;
    top:-727px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_3 {
    height: 25px;
    width: 25%;
    position: relative;
    left:537px;
    top:-727px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}

.box2_1 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_2 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_3 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:20px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_4 {
    height: 25px;
    width: 100%;
    position: relative;
    left:0px;
    top:20px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
a:link {color:blue;}
a:visited {color:purple;}
a：hover {color:green;}
a:active {color:red;}

.box3 {
    background-color:rgb(66, 66, 240);
    width:250px;
    height:960px;
    float:left;
    margin-right: 20px;
    
}
h1 {
    color:white;
    font-size:60px;
    position:relative;
    left:65px;
    top:20px;
}
```
