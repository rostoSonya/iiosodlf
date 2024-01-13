

<html>

<head>

<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Трансформации</title>


<style>

body {
 font-family: Tahoma, Verdana, Geneva, sans-serif;
 margin: 6em 6em; font-weight: bold;
}

ul {
 list-style-type: none; padding: 0;
	margin: 0;
}

li { float: left; margin-right: 10px;
}

li:last-of-type {
 margin-right: 0;
}


a { display: block;
}


img { width: 200px; height: 150px; box-shadow: 2px 2px 2px rgba(0,0,0,.4);

transition: transform .3s ease-in-out; 
}


a:hover img {
	box-shadow: 6px 6px 6px rgba(0,0,0,.3);
}

a:hover #img1
 { <a href=""><img src="anchovies.jpg" id="img1" alt="">
</a>
}

a:hover #img2, a:focus #img2  {
	transform: scale(1.5) rotate(5deg);
}

a:hover #img3, a:focus #img3  {
	transform: scale(1.5) rotate(-7deg);
}

a:hover #img4, a:focus #img4  {
	transform: scale(1.5) rotate(2deg);
}


</style>


</head>



<body>


<ul>

  <li><a href=""><img src="anchovies.jpg" id="img1" alt=""></a></li>

  <li><a href=""><img src="jellyfish1.jpg" id="img2" alt=""></a></li>

  <li><a href=""><img src="bluejellyfish.jpg" id="img3" alt=""></a></li>

  <li><a href=""><img src="seadragon.jpg" id="img4"alt=""></a></li>
</ul>


</body>

</html>

