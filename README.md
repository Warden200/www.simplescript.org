<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Script | язык программирования</title>
    <style>
        /* Стиль старого python.org — минималистичный, компактный */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #2c3e4e;
            font-family: 'Lucida Grande', 'Lucida Sans Unicode', 'Geneva', 'Verdana', sans-serif;
            font-size: 13px;
            line-height: 1.4;
            padding: 15px;
        }

        .container {
            max-width: 880px;
            margin: 0 auto;
            background: #ffffff;
            border: 1px solid #aaa;
            box-shadow: 5px 5px 10px rgba(0,0,0,0.2);
        }

        .header {
            background: #1f5a7e;
            background: linear-gradient(135deg, #1f5a7e 0%, #0f3b55 100%);
            padding: 12px 18px;
            border-bottom: 2px solid #ffcc00;
        }

        .logo h1 {
            font-size: 26px;
            color: white;
            text-shadow: 1px 1px 0 #1a3e55;
            display: inline;
        }

        .logo h1 span {
            color: #ffcc33;
        }

        .logo p {
            font-size: 11px;
            color: #ffdd99;
            display: inline;
            margin-left: 12px;
        }

        .nav {
            background: #f5f5f5;
            border-bottom: 1px solid #b0b7bc;
            padding: 5px 15px;
        }

        .nav ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            gap: 22px;
        }

        .nav ul li a {
            text-decoration: none;
            color: #1f5a7e;
            font-weight: bold;
            font-size: 12px;
        }

        .nav ul li a:hover {
            color: #c96f0e;
        }

        .main-content {
            display: flex;
            flex-wrap: wrap;
        }

        .sidebar {
            width: 30%;
            background: #f0f3f6;
            border-right: 1px solid #ccc;
            padding: 14px 12px;
            font-size: 12px;
        }

        .content {
            width: 70%;
            padding: 16px 18px;
        }

        .widget {
            background: #ffffff;
            border: 1px solid #cbd5e0;
            padding: 8px 10px;
            margin-bottom: 16px;
        }

        .widget h3 {
            background: #dce5ec;
            font-size: 12px;
            padding: 3px 6px;
            margin: -8px -10px 8px -10px;
            border-bottom: 1px solid #b9c4ce;
            font-weight: bold;
        }

        .widget ul {
            list-style: square;
            margin-left: 18px;
        }

        .widget ul li {
            margin-bottom: 4px;
        }

        .widget a {
            color: #226f9e;
            text-decoration: none;
        }

        .widget a:hover {
            text-decoration: underline;
        }

        .widget p {
            margin-bottom: 4px;
        }

        .content h2 {
            color: #1f5a7e;
            font-size: 18px;
            border-left: 4px solid #ffcc00;
            padding-left: 10px;
            margin-bottom: 12px;
        }

        .content h3 {
            font-size: 14px;
            margin: 14px 0 6px 0;
            color: #2c3e4e;
        }

        .content p {
            margin-bottom: 10px;
        }

        .button {
            display: inline-block;
            background: #ffcc33;
            color: #1f3b4a;
            padding: 5px 14px;
            font-weight: bold;
            text-decoration: none;
            font-size: 12px;
            border-radius: 3px;
            margin-top: 8px;
            margin-right: 8px;
        }

        .button:hover {
            background: #ffdd66;
        }

        .download-box {
            background: #f8f4e8;
            border: 1px solid #ffcc33;
            padding: 8px 12px;
            margin: 12px 0;
            text-align: center;
        }

        .version {
            font-size: 18px;
            font-weight: bold;
        }

        .year-badge {
            background: #1f5a7e;
            color: white;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 10px;
            display: inline-block;
            margin-left: 8px;
        }

        hr {
            margin: 12px 0;
            border-top: 1px solid #ccc;
        }

        .footer {
            background: #e4e9ee;
            padding: 8px 12px;
            font-size: 10px;
            text-align: center;
            border-top: 1px solid #b8c2ca;
        }

        .footer a {
            color: #1f5a7e;
            text-decoration: none;
        }

        .news-date {
            color: #cc7b1c;
            font-weight: bold;
        }

        .highlight {
            background: #fff8e0;
            padding: 2px 4px;
            border-radius: 3px;
        }

        @media (max-width: 650px) {
            .sidebar, .content {
                width: 100%;
            }
            .sidebar {
                border-right: none;
                border-bottom: 1px solid #ccc;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <div class="logo">
            <h1>Simple<span>Script</span></h1>
            <p>легкий язык для скриптов <span class="year-badge">est. 2008</span></p>
        </div>
    </div>
    
    <div class="nav">
        <ul>
            <li><a href="#">Главная</a></li>
            <li><a href="#">Скачать</a></li>
            <li><a href="#">Документация</a></li>
            <li><a href="#">Сообщество</a></li>
            <li><a href="#">Новости</a></li>
        </ul>
    </div>
    
    <div class="main-content">
        <div class="sidebar">
            <div class="widget">
                <h3>О языке</h3>
                <p><strong>Simple Script (SS)</strong> — легкий язык программирования, созданный в далеком 2008 и выпущенный в 2020 году.</p>
                <p style="margin-top: 6px;">✔ Легкий синтаксис<br>✔ Выучить за 30 минут<br>✔ Библиотеки не нужны!<br>✔ Работает на любом устройстве</p>
            </div>
            
            <div class="widget">
                <h3>Новости</h3>
                <ul>
                    <li><span class="news-date">Апрель 2026</span> — <strong>Переработка систем</strong></li>
                    <li><span class="news-date">Март 2026</span> — <a href="#">Simple Script 2.5.1</a></li>
                    <li><span class="news-date">2020</span> — <a href="#">Первый публичный релиз</a></li>
                </ul>
            </div>
            
            <div class="widget">
                <h3>Быстрые ссылки</h3>
                <ul>
                    <li><a href="#">Скачать SS</a></li>
                    <li><a href="#">Документация</a></li>
                    <li><a href="#">Примеры кода</a></li>
                    <li><a href="#">GitHub</a></li>
                    <li><a href="#">FAQ</a></li>
                </ul>
            </div>
            
            <div class="widget">
                <h3>Сообщество</h3>
                <p>Telegram: <a href="#">@simple_script</a><br>
                Discord: <a href="#">discord.gg/ss</a><br>
                Форум: <a href="#">forum.simplescript.ru</a></p>
            </div>
        </div>
        
        <div class="content">
            <h2>Simple Script (SS) — простота в чистом виде</h2>
            
            <div class="download-box">
                <div class="version">Simple Script 2.5.1</div>
                <p>Работает на любом устройстве — Windows, macOS, Linux, FreeBSD</p>
                <a href="#" class="button">⬇ Скачать SS</a>
                <a href="#" class="button">📖 Документация</a>
            </div>
            
            <h3>📄 Документация</h3>
            <p><strong>Simple Script (SS)</strong> — легкий язык, созданный в далеком 2008 и выпущенный только в 2020 году. Данный язык программирования имеет легкий синтаксис, который можно выучить за 30 минут. <strong>Библиотеки не нужны!</strong> Все необходимое уже встроено в язык. Работает на любом устройстве!</p>
            
            <h3>✨ Ключевые особенности</h3>
            <ul style="margin-left: 20px; margin-bottom: 12px;">
                <li>🎯 <strong>Легкий синтаксис</strong> — выучите за 30 минут</li>
                <li>📚 <strong>Библиотеки не нужны</strong> — всё уже есть</li>
                <li>💻 <strong>Работает на любом устройстве</strong> — полная кроссплатформенность</li>
                <li>⚡ <strong>Создан в 2008</strong> — выпущен в 2020, проверен временем</li>
                <li>🔧 <strong>Встроенные инструменты</strong> — работа с JSON, HTTP, файлами, regex</li>
            </ul>
            
            <h3>📰 Новости</h3>
            <div style="background: #f8f4e8; padding: 10px; border-left: 3px solid #ffcc33; margin: 10px 0;">
                <span class="news-date">Апрель 2026</span>
                <p style="margin: 5px 0 0 0;"><strong>Переработка систем</strong> — ведутся работы по улучшению производительности и оптимизации интерпретатора. Следите за обновлениями!</p>
            </div>
            
            <hr>
            
            <h3>История языка</h3>
            <p>Simple Script был задуман еще в далеком 2008 году как эксперимент по созданию максимально простого и доступного языка для написания скриптов. После многих лет разработки и доработок, в 2020 году состоялся первый публичный релиз. С тех пор язык продолжает развиваться, оставаясь верным своим принципам: простота, минимализм, независимость от внешних библиотек и работа на любом устройстве.</p>
            
            <p style="margin-top: 12px;"><a href="#" class="button">📖 Полная документация</a> <a href="#" class="button">💬 Сообщество</a></p>
        </div>
    </div>
    
    <div class="footer">
        <p>© 2008–2026 Simple Script Language Team. Легкий язык для скриптов.</p>
        <p><a href="#">О проекте</a> | <a href="#">Лицензия MIT</a> | <a href="#">GitHub</a> | <a href="#">Документация</a> | <a href="#">Контакты</a></p>
        <p style="margin-top: 4px; font-size: 9px;">Simple Script — работает на любом устройстве. Библиотеки не нужны!</p>
    </div>
</div>

<div style="text-align: center; margin-top: 10px; font-size: 10px; color:#ddd;">
    <span>✦ Simple Script — выучи за 30 минут. Работает везде. ✦</span>
</div>

</body>
</html>
