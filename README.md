<html>
<head>
<title>Smart Parking System</title>
<style>
h1 {
    text-align: center;
    color    :  orange;
	text-shadow: 3px 2px black;
	font-size: 70px;
	font-style: oblique;
} 
.button {
width: 200px;
height:100px;
  display: inline-block;
  padding: 15px 25px;
  font-size: 15px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #fff;
  background-color:silver;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}
.button:hover {
background-color: orange
}
.button:active {
  background-color: orange
  box-shadow: 0 5px #123;
  transform: translateY(4px);
}
body{
height: 200px;
    background: green; 
    background: linear-gradient(green,yellow); 
}
</style>
</head>
<body>
<div id="example1">
<h1>Welcome to Smart Parking system</h1></br></br>
<center>
<a href='https://SYED-FAIZANULLAH.github.io/'><button class="button"><h2>Choose your area</button></a>
</body>
</html>
<html>
<head>
<title>
Choose Your Area
</title>
<style>
body{
height: 200px;
    background: blue; 
    background: linear-gradient(white,blue); 
}
h1{
color : Lime;
text-align: center;
text-shadow: 3px 2px black;
font-size: 60px;
font-style: oblique;
}
.test{
display: inline-block;
  border-radius: 15px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  //font-size: 28px;
  padding: 3px 3px ;
  height: 100px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}
.test span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}
.test span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}
.test:hover span {
  padding-right: 25px;
}
.test:hover span:after {
  opacity: 1;
  right: 0;
}
 
</style>
</head>
<body>

<h1 >Select Your Area to check the Available slots</h1>
<center>
<a href='https://SYED-FAIZANULLAH.github.io'><button class="test" ><h2><span>Area1</span></h2></button></a>
&emsp; &emsp;
</body>
</html>
<html>
<head>
<title>Status Of Slots</title>

<style>
body{
width:100%;
height: 100%
}
#i{
float: right;
}
.abc{
text-align: center;
color: blue;
border-radius: 12px;
font-size: 20px;
width: 100px;
height:50px;
}
h1{
color:DarkMagenta;
font-size: 60px;
}
h2{
display: inline-block;
}
</style>
</head>
<body>

<center>
<h1>Status Of Slots</h1>
</center>
<center>
<iframe width="500" height="250" frameborder="0" src="https://app.ubidots.com/ubi/getchart/IlX0Nxei5Lag3Ybp12Qgziox2-Y"></iframe>
</center>
<center>
<iframe width="430" height="200" frameborder="0" src="https://app.ubidots.com/ubi/getchart/GpWLW-X6_yOmH7Y0GbQv6wkd1z0"></iframe>
<center><h2>Interested In Booking??</h2>&emsp;

<button class="abc" onclick="myFunction()">Click Me</button>
</center>
<center>
<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Thanks for showing interest!!!  We are  working on it. Will get back to you soon!!!!";
}
</script>


<br>

<img id="i" src="data:image/png;base64,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" width="40" height="40">
<p align="right"><font size="4">Filled: </p>

<img id="i" src="https://zalarieunique.ru/images/circle-clipart-neon-green-4.jpg" width="40" height="40">

<p align="right"><font size="4">Available: </p>
</body>
</html>
