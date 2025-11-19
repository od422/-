<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>الصحة والوقاية</title>
  <style>
    :root{
      --orange:#ff7a18;
      --green:#2fb86a;
      --white:#ffffff;
      --text:#333;
      --muted:#666;
    }
    *{box-sizing:border-box}
    body{font-family:system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0;background:linear-gradient(180deg,var(--white),#fafafa);color:var(--text);}
    header{background:linear-gradient(90deg,var(--orange),var(--green));color:var(--white);padding:28px 16px}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:64px;height:64px;background:var(--white);border-radius:12px;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--orange)}
    nav{margin-top:8px}
    nav a{color:rgba(255,255,255,0.95);text-decoration:none;margin-left:14px;font-weight:600}

    .hero{display:flex;gap:24px;align-items:center;padding:36px 0}
    .hero .left{flex:1}
    .hero h1{font-size:28px;margin:0 0 8px}
    .hero p{margin:0;color:var(--muted)}
    .cta{margin-top:16px}
    .btn{display:inline-block;padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700}
    .btn-primary{background:var(--white);color:var(--orange)}
    .btn-outline{background:transparent;color:var(--white);border:2px solid rgba(255,255,255,0.25)}

    .card-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:24px}
    .card{background:#fff;border-radius:12px;box-shadow:0 6px 18px rgba(10,10,10,0.06);padding:16px}
    .card h3{margin:0 0 6px}
    .card p{margin:0;color:var(--muted);font-size:14px}

    section{padding:28px 0;border-bottom:1px solid #eee}
    .section-title{display:flex;justify-content:space-between;align-items:center}
    .section-title h2{margin:0}

    .team{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:16px}
    .profile{background:linear-gradient(180deg,#fff,#fcfcfc);border-radius:12px;padding:14px;display:flex;gap:12px;align-items:center}
    .avatar{width:72px;height:72px;border-radius:12px;background:linear-gradient(180deg,var(--green),var(--orange));display:flex;align-items:center;justify-content:center;color:var(--white);font-weight:700}
    .role{font-weight:700}
    .duties{font-size:13px;color:var(--muted);margin-top:6px}

    .shop{display:grid;grid-template-columns:1fr 320px;gap:20px}
    .product{display:flex;gap:12px;align-items:center;padding:12px;border-radius:10px;background:#fff}
    .product img{width:84px;height:84px;border-radius:8px;object-fit:cover}
    .product .info{flex:1}
    .price{font-weight:800;color:var(--orange)}

    footer{padding:20px 0;color:var(--muted)}

    /* responsive */
    @media (max-width:800px){
      .hero{flex-direction:column}
      .shop{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="brand">
        <div class="logo">صحتك</div>
        <div>
          <div style="font-weight:800;font-size:18px">الصحة والوقاية</div>
          <div style="font-size:13px;opacity:0.95">رعاية تغذوية - منتجات صحية - فريق متخصص</div>
        </div>
      </div>
      <nav>
        <a href="#services">الخدمات</a>
        <a href="#team">الفريق</a>
        <a href="#shop">المتجر</a>
        <a href="#contact">اتصل بنا</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="left">
        <h1>صحتك أولاً — عيادة وخدمات تغذية متكاملة</h1>
        <p>استشارات غذائية طبية، برامج تغذية فردية، منتجات طعام صحي، ودعم كامل من فريقنا — أخصائيين، طهاة، وفريق لوجستي متكامل.</p>
        <div class="cta">
          <a class="btn btn-primary" href="#contact">حجز موعد</a>
          <a class="btn btn-outline" href="#shop">تسوق الآن</a>
        </div>
      </div>
      <div class="right">
        <img src="" alt="الصحة والوقاية" style="border-radius:12px;max-width:100%">


      </div>
    </section>  
    <section id="services">
      <div class="section-title">
        <h2>خدماتنا</h2>
        <div style="font-size:13px;color:var(--muted)">عيادة - استشارات - منتجات</div>  
      </div>
      <div class="card-grid">
        <div class="card">
          <h3>استشارات طبية تغذوية</h3>
          <p>جلسات مع أخصائي تغذية مع خطط علاجية مخصصة للحالات المرضية والوقائية.</p>
        </div>
        <div class="card">
          <h3>برامج غذائية فردية</h3>
          <p>خطط تغذية مفصّلة لفقدان الوزن، زيادة الكتلة العضلية، والحفاظ على الصحة.</p>
        </div>
        <div class="card">
          <h3>متجر منتجات صحية</h3>
          <p>مخبوزات منخفضة السكر، وجبات جاهزة صحية، مكملات موثوقة، وتغليف مريح للشحن.</p>
      </div>
      </div>
    </section>

    <section id="team">
      <div class="section-title">
        <h2>فريق العمل</h2>
        <div style="font-size:13px;color:var(--muted)">هيكل الفريق ومهام كل عضو</div>
      </div>

      <div class="team">
        <div class="profile">
          <div class="avatar">م</div>
          <div>
            <div class="role">المدير العام</div>
            <div class="duties">إدارة العمليات، التخطيط الاستراتيجي، تنسيق الأقسام.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">أ</div>
          <div>
            <div class="role">أخصائي تغذية</div>
            <div class="duties">تقييم حالات المرضى، وضع البروتوكولات العلاجية والمتابعة.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">م</div>
          <div>
            <div class="role">مساعد أخصائي تغذية</div>
            <div class="duties">إعداد خطط، متابعة قياسات المرضى، دعم جلسات التثقيف.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">ش</div>
          <div>
            <div class="role">الشيف / مساعد طهي</div>
            <div class="duties">تحضير وصفات صحية، تنفيذ قوائم الطعام الخاصة بالعملاء.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">ت</div>
          <div>
            <div class="role">التغليف والتعبئة</div>
            <div class="duties">تغليف آمن، إعداد الطلبيات للشحن، ضمان جودة المنتج.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">م</div>
          <div>
            <div class="role">التسويق</div>
            <div class="duties">إدارة حملات التواصل، تصميم عروض ترويجية وزيادة الوعي.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">د</div>
          <div>
            <div class="role">المصمم</div>
            <div class="duties">تصميم واجهات، محتوى بصري، والهوية التجارية.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">م</div>
          <div>
            <div class="role">المصور</div>
            <div class="duties">التقاط صور المنتجات والطعام، جلسات تصوير للعيادة.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">ل</div>
          <div>
            <div class="role">اللوجستيك / المخزون</div>
            <div class="duties">إدارة المخزون، التوريد، وتنظيم عمليات الشحن.</div>
          </div>
        </div>

        <div class="profile">
          <div class="avatar">ح</div>
          <div>
            <div class="role">المحاسبة</div>
            <div class="duties">فواتير، رواتب، متابعة الإيرادات والمصروفات.</div>
          </div>
        </div>
      </div>
    </section>

    <section id="shop">
      <div class="section-title">
        <h2>المتجر</h2>
        <div style="font-size:13px;color:var(--muted)">منتجات مختارة</div>
      </div>
      <div class="shop">
        <div>
          <div class="product">
            <img src="https://static.srpcdigital.com/styles/1037xauto/public/2015/04/30/Health-010515-3.jpg.webp" alt="منتج 1">
            <div class="info">
              <div style="font-weight:800">مخبوز صحي منخفض السكر</div>
              <div style="font-size:13px;color:var(--muted)">تفاصيل صغيرة عن المنتج، مكونات مختصرة.</div>
            </div>
            <div class="price">25 SR</div>
          </div>

          <div class="product" style="margin-top:12px">
            <img src="https://vid.alarabiya.net/images/2023/05/09/70ba808c-a47c-4d88-803a-f9bdce32f439/70ba808c-a47c-4d88-803a-f9bdce32f439_16x9_1200x676.PNG?width=555&format=jpg" alt="منتج 2">
            <div class="info">
              <div style="font-weight:800">وجبة جاهزة صحية</div>
              <div style="font-size:13px;color:var(--muted)">مناسبة للدايت والغذاء المتوازن.</div>
            </div>
            <div class="price">45 SR</div>
          </div>
        </div>

        <aside class="card">
          <h3>عربة المشتريات</h3>
          <p style="margin-top:8px">لا توجد منتجات بعد — مثال لتصميم سلة المشتريات والخصومات والشحن.</p>
          <div style="margin-top:12px">
            <a class="btn btn-primary" href="#" style="display:inline-block">الدفع</a>
          </div>
        </aside>
      </div>
    </section>

    <section id="contact">
      <div class="section-title">
        <h2>اتصل بنا</h2>
        <div style="font-size:13px;color:var(--muted)">موقعنا، مواعيد العمل، وحجز المواعيد</div>
      </div>
      <div class="card-grid">
        <div class="card">
          <h3>مواعيد العمل</h3>
          <p>السبت - الخميس: 9 صباحاً - 9 مساءً<br>الجمعة: 4 مساءً - 9 مساءً</p>
        </div>
        <div class="card">
          <h3>العنوان</h3>
          <p>عرعر، السعودية — </p>
        </div>
        <div class="card">
          <h3>حجز موعد</h3>
          <p>اتصل على: <strong>+966594918732</strong>  او <a href="https://wa.me/966594918732" target="_blank" 
   style="display: inline-flex; align-items: center; gap: 8px; 
   background: #25D366; padding: 10px 16px; color: #fff; 
   border-radius: 8px; text-decoration: none; font-weight: bold;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" 
         width="22" />
    واتساب
</a>

    تواصل معنا عبر الواتساب
</a>

        </div>
      </div>
    </section>
  </main>

  <footer class="container">
    <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap">
      <div>© جميع الحقوق محفوظة — الصحة والوقاية</div>
    </div>
  </footer>
</body>
</html>
