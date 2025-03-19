<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>施梦娇的个人简介</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
 
        body {
            background: linear-gradient(135deg, #2c3e50, #ecf0f1);
            min-height: 100vh;
            color: #2c3e50;
            line-height: 1.6;
        }
 
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
 
        header {
            text-align: center;
            padding: 3rem 0;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            margin-bottom: 2rem;
        }
 
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1rem;
            border: 3px solid #3498db;
        }
 
        h1 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
        }
 
        h2 {
            color: #3498db;
            margin-bottom: 1rem;
        }
 
        .section {
            background: rgba(255, 255, 255, 0.9);
            padding: 2rem;
            border-radius: 10px;
            margin-bottom: 2rem;
        }
 
        .education-item {
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: #f8f9fa;
            border-radius: 5px;
        }
 
        .skill-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
 
        .skill-item {
            padding: 1rem;
            background: #e9ecef;
            border-radius: 5px;
            text-align: center;
        }
 
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
            padding: 0.8rem;
            background: #f8f9fa;
            border-radius: 5px;
        }
 
        .contact-item i {
            margin-right: 1rem;
            color: #3498db;
        }
 
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="https://via.placeholder.com/150" alt="施梦娇" class="profile-img">
            <h1>施梦娇</h1>
            <h2>硕士研究生 | 资源与环境专业</h2>
        </header>
 
        <section class="section" id="about">
            <h2>📚 关于我</h2>
            <p>专注于资源与环境领域的硕士研究生，致力于通过跨学科研究解决环境问题。具备扎实的理论基础和实践经验，熟悉环境评估、数据分析及可持续发展策略。</p>
            <p>热爱探索新技术在环境保护中的应用，擅长将理论知识转化为实际解决方案。</p>
        </section>
 
        <section class="section" id="education">
            <h2>🎓 教育背景</h2>
            <div class="education-item">
                <h3>华中农业大学 | 资源与环境学院</h3>
                <p>硕士研究生 | 资源与环境专业 | 2024.09 - 至今</p>
                <p>研究方向：环境管理与可持续发展</p>
            </div>
            <div class="education-item">
                <h3>XX大学 | 环境科学系</h3>
                <p>本科 | 环境科学专业 | 2020.09 - 2024.06</p>
                <p>主修课程：环境化学、生态学、环境监测等</p>
            </div>
        </section>
 
        <section class="section" id="skills">
            <h2>🛠 技能专长</h2>
            <div class="skill-list">
                <div class="skill-item">
                    <h3>数据分析</h3>
                    <p>Python, R, SPSS, Excel</p>
                </div>
                <div class="skill-item">
                    <h3>环境评估</h3>
                    <p>EIA报告编制，生命周期评估</p>
                </div>
                <div class="skill-item">
                    <h3>GIS技术</h3>
                    <p>ArcGIS, QGIS, 空间数据分析</p>
                </div>
                <div class="skill-item">
                    <h3>语言能力</h3>
                    <p>英语CET-4，专业文献阅读</p>
                </div>
            </div>
        </section>
 
        <section class="section" id="contact">
            <h2>📧 联系方式</h2>
            <div class="contact-item">
                <i class="fas fa-envelope"></i>
                <a href="mailto:1076876223@example.com">yourname@example.com</a>
            </div>
            <div class="contact-item">
                <i class="fas fa-phone"></i>
                <a href="tel:+8618176578943">+86 123-4567-890</a>
            </div>
            <div class="contact-item">
                <i class="fab fa-github"></i>
                <a href="https://github.com/123S-OSS">GitHub</a>
            </div>
        </section>
    </div>
 
    <!-- 引入Font Awesome图标 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</body>
</html>
