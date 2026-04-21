            <!DOCTYPE html>
<html>
<head>
    <title>اول موقع</title>
</head>
<body>
    <h1>اهلا بيك 👋</h1>
    <p>انا بعمل اول موقع من الموبايل</p>
</body>
</html><img src="https://picsum.photos/300" alt="صورة" /><!DOCTYPE html>
<html>
<head>
    <title>اول موقع</title>

    <style>
        body {
            baeckground-color: #222;
            color: white;
            text-align: center;
            font-family: Arial;
        }

        h1 {
            color: orange;
        }

        p {
            font-size: 18px;
        }
    </style>

</head>
<body>

    <h1>👋 اهلا بيك</h1>
    <p>انا بعمل اول موقع من الموبايل</p>

</body>
</html><!DOCTYPE html>
<html>
<head>
    <title>اول موقع</title>

    <style>
        body {
            background-color: #222;
            color: white;
            text-align: center;
            font-family: Arial;
        }

        h1 {
            color: orange;
        }

        img {
            width: 200px;
            margin-top: 20px;
            border-radius: 10px;
        }
    </style>

</head>
<body>

    <h1>👋 اهلا بيك</h1>
    <p>انا بعمل اول موقع من الموبايل</p>

    <img src="https://picsum.photos/300" alt="صورة" />

</body>
</html><button>اضغط هنا</button>button {
    background-color: orange;
    color: black;
    padding: 10px;
    border: none;
    margin-top: 20px;
}<script>
function showMessage() {
    alert("👋 أهلاً! أنت ضغطت على الزرار");
}
</script><h1>👋 أهلاً بيك</h1>
<p>ده موقعي</p>
<img src="https://picsum.photos/300">
<button>اضغط هنا</button>body {
    background-color: #222;
    color: white;
}<script>
function showMessage() {
    alert("🔥 أنت ضغطت على الزرار");
}
</script><button onclick="showMessage()">اضغط هنا</button><!DOCTYPE html>
<html>
<head>
    <title>موقعي الشخصي</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background-color: #111;
            color: white;
        }

        .container {
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: orange;
        }

        img {
            width: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }

        .skills {
            margin-top: 30px;
        }

        .skill {
            background: #222;
            margin: 10px auto;
            padding: 10px;
            width: 200px;
            border-radius: 10px;
        }

        button {
            background-color: orange;
            border: none;
            padding: 10px 20px;
            margin-top: 20px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #ffb84d;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>👋 أهلاً أنا مبرمج مبتدئ</h1>
    <p>ده أول موقع شخصي ليا</p>

    <img src="https://picsum.photos/200" />

    <div class="skills">
        <h2>💡 مهاراتي</h2>

        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript (ببدأ فيه)</div>
    </div>

    <button onclick="contactMe()">تواصل معي</button>

</div>

<script>
function contactMe() {
    alert("📩 شكراً لتواصلك! قريباً هضيف صفحة تواصل حقيقية");
}
</script>

</body>
</html><!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: linear-gradient(#111, #222);
            color: white;
        }

        .container {
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: orange;
        }

        img {
            width: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }

        .section {
            margin-top: 40px;
        }

        .card {
            background: #333;
            padding: 15px;
            margin: 10px auto;
            width: 250px;
            border-radius: 10px;
        }

        button {
            background: orange;
            border: none;
            padding: 10px 20px;
            margin-top: 20px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #ffb84d;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>👋 أنا مبرمج مبتدئ</h1>
    <p>ده Portfolio بسيط ليا</p>

    <img src="https://picsum.photos/200" />

    <!-- المهارات -->
    <div class="section">
        <h2>💡 مهاراتي</h2>

        <div class="card">HTML</div>
        <div class="card">CSS</div>
        <div class="card">JavaScript (ببدأ فيه)</div>
    </div>

    <!-- المشاريع -->
    <div class="section">
        <h2>💼 مشاريعي</h2>

        <div class="card">موقع شخصي</div>
        <div class="card">صفحة هبوط (Landing Page)</div>
    </div>

    <!-- زرار التواصل -->
    <button onclick="contactMe()">📩 تواصل معي</button>

</div>

<script>
function contactMe() {
    alert("📩 شكراً لتواصلك! قريباً سأضيف وسيلة تواصل حقيقية");
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مطعم الذوق الملكي</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    direction: rtl;
    background: #111;
    color: white;
}

/* Navbar */
nav {
    display: flex;
    justify-content: space-between;
    padding: 15px 50px;
    background: black;
}
nav h2 {
    color: gold;
}
nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

/* Hero */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') no-repeat center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}
.hero h1 {
    font-size: 50px;
    background: rgba(0,0,0,0.6);
    padding: 20px;
}

/* Menu */
.menu {
    padding: 50px;
    text-align: center;
}
.menu h2 {
    color: gold;
}
.items {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
.card {
    background: #222;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
}
.card img {
    width: 100%;
    border-radius: 10px;
}

/* Footer */
footer {
    background: black;
    text-align: center;
    padding: 20px;
    margin-top: 20px;
}
</style>
</head>

<body>

<nav>
    <h2>🍽 مطعم الذوق الملكي</h2>
    <div>
        <a href="#">الرئيسية</a>
        <a href="#">المنيو</a>
        <a href="#">تواصل</a>
    </div>
</nav>

<section class="hero">
    <h1>أفضل تجربة طعام في المدينة</h1>
</section>

<section class="menu">
    <h2>🍔 قائمة الطعام</h2>

    <div class="items">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
            <h3>برجر خاص</h3>
            <p>لحم طازج مع صوص مميز</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1548365328-9f547fb0953c">
            <h3>بيتزا إيطالي</h3>
            <p>جبنة أصلية وطعم رائع</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1562967916-eb82221dfb36">
            <h3>باستا كريمي</h3>
            <p>مذاق غني لا يُقاوم</p>
        </div>
    </div>
</section>

<footer>
    <p>© جميع الحقوق محفوظة - مطعم الذوق الملكي</p>
</footer>

</body>
</html><section class="menu">
  <h2>Our Menu</h2>

  <div class="menu-category">
    <h3>Burgers</h3>
    <ul>
      <li>Classic Burger - 80 EGP</li>
      <li>Cheese Burger - 90 EGP</li>
    </ul>
  </div>

  <div class="menu-category">
    <h3>Pizza</h3>
    <ul>
      <li>Margherita - 100 EGP</li>
      <li>Pepperoni - 120 EGP</li>
    </ul>
  </div>

  <div class="menu-category">
    <h3>Drinks</h3>
    <ul>
      <li>Coca Cola - 20 EGP</li>
      <li>Orange Juice - 30 EGP</li>
    </ul>
  </div>
</section>.menu {
  padding: 40px;
  background-color: #f8f8f8;
  text-align: center;
}

.menu h2 {
  font-size: 30px;
  margin-bottom: 20px;
}

.menu-category {
  margin-bottom: 20px;
}

.menu-category h3 {
  color: #e63946;
}

.menu-category ul {
  list-style: none;
  padding: 0;
}

.menu-category li {
  margin: 5px 0;
  font-size: 18px;
}.menu h2 {
  font-size: 30px;
  margin-bottom: 20px;
}

.menu-category {
  margin-bottom: 20px;
}

.menu-category h3 {
  color: #e63946;
}

.menu-category ul {
  list-style: none;
  padding: 0;
}

.menu-category li {
  margin: 5px 0;
  font-size: 18px;
}
<a href="https:/
}

.menu-category ul {
  list-style: none;
  padding: 0;
}

.menu-category li {
  margin: 5px 0;
  font-size: 18px;
}
<a href="https://wa.me/01063353624" target="_blank">
  Contact me on WhatsApp
</acategory li {
  margin: 5px 0;
  font-size: 18px;
}
<a href="https://wa.me/01063353624" target="_blank">
  Contact me on WhatsApp
</aategory li {
  margin: 5px 0;
  font-size: 18px;
}
<a href="https://wa.me/01063353624" target="_blank">
  Contact me on WhatsApp
</ae: 18px;
}
<a href="https://wa.me/01063353624" target="_blank">
  Contact me on WhatsApp
</ae on WhatsApp
</a
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>McDonald's Ad</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>McDonald's</h1>

        <img src="https://images.unsplash.com/photo-1550547660-d9450f859349" alt="burger">

        <p>أفضل طعم هتجربه النهارده!</p>

        <button onclick="showMenu()">اطلب الآن</button>

        <div id="menu" class="menu">
            <h2>المنيو</h2>
            <ul>
                <li>🍔 بيج ماك</li>
                <li>🍟 بطاطس</li>
                <li>🥤 كولا</li>
            </ul>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>body {
    margin: 0;
    font-family: Arial;
    background: #111;
    color: white;
    text-align: center;
}

.container {
    padding: 20px;
}

img {
    width: 300px;
    border-radius: 20px;
    margin: 20px 0;
}

button {
    background: #FFC72C; /* أصفر ماكدونالدز */
    border: none;
    padding: 15px 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    transform: scale(1.1);
}

.menu {
    margin-top: 20px;
    background: #222;
    padding: 20px;
    border-radius: 15px;

    /* هنا السحر 👇 */
    opacity: 0;
    transform: translateY(20px);
    transition: all 0.5s ease;
    display: none;
}

.menu.show {
    display: block;
    opacity: 1;
    transform: translateY(0);
}function showMenu() {
    const menu = document.getElementById("menu");

    menu.style.display = "block";

    setTimeout(() => {
        menu.classList.add("show");
    }, 10);
}<p>جرّب أقوى عروض ماكدونالدز الآن!</p>
<p class="text">جرّب أقوى عروض ماكدونالدز الآن!</p>.text {
    opacity: 0;
    transform: translateY(30px);
    animation: fadeUp 1s ease forwards;
    animation-delay: 0.5s;
}

/* الحركة */
@keyframes fadeUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }https://images.unsplash.com/photo-1550547660-d9450f859349https://images.unsplash.com/photo-1541592106381-b31e9677c0e5https://images.unsplash.com/photo-1581006852262-e4307cf6283a<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>McDonald's Ad</title>

<style>
body {
  font-family: Arial;
  text-align: center;
  background: #111;
  color: white;
}

.btn {
  margin-top: 80px;
  padding: 15px 30px;
  font-size: 20px;
  background: red;
  color: white;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

/* البوب اب */
.popup {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.8);
  display: none;
  justify-content: center;
  align-items: center;
}

/* المحتوى */
.popup-content {
  background: white;
  color: black;
  padding: 20px;
  border-radius: 15px;
  width: 320px;
  animation: zoom 0.4s ease;
}

.food {
  margin: 15px 0;
}

.food img {
  width: 100%;
  border-radius: 10px;
  transition: 0.3s;
}

.food img:hover {
  transform: scale(1.05);
}

@keyframes zoom {
  from {transform: scale(0.5);}
  to {transform: scale(1);}
}
</style>

</head>

<body>

<button class="btn" onclick="openMenu()">اطلب الآن</button>

<div class="popup" id="popup">
  <div class="popup-content">

    <h2>🍔 المنيو</h2>

    <div class="food">
      <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
      <p>بيج ماك - 100 جنيه</p>
    </div>

    <div class="food">
      <img src="https://images.unsplash.com/photo-1541592106381-b31e9677c0e5">
      <p>بطاطس - 30 جنيه</p>
    </div>

    <div class="food">
      <img src="https://images.unsplash.com/photo-1581006852262-e4307cf6283a">
      <p>كولا - 20 جنيه</p>
    </div>

    <button onclick="closeMenu()">إغلاق</button>

  </div>
</div>

<script>
function openMenu() {
  document.getElementById("popup").style.display = "flex";
}

function closeMenu() {
  document.getElementById("popup").style.display = "none";
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>McDonald's Ad</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(45deg, red, orange);
  color: white;
  text-align: center;
}

/* النص */
.text {
  font-size: 28px;
  margin-top: 50px;
  animation: fadeIn 2s ease;
}

/* صورة */
img {
  width: 250px;
  margin-top: 30px;
  border-radius: 15px;
  transition: 0.4s;
}

img:hover {
  transform: scale(1.1);
}

/* زرار */
.btn {
  margin-top: 30px;
  padding: 15px 30px;
  font-size: 20px;
  background: yellow;
  color: black;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  animation: pulse 1.5s infinite;
}

/* أنيميشن */
@keyframes fadeIn {
  from {opacity:0;}
  to {opacity:1;}
}

@keyframes pulse {
  0% {transform: scale(1);}
  50% {transform: scale(1.1);}
  100% {transform: scale(1);}
}
</style>

</head>

<body>

<div class="text">
🍔 بيج ماك… تعالى كُل هنا بدل ما تاكل هناك!
</div>

<img src="https://images.unsplash.com/photo-1550547660-d9450f859349">

<br>

<button class="btn">اط
}<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Burger Ad</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(120deg, #ff0000, #ff9900);
  color: white;
  text-align: center;
}

/* العنوان */
h1 {
  margin-top: 20px;
  animation: drop 1s ease;
}

/* زرار */
.btn {
  padding: 15px 25px;
  font-size: 18px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  margin: 10px;
}

/* زرار اطلب */
.order-btn {
  background: yellow;
  color: black;
  animation: pulse 1.5s infinite;
}

/* زرار إضافة */
.add-btn {
  background: black;
  color: white;
}

/* منيو */
.menu {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 20px;
}

/* كارت الأكل */
.item {
  background: white;
  color: black;
  margin: 10px;
  border-radius: 15px;
  width: 200px;
  overflow: hidden;
  animation: fade 1s ease;
  transition: 0.3s;
}

.item:hover {
  transform: scale(1.05);
}

.item img {
  width: 100%;
  height: 140px;
  object-fit: cover;
}

/* السلة */
.cart {
  position: fixed;
  right: 10px;
  top: 10px;
  background: black;
  padding: 10px;
  border-radius: 10px;
  width: 180px;
}

/* أنيميشن */
@keyframes drop {
  from {transform: translateY(-50px); opacity: 0;}
  to {transform: translateY(0); opacity: 1;}
}

@keyframes fade {
  from {opacity: 0;}
  to {opacity: 1;}
}

@keyframes pulse {
  0% {transform: scale(1);}
  50% {transform: scale(1.1);}
  100% {transform: scale(1);}
}
</style>

</head>

<body>

<h1>🍔 مطعم البرجر السريع</h1>
<p>تعالى كُل هنا بدل ما تاكل هناك 😋</p>

<button class="btn order-btn" onclick="showMenu()">اطلب الآن</button>

<div class="menu" id="menu">

  <div class="item">
    <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
    <p>بيج برجر - 100 جنيه</p>
    <button class="btn add-btn" onclick="add('بيج برجر')">أضف للسلة</button>
  </div>

  <div class="item">
    <img src="https://images.unsplash.com/photo-1541592106381-b31e9677c0e5">
    <p>بطاطس - 30 جنيه</p>
    <button class="btn add-btn" onclick="add('بطاطس')">أضف للسلة</button>
  </div>

  <div class="item">
    <img src="https://images.unsplash.com/photo-1581006852262-e4307cf6283a">
    <p>كولا - 20 جنيه</p>
    <button class="btn add-btn" onclick="add('كولا')">أضف للسلة</button>
  </div>

</div>

<!-- السلة -->
<div class="cart">
  <h3>🛒 السلة</h3>
  <ul id="cartList"></ul>
</div>

<script>

function showMenu() {
  document.getElementById("menu").scrollIntoView({behavior: "smooth"});
}

function add(item) {
  let li = document.createElement("li");
  li.innerText = item;
  document.getElementById("cartList").appendChild(li);
}

</script>

</body>
</html>
