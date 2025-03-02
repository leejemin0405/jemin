안녕하세요 :)
ClassWay입니다!
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>학점은행제 상담</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background: #007bff;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 24px;
        }
        .container {
            max-width: 1100px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #343a40;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        학점은행제 상담 및 정보 제공
    </header>
    <div class="container">
        <div class="section">
            <h2>학점은행제란?</h2>
            <p>학점은행제는 교육부에서 주관하는 평생교육제도로, 대학교와 동일한 학위를 취득할 수 있는 제도입니다.</p>
        </div>
        <div class="section">
            <h2>상담 신청</h2>
            <form>
                <label for="name">이름:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="phone">연락처:</label>
                <input type="text" id="phone" name="phone" required><br><br>
                <label for="message">문의 내용:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                <button type="submit">상담 신청</button>
            </form>
        </div>
    </div>
    <footer>
        &copy; 2024 학점은행제 상담. All Rights Reserved.
    </footer>
</body>
</html>
