<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>رحلات الحج والعمرة</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

  <!-- شريط التنقل -->
  <header>
    <nav>
      <div class="logo">
        <a href="#">رحلات الحج والعمرة</a>
      </div>
      <ul>
        <li><a href="#">الرئيسية</a></li>
        <li><a href="#">خدماتنا</a></li>
        <li><a href="#">الحجز</a></li>
        <li><a href="#">اتصل بنا</a></li>
      </ul>
    </nav>
  </header>

  <!-- صورة رئيسية -->
  <section class="hero">
    <img src="mvmmm.jpg" alt="رحلة الحج والعمرة">
    <div class="hero-content">
      <h1>رحلات الحج والعمرة</h1>
      <p>ابدأ رحلتك الروحانية معنا</p>
      <a href="#" class="btn">احجز الآن</a>
    </div>
  </section>

  <!-- خدماتنا -->
  <section class="services">
    <h2>خدماتنا المميزة</h2>
    <div class="service-card">
      <i class="fas fa-plane"></i>
      <h3>تنظيم الرحلات</h3>
      <p>نوفر رحلات مريحة وآمنة مع خيارات متعددة لتلبية احتياجاتك.</p>
    </div>
    <div class="service-card">
      <i class="fas fa-mosque"></i>
      <h3>الإرشاد الروحاني</h3>
      <p>فريق من المرشدين سيرافقونك لتقديم أفضل التوجيهات خلال رحلتك.</p>
    </div>
    <div class="service-card">
      <i class="fas fa-hotel"></i>
      <h3>إقامة مريحة</h3>
      <p>نوفر لك إقامة مريحة في أفضل الفنادق القريبة من الحرم.</p>
    </div>
  </section>

  <!-- تواصل معنا -->
  <section class="contact">
    <h2>تواصل معنا</h2>
    <p>للحجز أو الاستفسار، اتصل بنا الآن على الرقم: 123456789 أو عبر البريد الإلكتروني: info@hajjomrah.com</p>
    <a href="#" class="btn">اتصل بنا</a>
  </section>

  <!-- القسم السفلي -->
  <footer>
    <p>حقوق الطبع © 2024 جميع الحقوق محفوظة</p>
    <ul>
      <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
      <li><a href="#"><i class="fab fa-twitter"></i></a></li>
      <li><a href="#"><i class="fab fa-instagram"></i></a></li>
    </ul>
  </footer>

</body>
</html>

/* إعدادات أساسية */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Tajawal', sans-serif;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
}

/* شريط التنقل */
header {
  background-color: #34495e;
  padding: 15px 0;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

nav .logo a {
  color: #fff;
  font-size: 24px;
  font-weight: bold;
  text-decoration: none;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
  font-size: 18px;
  padding: 8px 15px;
  transition: background-color 0.3s ease-in-out;
}

nav ul li a:hover {
  background-color: #16a085;
  border-radius: 5px;
}

/* صورة رئيسية */
.hero {
  position: relative;
  text-align: center;
  color: white;
}

.hero img {
  width: 100%;
  height: 100vh;
  object-fit: cover;
  filter: brightness(0.7);
}

.hero-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  animation: fadeIn 2s ease-in-out;
}

.hero h1 {
  font-size: 50px;
  margin-bottom: 20px;
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
}

.hero p {
  font-size: 24px;
  margin-bottom: 20px;
}

.btn {
  background-color: #e74c3c;
  padding: 12px 25px;
  color: white;
  text-decoration: none;
  font-size: 18px;
  border-radius: 5px;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.btn:hover {
  background-color: #c0392b;
  transform: scale(1.05);
}

/* قسم الخدمات */
.services {
  padding: 50px 20px;
  text-align: center;
  background-color: #f9f9f9;
}

.services h2 {
  font-size: 36px;
  margin-bottom: 30px;
  color: #2c3e50;
}

.service-card {
  display: inline-block;
  width: 30%;
  margin: 0 1%;
  padding: 20px;
  background-color: white;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.service-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.service-card i {
  font-size: 48px;
  color: #16a085;
  margin-bottom: 15px;
}

.service-card h3 {
  font-size: 24px;
  margin-bottom: 15px;
}

.service-card p {
  font-size: 18px;
  color: #7f8c8d;
}

/* قسم التواصل */
.contact {
  padding: 50px 20px;
  text-align: center;
  background-color: #2c3e50;
  color: white;
}

.contact h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.contact p {
  font-size: 18px;
  margin-bottom: 20px;
}

.contact .btn {
  background-color: #16a085;
}

.contact .btn:hover {
  background-color: #1abc9c;
}

/* القسم السفلي */
footer {
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
  position: fixed;
  width: 100%;
  bottom: 0;
}

footer p {
  margin: 0;
}

footer ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
}

footer ul li {
  margin: 0 15px;
}

footer ul li a {
  color: white;
  text-decoration: none;
  font-size: 20px;
  transition: color 0.3s ease;
}

footer ul li a:hover {
  color: #1abc9c;
}

/* Animation */
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
