---
title: Portofolio
date: 2021-09-25T12:37:28.594Z
description: Berikut contoh porofolio yang saya buat
---
```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>My Website</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@500&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
</head>
<body>

	<!-- sidebar -->
	<input type="checkbox" id="check">
	<div class="sidebar">
		<ul>
			<li><a href="#about">About</a></li>
			<li><a href="#skills">Skills</a></li>
			<li><a href="#portofolio">Portofolio</a></li>
			<li><a href="#contact">Contact</a></li>
		</ul>
	</div>

	<!-- bagian header -->
	<header>
		<div class="container">
			<h1><a href="">aziz</a></h1>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#skills">Skills</a></li>
				<li><a href="#portofolio">Portofolio</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>

			<!-- menu mobile -->
			<label for="check" class="mobile-menu"><i class="fas fa-bars fa-2x"></i></label>
		</div>
	</header>

	<!-- bagian banner -->
	<section class="banner">
		<div class="container">
			<div class="banner-left">
				<img src="Aziz.png">
				<h2>Hai...<br>
					Saya <span class="efek-ngetik"></span></h2>
				<p>Selamat datang di website saya</p>
			</div>
		</div>
	</section>

	<!-- bagian about -->
	<section id="about">
		<div class="container">
			<h3>About</h3>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries</p>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries</p>
		</div>
	</section>

	<!-- bagian skills -->
	<section id="skills">
		<div class="container">
			<h3>Skills</h3>
			<h4>HTML</h4>
			<div class="bar">
				<span class="nilai html">100%</span>
			</div>

			<h4>CSS</h4>
			<div class="bar">
				<span class="nilai css">90%</span>
			</div>

			<h4>JAVASCRIPT</h4>
			<div class="bar">
				<span class="nilai js">80%</span>
			</div>

			<h4>PHP</h4>
			<div class="bar">
				<span class="nilai php">95%</span>
			</div>

			<h4>PHOTOSHOP</h4>
			<div class="bar">
				<span class="nilai ps">85%</span>
			</div>
		</div>
	</section>


	<!-- bagian portofolio -->
	<section id="portofolio">
		<div class="container">
			<h3>Portofolio</h3>
			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 1</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 2</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 3</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 4</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 1</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 2</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 3</span>
				</a>
			</div>

			<div class="col-4">
				<a href="">
					<img src="LP.png">
					<span>Portofoilo 4</span>
				</a>
			</div>
		</div>
	</section>

	<!-- bagian contact -->
	<section id="contact">
		<div class="container">
			<h3>Contact</h3>
			<div class="col-3">
				<h4>Alamat</h4>
				<p>Jl. Kyai Legi</p>
			</div>

			<div class="col-3">
				<h4>Email</h4>
				<p>mohazizs0602@gmail.com</p>
			</div>

			<div class="col-3">
				<h4>Telp/HP</h4>
				<p>082324681202</p>
			</div>
		</div>
	</section>

	<!-- bagian footer -->
	<footer>
		<div class="container">
			<small>Copyright &copy; 2021 - Muhammad Aziz Sholihin.</small>
		</div>
	</footer>

	<script src="script.js"></script>

</body>
</html>
```

```
*{
	padding: 0;
	margin: 0;
	font-family: 'Quicksand', sans-serif;
	color: #333;
}
header{
	height: 70px;
}
header h1{
	display: inline-block;
	float: left;
	padding: 15px 24px;
	text-transform: uppercase;
}
header h1 a{
	transition: 0.3s;
}
header h1 a:hover{
	color: #F84744;
}
header ul{
	float: right;
}
header ul li{
	padding: 24px;
	display: inline-block;
}
header ul li a{
	transition: 0.3s;
}
header ul li a:hover{
	color: #F84744
}
a{
	text-decoration: none;
}
.container{
	width: 90%;
	margin: 0 auto;
}
.container::after{
	content: '';
	display: block;
	clear: both;
}
.mobile-menu{
	float: right;
	display: none;
	padding: 18px;
}
.mobile-menu:hover{
	cursor: pointer;
}
#check{
	display: none;
}
.sidebar{
	position: fixed;
	top: 0;
	bottom: 0;
	left: -300px;
	width: 300px;
	background-color: rgba(16, 47, 80, 0.9);
	transition: 0.3s;
	z-index: 9999;
}
.sidebar ul li a{
	color: #fff;
}
.sidebar ul li{
	padding: 24px;
	transition: 0.3s;
	transition-property: background-color;
}
.sidebar ul li:hover{
	background-color: #F84744;
}
#check:checked ~ .sidebar{
	left: 0;
}
.banner{
	background-color: #1F6886;
	padding: 150px 0;
}
section{
	padding: 50px 0;
}
.banner img{
	width: 100px;
	border-radius: 10px;
	box-shadow: 0 3px 5px #ddd;
	margin-bottom: 10px;
}
.banner h2,
.banner p,
.banner span{
	color: #fff;
}
}
.banner h2{
	margin-bottom: 10px;
}
.banner p{
	font-size: 18px;
}
.banner-left{
	padding-left: 24px;
}
section h3{
	padding-bottom: 20px;
	text-align: center;
	margin: 20px;
	position: relative;
}
section h3::before{
	content: '';
	display: block;
	position: absolute;
	bottom: 0;
	width: 120px;
	height: 1px;
	background-color: #ddd;
	left: calc(50% - 60px);
}
section h3::after{
	content: '';
	display: block;
	position: absolute;
	bottom: -1px;
	width: 40px;
	height: 4px;
	background-color: #F84744;
	left: calc(50% - 20px);
}
#about p{
	text-align: justify;
	text-indent: 30px;
	line-height: 25px;
	margin-bottom: 15px;
}
#skills,
#contact{
	background-color: #f9f9f9;
}
#skills .bar{
	height: 30px;
	background-color: #fff;
	border: 1px solid #ddd;
	margin: 5px 0 20px 0;
}
.bar .nilai{
	height: 30px;
	background-color: #F84744;
	display: inline-block;
	color: #fff;
	text-align: center;
}
.html{
	width: 100%;
}
.css{
	width: 90%;
}
.js{
	width: 80%;
}
.php{
	width: 95%;
}
.ps{
	width: 85%;
}
.col-4{
	width: 25%;
	box-sizing: border-box;
	padding: 5px;
	float: left;
	text-align: center;
	margin-bottom: 15px;
}
.col-4 img{
	width: 100%;
}
.col-4 a:hover img{
	transform: scale(1.2);
}
.col-3{
	width: 33.33%;
	box-sizing: border-box;
	float: left;
	text-align: center;
	padding: 50px 10px;
}
.col-3 h4{
	padding-bottom: 10px;
	border-bottom: 1px solid #ddd;
	margin-bottom: 15px;
}
footer{
	background-color: #333;
	padding: 50px;
	text-align: center;
}
footer small{
	color: #fff;
}
html{
	scroll-behavior: smooth;
}


@media (max-width: 768px){
	.mobile-menu{
		display: block;
	}
	header ul{
		display: none;
	}
	.col-4{
		width: 50%;
	}
	.col-3{
		width: 100%;
	}
}
```

```
const txtElement = ['Muhammad', 'Aziz', 'Sholihin'];
let count = 0;
let txtIndex = 0;
let currentTxt = '';
let words = '';

(function ngetik(){

	if(count == txtElement.length){
		count = 0;
	}

	currentTxt = txtElement[count];

	words = currentTxt.slice(0, ++txtIndex);
	document.querySelector('.efek-ngetik').textContent = words;

	if(words.length == currentTxt.length){
		count++;
		txtIndex = 0;
	}

	setTimeout(ngetik, 500);

})();
```

![LP.png](/img/lp.png "LP.png")

![Aziz.png](/img/aziz.png "Aziz.png")