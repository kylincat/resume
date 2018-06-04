# 第五天和第六天：三种简历
***
* [HTML](#html)
* CSS
  * [style_1.css](#style-1)
  * [style_2.css](#style-2)
  * [style_3.css](#style-3)
  <br>
***
## html
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>简历</title>
	<link rel="stylesheet" type="text/css" href="css/style-1.css" />
</head>
<body>



<div class="box3">
	<div></div>
	<h1>简历</h1>
</div>

<div class="div_1">
	<h2>基本信息</h2>
	<div class="box1">
		<div class="div_line"></div>
		<div class="box1_1">姓名：张三</div>
		<div class="box1_2">性别：男</div>
		<div class="box1_3">应聘职位：Web前端工程师</div>
		
	</div>
</div>

<div class="div_2">
	<h2>联系方式</h2>
	<div class="box1">
		<div class="div_line"></div>
		<div class="box1_2_1">手机：12345678910</div>
		<div class="box1_2_2">Email：<a href="https://mail.qq.com" target="_blank">1059914928@qq.com</a></div>
		<div class="box1_2_3">个人主页：<a href="https://github.com/kylincat" target="_blank">Github</a></div>
		
	</div>
</div>

<div class="div_3">
	<h2>能力描述</h2>
	
	<div class="box2_1">技术能力：
		<div class="div_line"></div>
	</div>
	<div class="box2_2">熟练掌握HTML,CSS,JvavScript</div>
	<div class="box2_3">综合能力：</div>
	<div class="box2_4">良好的沟通，主动积极，努力勤奋</div>
</div>

<div class="br"></div>

<div class="div_4">
	<h2>教育经历</h2>
	<div class="box2_1">本科
		<div class="div_line"></div>
	</div>
	<div class="box2_2">幻想大学</div>
	<div class="box2_3">研究生</div>
	<div class="box2_4">幻想大学天堂学院</div>
</div>

<div class="br"></div>

<div class="div_5">
	<h2>项目经历</h2>
	<div class="box2_1">小小度
		<div class="div_line"></div>
	</div>
	<div class="box2_2">作为前端攻城狮角色参与了ABC组件的开发</div>
	<div class="box2_3">SAN&nbsp;Doc</div>
	<div class="box2_4">作为文档攻城狮参与了SAN&nbsp;Coc编写</div>
</div>


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
.box1_2_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:0px;
    top:0px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_2 {
    height: 25px;
    width: 20%;
    position: relative;
    left:268px;
    top:-26px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_3 {
    height: 25px;
    width: 20%;
    position: relative;
    left:537px;
    top:-50px;
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

.br {
    height:20px;
    width:100%;
    position: relative;
    top:20px;
    left:0px;
    
}
```
***
## style-2
```


.box1 {
    height: 25px;
    width: 80%;
    position: relative;
    top:0px;
    left:270px;
    
    padding:0px;
    margin:0px;

}
.box1_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:0px;
    top:-668px;
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
    top:-668px;
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
    top:-668px;
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
    top:-570px;
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
    top:-570px;
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
    top:-570px;
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
    height:700px;
    float:left;
    margin-right: 20px;
    margin-bottom:20px;
    
}
h1 {
    color:white;
    font-size:60px;
    position:relative;
    left:65px;
    top:20px;
}
```
***
## style-3
```

.box1 {
    height: 112px;
    width: 1200px;
    position: relative;
    top:-131px;
    left:110px;
    
    padding:0px;
    margin:0px;

}
.box1_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:16px;
    top:-30px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2 {
    height: 25px;
    width: 20%;
    position: relative;
    left:258px;
    top:-57px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_3 {
    height: 25px;
    width: 25%;
    position: relative;
    left:500px;
    top:-84px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_1 {
    height: 25px;
    width: 20%;
    position: relative;
    left:18px;
    top:-30px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_2 {
    height: 25px;
    width: 25%;
    position: relative;
    left:260px;
    top:-57px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box1_2_3 {
    height: 25px;
    width: 25%;
    position: relative;
    left:563px;
    top:-84px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}

.box2_1 {
    height: 25px;
    width: 100%;
    position: relative;
    left:130px;
    top:-155px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_2 {
    height: 25px;
    width: 1090px;
    position: relative;
    left:220px;
    top:-180px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_3 {
    height: 25px;
    width: 100%;
    position: relative;
    left:130px;
    top:-165px;
    text-align:left;
    padding:0px 0;
    font-weight:bold;
    
    font-size:18px;
}
.box2_4 {
    height: 25px;
    width: 1090px;
    position: relative;
    left:220px;
    top:-190px;
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
    background-color:rgb(102, 99, 99);
    width:1315px;
    height:90px;
    position: relative;
    top:0px;
    left:0px;
    margin:0px; 
}
h1 {
    color:white;
    font-size:30px;
    position:relative;
    left:25px;
    top:25px;
}
h2{
    font-size:20px;
}
.div_1 {
    background-color:rgb(179, 174, 174);
    height:115px;
    width:110px;
    margin:0px;
    text-align:center;
    
    position:relative;
    top:-17px;
    line-height: 115px;
} 
.div_2 {
    background-color:rgb(179, 174, 174);
    height:115px;
    width:110px;
    margin:0px;
    text-align:center;
    
    position:relative;
    top:-31px;
    line-height: 115px;
} 
.div_3 {
    background-color:rgb(179, 174, 174);
    height:115px;
    width:110px;
    margin:0px;
    text-align:center;
    
    position:relative;
    top:-46px;
    line-height: 115px;
}
.div_4 {
    background-color:rgb(179, 174, 174);
    height:115px;
    width:110px;
    margin:0px;
    text-align:center;
    
    position:relative;
    top:-60px;
    line-height: 115px;
}
.div_5 {
    background-color:rgb(179, 174, 174);
    height:115px;
    width:110px;
    margin:0px;
    text-align:center;
    
    position:relative;
    top:-74px;
    line-height: 115px;
}
.div_line {
    background-color:rgb(209, 203, 203);
    
    position: relative;
    top:114px;
    left:-110px;
    width:1312px;
    height:3px;
}
.box2_1 div {
    background-color:rgb(209, 203, 203);
    
    position: relative;
    top:23px;
    left:-130px;
    width:1312px;
    height:3px;
}
.box3 div {
    background-color:rgb(209, 203, 203);
    position: relative;
    top:89px;
    right:-1312px;
    
    width:3px;
    height:588px;
}
```