<!doctype html>
<html lang="ar">
<head>
  <meta charset="utf-8">
  <title>موقع سيفوو | Saifo</title>
  <style>
    body {
      font-family: "Cairo", sans-serif;
      background: linear-gradient(120deg, #d7f3ff, #ffffff);
      margin: 0;
      padding: 0;
      color: #333;
      direction: rtl;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 20px 0;
      text-align: center;
      border-bottom: 5px solid #005fa3;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    nav {
      background-color: #eaf6ff;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: #0077cc;
      text-decoration: none;
      font-weight: bold;
      margin: 0 15px;
      font-size: 1.1em;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    section {
      background-color: #fff;
      border-radius: 15px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      margin: 20px 0;
      padding: 20px;
    }

    section h2 {
      color: #005f99;
      border-bottom: 2px solid #e0e0e0;
      padding-bottom: 5px;
    }

    form {
      margin-top: 15px;
      line-height: 1.8;
    }

    input[type="text"],
    input[type="number"],
    input[type="email"] {
      padding: 8px;
      border-radius: 6px;
      border: 1px solid #ccc;
      width: 70%;
      margin-bottom: 10px;
    }

    input[type="submit"] {
      background-color: #0077cc;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 6px;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #005fa3;
    }

    footer {
      background-color: #0077cc;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 30px;
      border-top: 5px solid #005fa3;
    }
  </style>
</head>
<body>

  <header>
    <h1>موقع سيفوو | Saifo</h1>
    <p>مرحباً بك في أول موقع من إنشائي!</p>
  </header>

  <nav>
    <a href="#php">قسم PHP</a>
    <a href="#html">قسم HTML</a>
    <a href="#forms">النموذج</a>
  </nav>

  <main>

    <section id="php">
      <h2>👋 قسم PHP</h2>
      <p>هذه أول تجربة بسيطة لعرض صفحة PHP.</p>
    </section>

    <section id="html">
      <h2>🌐 قسم HTML</h2>
      <p>Hello! This is my first HTML paragraph. I am learning how to create web pages.</p>
      <p><a href="https://www.w3schools.com/" target="_blank">Learn more about HTML</a></p>
    </section>

    <section id="forms">
      <h2>📝 النموذج الموحد</h2>

      <form action="https://formsubmit.co/sywfy8057@gmail.com" method="POST">
        <input type="hidden" name="_captcha" value="false">

        <label>الاسم الكامل:</label><br>
        <input type="text" name="fullname" placeholder="أدخل اسمك الكامل" required><br>

        <label>الجنس:</label><br>
        <input type="radio" name="gender" value="ذكر" checked> ذكر
        <input type="radio" name="gender" value="أنثى"> أنثى<br>

        <label>الكمية (بين 1 و 5):</label><br>
        <input type="number" name="quantity" min="1" max="5"><br>

        <label>البريد الإلكتروني:</label><br>
        <input type="email" name="email" placeholder="example@email.com" required><br>

        <label>اسم المستخدم:</label><br>
        <input type="text" name="username" placeholder="اكتب اسم المستخدم" required><br><br>

        <input type="submit" value="إرسال النموذج">
      </form>

    </section>

  </main>

  <footer>
    <p>© 2025 جميع الحقوق محفوظة لموقع سيفوو | Saifo</p>
  </footer>

</body>
</html>
<!doctype html>
<html lang="ar">
<head>
  <meta charset="utf-8">
  <title>موقع سيفوو | Saifo</title>
  <style>
    body {
      font-family: "Cairo", sans-serif;
      background: linear-gradient(135deg, #d7f3ff, #ffffff);
      margin: 0;
      padding: 0;
      color: #333;
      direction: rtl;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 25px 0;
      text-align: center;
      border-bottom: 5px solid #005fa3;
    }

    header h1 {
      margin: 0;
      font-size: 2.2em;
    }

    header p {
      margin: 5px 0 0 0;
      font-size: 1.1em;
    }

    nav {
      background-color: #eaf6ff;
      text-align: center;
      padding: 10px 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    nav a {
      color: #0077cc;
      text-decoration: none;
      font-weight: bold;
      margin: 0 15px;
      font-size: 1.1em;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }

    section {
      background-color: #fff;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      margin: 20px 0;
      padding: 25px;
    }

    section h2 {
      color: #005f99;
      border-bottom: 2px solid #e0e0e0;
      padding-bottom: 8px;
    }

    p.message {
      font-size: 1.1em;
      line-height: 1.6;
      color: #333;
    }

    form {
      margin-top: 20px;
      line-height: 2;
    }

    input[type="text"],
    input[type="number"],
    input[type="email"],
    select {
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      width: 80%;
      margin-bottom: 12px;
    }

    input[type="submit"] {
      background-color: #0077cc;
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1em;
    }

    input[type="submit"]:hover {
      background-color: #005fa3;
    }

    footer {
      background-color: #0077cc;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 30px;
      border-top: 5px solid #005fa3;
    }

    .hidden-field {
      display: none;
    }
  </style>

  <script>
    function toggleInstitutionName() {
      const type = document.getElementById('institution-type').value;
      const schoolField = document.getElementById('school-name-field');
      const collegeField = document.getElementById('college-name-field');
      const instituteField = document.getElementById('institute-name-field');

      schoolField.style.display = 'none';
      collegeField.style.display = 'none';
      instituteField.style.display = 'none';

      if(type === 'مدرسة') schoolField.style.display = 'block';
      else if(type === 'كلية') collegeField.style.display = 'block';
      else if(type === 'معهد') instituteField.style.display = 'block';
    }
  </script>
</head>
<body>

  <header>
    <h1>موقع سيفوو | Saifo</h1>
    <p>مرحباً بك! يسعدنا سماع رأيك من خلال هذا النموذج.</p>
  </header>

  <nav>
    <a href="#forms">النموذج</a>
  </nav>

  <main>

    <section id="forms">
      <h2>📝 النموذج الموحد</h2>

      <form action="https://formsubmit.co/sywfy8057@gmail.com" method="POST">
        <input type="hidden" name="_captcha" value="false">

        <label>الاسم الكامل:</label><br>
        <input type="text" name="fullname" placeholder="أدخل اسمك الكامل" required><br>

        <label>العمر:</label><br>
        <input type="number" name="age" placeholder="أدخل عمرك" min="1" required><br>

        <label>الجنس:</label><br>
        <input type="radio" name="gender" value="ذكر" checked> ذكر
        <input type="radio" name="gender" value="أنثى"> أنثى<br>

        <label>البريد الإلكتروني:</label><br>
        <input type="email" name="email" placeholder="example@email.com" required><br>

        <label>اسم المستخدم:</label><br>
        <input type="text" name="username" placeholder="اكتب اسم المستخدم" required><br>

        <label>نوع المؤسسة:</label><br>
        <select id="institution-type" name="institution_type" onchange="toggleInstitutionName()" required>
          <option value="">اختر نوع المؤسسة</option>
          <option value="مدرسة">مدرسة</option>
          <option value="كلية">كلية</option>
          <option value="معهد">معهد</option>
        </select><br>

        <div id="school-name-field" class="hidden-field">
          <label>اسم المدرسة:</label><br>
          <input type="text" name="school_name" placeholder="أدخل اسم المدرسة"><br>
        </div>

        <div id="college-name-field" class="hidden-field">
          <label>اسم الكلية:</label><br>
          <input type="text" name="college_name" placeholder="أدخل اسم الكلية"><br>
        </div>

        <div id="institute-name-field" class="hidden-field">
          <label>اسم المعهد:</label><br>
          <input type="text" name="institute_name" placeholder="أدخل اسم المعهد"><br>
        </div>

        <label>المحافظة أو الدولة:</label><br>
        <input type="text" name="location" placeholder="أدخل المحافظة أو الدولة" required><br><br>

        <input type="submit" value="إرسال النموذج">
      </form>

    </section>

  </main>

  <footer>
    <p>© 2025 جميع الحقوق محفوظة لموقع سيفوو | Saifo</p>
  </footer>

</body>
</html>


