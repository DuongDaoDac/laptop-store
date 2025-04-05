<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Chủ Laptop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            width: 90%;
            margin: 0 auto;
            max-width: 1200px;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 0;
            border-bottom: 1px solid #ccc;
            margin-bottom: 20px;
        }

        .logo a {
            text-decoration: none;
            color: #333;
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #555;
            padding: 5px 10px;
            border-radius: 5px;
        }

        nav ul li a:hover {
            background-color: #eee;
        }

        .search-bar input[type="text"] {
            padding: 8px 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-right: 10px;
        }

        .search-bar button {
            padding: 8px 15px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .slider {
            margin-bottom: 20px;
            /* Thêm CSS cho slider nếu bạn có */
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }

        .product-section {
            margin-bottom: 30px;
            padding: 15px 0;
            border-bottom: 1px solid #eee;
        }

        .product-section h2 {
            color: #333;
            margin-bottom: 15px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .product-item {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            background-color: #f9f9f9;
        }

        .product-item img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }

        .product-item h3 {
            font-size: 16px;
            margin-bottom: 5px;
            color: #333;
        }

        .product-item .price {
            color: #dc3545;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .product-item a {
            display: inline-block;
            padding: 8px 15px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .product-item a:hover {
            background-color: #218838;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #333;
            color: white;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <a href="#">Laptop Store</a>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Dell</a></li>
                    <li><a href="#">Asus</a></li>
                    <li><a href="#">Lenovo</a></li>
                    <li><a href="#">Apple</a></li>
                    <li><a href="#">Acer</a></li>
                    <li><a href="#">Samsung</a></li>
                    <li><a href="#">Phụ kiện</a></li>
                    <li><a href="#">Khuyến mãi</a></li>
                </ul>
            </nav>
            <div class="search-bar">
                <input type="text" placeholder="Tìm kiếm laptop...">
                <button type="submit">Tìm</button>
            </div>
        </header>

        <div class="slider">
            <img src="https://i.imgur.com/w6wKBnD.png" alt="Banner Quảng Cáo Laptop" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        </div>

        <section class="product-section">
            <h2>Laptop Dell</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://cdn.tgdd.vn/Products/Images/44/333105/Slider/dell-inspiron-15-3520-i7-1255u-16gb-512gb-15-6f-120hz-officehs-kyhd-win11-n5i7125w1638766997946624307.jpg" alt="Laptop Dell Inspiron 15 3520 i5 1235U">
                    <h3>Laptop Dell Inspiron 15 3520 i5 1235U</h3>
                    <p class="price">15.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://cdn.tgdd.vn/Products/Images/44/319754/Slider/vi-vn-dell-inspiron-14-5430-i7-20dy31-slider-1.jpg" alt="Laptop Dell 2">
                    <h3>Laptop Dell Inspiron 14 5430 i7 1360P/16GB/1TB/OfficeHS/Win11 (20DY31)</h3>
                    <p class="price">18.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <section class="product-section">
            <h2>Laptop Asus</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://vn.store.asus.com/media/catalog/product/cache/74e490e088db727ef90851ac50e1fa20/a/1/a1505va-l1114w_1_.png" alt="Laptop Asus 1">
                    <h3>Laptop Asus Gaming Vivobook K3605ZF i5 12500H/16GB/512GB/4GB RTX2050/Win11 (RP745W)</h3>
                    <p class="price">16.500.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://vn.store.asus.com/media/catalog/product/cache/74e490e088db727ef90851ac50e1fa20/f/a/fa506nc-hn011w.jpg"="Laptop Asus 2">
                    <h3>Laptop Asus TUF Gaming A15 FA506NCR R7 7435HS/16GB/512GB/4GB RTX3050/144Hz/Win11 (HN097W)</h3>
                    <p class="price">20.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <section class="product-section">
            <h2>Laptop Lenovo</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://cdn.tgdd.vn/Products/Images/44/325500/Slider/vi-vn-lenovo-ideapad-slim-3-15amn8-r5-82xq00j0vn-slider-1.jpg" alt="Laptop Lenovo 1">
                    <h3>Laptop Lenovo Ideapad Slim 3 15IAH8 i5 12450H/16GB/512GB/Win11 (83ER000EVN)</h3>
                    <p class="price">14.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://cdn.tgdd.vn/Products/Images/44/326558/Slider/vi-vn-lenovo-ideapad-slim-5-14imh9-ultra-7-83da001yvn-slider-1.jpg" alt="Laptop Lenovo 2">
                    <h3>Laptop Lenovo Ideapad Slim 5 14IAH8 i5 12450H/16GB/1TB/Win11 (83BF003WVN)</h3>
                    <p class="price">17.500.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <section class="product-section">
            <h2>Laptop Apple</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/mac-card-40-macbook-air-202503?wid=680&hei=528&fmt=p-jpg&qlt=95&.v=1739592123040" alt="Laptop Apple 1">
                    <h3>MacBook Air 13 inch</h3>
                    <p class="price">25.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/mbp-14-digitalmat-gallery-1-202410?wid=728&hei=666&fmt=png-alpha&.v=1728342371746" alt="Laptop Apple 2">
                    <h3>MacBook Pro 14 inch</h3>
                    <p class="price">30.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <section class="product-section">
            <h2>Laptop Acer</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://static-ecapac.acer.com/media/catalog/product/a/c/acer_aspire_lite_15_al15-51m_-_laptop_v_n_ph_ng_m_ng_nh_2024_-_nh_a_nx.krssv.001-b1.png?optimize=high&bg-color=255,255,255&fit=bounds&height=320&width=320&canvas=320:320&format=jpeg" alt="Laptop Acer 1">
                    <h3>Laptop Aspire Lite 15 | AL15-51M-55NB</h3>
                    <p class="price">13.500.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://static-ecapac.acer.com/media/catalog/product/a/c/acer_aspire_15_a15-51m_-_laptop_v_n_ph_ng_m_ng_nh_2024_-_nh_a_nx.krpsv.002-b1-1.png?optimize=high&bg-color=255,255,255&fit=bounds&height=320&width=320&canvas=320:320&format=jpeg" alt="Laptop Acer 2">
                    <h3>Laptop Aspire 15 | A15-51P-53T8</h3>
                    <p class="price">16.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <section class="product-section">
            <h2>Laptop Samsung</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://cdn2.cellphones.com.vn/insecure/rs:fill:0:358/q:90/plain/https://cellphones.com.vn/media/catalog/product/l/a/laptop-samsung-galaxy-book_1.jpg" alt="Laptop Samsung 1">
                    <h3>Samsung Galaxy Book</h3>
                    <p class="price">19.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
                <div class="product-item">
                    <img src="https://cdn.tgdd.vn/Products/Images/44/328598/Slider/vi-vn-samsung-galaxy-chromebook-go-xe340xda-n4500-slider-1.jpg" alt="Laptop Samsung 2">
                    <h3>Laptop Samsung Galaxy Chromebook Go XE340XDA N4500/4GB/32GB/ChromeOS</h3>
                    <p class="price">22.000.000 VNĐ</p>
                    <a href="#">Xem chi tiết</a>
                </div>
            </div>
        </section>

        <footer>
            <p>&copy; 2025 Cửa Hàng Laptop. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
