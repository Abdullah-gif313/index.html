# index.html
موقع معلومات بسيط
<!DOCTYPE html>

<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="موقع تعليمي متكامل عن البرمجة، الأنبياء، والحضارات">
  <title>موسوعة تعليمية</title>
  <style>
    body {
      font-family: "Cairo", sans-serif;
      margin: 0;
      background: #f4f7fb;
      color: #333;
      line-height: 1.9;
    }
    header {
      text-align: center;
      padding: 2.5rem;
      background: linear-gradient(90deg, #4facfe, #00f2fe);
      color: white;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      background: #ffffff;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      text-decoration: none;
      background: #0066cc;
      color: white;
      padding: 8px 14px;
      border-radius: 8px;
      font-size: 0.9rem;
    }
    nav a:hover {
      background: #004999;
    }
    .container {
      max-width: 950px;
      margin: auto;
      padding: 2rem;
    }
    .section {
      background: white;
      padding: 2rem;
      border-radius: 15px;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }
    .section img {
      width: 100%;
      max-width: 360px;
      display: block;
      margin: 1rem auto;
      border-radius: 12px;
    }
    h2 {
      color: #0066cc;
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #eee;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>موسوعة تعليمية شاملة</h1>
  <p>البرمجة • الأنبياء • الحضارات • العلوم</p>
</header>

<nav>
  <a href="#programming">البرمجة</a>
  <a href="#pioneers">رواد الحاسوب</a>
  <a href="#languages">لغات البرمجة</a>
  <a href="#prophets">الأنبياء</a>
  <a href="#mesopotamia">حضارة الرافدين</a>
  <a href="#egypt">الحضارة المصرية</a>
</nav>

<div class="container">

  <div class="section" id="programming">
    <h2>ما هي البرمجة؟</h2>
    <p>
      البرمجة هي عملية إعطاء أوامر وتعليمات للحاسوب بلغة يفهمها، ليقوم بتنفيذ مهام
      محددة. تعتمد البرمجة على التفكير المنطقي وحل المشكلات، وهي أساس جميع
      التطبيقات والمواقع الحديثة.
    </p>
    <p>
      تُستخدم البرمجة في مجالات متعددة مثل الطب، التعليم، الاتصالات، والألعاب،
      مما يجعلها من أهم علوم العصر الحديث.
    </p>
  </div>

  <div class="section" id="pioneers">
    <h2>رواد علم الحاسوب</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/Ada_Lovelace_portrait.jpg" alt="آدا لوفلايس">
    <p>
      آدا لوفلايس أول مبرمجة في التاريخ، كتبت أول خوارزمية للآلة التحليلية،
      وتنبأت باستخدام الحواسيب لأغراض متعددة غير الحساب.
    </p>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Charles_Babbage_-_1860.jpg" alt="تشارلز باباج">
    <p>
      تشارلز باباج يُعرف بأبي الحاسوب، وهو صاحب فكرة الآلة التحليلية التي شكّلت
      الأساس النظري للحواسيب الحديثة.
    </p>
  </div>

  <div class="section" id="languages">
    <h2>لغات البرمجة</h2>
    <p>
      بدأت لغات البرمجة بلغة الآلة ثم لغة التجميع، وبعدها ظهرت لغات عالية المستوى
      مثل FORTRAN و COBOL، مما سهّل كتابة البرامج.
    </p>
    <p>
      اليوم توجد لغات حديثة مثل Python و JavaScript تُستخدم في الذكاء الاصطناعي
      وتطوير المواقع والتطبيقات.
    </p>
  </div>

  <div class="section" id="prophets">
    <h2>الأنبياء ودورهم في الحضارة</h2>
    <p>
      ساهم الأنبياء في بناء المجتمعات من خلال نشر القيم الأخلاقية مثل العدل
      والأمانة والعمل، وهي أساس أي حضارة مستقرة.
    </p>
    <p>
      رسالات الأنبياء ساعدت على تنظيم حياة الناس، ونشرت العلم والتفكير السليم
      بين الأمم.
    </p>
  </div>

  <div class="section" id="mesopotamia">
    <h2>حضارة بلاد الرافدين</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Ziggurat_of_Ur.jpg" alt="زقورة أور">
    <p>
      ظهرت حضارة بلاد الرافدين بين نهري دجلة والفرات، وتُعد من أقدم الحضارات في
      التاريخ. اشتهرت بالكتابة المسمارية وسن القوانين.
    </p>
    <p>
      كان لهذه الحضارة دور كبير في تطور الزراعة والعلوم والفنون.
    </p>
  </div>

  <div class="section" id="egypt">
    <h2>الحضارة المصرية القديمة</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Kheops-Pyramid.jpg" alt="أهرامات الجيزة">
    <p>
      تميزت الحضارة المصرية القديمة ببناء الأهرامات والمعابد، وبتقدمها في الطب
      والهندسة والفلك.
    </p>
    <p>
      ما زالت آثارها شاهدة على عظمة هذه الحضارة حتى اليوم.
    </p>
  </div>

</div>

<footer>
 &copy; 2025 - 2026 — موقع الطالب عبدالله حسين كتاب
</footer>

</body>
</html>
