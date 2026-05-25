<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Men T-Shirt Store</title>

<style>
body{
  margin:0;
  background:#111;
  font-family:Arial;
  color:#aaa;
}

header{
  text-align:center;
  padding:20px;
  font-size:30px;
  font-weight:900;
  color:#fff;
  letter-spacing:2px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:12px;
  padding:12px;
}

.card{
  background:#1b1b1b;
  border-radius:12px;
  overflow:hidden;
  text-align:center;
  text-decoration:none;
  color:#ddd;
}

.card img{
  width:100%;
  height:150px;
  object-fit:cover;
  background:#222;
}

.name{
  padding-top:8px;
  font-size:14px;
}

.price{
  padding-bottom:10px;
  color:#fff;
  font-weight:bold;
}
</style>
</head>

<body>

<header>MEN T-SHIRT</header>

<div class="grid">

<a class="card" href="product.html?name=Black Wave&price=999">
<img src="https://via.placeholder.com/300x300?text=Black+Tshirt">
<div class="name">Black Wave</div>
<div class="price">Rs. 999</div>
</a>

<a class="card" href="product.html?name=Urban Grey&price=799">
<img src="https://via.placeholder.com/300x300?text=Grey+Tshirt">
<div class="name">Urban Grey</div>
<div class="price">Rs. 799</div>
</a>

<a class="card" href="product.html?name=Street King&price=899">
<img src="https://via.placeholder.com/300x300?text=Street+King">
<div class="name">Street King</div>
<div class="price">Rs. 899</div>
</a>

<a class="card" href="product.html?name=Dark Shadow&price=1099">
<img src="https://via.placeholder.com/300x300?text=Dark+Shadow">
<div class="name">Dark Shadow</div>
<div class="price">Rs. 1099</div>
</a>

<a class="card" href="product.html?name=White Classic&price=699">
<img src="https://via.placeholder.com/300x300?text=White+Tshirt">
<div class="name">White Classic</div>
<div class="price">Rs. 699</div>
</a>

<a class="card" href="product.html?name=Night Rider&price=950">
<img src="https://via.placeholder.com/300x300?text=Night+Rider">
<div class="name">Night Rider</div>
<div class="price">Rs. 950</div>
</a>

<a class="card" href="product.html?name=Minimal Black&price=999">
<img src="https://via.placeholder.com/300x300?text=Minimal+Black">
<div class="name">Minimal Black</div>
<div class="price">Rs. 999</div>
</a>

<a class="card" href="product.html?name=Grey Force&price=850">
<img src="https://via.placeholder.com/300x300?text=Grey+Force">
<div class="name">Grey Force</div>
<div class="price">Rs. 850</div>
</a>

<a class="card" href="product.html?name=Alpha Wear&price=1200">
<img src="https://via.placeholder.com/300x300?text=Alpha+Wear">
<div class="name">Alpha Wear</div>
<div class="price">Rs. 1200</div>
</a>

<a class="card" href="product.html?name=Storm Fit&price=899">
<img src="https://via.placeholder.com/300x300?text=Storm+Fit">
<div class="name">Storm Fit</div>
<div class="price">Rs. 899</div>
</a>

<a class="card" href="product.html?name=Neo Street&price=999">
<img src="https://via.placeholder.com/300x300?text=Neo+Street">
<div class="name">Neo Street</div>
<div class="price">Rs. 999</div>
</a>

<a class="card" href="product.html?name=Bold Edge&price=1050">
<img src="https://via.placeholder.com/300x300?text=Bold+Edge">
<div class="name">Bold Edge</div>
<div class="price">Rs. 1050</div>
</a>

</div>

</body>
</html>
