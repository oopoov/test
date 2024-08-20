<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人简介</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            max-width: 1200px;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        .skills-list {
            list-style-type: none;
            padding: 0;
        }
        .skills-list li {
            background-color: #e7f3e7;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
        }
        a {
            color: #4CAF50;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>个人简介</h1>
        </div>
    </header>
    
    <div class="container">
        <section>
            <h2>关于我</h2>
            <p>这里是你的个人简介，简单介绍你的背景、兴趣和目前的职业方向。</p>
        </section>
        
        <section>
            <h2>技能</h2>
            <ul class="skills-list">
                <li>技能 1</li>
                <li>技能 2</li>
                <li>技能 3</li>
            </ul>
        </section>
        
        <section>
            <h2>联系方式</h2>
            <p>你可以通过以下方式联系我：</p>
            <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
            <p>电话: 你的电话号码</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2024 你的名字. 保留所有权利。</p>
    </footer>
</body>
</html>
