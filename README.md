<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 25px 20px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #e6005c;
}

.active {
  background-color: #04AA6D;
}


#main-banner{
	width:100%;
	max-height:500px;
	overflow:hidden;
	}

#main-banner img{
	width:100%;
	}


#slider{
	position:relative;
	width:500%;
	margin:0;
	left:0;
	text-align:left;
	font-size:0;
	animation:10s slidy infinite;
	}
#slides img{
	width:20%;
	float:left;
	}
/*Animation*/
@keyframes slidy {
0% { left: 0%; }
28% { left: 0%; }
33% { left: -100%; }
61% { left: -100%; }
66% { left: -200%; }
94% { left: -200%; }
100% { left: 0%; }

h1{background-color:#b30047;}

</style>
</head>
<body>

<ul>
  <li><a href="things.html">Places To Visit</a></li>
  <li><a href="plan you.html">Plan your trip</a></li>
  <li><a href="cal.html">Event Calendar</a></li>
  <li style="float:right"><a class="active" href="about.html">About Bon Voyage</a></li>
</ul>


<!--  Banner Starts  -->
<div id ="main-banner">
	<div id="slider">
		<div id ="slides">
		<img src="mal.jpg" alt="banner" height="600px" width="1200px">
		<img src="pretty.jpg" alt="banner" height="600px" width="1200px">
		<img src="taj.jpg" alt="banner" height="600px" width="1200px">
               
		</div>
	</div>
</div> <table><tr><h1 align="center"style="color:#b30047;">Best Places To Visit</h1></tr></table>

<table width=100% height=100% cellpadding="20px">
<tr>
<td><img src="ei.jpg"width=300 height=300><h1 style="color:#b30047;">Exotic Paris</h1>
<iframe width="300" height="320" src="https://www.youtube.com/embed/q19D-lU44rI" title="YouTube video player" ></iframe>
</td>

<td ><img src="burji.jpg" width=300 height=300><h1 style="color:#b30047;">Enchanting Dubai</h1>
<iframe width="300" height="300" src="https://www.youtube.com/embed/5cUCxVr7xiw" title="YouTube video player"></iframe>
</td>
<td><img src="lunda.jpg" width=300 height=300/><h1 style="color:#b30047;">Elegant London</h1>
<iframe width="300" height="300" src="https://www.youtube.com/embed/KuBXNJG2c_I" title="YouTube video player" allowfullscreen></iframe>
</td>
<td><img src="suzy.jpg" width=300 height=300/><h1 style="color:#b30047;">Pretty Switzerland</h1>
<iframe width="300" height="300" src="https://www.youtube.com/embed/lZomNWn-R7E" title="YouTube video player" allowfullscreen></iframe>
</td>
</tr>

</table>


</body>
</html>
