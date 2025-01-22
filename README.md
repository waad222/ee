<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر النظارات</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="logo">متجر النظارات</div>
            <ul class="nav-links">
                <li><a href="#">الرئيسية</a></li>
                <li><a href="#products">المنتجات</a></li>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
                <li class="cart"><a href="#"><i class="fas fa-shopping-cart"></i> سلة التسوق</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>اكتشف أفضل تصاميم النظارات</h1>
        <p>جودة عالية، تصميم عصري، وأسعار مميزة.</p>
        <a href="#products" class="btn">تسوق الآن</a>
    </section>

    <section id="products" class="products">
        <h2>منتجاتنا</h2>
        <div class="product-grid">
            <div class="product">
                <img src="glasses1.jpg" alt="نظارة 1">
                <h3>نظارة شمسية</h3>
                <p>200 ريال</p>
                <button class="btn add-to-cart">إضافة إلى السلة</button>
            </div>
            <div class="product">
                <img src="glasses2.jpg" alt="نظارة 2">
                <h3>نظارة طبية</h3>
                <p>150 ريال</p>
                <button class="btn add-to-cart">إضافة إلى السلة</button>
            </div>
            <!-- أضف المزيد من المنتجات هنا -->
        </div>
    </section>

    <section id="about" class="about">
        <h2>من نحن</h2>
        <p>متجر النظارات يقدم مجموعة مميزة من النظارات الشمسية والطبية بجودة عالية وتصاميم عصرية تناسب جميع الأذواق.</p>
    </section>

    <section id="contact" class="contact">
        <h2>اتصل بنا</h2>
        <form>
            <input type="text" placeholder="الاسم" required>
            <input type="email" placeholder="البريد الإلكتروني" required>
            <textarea placeholder="رسالتك"></textarea>
            <button type="submit" class="btn">إرسال</button>
        </form>
    </section>

    <footer>
        <p>© 2025 متجر النظارات. جميع الحقوق محفوظة.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
