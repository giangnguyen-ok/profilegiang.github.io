<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pano với Hiệu Ứng Bay</title>
    <style>
        /* Thiết lập nền trang web */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fffacd; /* Vàng nhạt */
            overflow: hidden; /* Ẩn cuộn khi chữ bay */
        }

        /* Thiết lập kiểu dáng cho pano */
        .pano {
            background-color: #000000; /* Nền đen */
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            position: relative;
            overflow: hidden;
            color: transparent; /* Ban đầu ẩn chữ, chỉ hiển thị hiệu ứng */
            -webkit-background-clip: text;
            background-clip: text;
            background-size: 400%;
            animation: rainbow 3s infinite, fly 10s linear infinite;
        }

        /* Hiệu ứng cầu vồng cho chữ */
        @keyframes rainbow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Hiệu ứng chữ bay lượn */
        @keyframes fly {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        /* Tạo gradient cầu vồng */
        .pano {
            background-image: linear-gradient(
                to right, 
                red, orange, yellow, green, cyan, blue, violet
            );
        }
    </style>
</head>
<body>
    <div class="pano">
        NGUYỄN TRƯỜNG GIANG XIN CHÀO!
    </div>
</body>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Căn Lề Hình và Chữ</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9; /* Nền trang nhạt */
        }

        .container {
            display: flex; /* Sử dụng Flexbox để bố trí hình và chữ */
            justify-content: space-between; /* Đẩy hình và chữ ra hai bên */
            align-items: center; /* Căn giữa theo trục dọc */
            padding: 20px;
        }

        .image {
            margin-left: 0; /* Đảm bảo hình căn sát lề trái */
            max-width: 40%; /* Giới hạn kích thước hình */
        }

        .text {
            margin-right: 0; /* Đảm bảo chữ căn sát lề phải */
            text-align: right; /* Căn lề phải cho nội dung chữ */
            max-width: 50%; /* Giới hạn chiều rộng phần chữ */
            color: #007bff; /* Màu chữ xanh dương */
            line-height: 1.6; /* Tăng khoảng cách giữa các dòng */
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://via.placeholder.com/200" alt="Hình ảnh mẫu" class="image">
        <div class="text">
            <h1>Tiêu đề Màu Xanh</h1>
            <p>Đây là đoạn văn bản mẫu được căn lề phải và có màu xanh dương. Nội dung này hiển thị ở bên phải trang web.</p>
        </div>
    </div>
</body>

<ul>
<li> Mình là Trường Giang tên ở nhà là Minh. Nhà mình có 5 người ba, mẹ, chị, bà và mình. Mình thích xem bóng đá và có thần tượng là Kevin De Bruyne</li>
     <image src="462562213_1493977571293743_5719909131886436665_n.jpg">
<li> Thông tin cá nhân
    <ol>
    <li>Họ và tên: Nguyễn Trường Giang</li>
    <li>Trường trung học phổ thông Chuyên Bến Tre</li>
    <li>Lớp: 12 Lý</li>
    <li>Giới tính: Nam</li> 
    <li>Cân nặng: 60kg</li>
    <li>Chiều cao: 1,6m</li>
    </ol>
</li>
<li> Nguyện vọng tương lai 
    <ol>
    <li>Khối thi là Khoa học tự nhiên </li>
    <li>Nguyện vọng 1 là Đại học Bách Khoa</li>
    </ol>
</li>
