# the-phonique-world
Your online marketplace connecting buyers and sellers.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080808">
<title>PHONIQUE WORLD | Discover. Connect. Shop.</title>
<meta name="description" content="PHONIQUE WORLD connects buyers with trusted local sellers. Discover products and sell with us in Purulia.">

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:Arial,sans-serif;background:#080808;color:#fff}
a{text-decoration:none;color:inherit}
header{padding:22px 7%;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #292929}
.logo{font-size:25px;font-weight:900;letter-spacing:3px}
.logo span{color:#aaa}
nav{display:flex;gap:25px;font-size:13px;color:#ccc}
nav a:hover{color:white}
.hero{padding:105px 8%;min-height:570px;display:flex;flex-direction:column;justify-content:center;background:radial-gradient(ellipse at 80% 40%,#292929,#080808 65%)}
.tag{color:#aaa;font-size:12px;letter-spacing:4px;margin-bottom:25px}
h1{font-size:clamp(45px,8vw,88px);line-height:1.02;max-width:850px}
h1 span{color:#888}
.hero p{color:#bbb;max-width:520px;line-height:1.8;margin:25px 0}
.btn{display:inline-block;padding:15px 25px;background:#fff;color:#080808;font-weight:bold;font-size:13px;border-radius:3px;margin:5px 8px 5px 0}
.btn.outline{background:transparent;color:white;border:1px solid #777}
section{padding:85px 8%}
.eyebrow{color:#999;font-size:11px;letter-spacing:4px;margin-bottom:15px}
h2{font-size:clamp(30px,5vw,48px);margin-bottom:18px}
.desc{color:#aaa;line-height:1.8;max-width:650px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px;margin-top:35px}
.card{background:#151515;border:1px solid #303030;padding:30px 24px;min-height:160px}
.card .symbol{font-size:30px;margin-bottom:20px}
.card h3{margin-bottom:10px}
.card p{font-size:13px;color:#999;line-height:1.7}
.dark{background:#111}
.split{display:grid;grid-template-columns:1fr 1fr;gap:50px;align-items:center}
.steps{margin-top:30px}
.steps p{padding:17px 0;border-bottom:1px solid #333;color:#ccc}
form{margin-top:28px;max-width:550px}
input,select,textarea{width:100%;padding:15px;margin-bottom:13px;background:#151515;border:1px solid #444;color:white;border-radius:3px;font:inherit}
textarea{min-height:100px}
button{cursor:pointer;border:0}
form button{width:100%;padding:16px;background:white;color:black;font-weight:bold;font-size:14px}
.contact{background:#eaeaea;color:#111;text-align:center}
.contact .desc{color:#555;margin:auto}
.contact .btn{background:#111;color:white;margin-top:25px}
footer{padding:30px 8%;display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;color:#888;font-size:12px;border-top:1px solid #333}
footer strong{color:white}
@media(max-width:650px){
 header{flex-direction:column;gap:18px}
 nav{gap:13px;flex-wrap:wrap;justify-content:center}
 .hero{padding:75px 7%;min-height:500px}
 section{padding:65px 7%}
 .split{grid-template-columns:1fr;gap:25px}
}
</style>
</head>

<body>

<header>
  <a href="#" class="logo">PHONIQUE<span>.</span></a>
  <nav>
    <a href="#home">HOME</a>
    <a href="#about">ABOUT</a>
    <a href="#explore">EXPLORE</a>
    <a href="#seller">SELL WITH US</a>
    <a href="#contact">CONTACT</a>
  </nav>
</header>

<main>
<section class="hero" id="home">
  <div class="tag">WELCOME TO PHONIQUE WORLD</div>
  <h1>DISCOVER.<br><span>CONNECT.</span><br>SHOP.</h1>
  <p>Your online marketplace connecting buyers and sellers. Discover products, connect with local businesses and find what you're looking for — all in one place.</p>
  <div>
    <a class="btn" href="#explore">EXPLORE NOW ↗</a>
    <a class="btn outline" href="#seller">BECOME A SELLER</a>
  </div>
</section>

<section id="about">
  <div class="eyebrow">WHO WE ARE</div>
  <h2>A platform that brings<br>people together.</h2>
  <p class="desc">PHONIQUE WORLD is an online marketplace designed to bridge the gap between buyers and sellers. We work as a connecting platform, helping sellers showcase their products and helping buyers discover them easily.</p>
  <div class="cards">
    <div class="card">
      <div class="symbol">◈</div>
      <h3>For Buyers</h3>
      <p>Discover products and connect directly with sellers.</p>
    </div>
    <div class="card">
      <div class="symbol">◇</div>
      <h3>For Sellers</h3>
      <p>Showcase your products and reach more potential customers.</p>
    </div>
    <div class="card">
      <div class="symbol">↗</div>
      <h3>One Connection</h3>
      <p>We help buyers and sellers find each other through one platform.</p>
    </div>
  </div>
</section>

<section class="dark" id="explore">
  <div class="eyebrow">EXPLORE OUR MARKETPLACE</div>
  <h2>Find what you need.</h2>
  <p class="desc">Explore our growing product categories. New seller listings will be added as our marketplace expands.</p>
  <div class="cards">
    <div class="card">
      <div class="symbol">📱</div>
      <h3>Smartphones</h3>
      <p>Discover phones from local sellers.</p>
    </div>
    <div class="card">
      <div class="symbol">💻</div>
      <h3>Electronics</h3>
      <p>Explore electronic products and gadgets.</p>
    </div>
    <div class="card">
      <div class="symbol">🎧</div>
      <h3>Accessories</h3>
      <p>Discover accessories and everyday tech.</p>
    </div>
    <div class="card">
      <div class="symbol">🛍️</div>
      <h3>More Categories</h3>
      <p>Our marketplace will continue to grow.</p>
    </div>
  </div>
  <p style="color:#999;margin-top:25px;font-size:13px">Want to enquire about a product? Contact our team on WhatsApp.</p>
  <a class="btn" href="https://wa.me/918391091641?text=Hello%20PHONIQUE%20WORLD%2C%20I%20want%20to%20enquire%20about%20products." target="_blank">PRODUCT ENQUIRY ↗</a>
</section>

<section id="seller">
  <div class="split">
    <div>
      <div class="eyebrow">GROW WITH PHONIQUE</div>
      <h2>Have products to sell?</h2>
      <p class="desc">Join PHONIQUE WORLD and showcase your products to potential buyers. Whether you are an individual seller or a shop owner, we welcome you.</p>
      <div class="steps">
        <p>01 — Register as a seller</p>
        <p>02 — Share your product details</p>
        <p>03 — Get connected with buyers</p>
        <p>04 — Complete your sale directly</p>
      </div>
    </div>
    <div>
      <h3>Seller Registration</h3>
      <p class="desc" style="font-size:13px;margin-top:10px">Submit your details through WhatsApp.</p>
      <form id="sellerForm">
        <input id="name" placeholder="Your full name" required>
        <input id="phone" type="tel" placeholder="Your phone number" required>
        <select id="type" required>
          <option value="">Select seller type</option>
          <option>Individual Seller</option>
          <option>Shop / Business Owner</option>
        </select>
        <input id="product" placeholder="What do you want to sell?" required>
        <input id="location" placeholder="Your city / location" value="Purulia" required>
        <textarea id="message" placeholder="Tell us about your products (optional)"></textarea>
        <button type="submit">SUBMIT SELLER ENQUIRY ↗</button>
      </form>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="eyebrow">LET'S CONNECT</div>
  <h2>Let's make connections.</h2>
  <p class="desc">Have a question? Want to buy or sell? Our team is ready to hear from you.</p>
  <a class="btn" href="https://wa.me/918391091641?text=Hello%20PHONIQUE%20WORLD!" target="_blank">CHAT WITH US ON WHATSAPP ↗</a>
  <p style="margin-top:20px;font-size:13px">Operating location: Purulia, West Bengal</p>
</section>
</main>

<footer>
  <strong>PHONIQUE WORLD</strong>
  <span>Connecting buyers with sellers.</span>
  <span>© 2026 PHONIQUE WORLD. All rights reserved.</span>
</footer>

<script>
document.getElementById("sellerForm").addEventListener("submit",function(e){
  e.preventDefault();
  const fields = {
    name:document.getElementById("name").value,
    phone:document.getElementById("phone").value,
    type:document.getElementById("type").value,
    product:document.getElementById("product").value,
    location:document.getElementById("location").value,
    message:document.getElementById("message").value
  };
  const text = `PHONIQUE WORLD - Seller Registration\nName: ${fields.name}\nPhone: ${fields.phone}\nSeller type: ${fields.type}\nProducts: ${fields.product}\nLocation: ${fields.location}\nDetails: ${fields.message}`;
  window.open("https://wa.me/918391091641?text="+encodeURIComponent(text),"_blank");
});
</script>

</body>
</html>
