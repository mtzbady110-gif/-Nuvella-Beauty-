<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nuvella Beauty — نوفيلّا بيوتي</title>
  <meta name="description" content="نوفيلّا بيوتي — متجر مستحضرات التجميل للرجال والنساء. منتجات أصلية للعناية بالبشرة والشعر والمظهر. تسوق بموثوقية وتوصيل سريع. اتصل: +967 782245246.">
  <style>
    :root{--bg:#f7f3ef;--accent:#c49a6c;--muted:#8b8b8b;--dark:#2b2b2b}
    body{font-family:Tahoma,Arial,Helvetica,sans-serif;background:var(--bg);color:var(--dark);margin:0;padding:0}
    header{background:white;box-shadow:0 2px 8px rgba(0,0,0,0.05);padding:18px 20px;position:sticky;top:0;z-index:10}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .logo{display:flex;align-items:center;gap:12px}
    .logo h1{margin:0;font-size:20px;color:var(--dark)}
    .tag{color:var(--muted);font-size:13px}
    .hero{display:flex;gap:30px;align-items:center;padding:40px 20px}
    .hero .left{flex:1}
    .hero h2{font-size:32px;margin:0 0 10px}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .cta{display:flex;gap:12px}
    .btn{background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:600}
    .btn.ghost{background:transparent;color:var(--accent);border:2px solid var(--accent)}
    .hero .right{flex:1;text-align:center}
    .hero img{max-width:260px;border-radius:12px;box-shadow:0 6px 20px rgba(0,0,0,0.08)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    .card{background:white;padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)}
    .card img{width:100%;border-radius:8px}
    .muted{color:var(--muted)}
    footer{padding:24px 20px;text-align:center;color:var(--muted);font-size:14px}
    .small{font-size:13px}
    .badge{display:inline-block;background:#fff;padding:6px 10px;border-radius:999px;border:1px solid rgba(0,0,0,0.04);font-weight:600}
    @media(max-width:720px){.hero{flex-direction:column;text-align:center}.hero .right{order:-1}}
    .whatsapp{display:inline-flex;align-items:center;gap:8px}
    input,textarea,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e3e3e3;font-size:14px}
    label{display:block;margin-bottom:6px;font-weight:600}
    .form-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
    @media(max-width:600px){.form-row{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="container logo">
      <div>
        <h1>Nuvella Beauty</h1>
        <div class="tag">نوفيلّا بيوتي — جمال حقيقي، بثقة</div>
      </div>
      <div style="margin-inline-start:auto;text-align:left">
        <span class="badge">اتصل: +967 782245246</span>
      </div>
    </div>
  </header>

  <main class="container">
    <!-- Hero -->
    <section class="hero">
      <div class="left">
        <h2>متجر التجميل الموثوق للرجال والنساء</h2>
        <p>منتجات أصلية ومتنوعة للعناية بالبشرة، الشعر، والجمال — اختيار بعناية من علامات موثوقة. تجربة تسوّق سهلة، تصميم عصري، وتوصيل سريع.</p>
        <div class="cta">
          <a class="btn" href="#shop">تسوق الآن</a>
          <a class="btn ghost whatsapp" id="waHeroBtn" href="#">اطلب عبر الواتساب</a>
        </div>
        <p class="muted small" style="margin-top:12px">Nuvella QuickOrder — اطلب بسرعة بخطوتين: اختر المنتج ثم أرسل طلبك عبر واتساب.</p>
      </div>
      <div class="right">
        <img src="https://via.placeholder.com/360x360.png?text=Nuvella+Beauty" alt="Nuvella Beauty">
      </div>
    </section>

    <!-- About -->
    <section id="about" style="margin-top:20px">
      <div class="card">
        <h3>من نحن</h3>
        <p class="muted">نوفيلّا بيوتي متجر إلكتروني يقدّم مجموعة متنوعة من مستحضرات التجميل والعناية الشخصية للرجال والنساء. نختار منتجاتنا بعناية من علامات موثوقة لضمان الجودة والأمان، ونوفّر تجربة تسوّق سهلة وسريعة مع خدمة عملاء احترافية. مهمتنا أن نقدّم حلول تجميل فعالة تناسب كل أنواع البشرة، بأسعار عادلة وشفافية تامة.</p>
      </div>
    </section>

    <!-- Categories -->
    <section id="shop" style="margin-top:20px">
      <h3>أقسام المنتجات</h3>
      <div class="grid" style="margin-top:12px">
        <div class="card"><h4>العناية بالبشرة</h4><p class="muted">منظفات، مرطبات، سيروم، واقي شمس.</p></div>
        <div class="card"><h4>العناية بالشعر</h4><p class="muted">شامبو، بلسم، علاجات وتقوية.</p></div>
        <div class="card"><h4>مكياج</h4><p class="muted">أساس، أحمر شفاه، ماسكارا، وأكثر.</p></div>
        <div class="card"><h4>عناية الرجال</h4><p class="muted">منتجات الحلاقة، العناية باللحية، غسول الجسم.</p></div>
      </div>
    </section>

    <!-- Products sample -->
    <section style="margin-top:20px">
      <h3>منتجات مميزة</h3>
      <div class="grid" style="margin-top:12px">
        <!-- Sample product card (copy template to add more) -->
        <div class="card">
          <img src="https://via.placeholder.com/400x300.png?text=Product+1" alt="منتج 1">
          <h4>سيروم تفتيح وترطيب</h4>
          <p class="muted">تركيبة خفيفة مناسبة لجميع أنواع البشرة. نتائج ملحوظة خلال أسبوعين.</p>
          <p style="font-weight:700">35 ر.ي</p>
          <div style="display:flex;gap:8px;margin-top:10px">
            <a class="btn" href="#" onclick="openQuickOrder('سيروم تفتيح وترطيب',35);return false;">طلب سريع</a>
            <a class="btn ghost" href="#" onclick="addToCart('سيروم تفتيح وترطيب',35);return false;">أضف للسلة</a>
          </div>
        </div>

        <div class="card">
          <img src="https://via.placeholder.com/400x300.png?text=Product+2" alt="منتج 2">
          <h4>شامبو تقوية للشعر</h4>
          <p class="muted">مناسب للشعر المتساقط، غني بالمكونات الطبيعية.</p>
          <p style="font-weight:700">28 ر.ي</p>
          <div style="display:flex;gap:8px;margin-top:10px">
            <a class="btn" href="#" onclick="openQuickOrder('شامبو تقوية للشعر',28);return false;">طلب سريع</a>
            <a class="btn ghost" href="#" onclick="addToCart('شامبو تقوية للشعر',28);return false;">أضف للسلة</a>
          </div>
        </div>

        <!-- Add more product cards as needed -->
      </div>
    </section>

    <!-- QuickOrder form (hidden modal-style simple) -->
    <section style="margin-top:20px">
      <div class="card">
        <h3>Nuvella QuickOrder — طلب سريع</h3>
        <p class="muted">املأ البيانات بسرعة وسنرسل طلبك على واتساب. يمكنك أيضًا الضغط على زر "طلب سريع" أسفل أي منتج لإرسال اسم المنتج مباشرة.</p>
        <form id="quickOrderForm" onsubmit="sendWhatsApp(event)">
          <div class="form-row">
            <div>
              <label>الاسم</label>
              <input type="text" id="q_name" required>
            </div>
            <div>
              <label>الهاتف</label>
              <input type="text" id="q_phone" placeholder="مثال: 712345678" required>
            </div>
          </div>
          <div style="margin-top:10px">
            <label>المنتج (اكتب اسم المنتج أو الصق الاسم من صفحة المنتج)</label>
            <input type="text" id="q_product" required>
          </div>
          <div style="margin-top:10px">
            <label>العنوان</label>
            <input type="text" id="q_address" placeholder="المدينة، المنطقة، العنوان">
          </div>
          <div style="margin-top:10px">
            <label>ملاحظات</label>
            <textarea id="q_notes" rows="3"></textarea>
          </div>
          <div style="margin-top:12px;display:flex;gap:10px">
            <button class="btn" type="submit">إرسال الطلب عبر واتساب</button>
            <button class="btn ghost" type="button" onclick="clearQuickOrder()">مسح الحقول</button>
          </div>
        </form>
      </div>
    </section>

    <!-- Shipping & Returns -->
    <section style="margin-top:20px">
      <div class="card">
        <h3>الشحن والإرجاع</h3>
        <p class="muted">الشحن عادة خلال 3–7 أيام عمل داخل الجمهورية. الدفع نقدًا عند الاستلام أو عبر بوابات إلكترونية (اختياري). الإرجاع مقبول للمنتجات غير المفتوحة خلال 14 يومًا وفق الشروط.</p>
      </div>
    </section>

    <!-- Contact -->
    <section style="margin-top:20px">
      <div class="card">
        <h3>تواصل معنا</h3>
        <p class="muted">للطلبات والاستفسارات تواصل معنا عبر الواتساب أو الهاتف:</p>
        <p style="font-weight:700">+967 782245246</p>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <div>© <strong>Nuvella Beauty</strong> — نوفيلّا بيوتي</div>
      <div style="margin-top:6px;color:var(--muted)">منتجات أصلية — مصداقية وشفافية — توصيل سريع</div>
    </div>
  </footer>

  <script>
    const WA_NUMBER = '967782245246'; // without + sign for wa.me link

    // Build hero WhatsApp button
    const waHeroBtn = document.getElementById('waHeroBtn');
    waHeroBtn.href = `https://wa.me/${WA_NUMBER}?text=${encodeURIComponent('السلام عليكم، أود الاستفسار عن منتجات Nuvella Beauty')}`;

    // Quick Order functions
    function openQuickOrder(productName, price){
      document.getElementById('q_product').value = productName;
      window.scrollTo({top:document.getElementById('quickOrderForm').offsetTop - 40,behavior:'smooth'});
    }

    function sendWhatsApp(e){
      e.preventDefault();
      const name = document.getElementById('q_name').value.trim();
      const phone = document.getElementById('q_phone').value.trim();
      const product = document.getElementById('q_product').value.trim();
      const address = document.getElementById('q_address').value.trim();
      const notes = document.getElementById('q_notes').value.trim();

      let message = `السلام عليكم،\nأود طلب من Nuvella Beauty:\n- المنتج: ${product}\n- الاسم: ${name}\n- الهاتف: ${phone}`;
      if(address) message += `\n- العنوان: ${address}`;
      if(notes) message += `\n- ملاحظات: ${notes}`;

      const waLink = `https://wa.me/${WA_NUMBER}?text=${encodeURIComponent(message)}`;
      window.open(waLink, '_blank');
    }

    function clearQuickOrder(){
      document.getElementById('quickOrderForm').reset();
    }

    // Simple addToCart placeholder
    function addToCart(name,price){
      alert(name + ' تمت إضافته إلى السلة (تجريبي)');
    }
  </script>
</body>
</html>
# -Nuvella-Beauty-
