<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MASRAFI | Official Website</title>
  <style>
    body{
      margin:0;
      font-family: 'Segoe UI', sans-serif;
      background:#0f172a;
      color:#f8fafc;
    }
    header{
      background:#020617;
      padding:20px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }
    header h1{
      margin:0;
      color:#facc15;
      letter-spacing:2px;
    }
    nav a{
      color:#e5e7eb;
      margin-left:20px;
      text-decoration:none;
      font-weight:500;
    }
    nav a:hover{color:#facc15;}
    .hero{
      padding:100px 20px;
      text-align:center;
      background:linear-gradient(135deg,#020617,#1e293b);
    }
    .hero h2{
      font-size:42px;
      color:#facc15;
    }
    .hero p{
      max-width:700px;
      margin:20px auto;
      color:#cbd5f5;
      font-size:18px;
    }
    .btn{
      display:inline-block;
      margin-top:25px;
      padding:14px 32px;
      background:#facc15;
      color:#020617;
      font-weight:600;
      border-radius:30px;
      text-decoration:none;
    }
    section{
      padding:80px 40px;
    }
    section h3{
      text-align:center;
      font-size:32px;
      margin-bottom:40px;
      color:#facc15;
    }
    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }
    .card{
      background:#020617;
      padding:30px;
      border-radius:18px;
      box-shadow:0 10px 25px rgba(0,0,0,0.4);
    }
    .card h4{margin-top:0;color:#fde047;}
    footer{
      background:#020617;
      padding:30px;
      text-align:center;
      color:#94a3b8;
    }
  </style>
</head>
<body>

<header>
  <h1>MASRAFI</h1>
  <!-- Logo can be placed here -->
  <nav>
    <a href="#home">হোম</a>
    <a href="#about">আমার সম্পর্কে</a>
    <a href="#services">কাজ</a>
    <a href="#contact">যোগাযোগ</a>
  </nav>
</header>

<section class="hero" id="home">
  <img src="logo.png" alt="MASRAFI Logo" style="max-width:140px;margin-bottom:20px;">
  <h2>MASRAFI – Digital Creator</h2>
  <p>আমি একজন প্রফেশনাল ডিজিটাল কনটেন্ট ক্রিয়েটর। ইসলামিক, ভিডিও, লিরিক্স এবং ক্রিয়েটিভ ডিজাইনের মাধ্যমে মানুষের কাছে ভ্যালু পৌঁছে দেওয়াই আমার লক্ষ্য।</p>
  <a class="btn" href="#contact">যোগাযোগ করুন</a>
</section>

<section id="about">
  <h3>আমার সম্পর্কে</h3>
  <p style="max-width:800px;margin:auto;text-align:center;color:#cbd5f5;">
    MASRAFI একটি ব্যক্তিগত ব্র্যান্ড যেখানে আমি আমার ডিজিটাল দক্ষতা, অভিজ্ঞতা ও ক্রিয়েটিভ আইডিয়াগুলো শেয়ার করি। আমার কাজ মানে গুণগত মান ও বিশ্বাসযোগ্যতা।
  </p>
</section>

<section id="services">
  <h3>আমার কাজ</h3>
  <div class="grid">
    <div class="card">
      <h4>ইসলামিক কনটেন্ট</h4>
      <p>শরীয়াহসম্মত ও সুন্দর ইসলামিক ভিডিও ও পোস্ট তৈরি।</p>
    </div>
    <div class="card">
      <h4>লিরিক্স ভিডিও</h4>
      <p>প্রফেশনাল বাংলা ও ইংরেজি লিরিক্স ভিডিও ডিজাইন।</p>
    </div>
    <div class="card">
      <h4>ডিজিটাল ব্র্যান্ডিং</h4>
      <p>ব্যক্তিগত ও বিজনেস ব্র্যান্ডের জন্য আধুনিক ডিজিটাল সল্যুশন।</p>
    </div>
  </div>
</section>

<section id="contact">
  <a href="https://wa.me/880000000000" class="btn" style="margin-bottom:20px;">WhatsApp এ মেসেজ দিন</a>
  <h3>যোগাযোগ</h3>
  <p style="text-align:center;color:#cbd5f5;">WhatsApp / Facebook / Email এর মাধ্যমে যোগাযোগ করুন</p>
</section>

<footer>
  © 2026 MASRAFI | All Rights Reserved
</footer>

</body>
</html>
