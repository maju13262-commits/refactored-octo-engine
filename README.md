<!DOCTYPE html>
<html lang="ur">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chaman Non Custom Mobile Shop - Peshawar</title>
<style>
body{font-family:Arial,sans-serif;background:#f5f7fb;margin:0}
.header{background:#0f172a;color:#fff;padding:15px;text-align:center;position:sticky;top:0;z-index:10}
.header h1{margin:0;font-size:22px} .header span{color:#38bdf8}
.header a{background:#25D366;color:#fff;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;margin-top:8px;font-weight:bold}
.paybox{background:#0f172a;color:#fff;margin:15px;border-radius:15px;padding:15px}
.paybox b{color:#38bdf8}
.products{display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:12px;padding:15px}
.card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 2px 8px rgba(0,0,0,.1);position:relative}
.card img{width:100%;height:150px;object-fit:cover}
.card-body{padding:10px} .card-body h4{font-size:13px;margin:0;height:32px;overflow:hidden}
.old{font-size:11px;color:#999;text-decoration:line-through} .new{font-size:15px;font-weight:bold}
.off{position:absolute;top:8px;left:8px;background:red;color:#fff;font-size:11px;padding:3px 7px;border-radius:20px}
.btn{width:100%;margin-top:7px;background:#25D366;color:#fff;border:none;padding:7px;border-radius:8px;font-weight:bold}
</style>
</head>
<body>
<div class="header">
<h1>CHAMAN <span>NON CUSTOM</span> SHOP</h1>
<p style="margin:5px 0;font-size:13px">Peshawar Karkhano Market - All Pakistan Delivery</p>
<a href="https://wa.me/923056814132?text=Salam Chaman Bhai Mobile Chahiye">WhatsApp: 03056814132</a>
</div>

<div class="paybox">
<b>JazzCash / Easypaisa:</b> 03056814132 (Chaman)<br>
<b>Address:</b> Peshawar - Chaman Non Custom Mobile Shop<br>
<b>Note:</b> Har mobile ki alag tasveer + discount rate
</div>

<div class="products" id="grid"></div>

<script>
const data=[
["iPhone 14 Pro Max 256GB","89999","124999","35%","https://images.unsplash.com/photo-1592750475338-74b7b21085ab?w=400"],
["Samsung S23 Ultra 512GB","89999","149999","40%","https://images.unsplash.com/photo-1610945264803-c22b62d2a7b3?w=400"],
["Vivo X90 Pro 256GB","52999","89999","41%","https://images.unsplash.com/photo-1592899677977-9c10ca588bbd?w=400"],
["Infinix Zero 30 256GB","28999","46999","38%","https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400"],
["Redmi Note 12 Pro+","29999","49999","40%","https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400"],
["Oppo Reno 10 Pro+","42999","69999","38%","https://images.unsplash.com/photo-1598327105666-5b89351aff97?w=400"],
["Tecno Camon 20 Premier","28999","46999","38%","https://images.unsplash.com/photo-1580910051074-3eb694886505?w=400"],
["iPhone 11 Pro Max 256GB","42999","64999","33%","https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400"],
["Samsung A73 256GB","32999","54999","40%","https://images.unsplash.com/photo-1598327105666-5b89351aff97?w=400"],
["Google Pixel 7 Pro","59999","99999","40%","https://images.unsplash.com/photo-1598327105666-5b89351aff97?w=400"]
];
let html="";
data.forEach(d=>{
html+=`<div class="card"><div class="off">${d[3]} OFF</div><img src="${d[4]}"><div class="card-body"><h4>${d[0]}</h4><div class="old">Rs ${d[2]}</div><div class="new">Rs ${d[1]}</div><button class="btn" onclick="window.open('https://wa.me/923056814132?text=Mujhe chahiye ${d[0]} Rs ${d[1]}','_blank')">Order on WhatsApp</button></div></div>`;
});
document.getElementById("grid").innerHTML=html;
</script>
</body>
</html>
