<!doctype html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>محلات محمد الشامي لقطع الغيار</title>
    <meta name="description" content="محلات محمد الشامي لقطع الغيار - سيارات ونقل ثقيل، بطاريات، إطارات، زيوت وفلاتر، مصابيح وقطع غيار المحركات.">

    <style>
:root {
    --navy: #071a2b;
    --navy-light: #0d2a40;
    --red: #ed1828;
    --green: #08a34a;
    --light: #f6f7f9;
    --line: #d8dee5;
    --text: #101820;
}

* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    background: var(--light);
    color: var(--text);
    font-family: Tahoma, Arial, sans-serif;
}

button,
input,
textarea {
    font: inherit;
}

a {
    color: inherit;
    text-decoration: none;
}

.top {
    height: 42px;
    padding: 0 4%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #071321;
    color: #fff;
    font-size: 14px;
}

.top .contact,
.top .right {
    display: flex;
    align-items: center;
    gap: 18px;
}

.top .right {
    gap: 22px;
}

.wa {
    color: #fff;
}

.header {
    padding: 14px 4%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
    background: #fff;
    border-bottom: 1px solid #ddd;
}

.brand {
    min-width: 300px;
    display: flex;
    align-items: center;
    gap: 12px;
}

.logo {
    width: 64px;
    height: 64px;
    display: grid;
    place-items: center;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--red), #b30d19);
    color: #fff;
    font-size: 30px;
    box-shadow: 0 4px 12px #0002;
}

.brand h1 {
    margin: 0;
    font-size: 27px;
}

.brand .sub {
    color: var(--red);
    font-size: 20px;
    font-weight: 800;
}

.brand small {
    display: block;
    color: #283746;
    font-weight: 700;
}

.search {
    width: 100%;
    max-width: 600px;
    height: 48px;
    display: flex;
    overflow: hidden;
    border: 1px solid #cbd2da;
    border-radius: 10px;
    background: #fff;
}

.search input {
    flex: 1;
    padding: 0 18px;
    border: 0;
    outline: 0;
    color: #555;
}

.search button {
    width: 62px;
    border: 0;
    background: var(--red);
    color: #fff;
    font-size: 22px;
    cursor: pointer;
}

.cart {
    display: flex;
    align-items: center;
    gap: 8px;
    white-space: nowrap;
    font-size: 15px;
    font-weight: 800;
}

.cart .bubble {
    padding: 2px 7px;
    border-radius: 50%;
    background: var(--red);
    color: #fff;
    font-size: 12px;
}

.nav {
    display: flex;
    justify-content: center;
    overflow-x: auto;
    padding: 0 2%;
    background: var(--navy);
    color: #fff;
}

.nav button {
    min-width: 125px;
    padding: 14px 8px 12px;
    border: 0;
    border-bottom: 4px solid transparent;
    background: transparent;
    color: #fff;
    cursor: pointer;
    font-weight: 800;
    white-space: nowrap;
}

.nav button:hover,
.nav button.active {
    border-bottom-color: var(--red);
    background: #0c263b;
}

main {
    max-width: 1500px;
    margin: 0 auto;
}

.hero {
    position: relative;
    height: 390px;
    overflow: hidden;
    background: #071421;
}

.hero img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: cover;
    filter: saturate(1.05);
}

.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(90deg, rgba(3, 13, 24, .15), rgba(3, 13, 24, .83));
}

.heroContent {
    position: absolute;
    z-index: 2;
    top: 50%;
    right: 5%;
    width: min(48%, 650px);
    transform: translateY(-50%);
    color: #fff;
}

.eyebrow {
    display: inline-block;
    padding: 8px 22px;
    background: var(--red);
    font-size: 18px;
    font-weight: 900;
    clip-path: polygon(6% 0, 100% 0, 94% 100%, 0 100%);
}

.hero h2 {
    margin: 14px 0 10px;
    font-size: 48px;
    line-height: 1.1;
}

.hero p {
    margin: 0 0 16px;
    font-size: 19px;
    line-height: 1.8;
    font-weight: 700;
}

.features {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin: 12px 0 18px;
}

.feature {
    padding: 9px 12px;
    border-right: 1px solid #ffffff55;
    font-size: 14px;
}

.cta {
    padding: 13px 30px;
    border: 0;
    border-radius: 30px;
    background: var(--red);
    color: #fff;
    cursor: pointer;
    font-size: 18px;
    font-weight: 900;
    box-shadow: 0 8px 20px #e6001b33;
}

.section {
    padding: 22px 4%;
}

.sectionHead {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 15px;
}

.sectionHead h3 {
    margin: 0;
    font-size: 24px;
}

.sectionHead .all {
    color: var(--red);
    cursor: pointer;
    font-weight: 900;
}

.categories,
.products {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 14px;
}

.cat {
    overflow: hidden;
    border: 1px solid #d6dde5;
    border-radius: 10px;
    background: #fff;
    cursor: pointer;
    box-shadow: 0 2px 8px #0000000b;
    transition: .2s;
}

.cat:hover {
    transform: translateY(-3px);
    box-shadow: 0 7px 18px #0002;
}

.cat img {
    width: 100%;
    height: 110px;
    display: block;
    object-fit: cover;
}

.cat .label {
    padding: 10px;
    background: var(--navy);
    color: #fff;
    text-align: center;
    font-weight: 900;
}

.product {
    min-height: 275px;
    padding: 10px;
    display: flex;
    flex-direction: column;
    border: 1px solid var(--line);
    border-radius: 10px;
    background: #fff;
}

.product img {
    width: 100%;
    height: 140px;
    display: block;
    object-fit: cover;
    border-radius: 8px;
    background: #f0f2f5;
}

.product h4 {
    margin: 8px 2px 5px;
    font-size: 14px;
    line-height: 1.5;
}

.price {
    margin-bottom: 8px;
    color: var(--red);
    font-size: 18px;
    font-weight: 900;
}

.order {
    margin-top: auto;
    padding: 9px;
    border: 0;
    border-radius: 8px;
    background: var(--green);
    color: #fff;
    cursor: pointer;
    text-align: center;
    font-weight: 900;
}

.benefits {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 20px 4%;
    background: var(--navy);
    color: #fff;
}

.benefit {
    padding: 8px;
    border-left: 1px solid #ffffff24;
    text-align: center;
}

.benefit:last-child {
    border-left: 0;
}

.benefit b {
    display: block;
    margin-bottom: 6px;
    color: #fff;
    font-size: 17px;
}

.benefit span {
    color: #d8e2ea;
    font-size: 13px;
}

.footer {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 25px;
    padding: 25px 4%;
    background: #04111e;
    color: #fff;
}

.footer h4 {
    margin: 0 0 10px;
    font-size: 18px;
}

.footer p,
.footer li {
    color: #c8d3dc;
    font-size: 13px;
    line-height: 1.8;
}

.footer ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

.social {
    display: flex;
    gap: 8px;
    margin-top: 12px;
}

.social a {
    width: 36px;
    height: 36px;
    display: grid;
    place-items: center;
    border-radius: 8px;
    background: #102b42;
}

.copyright {
    padding: 12px;
    background: #020b13;
    color: #9fb0bf;
    text-align: center;
    font-size: 12px;
}

.toast {
    position: fixed;
    z-index: 20;
    left: 20px;
    bottom: 20px;
    display: none;
    padding: 13px 18px;
    border-radius: 10px;
    background: var(--navy);
    color: #fff;
    box-shadow: 0 10px 30px #0004;
}

.modal {
    position: fixed;
    z-index: 30;
    inset: 0;
    display: none;
    align-items: center;
    justify-content: center;
    padding: 20px;
    background: #0008;
}

.modalBox {
    position: relative;
    width: min(560px, 100%);
    padding: 22px;
    border-radius: 15px;
    background: #fff;
}

.close {
    position: absolute;
    top: 10px;
    left: 12px;
    width: 32px;
    height: 32px;
    border: 0;
    border-radius: 50%;
    background: #eee;
    cursor: pointer;
}

.modalBox h3 {
    margin-top: 0;
}

.modalBox input,
.modalBox textarea {
    width: 100%;
    margin: 7px 0;
    padding: 11px;
    border: 1px solid #ccd4dd;
    border-radius: 8px;
    outline: none;
}

.modalBox > button:last-child {
    padding: 11px 18px;
    border: 0;
    border-radius: 8px;
    background: var(--red);
    color: #fff;
    cursor: pointer;
    font-weight: 900;
}

@media (max-width: 1100px) {
    .categories,
    .products {
        grid-template-columns: repeat(3, 1fr);
    }

    .heroContent {
        width: 58%;
    }

    .hero h2 {
        font-size: 40px;
    }

    .footer {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 700px) {
    .top {
        font-size: 11px;
    }

    .header {
        flex-wrap: wrap;
    }

    .brand {
        width: 100%;
        min-width: 0;
        justify-content: center;
    }

    .brand h1 {
        font-size: 21px;
    }

    .search {
        order: 3;
        max-width: none;
    }

    .nav {
        justify-content: flex-start;
    }

    .nav button {
        min-width: 105px;
        font-size: 12px;
    }

    .hero {
        height: 470px;
    }

    .heroContent {
        top: auto;
        right: 5%;
        bottom: 25px;
        width: 90%;
        transform: none;
    }

    .hero h2 {
        font-size: 32px;
    }

    .hero p {
        font-size: 15px;
    }

    .categories,
    .products {
        grid-template-columns: repeat(2, 1fr);
    }

    .benefits {
        grid-template-columns: 1fr 1fr;
    }

    .footer {
        grid-template-columns: 1fr;
    }
}
    </style>
</head>
<body>
    <div class="top">
        <div class="contact">
            <span>📞 تواصل معنا</span>
            <a class="wa" href="https://wa.me/967771234567" target="_blank">🟢 +967 77 123 4567</a>
        </div>
        <div class="right">
            <span>👤 تسجيل الدخول</span>
            <span>✚ إنشاء حساب</span>
        </div>
    </div>

    <header class="header">
        <div class="cart">
            🛒
            <span class="bubble" id="cartCount">0</span>
            سلة المشتريات
        </div>

        <div class="search">
            <input id="search" placeholder="ابحث عن القطعة التي تحتاجها ...">
            <button type="button">⌕</button>
        </div>

        <div class="brand">
            <div>
                <h1>محلات محمد الشامي</h1>
                <div class="sub">لقطع الغيار</div>
                <small>جودة .. ثقة .. لرحلة آمنة</small>
            </div>
            <div class="logo">🚗</div>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="heroContent">
                <span class="eyebrow">قطع أصلية 100%</span>
                <h2>جميع أنواع قطع غيار السيارات والنقل الثقيل</h2>
                <p>نوفر لكم أفضل قطع الغيار الأصلية والمضمونة بأعلى معايير الجودة وبأفضل الأسعار.</p>
            </div>
        </section>

        <section class="section">
            <div class="sectionHead">
                <h3>الأقسام الرئيسية</h3>
            </div>
            <div class="categories">
                <div class="cat"><div class="label">قطع غيار السيارات</div></div>
                <div class="cat"><div class="label">النقل الثقيل</div></div>
                <div class="cat"><div class="label">البطاريات</div></div>
                <div class="cat"><div class="label">الزيوت والفلاتر</div></div>
                <div class="cat"><div class="label">الإطارات والجنوط</div></div>
                <div class="cat"><div class="label">المصابيح والكشافات</div></div>
            </div>
        </section>
    </main>

    <footer>
        <div class="copyright">© 2026 محلات محمد الشامي لقطع الغيار - جميع الحقوق محفوظة</div>
    </footer>
</body>
</html>
