<!-- index.html -->
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>หน้าแรก - เว็บไซต์ส่วนตัว</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            background: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px;
            background: #ffffff;
            color: white;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-align: center;
            color: #000000;
        }
        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: rgb(255, 2, 2);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center
        }
        img.profile {
            width: 150px;
            border-radius: 50%;
        }
    </style>
</head>
<body>

<header>
    <h1>ยินดีต้อนรับสู่เว็บไซต์ของฉัน</h1>
</header>

<nav>
    <a href="index.html">หน้าแรก</a>
    <a href="about.html">เกี่ยวกับฉัน</a>
    <a href="gallery.html">แกลอรี่</a>
</nav>

<section id="home">
    <h2>หน้าแรก (Home)</h2>
    <img class="profile" src="16.3.png" alt="รูปโปรไฟล์">
    <p>สวัสดี! ฉันชื่อ ถิรวัฒน์ กันทะกอง ยินดีที่ได้รู้จัก</p>
</section>

</body>
</html>

<!-- gallery.html -->   
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>แกลอรี่ - เว็บไซต์ส่วนตัว</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            background: #414141;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px;
            background: #000000;
            color: #ffffff;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color:  #ffffff;
        }
        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 0 10px #070707;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1>แกลอรี่</h1>
</header>

<nav>
    <a href="index.html">หน้าแรก</a>
    <a href="about.html">เกี่ยวกับฉัน</a>
    <a href="gallery.html">แกลอรี่</a>
</nav>

<section id="gallery">
    <h2>รวมภาพผลงานและกิจกรรมของฉัน</h2>
    <img src="16.2.jpg" alt="ผลงาน 1" width="200">
    <img src="16.4.jpg" alt="ผลงาน 2" width="200">
    <img src="16.jpg" alt="ผลงาน 3" width="200">
</section>

</body>
</html>
