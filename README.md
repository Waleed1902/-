<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>حرس سلاح</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #121212;
      color: #f1f1f1;
      line-height: 1.6;
    }
    header, footer {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
    }
    header h1::before {
      content: "\2694"; /* ⚔ رمز سيفين متقاطعين */
      font-size: 1.5em;
    }
    nav a {
      color: #f1f1f1;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      color: #00bcd4;
    }
    .container {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 40px;
    }
    .article-card {
      background-color: #1e1e1e;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    .article-card img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    .article-card h3 {
      color: #00bcd4;
    }
    .article-card small {
      color: #999;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      background-color: #2c2c2c;
      color: #fff;
    }
    form button {
      padding: 10px 20px;
      background-color: #00bcd4;
      color: #000;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #0097a7;
    }
    @media (max-width: 768px) {
      nav a { display: block; margin: 10px 0; }
      header h1 { flex-direction: column; gap: 5px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>حرس سلاح</h1>
    <nav>
      <a href="#home">الرئيسية</a>
      <a href="#about">من نحن</a>
      <a href="#services">الخدمات</a>
      <a href="#contact">تواصل معنا</a>
    </nav>
  </header>

  <div class="container">
    <section id="home">
      <h2>أحدث الأخبار والتحليلات</h2>

      <div class="article-card">
        <img src="https://via.placeholder.com/800x400?text=دبابة+معركة" alt="دبابة">
        <h3>تحليل: تطورات الحرب المدرعة في أوروبا الشرقية</h3>
        <small>نُشر في: 18 أبريل 2025</small>
        <p>تزايد استخدام الدبابات المتقدمة يُعيد تعريف التكتيكات الحديثة في ساحات القتال.</p>
      </div>

      <div class="article-card">
        <img src="https://via.placeholder.com/800x400?text=طائرة+مقاتلة" alt="طائرة مقاتلة">
        <h3>مقارنة بين F-35 وSu-57: من يملك الأفضلية؟</h3>
        <small>نُشر في: 16 أبريل 2025</small>
        <p>استعراض تقني لمميزات الطائرتين وأدوارهما في الصراعات المستقبلية.</p>
      </div>
    </section>

    <section id="about">
      <h2>من نحن</h2>
      <p>نحن فريق متخصص في الشؤون العسكرية نقدم تحليلات وقراءات استراتيجية للأحداث الراهنة.</p>
    </section>

    <section id="services">
      <h2>الخدمات</h2>
      <ul>
        <li>تحليلات عسكرية مخصصة</li>
        <li>تقارير دورية وعمليات تقييم</li>
        <li>استشارات في مجال التسليح والتكتيك</li>
      </ul>
    </section>

    <section id="contact">
      <h2>تواصل معنا</h2>
      <form>
        <input type="text" placeholder="الاسم الكامل" required>
        <input type="email" placeholder="البريد الإلكتروني" required>
        <textarea rows="5" placeholder="رسالتك" required></textarea>
        <button type="submit">إرسال</button>
      </form>
    </section>
  </div>

  <footer>
    <p>جميع الحقوق محفوظة &copy; 2025</p>
  </footer>
</body>
</html># -
موقع مهتم بالشئون العسكرية 
