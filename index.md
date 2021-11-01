<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

a1 {
  float: left;
  padding: 20px;
  width: 50%;
  background-color: skyblue;
}

a2 {
  float: right;
  padding: 30px;
  width: 50%;
  background-color: yellow;
}

a3 {
  float: left;
  padding: 20px;
  width: 50%;
  background-color: skyblue;
}

a4 {
  float: right;
  padding: 30px;
  width: 50%;
  background-color: yellow;
}


/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
div {
	width: 900px;
    height: 130px;
    border: 15px solid green;
    padding: 40px;
    margin-top: 25px;
    margin-left: 20px;
    margin-right: 20px;
}
</style>
</head>
<body>
<header>
  <h2>CSS Test 10/14</h2>
</header>

<section>

<div>Box test</div>

</section>


</body>
</html>

