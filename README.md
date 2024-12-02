<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới Thiệu Thành Viên Nhóm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        h1 {
            margin-top: 20px;
            color: #333;
        }
        .team {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            width: 90%;
            max-width: 800px;
            margin: 20px auto;
        }
        .member {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .member:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }
        .member h3 {
            margin: 10px 0 5px;
            font-size: 18px;
            color: #007BFF;
        }
        .member a {
            text-decoration: none;
            color: #555;
            font-size: 14px;
        }
        .member a:hover {
            color: #007BFF;
        }
    </style>
</head>
<body>
    <h1>Giới Thiệu Thành Viên Nhóm</h1>
    <div class="team">
        <!-- Thành viên 1 -->
        <div class="member">
            <img src="467741360_1094411988975241_318173132677453606_n.jpg" alt="Hình ảnh thành viên 1">
            <h3>Tăng Phúc Thiên Bảo</h3>
            <a href="https://www.facebook.com/thienbao2302/" target="_blank">Facebook</a>
        </div>
        <!-- Thành viên 2 -->
        <div class="member">
            <img src="265441558_408042444345023_5930426404168105605_n.jpg" alt="Hình ảnh thành viên 2">
            <h3>Phạm Phúc Thịnh</h3>
            <a href="https://www.facebook.com/profile.php?id=100054178110005" target="_blank">Facebook</a>
        </div>
        <!-- Thành viên 3 -->
        <div class="member">
            <img src="https://via.placeholder.com/100" alt="Hình ảnh thành viên 3">
            <h3>Phan Nguyễn Bảo Khánh</h3>
            <a href="https://www.facebook.com/socsnaau.hihi" target="_blank">Facebook</a>
        </div>
        <!-- Thành viên 4 -->
        <div class="member">
            <img src="461165182_3804127103238518_1074846194109332916_n.jpg" alt="Hình ảnh thành viên 4">
            <h3>Trà Chung Phú</h3>
            <a href="https://www.facebook.com/profile.php?id=100041368508523" target="_blank">Facebook</a>
        </div>
        <!-- Thành viên 5 -->
        <div class="member">
            <img src="462545431_583799810795475_6815358823630875842_n.jpg" alt="Hình ảnh thành viên 5">
            <h3>Phạm Ngọc Xuân Yến</h3>
            <a href="https://www.facebook.com/profile.php?id=100029813313707" target="_blank">Facebook</a>
        </div>
        <a href="https://trachungphu.github.io/">Quay lại Trang Thông Tin Bài làm</a>
    </div>
</body>
</html>
