<!doctype html>

<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>محمد جرافيك — مصمم جرافيك ومواقع الويب</title>
  <meta name="description" content="محمد جرافيك — تصميم جرافيك وتطوير مواقع الويب. خدمات احترافية للشركات والمبدعين.">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,"Droid Arabic Kufi","Noto Naskh Arabic",sans-serif;background:linear-gradient(180deg,#071023 0%,var(--bg) 100%);color:#e6eef6;line-height:1.6}
    .container{max-width:1100px;margin:32px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700}
    h1{margin:0;font-size:1.6rem}
    p.lead{color:var(--muted);margin:6px 0 0}
    nav a{color:var(--muted);text-decoration:none;margin-left:14px}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:24px;margin-top:26px;align-items:center}
    .card{background:var(--card);padding:20px;border-radius:14px;box-shadow:0 6px 20px rgba(2,6,23,0.6)}
    .services{display:flex;flex-direction:column;gap:12px}
    .service{display:flex;gap:12px;align-items:center}
    .icon{width:52px;height:52px;border-radius:10px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent)}
    .btn{display:inline-block;padding:10px 16px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#7c3aed);color:#051023;text-decoration:none;font-weight:700}
    .contact-card{display:flex;flex-direction:column;gap:10px}
    .portfolio-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}
    .port-item{height:140px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(0,0,0,0.12));display:flex;align-items:center;justify-content:center;font-weight:700}
    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:0.9rem}
    @media(max-width:900px){.hero{grid-template-columns:1fr;}.portfolio-grid{grid-template-columns:repeat(2,1fr)} }
    @media(max-width:520px){.portfolio-grid{grid-template-columns:1fr}.logo{width:52px;height:52px}.brand h1{font-size:1.1rem}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">م</div>
        <div>
          <h1>محمد جرافيك</h1>
          <p class="lead">مصمم جرافيك ومطور مواقع — حلول بصرية تُحكى</p>
        </div>
      </div>
      <nav>
        <a href="#services">الخدمات</a>
        <a href="#portfolio">الأعمال</a>
        <a href="#contact">تواصل</a>
      </nav>
    </header><section class="hero">
  <div class="card">
    <h2>مرحبا— أنا محمد، مصمم جرافيك ومطور ويب</h2>
    <p class="lead">أصمم هويات بصرية، بوستات سوشال ميديا، وشعارات احترافية. أطور أيضاً مواقع سريعة ومستجيبة تناسب نشاطك التجاري.</p>

    <div style="margin-top:16px" id="services">
      <h3>الخدمات</h3>
      <div class="services">
        <div class="service">
          <div class="icon">🎨</div>
          <div>
            <strong>تصميم جرافيك</strong>
            <div class="muted">شعارات — هوية بصرية — منشورات تيك توك وإنستجرام</div>
          </div>
        </div>

        <div class="service">
          <div class="icon">💻</div>
          <div>
            <strong>تطوير مواقع الويب</strong>
            <div class="muted">مواقع تعريفية — متاجر إلكترونية — صفحات هبوط</div>
          </div>
        </div>

        <div class="service">
          <div class="icon">⚡</div>
          <div>
            <strong>تحسين الأداء والتسليم السريع</strong>
            <div class="muted">سيو أساسي، سرعة تحميل، وتصميم متجاوب</div>
          </div>
        </div>
      </div>

      <div style="margin-top:16px">
        <a class="btn" href="#contact">اطلب عرض سعر</a>
      </div>
    </div>
  </div>

  <aside class="card contact-card" id="contact" style="align-self:start">
    <h3>تواصل معي</h3>
    <p style="margin:0">الإسم: <strong>محمد جرافيك</strong></p>
    <p style="margin:0">البريد الإلكتروني: <a href="mailto:medmbeirik761@gmail.com">medmbeirik761@gmail.com</a></p>
    <p style="margin:0;color:var(--muted)">مستعد للعمل مع الشركات الصغيرة، المؤثرين، وأصحاب المشاريع.</p>
    <div style="margin-top:12px;display:flex;gap:8px">
      <a class="btn" href="mailto:medmbeirik761@gmail.com">راسلني الآن</a>
    </div>

    <div style="margin-top:12px;color:var(--muted);font-size:0.9rem">ملاحظة: أستطيع تهيئة هذا الموقع للنشر على استضافة مجانية أو شراء دومين لك.</div>
  </aside>
</section>

<section class="card" style="margin-top:20px">
  <h3 id="portfolio">معرض أعمالي (نماذج)</h3>
  <div class="portfolio-grid">
    <div class="port-item">شعار لعلامة تجارية</div>
    <div class="port-item">تصميم منشور إنستجرام</div>
    <div class="port-item">صفحة هبوط لمتجر</div>
    <div class="port-item">قالب فيديو تيك توك</div>
    <div class="port-item">كتيب تعريفي (PDF)</div>
    <div class="port-item">عرض هوية بصرية</div>
  </div>
</section>

<section class="card" style="margin-top:20px">
  <h3>نبذة عني</h3>
  <p class="lead">أعمل كمصمم جرافيك ومطوّر واجهات منذ سنوات، أحب التحديات البصرية وأقدّم حلولاً عملية تلائم أهداف العملاء. أسعي دائماً لموازنة الجمال والوظيفة في كل مشروع.</p>
</section>

<footer>
  © <span id="year"></span> محمد جرافيك — البريد: <a href="mailto:medmbeirik761@gmail.com">medmbeirik761@gmail.com</a>
</footer>

  </div>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html><img width="1994" height="2048" alt="1000036518" src="https://github.com/user-attachments/assets/533c34c3-f01e-4d5b-9274-666024dabcbb" />
