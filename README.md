<!DOCTYPE html>
<html lang="zh-Hant-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的第一個網頁</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        h1 {
            color: #0056b3;
        }
        .btn {
            display: inline-block;
            background: #0056b3;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
        }
        .btn:hover {
            background: #004085;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- 網頁主標題 -->
        <h1>歡迎來到我的網站！</h1>
        
        <!-- 副標題與段落 -->
        <h2>關於這個網頁</h2>
        <p>這是一個使用 <strong>HTML5</strong> 和基礎 <strong>CSS</strong> 建立的標準網頁範本。你可以在這裡自由修改內容，加入你想展示的文字。</p>
        
        <!-- 圖片標籤 (請將 src 替換成你的圖片網址) -->
        <h2>精選圖片</h2>
        <img src="https://picsum.photos" alt="範例圖片" style="max-width:100%; height:auto; border-radius:5px;">

        <!-- 條列式清單 -->
        <h2>我學習網頁的目標</h2>
        <ul>
            <li>掌握 HTML 網頁結構標籤</li>
            <li>學會用 CSS 美化排版與顏色</li>
            <li>加入 JavaScript 製作互動效果</li>
        </ul>

        <!-- 超連結按鈕 -->
        <h2>聯絡與更多資訊</h2>
        <p>點擊下方按鈕可以前往外部網站查看更多教學：</p>
        <a href="https://www.google.com" target="_blank" class="btn">前往 Google 搜尋</a>
    </div>

</body>
</html>
