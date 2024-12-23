<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ẩm Thực Đặc Sắc</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Roboto:wght@400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #fff5e4, #fdf6e3); /* Gradient nhẹ nhàng */
            color: #333;
        }

        header {
            position: relative;
            height: 200px; /* Tăng chiều cao để làm nổi bật hơn */
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), 
                        url('https://cdn-i.vtcnews.vn/resize/th/upload/2023/04/21/7-quan-pho-ngon-nuc-tieng-duoc-long-nguoi-sanh-an-trong-khu-pho-co-ha-noi-1-1632824891-23553249.jpg') 
                        no-repeat center center/cover;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        header h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 4rem; /* Tăng kích thước chữ */
            color: #fff;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.7); /* Hiệu ứng bóng chữ */
            z-index: 2;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px; /* Tạo khoảng cách giữa các khối */
        }

        .region {
            text-align: center;
            width: 22%;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Hiệu ứng nổi cho khối */
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .region:hover {
            transform: translateY(-10px); /* Hiệu ứng nổi khi hover */
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        h2 {
            color: #ff6347; /* Màu đỏ cam nổi bật */
            font-weight: 700;
            margin-top: 20px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 20px 0;
            transition: transform 0.3s;
        }

        li:hover {
            transform: scale(1.05); /* Phóng to ảnh khi hover */
        }

        li img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        li p {
            margin: 10px 0 0;
            color: #333;
            font-weight: bold;
            transition: color 0.3s;
        }

        li:hover p {
            color: #ff6347; /* Đổi màu chữ khi hover */
        }
    </style>
</head>
<body>
    <header>
        <h1>Ẩm Thực Đặc Sắc</h1>
    </header>

    <div class="container">
        <div class="region">
            <h2>Miền Bắc</h2>
            <ul>
                <li>
                    <a href="pho-hanoi.html">
                        <img src="https://cdn-i.vtcnews.vn/resize/th/upload/2023/04/21/7-quan-pho-ngon-nuc-tieng-duoc-long-nguoi-sanh-an-trong-khu-pho-co-ha-noi-1-1632824891-23553249.jpg" alt="Phở Hà Nội">
                        <p>Phở Hà Nội</p>
                    </a>
                </li>
                <li>
                    <a href="banh-da-cua-haiphong.html">
                        <img src="https://bepxua.vn/wp-content/uploads/2021/05/banh-da-cua-hai-phong.jpg" alt="Bánh đa cua Hải Phòng">
                        <p>Bánh đa cua Hải Phòng</p>
                    </a>
                </li>
            </ul>
        </div>

        <div class="region">
            <h2>Miền Trung</h2>
            <ul>
                <li>
                    <a href="bun-bo-hue.html">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTS_zrsVZcHCfK-3_n78Z7BGR2EPVgklxQrIw&s" alt="Bún bò Huế">
                        <p>Bún bò Huế</p>
                    </a>
                </li>
                <li>
                    <a href="cao-lau-hoi-an.html">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/BANH_DA_CUA_1.jpg/640px-BANH_DA_CUA_1.jpg" alt="Cao lầu Hội An">
                        <p>Cao lầu Hội An</p>
                    </a>
                </li>
            </ul>
        </div>

        <div class="region">
            <h2>Miền Nam</h2>
            <ul>
                <li>
                    <a href="pha-lau.html">
                        <img src="https://cdn-media.sforum.vn/storage/app/media/wp-content/uploads/2023/12/cach-lam-pha-lau-thumbnail.jpg" alt="Phá lấu">
                        <p>Phá lấu</p>
                    </a>
                </li>
                <li>
                    <a href="com-tam.html">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYn4DxXBYgCK2gw3udITmaTchjtRcVil1_og&s" alt="Cơm tấm">
                        <p>Cơm tấm</p>
                    </a>
                </li>
            </ul>
        </div>

        <div class="region">
            <h2>Miền Tây</h2>
            <ul>
                <li>
                    <a href="banh-pia-soc-trang.html">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSy7Mcl59a78Va2H16X8JsrQ1tn2H4-KS6QLg&s" alt="Bánh pía Sóc Trăng">
                        <p>Bánh pía Sóc Trăng</p>
                    </a>
                </li>
                <li>
                    <a href="hu-tieu-my-tho.html">
                        <img src="https://vcdn1-dulich.vnecdn.net/2016/05/23/1-6532-1464000261.jpg?w=460&h=0&q=100&dpr=2&fit=crop&s=gGqpETsMrmYH70sbgx-I0Q" alt="Hủ tiếu Mỹ Tho">
                        <p>Hủ tiếu Mỹ Tho</p>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</body>
</html>
