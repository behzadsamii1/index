<html>
<head>
	<title>menu</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css?family=Work+Sans" rel="stylesheet">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css">
	<style type="text/css">
		body{
			margin:0;
			padding:0;
			font-size:"Work Sans", sans-serif;
			background-image:url(https://images.pexels.com/photos/1275393/pexels-photo-1275393.jpeg?cs=srgb&dl=float-floating-globe-1275393.jpg&fm=jpg);
			background-repeat:no-repeat;
			background-position:center;
			background-attachment:fixed;
			background-size:100%;
		}
		.back{
			position:fixed;
			display:block;
			overflow:hidden;
			top:0;
			left:0;
			right:0;
			width:100%;
			background:#000;
			border:none;
			border-bottom:1px solid #fff;
			margin:0;
			padding:20px 0;
		}
		.back nav a{
			text-decoration:none;
			color:#fff;
			font-family:"Work Sans";
			border:1px solid #fff;
			border-radius:5px;
			padding:10px 40px;
			margin:10px 20px;
			font-size:18pt;
		}
		.close{
			background:#000;
			width:10%;
			height:5%;
			text-align:center;
		}
		.close a{
			text-decoration:none;
			color:#fff;
			padding:10px 40px;
			font-family:"Work Sans";
			margin:5px 0;
		}
		.pages{
			position:fixed;
			display:none;
			top:0;
			left:0;
			bottom:0;
			right:0;
			overflow:hidden;
			width:100%;
			height:100%;
			background:#fff;
			opacity:0;
			z-index:100;
			-webkit-animation:l-me 1s forwards;
			
		}
		.pages:target{
			display:table;
		}
		.link{
			width:60%;
			margin:auto;
			margin-top:100px;
			text-align:center;
			border:1px solid #fff;
			font-family:"Work Sans";
		}
		.link a{
			text-decoration:none;
			color:#000;
			display:block;
			border:1px solid #000;
			border-radius:5px;
			width:10%;
			font-size:18pt;
			text-align:center;
			margin:50px 300px;
			padding:10px 40px;
		}
		@-webkit-keyframes l-me{
			0%{transform:translateX(0);}
			100%{opacity:1;}
		}
	</style>
</head>
<body>
	<div class="back">
		<nav>
			<a href="#menu">Menu</a>
		</nav>
	</div>
	<div id="menu" class="pages">
		<div class="close">
			<a href="#">Close</a>
		</div>
		<div class="link">
			<a href="#">Home</a>
			<a href="#">Contact</a>
			<a href="#">About</a>
		</div>
	</div>
</body>
</html>
