<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE哆啦A夢展 台北 2023-2024</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em;
        }

        section {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1,
        h2,
        h3 {
            color: #4CAF50;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        p {
            line-height: 1.6;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .ticket-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        .ticket-table th,
        .ticket-table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }

        .ticket-table th {
            background-color: #4CAF50;
            color: white;
        }

        .ticket-btn {
            display: block;
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            margin-top: 10px;
            text-decoration: none;
            text-align: center;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <header>
        <h1>THE哆啦A夢展 台北 2023-2024</h1>
    </header>

    <section>
        <h2>歡迎來到哆啦A夢的奇幻世界！</h2>
        <img src="https://www.funtime.com.tw/localtour/topic/img/authorization/Doraemon1.jpg" alt="哆啦A夢展示圖">
        <p>「THE哆啦A夢展 台北 2023」將帶您進入一場夢幻與回憶的冒險。這是一個專屬於大家心中的童年回憶，讓您重溫那些溫馨、幽默的時光。</p>
        <p>展覽將展示豐富的哆啦A夢相關內容，包括獨家插畫展覽、互動遊戲區、限定商品販售等精彩內容。無論您是小朋友還是大人，都能在這裡找到屬於自己的幸福時光。</p>
        <h3>展覽詳情</h3>
        <ul>
            <li><strong>日期：</strong>2023年5月1日至5月31日</li>
            <li><strong>地點：</strong>台北展覽中心</li>
            <li><strong>票價：</strong>成人NT$300，學生NT$200，兒童(6歲以下)免費</li>
        </ul>
        <p>別錯過這個難得一見的機會，和哆啦A夢一起度過美好的時光！</p>
        <h3>選擇票價</h3>
        <table class="ticket-table">
            <tr>
                <th>票種</th>
                <th>價格</th>
            </tr>
            <tr>
                <td>大人</td>
                <td>NT$500</td>
            </tr>
            <tr>
                <td>小孩</td>
                <td>NT$400</td>
            </tr>
            <tr>
                <td>愛心票</td>
                <td>NT$350</td>
            </tr>
        </table>
        <div>
            <label for="adult">大人：</label>
            <input type="number" id="adult" name="adult" value="1" min="1">
        </div>
        <div>
            <label for="child">小孩：</label>
            <input type="number" id="child" name="child" value="1" min="1">
        </div>
        <div>
            <label for="love">愛心票：</label>
            <input type="number" id="love" name="love" value="1" min="1">
        </div>
        <a href="#" class="ticket-btn">立即購票</a>
    </section>

    <footer>
        <p>&copy; 2023 THE哆啦A夢展 台北. All rights reserved.</p>
    </footer>

</body>

</html>
