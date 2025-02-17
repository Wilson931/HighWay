# HighWay
<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>篮球鞋购买与回收</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-image: url('https://image.example.com/basketball_court_pattern.jpg');
            background-repeat: repeat;
        }

        h1 {
            text-align: center;
            color: #0056b3;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        h2 {
            margin-top: 30px;
            color: #333;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 5px 10px;
            border-radius: 5px;
            display: inline-block;
        }

     .product {
            border: 2px solid #0056b3;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            display: inline-block;
            width: 350px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: rgba(255, 255, 255, 0.9);
            position: relative;
            cursor: pointer;
        }

     .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

     .product img:hover {
            transform: scale(1.1);
        }

     .product-details {
            margin-top: 15px;
            display: none;
        }

     .product.open.product-details {
            display: block;
        }

     .product-details p {
            margin: 8px 0;
            font-size: 16px;
        }

     .product-details strong {
            color: #0056b3;
        }

     .product-nba-color {
            border: 2px solid #0056b3;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            display: inline-block;
            width: 350px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: rgba(255, 255, 255, 0.9);
            background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.5));
            background-size: cover;
            background-position: center;
        }

     .product-nba-color.kobe {
            background-color: rgba(255, 255, 255, 0.9);
            background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.5)), url('https://image.example.com/lakers_logo.png');
            background-size: 100px, cover;
            background-position: top right, center;
            background-repeat: no-repeat;
        }

     .product-nba-color.jordan {
            background-color: rgba(255, 255, 255, 0.9);
            background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.5)), url('https://image.example.com/bulls_logo.png');
            background-size: 100px, cover;
            background-position: top right, center;
            background-repeat: no-repeat;
        }

     .product-nba-color.nike {
            background-color: rgba(255, 255, 255, 0.9);
            background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.5)), url('https://image.example.com/nike_basketball_logo.png');
            background-size: 100px, cover;
            background-position: top right, center;
            background-repeat: no-repeat;
        }

     .search-filter {
            text-align: center;
            margin-bottom: 20px;
        }

     .search-filter input[type="text"] {
            padding: 8px;
            width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

     .search-filter select {
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-left: 10px;
        }

     .user-reviews {
            margin-top: 15px;
        }

     .user-reviews p {
            margin-bottom: 5px;
        }

     .user-reviews ul {
            list-style-type: none;
            padding: 0;
        }

     .user-reviews ul li {
            margin-bottom: 5px;
        }

     .related-products {
            margin-top: 15px;
        }

     .related-products h3 {
            margin-bottom: 10px;
        }

    </style>
</head>

<body>
    <h1>篮球鞋购买与回收</h1>

    <div class="search-filter">
        <input type="text" placeholder="搜索篮球鞋">
        <select>
            <option value="all">所有品牌</option>
            <option value="kobe">科比</option>
            <option value="jordan">乔丹</option>
            <option value="nike">耐克</option>
        </select>
    </div>

    <h2>科比系列篮球鞋</h2>
    <!-- Kobe 4 example -->
    <div class="product product-nba-color kobe" onclick="toggleDetails(this)">
        <img src="https://image.example.com/kobe4.jpg" alt="科比4代">
        <p><strong>型号:</strong> 科比4代</p>
        <div class="product-details">
            <p><strong>颜色选择:</strong> 湖人配色（紫/金）, 黑/白, 不败系列</p>
            <p><strong>可选尺码:</strong> 美码8、8.5、9、9.5、10、10.5、11</p>
            <p><strong>成色:</strong></p>
            <ul>
                <li>全新: 全新未使用，成色完美，适合收藏。</li>
                <li>二手: 中度使用，鞋底有一些磨损痕迹，但缓震性能完好。</li>
                <li>签名版: 由专业鉴定机构验证签名，对球迷来说是很有价值的物品。</li>
            </ul>
            <p><strong>鞋面材质:</strong> 飞线和合成材料</p>
            <p><strong>中底科技:</strong> 全长Zoom Air单元</p>
            <p><strong>描述:</strong> 科比4代采用低帮设计，增加脚踝灵活性。它结合了飞线技术和合成鞋面，提供轻质支撑。全长Zoom Air单元提供平稳且响应迅速的脚感。</p>
            <div class="user-reviews">
                <p><strong>评分:</strong> 4.5/5（基于50条评价）</p>
                <ul>
                    <li>"很棒的鞋子，打篮球非常舒服。" - 约翰</li>
                    <li>"设计很棒，但尺码有点偏小。" - 艾米丽</li>
                </ul>
            </div>
            <div class="related-products">
                <h3>相关产品</h3>
                <div class="product product-nba-color kobe">
                    <img src="https://image.example.com/kobe5.jpg" alt="科比5代">
                    <div class="product-details">
                        <p><strong>型号:</strong> 科比5代</p>
                    </div>
                </div>
                <div class="product product-nba-color kobe">
                    <img src="https://image.example.com/kobe8.jpg" alt="科比8代">
                    <div class="product-details">
                        <p><strong>型号:</strong> 科比8代</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- 其他鞋款示例，结构类似Kobe 4，依次添加中文内容 -->
    <script>
        function toggleDetails(product) {
            const details = product.querySelector('.product-details');
            product.classList.toggle('open');
            if (details.style.display === 'block') {
                details.style.display = 'none';
            } else {
                details.style.display = 'block';
            }
        }
    </script>
</body>

</html>
