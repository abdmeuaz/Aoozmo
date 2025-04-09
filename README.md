<!-- زر دفع PayPal -->
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_xclick">
  <input type="hidden" name="business" value="YOUR_PAYPAL_EMAIL">
  <input type="hidden" name="item_name" value="Product Name">
  <input type="hidden" name="amount" value="PRODUCT_PRICE">
  <input type="hidden" name="currency_code" value="USD">
  <input type="hidden" name="return" value="YOUR_RETURN_URL">
  <input type="hidden" name="cancel_return" value="YOUR_CANCEL_URL">
  <input type="submit" value="ادفع الآن عبر PayPal" class="pay-now-button">
</form><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Plugsy - متجر إكسسوارات الهواتف</title>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Tajawal', sans-serif;
      background: #f5f7fa;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 20px;
      opacity: 0.9;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }
    .product {
      background: white;
      border-radius: 16px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .product:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
      height: 220px;
      object-fit: cover;
    }
    .product h3 {
      font-size: 22px;
      margin: 14px 0 10px;
    }
    .product p {
      font-size: 15px;
      color: #555;
      margin-bottom: 12px;
    }
    .price {
      font-size: 18px;
      color: #28a745;
      margin: 12px 0;
      font-weight: bold;
    }
    .whatsapp-button {
      background-color: #25D366;
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 8px;
      display: inline-block;
      font-weight: bold;
    }
    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      left: 20px;
      background-color: #25D366;
      color: white;
      padding: 12px 16px;
      border-radius: 50px;
      text-decoration: none;
      font-size: 16px;
      font-weight: bold;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      z-index: 1000;
    }
    footer {
      text-align: center;
      padding: 30px;
      font-size: 14px;
      color: #999;
      background: #fff;
      border-top: 1px solid #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>Plugsy</h1>
    <p>كل ما تحتاجه لهاتفك من شواحن وإكسسوارات عصرية وموثوقة</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://ae01.alicdn.com/kf/Sbc0ab45b769740d3abf3cbcdbeec45c59.jpg" alt="سماعة بلوتوث لاسلكية">
      <h3>سماعة بلوتوث لاسلكية</h3>
      <p>صوت نقي – تصميم مريح – بطارية تدوم طويلاً</p>
      <div class="price">129 درهم</div>
      <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء سماعة بلوتوث من Plugsy">اطلب الآن</a>
    </div>

    <div class="product">
      <img src="https://ae01.alicdn.com/kf/S586b78b6e3534c48ae26f6d09e27470ff.jpg" alt="شاحن سريع بقوة 20W">
      <h3>شاحن سريع بقوة 20W</h3>
      <p>شحن فائق السرعة لجميع الهواتف – صغير الحجم وعالي الأداء</p>
      <div class="price">89 درهم</div>
      <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء شاحن سريع من Plugsy">اطلب الآن</a>
    </div>

    <div class="product">
      <img src="https://ae01.alicdn.com/kf/H1a8e26b5ab8d4fc4b66cb5e6e8b4a18db.jpg" alt="حامل مغناطيسي للسيارة">
      <h3>حامل مغناطيسي للسيارة</h3>
      <p>تثبيت قوي – تصميم أنيق – دوران كامل 360°</p>
      <div class="price">59 درهم</div>
      <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء حامل مغناطيسي من Plugsy">اطلب الآن</a>
    </div>

    <div class="product">
      <img src="https://ae01.alicdn.com/kf/H3b0f4c1286e346bdb1edb8cc4d779bc2H.jpg" alt="كابل شحن قوي TYPE-C">
      <h3>كابل شحن قوي TYPE-C</h3>
      <p>قوي ومرن – يدعم نقل البيانات والشحن السريع</p>
      <div class="price">39 درهم</div>
      <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء كابل TYPE-C من Plugsy">اطلب الآن</a>
    </div>
  </section>

  <a class="floating-whatsapp" href="https://wa.me/212668071561" target="_blank">تحدث معنا</a>

  <footer>
    &copy; 2025 Plugsy. جميع الحقوق محفوظة.
  </footer>
</body>
</html>
Plugsy - متجر إكسسوارات الهواتف body { font-family: 'Tajawal', sans-serif; background: #f5f7fa; margin: 0; padding: 0; color: #333; } header { background: linear-gradient(135deg, #0f2027, #203a43, #2c5364); color: white; text-align: center; padding: 60px 20px; } header h1 { font-size: 40px; margin-bottom: 10px; } header p { font-size: 20px; opacity: 0.9; } .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 30px; padding: 40px; max-width: 1200px; margin: auto; } .product { background: white; border-radius: 16px; box-shadow: 0 8px 20px rgba(0,0,0,0.1); padding: 20px; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease; } .product:hover { transform: translateY(-6px); box-shadow: 0 10px 25px rgba(0,0,0,0.15); } .product img { width: 100%; border-radius: 10px; height: 220px; object-fit: cover; } .product h3 { font-size: 22px; margin: 14px 0 10px; } .product p { font-size: 15px; color: #555; margin-bottom: 12px; } .price { font-size: 18px; color: #28a745; margin: 12px 0; font-weight: bold; } .whatsapp-button { background-color: #25D366; color: white; text-decoration: none; padding: 10px 20px; border-radius: 8px; display: inline-block; font-weight: bold; } .floating-whatsapp { position: fixed; bottom: 20px; left: 20px; background-color: #25D366; color: white; padding: 12px 16px; border-radius: 50px; text-decoration: none; font-size: 16px; font-weight: bold; box-shadow: 0 4px 12px rgba(0,0,0,0.3); z-index: 1000; } footer { text-align: center; padding: 30px; font-size: 14px; color: #999; background: #fff; border-top: 1px solid #eee; } Plugsy 

كل ما تحتاجه لهاتفك من شواحن وإكسسوارات عصرية وموثوقة

سماعة بلوتوث لاسلكية 

صوت نقي – تصميم مريح – بطارية تدوم طويلاً

129 درهم

اطلب الآن 

<div class="product"> <img src="https://ae01.alicdn.com/kf/S586b78b6e3534c48ae26f6d09e27470ff.jpg" alt="شاحن سريع بقوة 20W"> <h3>شاحن سريع بقوة 20W</h3> <p>شحن فائق السرعة لجميع الهواتف – صغير الحجم وعالي الأداء</p> <div class="price">89 درهم</div> <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء شاحن سريع من Plugsy">اطلب الآن</a> </div> <div class="product"> <img src="https://ae01.alicdn.com/kf/H1a8e26b5ab8d4fc4b66cb5e6e8b4a18db.jpg" alt="حامل مغناطيسي للسيارة"> <h3>حامل مغناطيسي للسيارة</h3> <p>تثبيت قوي – تصميم أنيق – دوران كامل 360°</p> <div class="price">59 درهم</div> <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء حامل مغناطيسي من Plugsy">اطلب الآن</a> </div> <div class="product"> <img src="https://ae01.alicdn.com/kf/H3b0f4c1286e346bdb1edb8cc4d779bc2H.jpg" alt="كابل شحن قوي TYPE-C"> <h3>كابل شحن قوي TYPE-C</h3> <p>قوي ومرن – يدعم نقل البيانات والشحن السريع</p> <div class="price">39 درهم</div> <a class="whatsapp-button" href="https://wa.me/212668071561?text=أرغب في شراء كابل TYPE-C من Plugsy">اطلب الآن</a> </div> 

تحدث معنا

© 2025 Plugsy. جميع الحقوق محفوظة. 
