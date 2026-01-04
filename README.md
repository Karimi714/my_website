<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>شرکت کوهپیما</title>
  <style>
    body {
      font-family: Tahoma, sans-serif;
      direction: rtl;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #066231;
      color: rgb(231, 217, 200);
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #176846;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: rgb(225, 208, 190);
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
    }
    footer {
      background-color: #196c57;
      color: rgb(235, 211, 198);
      text-align: center;
      padding: 15px;
    }
    
    .image-section {
      display: flex;
      align-items: center;
      padding: 40px;
      gap: 20px;
    }
    .image-section img {
      width: 600px;
      height: auto;
      border-radius: 10px;
    }
    .image-section .text {
      flex: 1;
    }
  </style>
</head>
<body>

  <header>
    <h1>شرکت کوهپیما</h1>
  </header>

  <nav>
    <a href="#about">درباره ما</a>
    <a href="#products">محصولات</a>
    <a href="#members">اعضا</a>
    <a href="#contact">ارتباط با ما</a>
  </nav>

  <!-- بخش درباره ما با عکس سمت چپ -->
  <section id="about" class="image-section">
    <img src="https://www.grisport.co.uk/blog/wp-content/uploads/2021/07/hiking-1536x1025.jpeg" alt="کوه">
    <div class="text">
      <h2>درباره شرکت</h2>
      <p>
        شرکت کوهپیما با هدف ارائه بهترین تجهیزات کوهنوردی تأسیس شده است.  
        ما تلاش می‌کنیم تا تجربه‌ای ایمن و لذت‌بخش برای علاقه‌مندان به طبیعت فراهم کنیم.
      </p>
    </div>
  </section>

  <!-- بخش محصولات با عکس روبرو -->
  <section id="products" class="image-section">
    <div class="text">
      <h2>محصولات</h2>
      <p>در این بخش می‌توانید محصولات شرکت ما را مشاهده کنید.</p>
      <ul>
        <li>کفش کوهنوردی</li>
        <li>باتوم</li>
        <li>کوله پشتی</li>
        <li>یخ شکن</li>
        <li>ارتفاع سنج</li>
        <li>کیسه‌خواب</li>
        <li>طناب و کارابین</li>
        <li>نقشه و قطب‌نما</li>
        <li>لباس</li>
      </ul>
    </div>
    <img src="https://www.outdoors.org/wp-content/uploads/2022/12/Winter-Hiking-Essential-Gear-List-1024x538-1.jpg" alt="محصولات کوهنوردی">
  </section>

  <section id="members">
    <h2>اعضا</h2>
    <p>اعضای اصلی تیم ما:</p>
    <ul>
      <li>مدیرعامل: فاطمه کریمی</li>
      <li>مدیر فنی: ایلان ماسک</li>
      <li>مدیر فروش: سیاوش قمیشی</li>
    </ul>
  </section>

  <section id="contact">
    <h2>ارتباط با ما</h2>
    <p>ایمیل: karimifateme355@gmail.com</p>
    <p>تلفن: 021-12345678</p>
  </section>

  <footer>
    <p>© ^..^ کوهپیما - با ما قله‌ها را فتح کنید.</p>
  </footer>

</body>
</html>
