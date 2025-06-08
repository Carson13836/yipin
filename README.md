<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>一品科技 - 室内设计专家</title>
    <style>
        /* 全局样式 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        /* 标题样式 */
        h1 {
            color: #333;
            text-align: center;
        }

        /* 导航栏样式 */
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }

        nav ul li {
            cursor: pointer;
        }

        /* 内容区域样式 */
        .content {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        /* 图片展示样式 */
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }

        .image-gallery img {
            width: 100%;
            height: auto;
            cursor: pointer;
        }

        /* 联系方式样式 */
        .contact-info {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <!-- 导航栏 -->
    <nav>
        <ul>
            <li>首页</li>
            <li>服务项目</li>
            <li>案例展示</li>
            <li>关于我们</li>
        </ul>
    </nav>

    <!-- 公司名称标题 -->
    <h1>一品科技 - 室内设计有限公司</h1>

    <!-- 内容区域 -->
    <div class="content">
        <!-- 公司简介 -->
        <p>一品科技是一家专注于室内设计的公司，拥有专业的设计团队和丰富的经验，致力于为客户打造高品质的室内空间。</p>

        <!-- 材料展示图片 -->
        <h2>材料展示</h2>
        <div class="image-gallery">
            <img src="materials/material1.jpg" alt="材料1">
            <img src="materials/material2.jpg" alt="材料2">
            <img src="materials/material3.jpg" alt="材料3">
            <!-- 可继续添加更多材料图片 -->
        </div>

        <!-- 施工图片 -->
        <h2>施工过程</h2>
        <div class="image-gallery">
            <img src="construction/construction1.jpg" alt="施工1">
            <img src="construction/construction2.jpg" alt="施工2">
            <img src="construction/construction3.jpg" alt="施工3">
            <!-- 可继续添加更多施工图片 -->
        </div>
    </div>

    <!-- 联系方式 -->
    <div class="contact-info">
        <p>联系电话：0912345678</p>
    </div>
</body>

</html>
