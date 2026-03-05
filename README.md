# cuahangsachnho.github.io
Cửa hàng sách nhỏ
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BookWorld - Thế giới sách</title>

<style>
body{
font-family: Arial, sans-serif;
margin:0;
background:#f5f5f5;
}

header{
background:#222;
color:white;
padding:20px;
text-align:center;
}

nav{
background:#444;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
color:#ffd700;
}

.banner{
background:url("https://images.unsplash.com/photo-1512820790803-83ca734da794") center/cover;
height:350px;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:40px;
font-weight:bold;
}

.container{
width:90%;
margin:auto;
}

.section-title{
text-align:center;
margin:40px 0 20px;
font-size:28px;
}

.books{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.book{
background:white;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
text-align:center;
}

.book img{
width:100%;
height:250px;
object-fit:cover;
border-radius:8px;
}

.book h3{
font-size:18px;
}

.price{
color:red;
font-weight:bold;
}

button{
background:#ff6600;
color:white;
border:none;
padding:10px 15px;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:#e65c00;
}

.about, .contact{
background:white;
padding:30px;
margin-top:40px;
border-radius:10px;
}

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:40px;
}
</style>
</head>

<body>

<header>
<h1>📚 BookWorld</h1>
<p>Thiên đường dành cho người yêu sách</p>
</header>

<nav>
<a href="#">Trang chủ</a>
<a href="#">Tiểu thuyết</a>
<a href="#">Kinh doanh</a>
<a href="#">Khoa học</a>
<a href="#">Thiếu nhi</a>
<a href="#">Liên hệ</a>
</nav>

<div class="banner">
Khám phá thế giới tri thức
</div>

<div class="container">

<h2 class="section-title">Sách nổi bật</h2>

<div class="books">

<div class="book">
<img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f">
<h3>Đắc Nhân Tâm</h3>
<p class="price">89.000đ</p>
<button>Mua ngay</button>
</div>

<div class="book">
<img src="https://images.unsplash.com/photo-1519681393784-d120267933ba">
<h3>Nhà Giả Kim</h3>
<p class="price">95.000đ</p>
<button>Mua ngay</button>
</div>

<div class="book">
<img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353">
<h3>Tuổi Trẻ Đáng Giá Bao Nhiêu</h3>
<p class="price">75.000đ</p>
<button>Mua ngay</button>
</div>

<div class="book">
<img src="https://images.unsplash.com/photo-1495446815901-a7297e633e8d">
<h3>Doraemon Truyện Ngắn</h3>
<p class="price">45.000đ</p>
<button>Mua ngay</button>
</div>

<div class="book">
<img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f">
<h3>Sapiens - Lược Sử Loài Người</h3>
<p class="price">120.000đ</p>
<button>Mua ngay</button>
</div>

<div class="book">
<img src="https://images.unsplash.com/photo-1476275466078-4007374efbbe">
<h3>Atomic Habits</h3>
<p class="price">110.000đ</p>
<button>Mua ngay</button>
</div>

</div>

<div class="about">
<h2>Giới thiệu</h2>
<p>
BookWorld là website bán sách online với hàng nghìn đầu sách thuộc nhiều thể loại
như tiểu thuyết, kinh doanh, khoa học, thiếu nhi và kỹ năng sống.
Chúng tôi mang đến cho bạn những cuốn sách chất lượng với giá tốt nhất.
</p>
</div>

<div class="contact">
<h2>Liên hệ</h2>
<p>Email: bookworld@gmail.com</p>
<p>Hotline: 0123 456 789</p>
<p>Địa chỉ: Hà Nội, Việt Nam</p>
</div>

</div>

<footer>
<p>© 2026 BookWorld - Website bán sách</p>
</footer>

</body>
</html>
