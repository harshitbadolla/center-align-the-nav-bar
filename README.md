# center-align-the-nav-bar
How do i center align the nav bar in the following CSS code


here is the code=

<!DOCTYPE html>
<html>
<title> CREVICES </title>

<head> 
	<meta charset=utf-8>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
	
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	
<style>
 ul {
	list-style-type:none;
	padding:0;
	margin:0;
	overflow:hidden;
	background-color:#323232;

	}
	

 li a {
	display:block;
	text-decoration:none;
	color:white;
	padding: 14px 16px;
	
}
 
 li {
	float:left;
	
 }
 
 li a:hover {
	color:#8C8C8C;
	text-align:center;
 
 }
 
 li {
	margin:auto;
	text-align:center;
	display:inline;
 }
  
  


</style>
</head>
<body> 


<div>
	<ul class="container">
	<li> <a href="#logo">Logo</a> </li>
	<li> <a href="#Tshirt">T-shirt	</a> </li>
	<li> <a href="#We are hiring"> We Are Hiring</a> </li>
	<li> <a href="#contact"> Contact</a> </li>
	<li> <a href="#search"> <i class="fa fa-search"></i></a> </li>
</div>


</body>


 
</html>
