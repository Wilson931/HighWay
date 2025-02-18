<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electronic Products Sale</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        h1 {
            text-align: center;
            color: #007BFF;
            background-color: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        h2 {
            margin-top: 30px;
            color: #333;
            background-color: #fff;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
            cursor: pointer;
        }

     .product - category {
            border: 2px solid #007BFF;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            display: inline - block;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: #fff;
            position: relative;
        }

     .product - details {
            margin-top: 15px;
            display: none;
        }

     .product - category.open.product - details {
            display: block;
        }

     .product - details p {
            margin: 8px 0;
            font-size: 16px;
        }

     .product - details strong {
            color: #007BFF;
        }

     .language - switch {
            position: fixed;
            top: 10px;
            right: 10px;
            background-color: #fff;
            padding: 5px 10px;
            border: 1px solid #ccc;
            border - radius: 5px;
            cursor: pointer;
        }

     .language - pair {
            display: flex;
            flex - direction: column;
        }

     .language - pair p {
            margin: 0;
            font - size: 14px;
        }

     .language - pair.english {
            color: #333;
        }

     .language - pair.chinese {
            color: #666;
        }
    </style>
</head>

<body>
    <div class="language - switch" onclick="toggleLanguage()">
        <span class="english">English</span>
        <span class="chinese">中文</span>
    </div>
    <h1>
        <div class="language - pair">
            <p class="english">Electronic Products Sale</p>
            <p class="chinese">电子产品销售</p>
        </div>
    </h1>

    <!-- Mobile Phones Category -->
    <div class="product - category" onclick="toggleDetails(this)">
        <h2>
            <div class="language - pair">
                <p class="english">Mobile Phones</p>
                <p class="chinese">手机</p>
            </div>
        </h2>
        <div class="product - details">
            <div class="language - pair">
                <p><strong class="english">Product 1:</strong> iPhone 15 Pro</p>
                <p><strong class="chinese">产品1:</strong> iPhone 15 Pro</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Price:</strong> $999</p>
                <p><strong class="chinese">价格:</strong> 999美元</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Stock:</strong> 50</p>
                <p><strong class="chinese">库存:</strong> 50</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Description:</strong> A high - end smartphone with advanced camera features and powerful performance.</p>
                <p><strong class="chinese">描述:</strong> 一款拥有先进摄像功能和强大性能的高端智能手机。</p>
            </div>
        </div>
    </div>

    <!-- Smart Watches Category -->
    <div class="product - category" onclick="toggleDetails(this)">
        <h2>
            <div class="language - pair">
                <p class="english">Smart Watches</p>
                <p class="chinese">手表</p>
            </div>
        </h2>
        <div class="product - details">
            <div class="language - pair">
                <p><strong class="english">Product 1:</strong> Apple Watch Series 9</p>
                <p><strong class="chinese">产品1:</strong> Apple Watch Series 9</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Price:</strong> $399</p>
                <p><strong class="chinese">价格:</strong> 399美元</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Stock:</strong> 30</p>
                <p><strong class="chinese">库存:</strong> 30</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Description:</strong> A smartwatch with health - tracking features and a sleek design.</p>
                <p><strong class="chinese">描述:</strong> 一款具有健康追踪功能和时尚设计的智能手表。</p>
            </div>
        </div>
    </div>

    <!-- Tablets Category -->
    <div class="product - category" onclick="toggleDetails(this)">
        <h2>
            <div class="language - pair">
                <p class="english">Tablets</p>
                <p class="chinese">平板</p>
            </div>
        </h2>
        <div class="product - details">
            <div class="language - pair">
                <p><strong class="english">Product 1:</strong> iPad Pro</p>
                <p><strong class="chinese">产品1:</strong> iPad Pro</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Price:</strong> $799</p>
                <p><strong class="chinese">价格:</strong> 799美元</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Stock:</strong> 40</p>
                <p><strong class="chinese">库存:</strong> 40</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Description:</strong> A powerful tablet with a high - resolution display and fast processing speed.</p>
                <p><strong class="chinese">描述:</strong> 一款拥有高分辨率显示屏和快速处理速度的强大平板。</p>
            </div>
        </div>
    </div>

    <!-- Laptops Category -->
    <div class="product - category" onclick="toggleDetails(this)">
        <h2>
            <div class="language - pair">
                <p class="english">Laptops</p>
                <p class="chinese">笔记本</p>
            </div>
        </h2>
        <div class="product - details">
            <div class="language - pair">
                <p><strong class="english">Product 1:</strong> MacBook Pro</p>
                <p><strong class="chinese">产品1:</strong> MacBook Pro</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Price:</strong> $1299</p>
                <p><strong class="chinese">价格:</strong> 1299美元</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Stock:</strong> 20</p>
                <p><strong class="chinese">库存:</strong> 20</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Description:</strong> A high - performance laptop with a Retina display and long - lasting battery life.</p>
                <p><strong class="chinese">描述:</strong> 一款拥有视网膜显示屏和长续航电池的高性能笔记本。</p>
            </div>
        </div>
    </div>

    <!-- Headphones Category -->
    <div class="product - category" onclick="toggleDetails(this)">
        <h2>
            <div class="language - pair">
                <p class="english">Headphones</p>
                <p class="chinese">耳机</p>
            </div>
        </h2>
        <div class="product - details">
            <div class="language - pair">
                <p><strong class="english">Product 1:</strong> AirPods Pro</p>
                <p><strong class="chinese">产品1:</strong> AirPods Pro</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Price:</strong> $249</p>
                <p><strong class="chinese">价格:</strong> 249美元</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Stock:</strong> 60</p>
                <p><strong class="chinese">库存:</strong> 60</p>
            </div>
            <div class="language - pair">
                <p><strong class="english">Description:</strong> Wireless earbuds with active noise cancellation and high - quality sound.</p>
                <p><strong class="chinese">描述:</strong> 具有主动降噪和高品质音效的无线耳塞。</p>
            </div>
        </div>
    </div>

    <script>
        function toggleDetails(product) {
            const details = product.querySelector('.product - details');
            product.classList.toggle('open');
            if (details.style.display === 'block') {
                details.style.display = 'none';
            } else {
                details.style.display = 'block';
            }
        }

        function toggleLanguage() {
            const languagePairs = document.querySelectorAll('.language - pair');
            languagePairs.forEach(pair => {
                const english = pair.querySelector('.english');
                const chinese = pair.querySelector('.chinese');
                if (english.style.display === 'none') {
                    english.style.display = 'block';
                    chinese.style.display = 'none';
                } else {
                    english.style.display = 'none';
                    chinese.style.display = 'block';
                }
            });
        }
    </script>
</body>

</html>
