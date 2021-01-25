10 questions
Should it be responsive

Will it work on multiple devices

What requirements will be needed for the website

What product or services do they provide

Does it need to be updated regularily

Are payments required

Are login details required for the website

how many pages will the website have and what will they be about

What devices will it be compatible with

If you need login details will they be protected

Can those with disabilities be able to use it

will it have a contact page

html for website:
<!DOCTYPE html>
<html>
<head>
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  background: url(xbackground.jpg);
  background-position: center top;
  background-size: 1500px 855px;
  background-repeat: no-repeat;
  }
 .topnav {
  overflow: hidden;
  background-color: #333;
}
.topnav a {
  float: left;
  display: block;
  color: #F2F2F2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
.topnav .icon {
  display: none;
}
@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}
@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
	<script>
function myFunction() {
  var x = document.getElementById("topnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
	</script>
<div class="topnav" id="mytopnav">
	<a href="file:///home/chronos/u-2bbbf9d5034514ef6dd3f7fde7e10dd3056cce96/MyFiles/Downloads/xtremesports2/xtremesportshome2.html"class="active">home</a>
  <a href="file:///home/chronos/u-2bbbf9d5034514ef6dd3f7fde7e10dd3056cce96/MyFiles/Downloads/xtremesports2/abouttheweb2.html">aboutthewebsite</a>
  <a href="file:///home/chronos/u-2bbbf9d5034514ef6dd3f7fde7e10dd3056cce96/MyFiles/Downloads/xtremesports2/promovid2.html">promovideos</a>
  <a href="file:///home/chronos/u-2bbbf9d5034514ef6dd3f7fde7e10dd3056cce96/MyFiles/Downloads/xtremesports2/xxsports.html">extremesports</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
  <i class="fa fa-bars"></i>
  </a>
</div>
<div style="padding-left:16px">
<br>
<br>
<br>
<br>
  <h2>EXTREME SPORTS HOME</h2>
  <p> 2021</p>
</div>
</body>
</html>
