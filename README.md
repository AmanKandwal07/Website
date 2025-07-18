<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="Stylesheet" href="Project.css"/>
</head>
<body>
  <header id="header">
    <div id="logo"><a href="#">Amazon.in</a></div>
    <div id="search-box">
      <input type="text" placeholder="Search any products !" />
      <button>Search</button>
    </div>
    <div id="cart">🛒 Cart</div>
  </header>
  <div id="nav">
    <a href="#">All</a>
    <a href="#">Electronics</a>
    <a href="#">Mobiles</a>
    <a href="#">Fashion</a>
    <a href="#">Home</a>
    <a href="#">Deals</a>
</div>

  <section id="Ads">
    <img src="https://p1-ofp.static.pub/medias/23498737439_Gaming315ACH6_202104301141091666198209703.png" alt="Gaming Laptop">
    <h3>Lenovo Ideapad Gaming3</h3>
  </section>
  
  <section id="products">
    <h2>Deals of the Day</h2>
    <div class="product-view">
      <div id="product">
        <img src="https://th.bing.com/th/id/OPAC.CA5QXEDKaWvhTA474C474?w=220&h=210&c=17&o=5&dpr=1.3&pid=21.1" alt="Mi 10T"/>
        <h3>Smartphone</h3>
        <p>₹18,999</p>
      </div>
      <div id="product">
        <img src="https://th.bing.com/th/id/OPAC.yUVimuBx9QYisQ474C474?w=220&h=220&c=17&o=5&dpr=1.3&pid=21.1" alt="JBL Speaker" />
        <h3>Bluetooth Speaker</h3>
        <p>₹3,479</p>
      </div>
      <div id="product">
        <img src="https://th.bing.com/th/id/OPAC.jpsbljLgllVWCQ474C474?w=220&h=210&c=17&o=5&dpr=1.3&pid=21.1" alt="Mouse" />
        <h3>Gaming Mouse</h3>
        <p>₹949</p>
      </div>
      <div id="product">
        <img src="https://th.bing.com/th/id/OPAC.FZHQSxiHixftfw474C474?w=220&h=220&c=17&o=5&dpr=1.3&pid=21.1" alt="Keyboard" />
        <h3>KeyBoard</h3>
        <p>₹949</p>
      </div>
    </div>
  </section>
  <footer id="footer">
    <p>&copy; 2025 ShopNow | Welcome for everone.</p>
  </footer>
</body>
</html>


body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: white;
}
#header {
  background: black;
  color: white;
  display: flex;
  align-items: center;
  padding: 10px 20px;
  justify-content: space-between;
}
#logo a {
  font-size: 25px;
  font-weight: bold;
  color:white;
  text-decoration: none;
}
#search-box {
  flex: 1;
  margin: 20px;
  display: flex;
}
#search-box input {
  width: 100%;
  padding: 10px;
  border: none;
}
#search-box button {
  padding: 10px;
  background-color: #febd69;
  border: none;
  cursor: pointer;
}
#cart {
  font-size: 1.1rem;
}
#nav {
  background: #232f3e;
  padding: 10px;
  display: flex;
  gap: 15px;
}
#nav a {
  color: white;
  text-decoration: none;
  font-size: 0.95rem;
}
# Ads{
  width: 20%;
  max-height: 200px;
  object-fit: static;
  position: contain;
}
#products {
  padding: 20px;
}
#products h2 {
  text-align: center;
  margin-bottom: 20px;
}
.product-view {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}
#product {
  background: white;
  padding: 15px;
  border-radius: 8px;
  width: 200px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  text-align: center;
}
#product img {
  width: 100%;
  height: 150px;
  object-fit: contain;
}
#product h3 {
  font-size: 1rem;
  margin: 10px 0 5px;
}
#product p {
  color: green;
  font-weight: bold;
}
#footer {
  background: #131921;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
