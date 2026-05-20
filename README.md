<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hridoy Tech</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: #f5f5f5;
}

/* Header */
.header {
  background: #0b1c2c;
  color: white;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 20px;
  font-weight: bold;
  color: orange;
}

/* Search */
.search-box {
  padding: 10px;
}

.search-box input {
  width: 100%;
  padding: 10px;
  border-radius: 8px;
  border: 1px solid #ccc;
}

/* Banner */
.banner {
  margin: 10px;
}

.banner img {
  width: 100%;
  border-radius: 10px;
}

/* Product */
.products {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 10px;
  padding: 10px;
}

.product {
  background: white;
  padding: 10px;
  border-radius: 10px;
  text-align: center;
}

.product img {
  width: 100%;
}

.price {
  color: red;
  font-weight: bold;
}

/* Bottom Nav */
.bottom-nav {
  position: fixed;
  bottom: 0;
  width: 100%;
  background: #0b1c2c;
  color: white;
  display: flex;
  justify-content: space-around;
  padding: 10px 0;
}

</style>
</head>

<body>

<div class="header">
  <div>☰</div>
  <div class="logo">Hridoy Tech</div>
  <div>🛒</div>
</div>

<div class="search-box">
  <input type="text" placeholder="Search Products...">
</div>

<div class="banner">
  <img src="https://via.placeholder.com/600x250" alt="">
</div>

<div class="products">

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <h4>Laptop</h4>
    <p class="price">৳50,000</p>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <h4>Smartphone</h4>
    <p class="price">৳20,000</p>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <h4>Headphone</h4>
    <p class="price">৳2,000</p>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <h4>Monitor</h4>
    <p class="price">৳15,000</p>
  </div>

</div>

<div class="bottom-nav">
  <div>🏠 Home</div>
  <div>🔥 Offers</div>
  <div>🖥 PC</div>
  <div>⚖ Compare</div>
  <div>👤 Account</div>
</div>

</body>
</html>
