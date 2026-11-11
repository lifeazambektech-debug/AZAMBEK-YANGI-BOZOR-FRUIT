<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sokinat Safo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            text-align: center;
            padding: 20px;
            margin: 0;
        }
        .container {
            max-width: 500px;
            margin: 0 auto;
            background: #fff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 24px;
            margin-bottom: 10px;
        }
        .address {
            color: #555;
            font-size: 16px;
            margin-bottom: 20px;
        }
        .phone {
            font-size: 18px;
            font-weight: bold;
            color: #27ae60;
            margin-bottom: 25px;
        }
        .btn {
            display: block;
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            font-size: 16px;
            font-weight: bold;
            text-decoration: none;
            color: white;
            border-radius: 8px;
            transition: background 0.3s;
            box-sizing: border-box;
        }
        .telegram {
            background-color: #0088cc;
        }
        .telegram:hover {
            background-color: #0077b5;
        }
        .instagram {
            background: radial-gradient(circle at 30% 107%, #fdf497 0%, #df497 5%, #fafd6 15%, #d62976 50%, #962fbf 75%, #4f5bd5 100%);
        }
        .instagram:hover {
            opacity: 0.9;
        }
        .subscribe-section {
            margin-top: 25px;
            padding-top: 15px;
            border-top: 1px solid #eee;
        }
        .sub-btn {
            background-color: #e74c3c;
        }
        .sub-btn:hover {
            background-color: #c0392b;
        }
        .subscriber-count {
            font-size: 14px;
            color: #7f8c8d;
            margin-top: 8px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Sokinat Safo</h1>
        <div class="address">📍 Manzil: Adolat 2-berk koʻcha, 103A</div>
        <div class="phone">📞 Tel: <a href="tel:995395796" style="color: inherit; text-decoration: none;">99-539-57-96</a></div>

        <!-- Ijtimoiy tarmoqlar havolalari -->
        <a href="https://t.me/sokinat_safo" class="btn telegram" target="_blank">Telegram kanalimizga o'tish</a>
        <a href="https://www.instagram.com/azambek6961?obrf=N2I3ZWExb2xxNTFp" class="btn instagram" target="_blank">Instagram sahifamiz</a>

        <!-- Obuna bloki -->
        <div class="subscribe-section">
            <button class="btn sub-btn" onclick="alert('Obuna bo\'lganingiz uchun rahmat!')">Obuna bo'lish</button>
            <div class="subscriber-count">Obunachilar soni: <span id="count">1,245</span> ta</div>
        </div>
    </div>

</body>
</html>
