# parkingsystem
<!DOCTYPE html>
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
