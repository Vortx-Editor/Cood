<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>روابطي | My Links</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            /* خلفية بتدرج لوني متحرك بهدوء */
            background: linear-gradient(-45deg, #0f2027, #203a43, #2c5364, #1f1c2c, #928dab);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            color: #fff;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            /* تأثير الزجاج الفخم */
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 40px 20px;
            width: 100%;
            max-width: 450px;
            text-align: center;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        /* حاوية الشعار */
        .logo-container {
            width: 120px;
            height: 120px;
            margin: 0 auto 20px;
            border-radius: 50%;
            padding: 4px;
            background: linear-gradient(45deg, #ff00cc, #333399);
            animation: spinBorder 4s linear infinite;
        }

        @keyframes spinBorder {
            100% { filter: hue-rotate(360deg); }
        }

        .logo {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #1a1a2e;
        }

        h1 {
            font-size: 26px;
            font-weight: 900;
            margin-bottom: 5px;
            letter-spacing: 1px;
        }

        p.bio {
            font-size: 15px;
            color: #d1d1d1;
            margin-bottom: 30px;
            line-height: 1.5;
        }

        .links-wrapper {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: #fff;
            background: rgba(255, 255, 255, 0.1);
            padding: 15px 20px;
            border-radius: 12px;
            font-size: 18px;
            font-weight: 700;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.05);
            position: relative;
            overflow: hidden;
        }

        /* تأثير مرور الماوس على الأزرار العادية */
        .link-btn:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        /* زر المتجر الإلكتروني - مميز لجذب الانتباه */
        .store-btn {
            background: linear-gradient(90deg, #ff8a00, #e52e71);
            border: none;
            animation: pulseGlow 2s infinite;
        }

        .store-btn:hover {
            background: linear-gradient(90deg, #e52e71, #ff8a00);
            transform: scale(1.02);
        }

        @keyframes pulseGlow {
            0% { box-shadow: 0 0 0 0 rgba(229, 46, 113, 0.7); }
            70% { box-shadow: 0 0 0 15px rgba(229, 46, 113, 0); }
            100% { box-shadow: 0 0 0 0 rgba(229, 46, 113, 0); }
        }

    </style>
</head>
<body>

    <div class="container">
        <div class="logo-container">
            <img src="https://via.placeholder.com/120" alt="الشعار الشخصي" class="logo">
        </div>

        <h1>اسمك أو اسم الحساب</h1>
        <p class="bio">صانع محتوى | تصميم ومونتاج | أهلاً بكم في صفحتي الرسمية</p>

        <div class="links-wrapper">
            <a href="رابط_متجرك_هنا" class="link-btn store-btn">
                🛒 المتجر الإلكتروني
            </a>

            <a href="رابط_تيك_توك" class="link-btn">
                📱 تيك توك
            </a>
            
            <a href="رابط_يوتيوب" class="link-btn">
                ▶️ يوتيوب
            </a>
            
            <a href="رابط_انستقرام" class="link-btn">
                📸 إنستقرام
            </a>
            
            <a href="رابط_تويتر" class="link-btn">
                🐦 إكس (تويتر)
            </a>
        </div>
    </div>

</body>
</html>
