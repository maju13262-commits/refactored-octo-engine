<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chaman Mobile</title>
<style>
body{font-family:system-ui;background:#f5f5f5;margin:0}
.header{background:#111;color:#fff;padding:20px;text-align:center}
.container{max-width:1200px;margin:auto;padding:15px;display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:15px}
.card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 2px 8px rgba(0,0,0,0.1);text-align:center;padding-bottom:10px}
.card img{width:100%;height:150px;object-fit:contain;padding:10px}
.card h3{font-size:14px;margin:8px}
.price{color:#e11d48;font-weight:bold;margin:5px}
.btn{background:#000;color:#fff;border:none;padding:10px 15px;border-radius:8px;width:90%;cursor:pointer;font-weight:bold}
</style>
</head>
<body>
<div class="header">
<h1>Chaman Mobile Peshawar - 03056814132</h1>
</div>
<div class="container" id="products"></div>
<script>
const mobiles = ["iPhone 14 Pro Max","iPhone 13","Samsung S23 Ultra","Samsung A32","Samsung A12","Infinix Hot 10","Infinix Note 12","Tecno Spark 8","Tecno Camon 19","Redmi Note 12","Redmi 10A","Vivo Y21","Vivo Y33s","Oppo A16","Oppo F21","Realme C35","Realme 9 Pro","Nokia G21","Nokia 105","OnePlus Nord 2","iPhone 12","iPhone 11","Samsung A52","Samsung A23","Infinix Zero 5G","Tecno Pova 2","Redmi Note 11","Vivo Y15s","Oppo A57","Realme C21","Samsung S22","iPhone X","iPhone 8 Plus","Samsung A03s","Infinix Smart 6","Tecno Spark 7","Redmi 9C","Vivo Y01","Oppo A16e","Realme Narzo 50","OnePlus 9","Samsung M11","Infinix Hot 12","Tecno Camon 18","Redmi Note 10 Pro","Vivo V23","Oppo Reno 6","Realme GT Master","Nokia 1100","Honor X9"];
const container = document.getElementById('products');
mobiles.forEach((name
