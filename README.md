<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5天4夜花蓮戶外教育體驗營</title>
    <style>
        :root {
            --primary-color: #2b6777; /* 海洋與森林的主題色 */
            --secondary-color: #52ab98;
            --accent-color: #c8d8e4;
            --text-color: #333;
            --bg-color: #f4f7f6;
        }
        body {
            font-family: 'Helvetica Neue', Arial, '微軟正黑體', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            background-color: var(--bg-color);
            line-height: 1.6;
        }
        header {
            background: linear-gradient(rgba(43, 103, 119, 0.85), rgba(82, 171, 152, 0.85)), url('https://images.unsplash.com/photo-1552465011-b4e21bf6e79a?auto=format&fit=crop&w=1920&q=80') center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        header h1 {
            font-size: 2.8em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.4);
        }
        header p {
            font-size: 1.2em;
            font-weight: 300;
            letter-spacing: 2px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 50px 20px;
        }
        /* 時間軸設計 */
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
        }
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: var(--secondary-color);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
            border-radius: 3px;
        }
        .container-box {
            padding: 10px 40px;
            position: relative;
            background-color: inherit;
            width: 50%;
            box-sizing: border-box;
        }
        .container-box::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            right: -16px;
            background-color: white;
            border: 4px solid var(--primary-color);
            top: 15px;
            border-radius: 50%;
            z-index: 1;
        }
        .left { left: 0; }
        .right { left: 50%; }
        .left::before {
            content: " ";
            height: 0;
            position: absolute;
            top: 22px;
            width: 0;
            z-index: 1;
            right: 30px;
            border: medium solid white;
            border-width: 10px 0 10px 10px;
            border-color: transparent transparent transparent white;
        }
        .right::before {
            content: " ";
            height: 0;
            position: absolute;
            top: 22px;
            width: 0;
            z-index: 1;
            left: 30px;
            border: medium solid white;
            border-width: 10px 10px 10px 0;
            border-color: transparent white transparent transparent;
        }
        .right::after { left: -16px; }
        .content {
            padding: 25px 30px;
            background-color: white;
            position: relative;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }
        .content:hover {
            transform: translateY(-5px);
        }
        .content h2 {
            color: var(--primary-color);
            margin-top: 0;
            font-size: 1.4em;
        }
        .content .day {
            display: inline-block;
            background: var(--primary-color);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 15px;
        }
        .content ul {
            padding-left: 20px;
            color: #555;
        }
        .content li {
            margin-bottom: 8px;
        }
        footer {
            text-align: center;
            padding: 30px;
            background-color: var(--primary-color);
            color: white;
            margin-top: 20px;
        }
        /* 手機版響應式設計 */
        @media screen and (max-width: 600px) {
            header h1 { font-size: 2em; }
            .timeline::after { left: 31px; }
            .container-box { width: 100%; padding-left: 70px; padding-right: 25px; }
            .container-box::before { left: 60px; border: medium solid white; border-width: 10px 10px 10px 0; border-color: transparent white transparent transparent; }
            .left::after, .right::after { left: 15px; }
            .right { left: 0%; }
        }
    </style>
</head>
<body>

<header>
    <h1>5天4夜花蓮戶外教育體驗營</h1>
    <p>從山海到田野，探索土地的變遷與生態韌性</p>
</header>

<div class="container">
    <div class="timeline">
        
        <!-- Day 1 -->
        <div class="container-box left">
            <div class="content">
                <span class="day">Day 1</span>
                <h2>產業與生態：立川漁場</h2>
                <p>利用天然湧泉養殖黃金蜆、金目鱸魚等水產，是花蓮著名的養殖漁業示範區。</p>
                <ul>
                    <li><strong>湧泉生態與水資源：</strong>認識花蓮特有的天然湧泉環境與乾淨水質。</li>
                    <li><strong>摸蜆體驗：</strong>下水實地體驗早期農村捕捉蜆的過程。</li>
                </ul>
            </div>
        </div>

        <!-- Day 2 -->
        <div class="container-box right">
            <div class="content">
                <span class="day">Day 2</span>
                <h2>海洋保育：多羅滿賞鯨 + 海洋公園</h2>
                <p>從友善賞鯨到海洋動物救援，實地進行太平洋的生命教育。</p>
                <ul>
                    <li><strong>太平洋生態觀察：</strong>出海尋找飛旋海豚與花紋海豚等。</li>
                    <li><strong>海洋動物救援：</strong>參訪鯨豚保育基地，探討海洋廢棄物衝擊。</li>
                </ul>
            </div>
        </div>

        <!-- Day 3 -->
        <div class="container-box left">
            <div class="content">
                <span class="day">Day 3</span>
                <h2>低碳移動：七星潭至鯉魚潭自行車道</h2>
                <p>串聯礫石海灣與內陸湖泊，以單車實踐低碳綠色旅遊。</p>
                <ul>
                    <li><strong>綠色交通鍛鍊：</strong>長距離騎乘培養孩子毅力與團隊精神。</li>
                    <li><strong>水域地貌比較：</strong>實地觀察並比較海岸灘塗與堰塞湖的差異。</li>
                </ul>
            </div>
        </div>

        <!-- Day 4 -->
        <div class="container-box right">
            <div class="content">
                <span class="day">Day 4</span>
                <h2>地質與變遷：清水斷崖 + 得卡倫步道</h2>
                <p>走入太魯閣國家公園邊界，觀察大自然的力量與復原過程。</p>
                <ul>
                    <li><strong>板塊運動：</strong>觀察清水斷崖斷層海岸的險峻。</li>
                    <li><strong>環境韌性：</strong>走訪得卡倫步道，觀察地震與風災過後的地貌改變。</li>
                </ul>
            </div>
        </div>

        <!-- Day 5 -->
        <div class="container-box left">
            <div class="content">
                <span class="day">Day 5</span>
                <h2>海運與指引：花蓮港 + 奇萊鼻燈塔</h2>
                <p>了解花蓮商港歷史，並在壯闊的四八高地岬角畫下營隊句點。</p>
                <ul>
                    <li><strong>商港運作：</strong>認識東部國際商港的現代航運功能。</li>
                    <li><strong>海岸防護：</strong>觀察五角形的奇萊鼻燈塔在航海安全上的重要性。</li>
                </ul>
            </div>
        </div>

    </div>
</div>

<footer>
    <p>2026 適野冬令生活體驗 | 與自然共存，向土地學習</p>
    <p style="font-size: 0.8em; margin-top: 10px;">報名與聯絡資訊請洽主辦單位</p>
</footer>

</body>
</html>
