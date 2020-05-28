<!DOCTYPE html>
<html>
<head>
<style>
img{
height:350px;
}
.c1{
filter:blur(5px);

}
.c2{
filter:sepia(100%);
</style>
</head>

<body>

<h2>JavaScript Filters</h2>

<p><details>
<summary>Filters</summary>
Here u will find two filters.
<ul>
<li>Blur</li>
<li>Sepia</li>
</ul>
</details>
</p>

<p id="demo"></p>
<img src="https://image.freepik.com/free-vector/abstract-dynamic-pattern-wallpaper-vector_53876-59131.jpg">
<img id="i1" src="https://image.freepik.com/free-vector/abstract-dynamic-pattern-wallpaper-vector_53876-59131.jpg" alt="filter image">
<p>
<input type="button" value="Blur" onclick="myf()">
<input type="button" value="Sepia" onclick="myf2()">
</p>
<script>
function myf(){
var x;
x=document.getElementById("i1").className="c1";
}
function myf2(){
var y;
y=document.getElementById("i1").className="c2";
}
</script>
<h3>
<details>
<summary>for More information</summary>
Go to Hell!😎
</details>
</h3>
</body>
</html>
