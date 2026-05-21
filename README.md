<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RENJUN 323</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@300;400;600;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet" />
</head>
<body>

  <!-- ===== NAVBAR ===== -->
  <nav class="navbar">
    <div class="nav-logo">RENJUN <span>323</span></div>
    <ul class="nav-links">
      <li><a href="#home">หน้าแรก</a></li>
      <li><a href="#profile">ประวัติ</a></li>
      <li><a href="#support">วิธีซัพ</a></li>
      <li><a href="#works">ผลงาน</a></li>
      <li><a href="#news">ข่าวสาร</a></li>
    </ul>
    <div class="hamburger" onclick="toggleMenu()">☰</div>
  </nav>

  <!-- ===== HERO (หน้าแรก) ===== -->
  <section id="home" class="hero">
    <div class="hero-content">
      <p class="hero-name-th">หวงเหรินจวิ้น · ฮวังอินจุน</p>
      <h1 class="hero-title">HUANG RENJUN</h1>
      <p class="hero-name-cn">黄仁俊 · 황런쥔</p>
      <p class="hero-birth">เกิดเมื่อ 23 . 03 . 2000</p>
      <div class="hero-btns">
        <a href="#profile" class="btn-outline">ประวัติ</a>
        <a href="#support" class="btn-fill">วิธีซัพ</a>
      </div>
    </div>
  </section>

  <!-- ===== PROFILE (ประวัติ) ===== -->
  <section id="profile" class="section">
    <div class="container">

      <div class="section-header">
        <p class="section-num">01</p>
        <h2 class="section-title">ประวัติ & โปรไฟล์</h2>
        <p class="section-sub">ทุกอย่างที่ควรรู้เกี่ยวกับ Huang Renjun</p>
      </div>

      <!-- ข้อมูลส่วนตัว -->
      <div class="card">
        <h3 class="card-title">🪪 ข้อมูลส่วนตัว</h3>
        <table class="info-table">
          <tr>
            <td>ชื่อจีน</td>
            <td>黄仁俊 (Huáng Rénjùn)</td>
          </tr>
          <tr>
            <td>ชื่อเกาหลี</td>
            <td>황런쥔 (Hwang Reon-jun)</td>
          </tr>
          <tr>
            <td>ชื่อเล่น</td>
            <td>Renjun, Injun</td>
          </tr>
          <tr>
            <td>วันเกิด</td>
            <td>23 มีนาคม ค.ศ. 2000</td>
          </tr>
          <tr>
            <td>สัญชาติ</td>
            <td>จีน 🇨🇳</td>
          </tr>
          <tr>
            <td>เมืองเกิด</td>
            <td>Jilin, จีน</td>
          </tr>
          <tr>
            <td>กรุ๊ปเลือด</td>
            <td>O</td>
          </tr>
        </table>
      </div>

    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
