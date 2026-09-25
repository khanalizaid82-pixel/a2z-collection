# a2z-collection
A2Z Collection - Latest Clothing Collection
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>A2Z Collection | Latest Clothing</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
  font-family:Arial,sans-serif;
}

body{
  background:#f7f7f7;
  color:#111;
}

header{
  background:#111;
  color:white;
  padding:22px 18px;
  text-align:center;
}

header h1{
  font-size:30px;
  letter-spacing:2px;
}

header p{
  margin-top:7px;
  color:#ccc;
}

.hero{
  padding:45px 20px;
  text-align:center;
  background:linear-gradient(135deg,#111,#333);
  color:white;
}

.hero h2{
  font-size:32px;
  margin-bottom:12px;
}

.hero p{
  margin-bottom:22px;
}

.btn{
  display:inline-block;
  background:white;
  color:#111;
  padding:13px 22px;
  border-radius:25px;
  text-decoration:none;
  font-weight:bold;
}

section{
  padding:30px 16px;
}

section h2{
  text-align:center;
  margin-bottom:25px;
}

.products{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:15px;
}

.card{
  background:white;
  border-radius:14px;
  overflow:hidden;
  box-shadow:0 3px 12px #0001;
}

.card img{
  width:100%;
  height:210px;
  object-fit:cover;
  background:#ddd;
}

.card-content{
  padding:13px;
}

.card h3{
  font-size:17px;
  margin-bottom:6px;
}

.price{
  font-weight:bold;
  margin-bottom:10px;
}

.order{
  display:block;
  text-align:center;
  background:#111;
  color:white;
  padding:10px;
  border-radius:8px;
  text-decoration:none;
}

.about{
  background:white;
  text-align:center;
  line-height:1.6;
}

footer{
  background:#111;
  color:white;
  text-align:center;
  padding:25px 15px;
}

@media(max-width:380px){
  .products{
    grid-template-columns:1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>A2Z COLLECTION</h1>
  <p>Latest Clothing Collection</p>
</header>

<div class="hero">
  <h2>Style That Speaks</h2>
  <p>Discover the latest fashion at A2Z Collection.</p>
  <a href="#products" class="btn">Shop Now</a>
</div>

<section id="products">
  <h2>Our Collection</h2>

  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/500x600?text=Product+1">
      <div class="card-content">
        <h3>Premium T-Shirt</h3>
        <p class="price">₹499</p>
        <a class="order" href="https://wa.me/91XXXXXXXXXX?text=Hello%20A2Z%20Collection,%20I%20want%20to%20order%20Premium%20T-Shirt">
          Order Now
        </a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/500x600?text=Product+2">
      <div class="card-content">
        <h3>Stylish Shirt</h3>
        <p class="price">₹699</p>
        <a class="order" href="https://wa.me/91XXXXXXXXXX?text=Hello%20A2Z%20Collection,%20I%20want%20to%20order%20Stylish%20Shirt">
          Order Now
        </a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/500x600?text=Product+3">
      <div class="card-content">
        <h3>Casual Wear</h3>
        <p class="price">₹599</p>
        <a class="order" href="https://wa.me/91XXXXXXXXXX?text=Hello%20A2Z%20Collection,%20I%20want%20to%20order%20Casual%20Wear">
          Order Now
        </a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/500x600?text=Product+4">
      <div class="card-content">
        <h3>New Collection</h3>
        <p class="price">₹799</p>
        <a class="order" href="https://wa.me/91XXXXXXXXXX?text=Hello%20A2Z%20Collection,%20I%20want%20to%20order%20New%20Collection">
          Order Now
        </a>
      </div>
    </div>

  </div>
</section>

<section class="about">
  <h2>About A2Z Collection</h2>
  <p>
    Welcome to A2Z Collection — your destination for
    stylish and latest clothing. Quality fashion at
    affordable prices.
  </p>
</section>

<footer>
  <h3>A2Z COLLECTION</h3>
  <p>Latest Clothing Collection</p>
  <p>© 2026 A2Z Collection</p>
</footer>

</body>
</html>