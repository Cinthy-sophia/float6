# float6
ejercicio 3 float 3 columnas 
```html

<!DOCTYPE HTML>
<html>
<head>
<meta charset="UTF-8">
<title>3 column layout</title>
<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
<style>
aside, article, section, header, footer, nav {
	display: block;
}
html, body {
	margin: 0;
	padding: 0;
}
html {
	background: rgb(123, 121, 143);
}
body {
	width: 960px;
	background: #fff;
	margin: 0 auto 2em;
	font: 100% Georgia, "Times New Roman", Times, serif;
}
header {
	background: rgb(76, 67, 65);
	margin-bottom: 20px;
}
header h1 {
	font: normal 2em Arial, Helvetica, sans-serif;
	color: white;
	text-align: center;
	line-height: 4em;
	text-transform: uppercase;
	letter-spacing:.1em;
	margin: 0;
}
article{
	float: left;
	width:634px;
}
aside{
	float:right;
	width: 266px;
	height: 500px;
	padding:20px;
	background: rgb(173, 169, 130);
}
.col1{
	background: rgb(237, 228, 214);
	float: left;
	height: 500px;
	padding: 20px;
	width: 266px;

}
.col2{
	background: rgb(219, 126, 64);
	float: right;
	height: 500px;
	padding: 20px;
	width: 266px;

}
footer {
	background: rgb(100, 98, 102);
	line-height: 3em;
	font-size: .6em;
	color: white;
	padding: 0 2em;
	clear: both;
}
</style>
</head>
<body>
<header>
<h1>Cool company header</h1>
</header>
<article>
<section class="col1">
This is where the really important stuff goes.
</section>
<section class="col2">
This is equally important stuff.
</section>
</article>
<aside>
I am related content.
</aside>
<footer>Copyright stuff....</footer>
</body>
</html>
```
