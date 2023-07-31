# landingpage
<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width-device-width, initial-scale=1.0">
<title>Landing page</title>	
	<link rel="stylesheet"  href=" style45.css">
	<link rel="stylesheet"  href=" https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
	</head>
	<body>
		<div class="container">
			<nav>
				<a href="#" class="logo">AT FIRST ZONE<a>
					<ul>
						<li class="active"><a href="#">Home</a></li>
						<li><a href="#">About</a></li>
						<li><a href="#">Services</a></li>
						<li><a href="#">Blog</a></li>
						<li><a href="#">Contact</a></li>
					</ul>
				</nav>
				<div class="content">
					<h1>Good Book <br> has no ending</h1>
					<p>lorem ipsum dolor sit consetectur adipsing elit .</p>
					<a href="#" class="btn">Lets work together</a>
			</div>
			<div class="social-links">
				<a href="#"><i class="fa-brands fa-facebook-f"></i>
				<a href="#"><i class="fa-brands fa-twitter"></i>	
                <a href="#"><i class="fa-brands fa-instagram"></i>
                <a href="#"><i class="fa-brands fa-google"></i>

</body>
</html>
#css used
*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	font-family: sans-serif;
	text-decoration: none;
}
.container{
	width: 100%;
	height: 100vh;
	background:url(hello.avif);
	background-size: cover;
	background-position: top;
}
.container nav{
	width: 90%;
	margin: auto;
	height: 80px;
	display: flex;
	justify-content: space-between;
	align-items: center;
}
.container nav .logo{
	font-size: 40px;
	font-weight: bold;
	color: black;
}
.container nav  ul li{
	display: inline-block;
	margin-left: 35px;
	position: relative;
}
.container nav  ul li a{
	color: black;
	font-size: 15px;
	text-transform: capitalize;
}
.container nav  ul li ::after{
	content: '';
	position: absolute;
	bottom: -3px;
	left: 0;
	background-color: white;
	width: 0%;
	height: 2px;
	transition: 0.3s ;
}
.container nav  ul li:hover ::after,
.container nav  ul li:hover ::after{
	width: 100%;
}
.content{
	position:absolute ;
	top: 50%;
	left: 6%;
	transform: translateY(-50%);
	width: 50%;
}
.content h1{
	color: white;
	font-size: 80px;
	font-weight: bold;
	text-transform: capitalize;
	margin-bottom: 20px;
}
.content p{
	color: white;
	line-height: 1.7;
	letter-spacing:1.5px ;
}
.content.btn{
	padding: 15px  25px;
	background-color: #ef8653 ;
	color: white;
	border-radius: 30px;
	text-transform: capitalize;
}
.content  .btn:hover{
	background-color: transparent;
	color: #ef8653;
}
.social-links{
	position: absolute;
	bottom: 50px;
	left: 6%;
}
.social-links a  i{
	width: 40px;
	height: 40px;
	border: 1px solid rgba(255, 255, 255, 0.5);
	text-align: center;
	line-height: 40px;
	border-radius: 50%;
	color: #fff;
	margin-right: 10px;
	transition: 0.4s;
}
.social-links  a  i:hover{
	background-color: #ef8653;
}
