<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هاشم TV - البوابة الرقمية للمحتوى</title>
    <style>
        :root {
            --primary-color: #1a73e8;
            --secondary-color: #0f9d58;
            --dark-bg: #121212;
            --light-bg: #f8f9fa;
            --text-color: #333;
            --card-bg: #fff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--light-bg);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1a73e8, #0f9d58);
            color: white;
            text-align: center;
            padding: 2.5rem 1rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 0.5rem 0 0;
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        section {
            background: var(--card-bg);
            margin-bottom: 2rem;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }

        section h2 {
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 0.5rem;
            margin-top: 0;
            color: var(--primary-color);
        }

        /* شبكة عرض الصور */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .gallery-item {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
        }

        .gallery-item:hover {
            transform: translateY(-5px);
        }

        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            display: block;
        }

        .gallery-item .caption {
            padding: 1rem;
            text-align: center;
            font-weight: bold;
            color: #555;
        }

        /* زر الواتساب العائم أو البارز */
        .whatsapp-banner {
            text-align: center;
            background: #25d366;
            color: white;
            padding: 1.5rem;
            border-radius: 12px;
            margin-top: 2rem;
        }

        .whatsapp-btn {
            display: inline-block;
            background: white;
            color: #25d366;
            padding: 0.75rem 2rem;
            border-radius: 30px;
            font-weight: bold;
            text-decoration: none;
            margin-top: 1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            transition: background 0.2s;
        }

        .whatsapp-btn:hover {
            background: #f0f0f0;
        }

        footer {
            text-align: center;
            padding: 1.5rem;
            background: #333;
            color: white;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>هاشم TV</h1>
        <p>منصتك الرقمية للمحتوى المرئي، البروموهات، والإعلانات في زالنجي وكل السودان</p>
    </header>

    <div class="container">
        
        <!-- قسم معرض الصور -->
        <section>
            <h2>معرض الصور والبروموهات</h2>
            <p>استعرض أحدث الصور، اللقطات، والتصميمات الخاصة بمنصة هاشم TV:</p>
            
            <div class="gallery-grid">
                <!-- الصورة الأولى -->
                <div class="gallery-item">
                    <a href="https://wa.me/249998040864" target="_blank">
                        <img src="images/image1.jpg" alt="برومو هاشم TV">
                    </a>
                    <div class="caption">إعلانات وخدمات هاشم TV</div>
                </div>

                <!-- الصورة الثانية -->
                <div class="gallery-item">
                    <a href="https://wa.me/249998040864" target="_blank">
                        <img src="images/image2.jpg" alt="مدينة زالنجي ووادي أريبو">
                    </a>
                    <div class="caption">مناظر من زالنجي وجبل مرة</div>
                </div>

                <!-- الصورة الثالثة -->
                <div class="gallery-item">
                    <a href="https://wa.me/249998040864" target="_blank">
                        <img src="images/image3.jpg" alt="جلسات الفن والموسيقى">
                    </a>
                    <div class="caption">إنتاج مرئي وصوتي</div>
                </div>
            </div>
        </section>

        <!-- قسم الإعلانات والتواصل -->
        <div class="whatsapp-banner">
            <h2>هل تريد الإعلان معنا أو طلب خدمات هاشم TV؟</h2>
            <p>تواصل معنا مباشرة عبر واتساب لطلب الخدمات الإعلانية وحجز المساحات الترويجية.</p>
            <a href="https://wa.me/249998040864" class="whatsapp-btn" target="_blank">تواصل عبر واتساب (+249998040864)</a>
        </div>

    </div>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2026 - هاشم TV</p>
    </footer>

</body>
</html>
