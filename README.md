<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <style>
    h1 {
            display: none;
            }
    body {
      background-color: #FAD0C4; /* Màu hồng nhạt */
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Pano đầu trang */
    .header {
      background-color: #000000; /* Màu đen */
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* Chữ với hiệu ứng bay lơ lửng */
    .floating-text {
      font-size: 36px;
      font-weight: bold;
      background-image: linear-gradient(45deg, red, orange, yellow, green, cyan, blue, violet);
      background-size: 200% 200%;
      color: transparent;
      background-clip: text;
      display: inline-block;
      animation: rainbow 3s linear infinite, float 2s ease-in-out infinite;
    }

    /* Hiệu ứng chữ 7 màu chuyển động */
    @keyframes rainbow {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }

    /* Hiệu ứng bay lơ lửng */
    @keyframes float {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="header">
    <h1 class="floating-text">NGUYỄN TRƯỜNG GIANG XIN CHÀO</h1>
  </div>
</body>




<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora&display=swap" rel="stylesheet"> <!-- Thêm link font Lora -->
  <style>
    body {
      font-family: 'Lora', serif; /* Sử dụng font Lora */
      margin: 0;
      padding: 0;
      background-color: #f8d7d7; /* Màu nền nhẹ */
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 20px;
    }

    /* Dòng giới thiệu khái quát bản thân */
    .intro {
      font-size: 24px;
      color: #003366; /* Màu xanh dương đậm */
      font-weight: normal;
      text-align: center;
      margin-bottom: 40px;
    }

    .section {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      margin-bottom: 40px;
      flex-wrap: wrap;
    }

    /* Nội dung chính đầu tiên */
    .first-section {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      width: 100%;
    }

    .first-section .image {
      flex: 1;
      text-align: center;
    }

    .first-section .text-container {
      flex: 1;
      text-align: left;
    }

    .first-section .title {
      font-size: 28px;
      font-weight: bold;
      color: red;
      text-align: left;
    }

    .first-section .text {
      font-size: 20px;
      font-weight: normal;
      color: #003366; /* Màu xanh dương đậm */
    }

    /* Nội dung chính thứ 2 */
    .second-section {
      display: flex;
      justify-content: flex-end;
      align-items: center;
      width: 100%;
    }

    .second-section .image {
      flex: 1;
      text-align: center;
    }

    .second-section .text-container {
      flex: 1;
      text-align: right;
    }

    .second-section .title {
      font-size: 28px;
      font-weight: bold;
      color: red;
      text-align: right;
    }

    .second-section .text {
      font-size: 20px;
      font-weight: normal;
      color: #003366; /* Màu xanh dương đậm */
    }

    /* Căn chỉnh ảnh */
    .image img {
      width: 80%;
      height: auto;
      border-radius: 8px;
    }

  </style>
</head>
<body>

  <div class="container">
    <!-- Dòng giới thiệu khái quát bản thân -->
    <div class="intro">
      Mình là Trường Giang tên ở nhà là Minh. Nhà mình có 5 người ba, mẹ, chị, bà và mình. Mình thích xem bóng đá và có thần tượng là Kevin De Bruyne
    </div>

    <!-- Nội dung chính đầu tiên -->
    <div class="section first-section">
      <div class="image">
        <img src="462562213_1493977571293743_5719909131886436665_n.jpg" alt="Ảnh 1">
      </div>
      <div class="text-container">
        <div class="title">Thông tin cá nhân</div>
        <div class="text">Hiện tại mình học lớp 12 Lý, trường THPT Chuyên Bến Tre. Mình nặng 60kg và cao 1,70m</div>
      </div>
    </div>

    <!-- Nội dung chính thứ 2 -->
    <div class="section second-section">
      <div class="text-container">
        <div class="title">Nguyện vọng tương lai</div>
        <div class="text">Mình chọn thi khối Khoa học tự nhiên, nguyện vọng 1 là ngành Cơ khí trường Đại học Bách Khoa</div>
      </div>
      <div class="image">
        <img src="kevin-de-bruyne-06500327.jpeg" alt="Ảnh 2">
      </div>
    </div>

  </div>

</body>
</html>
