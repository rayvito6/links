# links
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naomi Itabashi | Official Links</title>
    <style>
        /* 基礎設定 */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Inter', -apple-system, sans-serif;
            background-color: #000;
            color: white;
            overflow-x: hidden;
        }

        /* 背景：建議放一張藝術處理後的圖片 [cite: 33] */
        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1614850523296-d8c1af93d400?q=80&w=2070') no-repeat center center/cover;
            z-index: -1;
            filter: blur(5px);
        }

        /* 內容容器 */
        .container {
            max-width: 450px;
            margin: 0 auto;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* 大頭照 */
        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid rgba(255,255,255,0.3);
            margin-bottom: 15px;
            object-fit: cover;
        }

        .name {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 5px;
            letter-spacing: 1px;
        }

        .bio {
            font-size: 0.9rem;
            color: rgba(255,255,255,0.8);
            margin-bottom: 30px;
        }

        /* 按鈕列表 */
        .links {
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        /* 玻璃質感按鈕 */
        .link-btn {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            color: white;
            padding: 18px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .link-btn:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }

        /* 特別突出的 CTA 按鈕 (OnlyFans/DLsite) [cite: 108, 109] */
        .cta-btn {
            background: linear-gradient(45deg, #ff00cc, #3333ff);
            border: none;
            margin-top: 10px;
        }

        .footer {
            margin-top: 50px;
            font-size: 0.7rem;
            color: rgba(255,255,255,0.4);
        }
    </style>
</head>
<body>

    <div class="background"></div>

    <div class="container">
        <img src="https://via.placeholder.com/150" alt="Profile" class="profile-pic">
        
        <div class="name">Naomi Itabashi</div>
        <div class="bio">Digital Artist & Slow Life Enthusiast</div>

        <div class="links">
            <a href="https://instagram.com/naomiii.live" class="link-btn">Instagram</a>
            <a href="https://threads.net" class="link-btn">Threads</a>
            <a href="https://tiktok.com" class="link-btn">TikTok</a>
            
            <a href="YOUR_ONLYFANS_LINK" class="link-btn cta-btn">Exclusive Content (OnlyFans)</a>
            <a href="YOUR_DLSITE_LINK" class="link-btn">Digital Store (DLsite)</a>
        </div>

        <div class="footer">
            © 2026 Naomi Itabashi. All Rights Reserved.
        </div>
    </div>

</body>
</html>
