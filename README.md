<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>似乎被遗忘了</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --bg-color: #f8f9fa;
            --text-color: #2c3e50;
            --accent-color: #34495e;
            --secondary-color: #7f8c8d;
            --light-accent: #ecf0f1;
            --hover-color: #3498db;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body, html {
            font-family: 'Noto Serif SC', serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            height: 100%;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            overflow-x: hidden;
        }

        .container {
            width: 100%;
            max-width: 800px;
            padding: 20px;
            text-align: center;
            margin: 0 auto;
        }

        header {
            margin-bottom: 2rem;
        }

        h1 {
            font-size: 2.5rem;
            color: var(--accent-color);
            margin-bottom: 0.5rem;
            font-weight: 700;
        }

        .subtitle {
            font-size: 1.1rem;
            color: var(--secondary-color);
            font-weight: 300;
        }

        .content-section {
            margin-bottom: 3rem;
        }

        h2 {
            color: var(--accent-color);
            font-weight: 400;
            font-size: 1.8rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 1px solid var(--secondary-color);
        }

        .content-section p {
            margin-bottom: 1rem;
            font-weight: 400;
            font-size: 1.1rem;
        }

        .nav-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin-top: 1.5rem;
        }

        .nav-item, .quote {
            flex: 1 1 calc(33.333% - 1rem);
            min-width: 200px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: var(--text-color);
            background-color: var(--light-accent);
            border-radius: 10px;
            padding: 1.5rem;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .nav-item:hover, .quote:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .nav-item:active, .quote:active {
            transform: translateY(0);
            box-shadow: 0 5px 10px rgba(0,0,0,0.05);
        }

        .nav-icon {
            font-size: 2rem;
            margin-bottom: 0.5rem;
            position: relative;
            z-index: 2;
            transition: transform 0.3s ease;
        }

        .nav-item:hover .nav-icon {
            transform: scale(1.1);
        }

        .nav-name {
            font-size: 1.1rem;
            text-align: center;
            position: relative;
            z-index: 2;
            font-weight: 500;
        }

        .quote {
            color: var(--text-color);
            margin: 1.5rem 0;
            min-height: 120px;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            flex: 1 1 100%;
            padding: 2rem;
            position: relative;
        }

        .quote::before,
        .quote::after {
            font-family: 'Font Awesome 6 Free';
            font-weight: 900;
            font-size: 2rem;
            color: var(--secondary-color);
            opacity: 0.2;
            position: absolute;
            top: 10px;
        }

        .quote::before {
            content: '\f10d';
            left: 10px;
        }

        .quote::after {
            content: '\f10d';
            right: 10px;
            transform: scale(-1, 1);
        }

        .quote p {
            text-align: center;
            max-width: 90%;
            margin: 0;
            padding: 0;
            position: relative;
            z-index: 2;
            font-weight: 500;
            font-size: 1.1rem;
        }

        footer {
            width: 100%;
            text-align: center;
            padding: 1.5rem 0;
            background-color: var(--light-accent);
            margin-top: auto;
        }

        footer p {
            margin: 0.3rem 0;
            font-size: 0.9rem;
            color: var(--accent-color);
        }

        footer a {
            color: var(--accent-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: var(--hover-color);
        }

        .police-record {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .police-record img {
            width: 20px;
            height: 20px;
            margin-right: 5px;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            .subtitle {
                font-size: 1rem;
            }
            h2 {
                font-size: 1.5rem;
            }
            .nav-item, .quote {
                flex: 1 1 100%;
            }
            .content-section p, .quote p {
                font-size: 1rem;
            }
            .nav-name {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>似乎被遗忘了</h1>
            <p class="subtitle">记录生活 | 分享思考 | 探索未知</p>
        </header>
        <section class="content-section">
            <h2>网站前言</h2>
            <p>你终于来了 还记得我吗 想起了 就来看看吧</p>
            <p>欢迎来到我的引导页 这里是我记录生活点滴</p>
            <p>分享个人思考的空间 虽然似乎被世界遗忘了</p>
            <p>但我依然在这里留下自己的印记 期待与你分享</p>
        </section>
        <section class="content-section">
            <h2>网页导航</h2>
            <nav class="nav-list">
                <a href="#" class="nav-item">
                    <i class="nav-icon fas fa-sitemap" aria-hidden="true"></i>
                    <span class="nav-name">旗下网站</span>
                </a>
                <a href="#" class="nav-item">
                    <i class="nav-icon fas fa-book-open" aria-hidden="true"></i>
                    <span class="nav-name">生活笔记</span>
                </a>
                <a href="#" class="nav-item">
                    <i class="nav-icon fas fa-laptop-code" aria-hidden="true"></i>
                    <span class="nav-name">技术探索</span>
                </a>
            </nav>
        </section>
        <section class="content-section">
            <h2>随心一言</h2>
            <div class="quote">
                <p>世界那么大 我想去看看</p>
            </div>
        </section>
    </div>
    <footer>
            <p>似乎被遗忘了 | 保留所有权利</p>
            <p><a href="https://beian.miit.gov.cn/" target="_blank" rel="noopener noreferrer">皖ICP备2024060728号</a></p>
            <p class="police-record">
            <img src="beian_icon.png" alt="公安备案图标" />
            <a href="https://beian.mps.gov.cn/#/query/webSearch?code=34032102180091" rel="noreferrer" target="_blank">皖公网安备34032102180091号</a></p>
    </footer>
</body>
</html>
