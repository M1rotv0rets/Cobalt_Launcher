<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minecraft Launcher</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
            color: #e0e0e0;
            min-height: 100vh;
            overflow: hidden;
            position: relative;
        }

        .background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://images.unsplash.com/photo-1633453828335-9d0f7c4f8f5d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80');
            background-size: cover;
            background-position: center;
            opacity: 0.25;
            z-index: -1;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 12px 12px 0 0;
            border-bottom: 2px solid #00a8ff;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            margin-bottom: 10px;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .logo img {
            height: 50px;
            filter: drop-shadow(0 0 5px #00a8ff);
        }

        .logo-text {
            font-family: 'Press Start 2P', cursive;
            font-size: 24px;
            color: #4dff4d;
            text-shadow: 0 0 10px #00ff00;
        }

        .tabwidget {
            display: flex;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 0 0 12px 12px;
            overflow: hidden;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            flex-wrap: wrap;
        }

        .tab {
            padding: 15px 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            color: #aaa;
        }

        .tab:hover {
            background: rgba(50, 50, 70, 0.8);
            color: #fff;
        }

        .tab.active {
            background: rgba(30, 30, 50, 0.9);
            color: #4dff4d;
            border-bottom: 3px solid #00a8ff;
        }

        .tab i {
            font-size: 18px;
        }

        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            margin-top: 20px;
            gap: 20px;
        }

        .play-section {
            background: rgba(0, 0, 0, 0.7);
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .controls {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            align-items: center;
        }

        .combobox {
            flex: 1;
            min-width: 250px;
            position: relative;
        }

        .combobox label {
            display: block;
            margin-bottom: 8px;
            color: #00a8ff;
            font-weight: 600;
        }

        .combobox select {
            width: 100%;
            padding: 12px 15px;
            border-radius: 8px;
            border: 2px solid #333;
            background: #111;
            color: #fff;
            font-size: 16px;
            transition: all 0.3s;
            appearance: none;
        }

        .combobox select:focus {
            border-color: #00a8ff;
            outline: none;
            box-shadow: 0 0 10px rgba(0, 168, 255, 0.5);
        }

        .combobox::after {
            content: '\f078';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            position: absolute;
            right: 15px;
            top: 40px;
            color: #00a8ff;
            pointer-events: none;
        }

        .action-buttons {
            display: flex;
            gap: 15px;
            align-items: flex-end;
        }

        .btn {
            padding: 12px 20px;
            border-radius: 8px;
            border: none;
            background: linear-gradient(to bottom, #00a8ff, #0077b6);
            color: white;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        .btn:hover {
            background: linear-gradient(to bottom, #0097e6, #005f8a);
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }

        .btn i {
            font-size: 18px;
        }

        .btn.play {
            background: linear-gradient(to bottom, #4CAF50, #2E7D32);
            padding: 15px 30px;
            font-size: 18px;
        }

        .btn.play:hover {
            background: linear-gradient(to bottom, #43A047, #1B5E20);
        }

        .progress-section {
            background: rgba(0, 0, 0, 0.7);
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }

        .progress-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .progress-label {
            display: flex;
            justify-content: space-between;
            font-size: 14px;
            color: #aaa;
        }

        .progress-bar {
            height: 20px;
            background: #111;
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid #333;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(to right, #00a8ff, #4dff4d);
            width: 65%;
            border-radius: 10px;
            transition: width 0.5s ease;
            position: relative;
        }

        .progress-fill::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, 
                rgba(255,255,255,0) 0%, 
                rgba(255,255,255,0.2) 50%, 
                rgba(255,255,255,0) 100%);
            animation: shine 2s infinite;
        }

        @keyframes shine {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        .tab-content {
            flex: 1;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            display: none;
            overflow-y: auto;
        }

        .tab-content.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .tab-content h2 {
            color: #00a8ff;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #333;
        }

        .tab-content p {
            line-height: 1.6;
            margin-bottom: 15px;
        }

        .minecraft-block {
            display: inline-block;
            width: 30px;
            height: 30px;
            margin: 5px;
            border: 2px solid #555;
            border-radius: 4px;
            box-shadow: inset 0 0 5px rgba(0,0,0,0.5);
        }

        .grass { background: linear-gradient(135deg, #7CFC00, #32CD32); }
        .dirt { background: linear-gradient(135deg, #8B4513, #A0522D); }
        .stone { background: linear-gradient(135deg, #808080, #A9A9A9); }
        .wood { background: linear-gradient(135deg, #8B4513, #CD853F); }
        .diamond { background: linear-gradient(135deg, #00BFFF, #1E90FF); }
        .gold { background: linear-gradient(135deg, #FFD700, #DAA520); }

        .content-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: rgba(30, 30, 40, 0.8);
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.3s;
            border: 1px solid #333;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: #00a8ff;
        }

        .card h3 {
            color: #4dff4d;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .card p {
            color: #ccc;
            font-size: 14px;
        }

        .footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 14px;
            margin-top: 20px;
        }

        @media (max-width: 768px) {
            .controls {
                flex-direction: column;
                align-items: stretch;
            }
            
            .tab {
                padding: 10px 12px;
                font-size: 14px;
            }
            
            .logo-text {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <div class="background"></div>
    
    <div class="container">
        <div class="header">
            <div class="logo">
                <i class="fas fa-cube" style="font-size: 36px; color: #4dff4d;"></i>
                <div class="logo-text">MINECRAFT LAUNCHER</div>
            </div>
            <div class="status">
                <i class="fas fa-wifi" style="color: #4dff4d;"></i>
                <span>Online</span>
            </div>
        </div>
        
        <div class="tabwidget">
            <div class="tab active" data-tab="home">
                <i class="fas fa-home"></i>
                <span>Главная</span>
            </div>
            <div class="tab" data-tab="notes">
                <i class="fas fa-sticky-note"></i>
                <span>Заметки</span>
            </div>
            <div class="tab" data-tab="logs">
                <i class="fas fa-clipboard-list"></i>
                <span>Логи</span>
            </div>
            <div class="tab" data-tab="news">
                <i class="fas fa-newspaper"></i>
                <span>Новости</span>
            </div>
            <div class="tab" data-tab="settings">
                <i class="fas fa-cog"></i>
                <span>Настройки</span>
            </div>
            <div class="tab" data-tab="tools">
                <i class="fas fa-tools"></i>
                <span>Инструменты</span>
            </div>
            <div class="tab" data-tab="cobalt">
                <i class="fas fa-robot"></i>
                <span>Cobalt Ассистент</span>
            </div>
            <div class="tab" data-tab="library">
                <i class="fas fa-book"></i>
                <span>Библиотека</span>
            </div>
            <div class="tab" data-tab="mods">
                <i class="fas fa-puzzle-piece"></i>
                <span>Моды и сборки</span>
            </div>
            <div class="tab" data-tab="search">
                <i class="fas fa-search"></i>
                <span>Поиск</span>
            </div>
            <div class="tab" data-tab="projects">
                <i class="fas fa-folder"></i>
                <span>Проекты</span>
            </div>
            <div class="tab" data-tab="about">
                <i class="fas fa-info-circle"></i>
                <span>О нас</span>
            </div>
        </div>
        
        <div class="main-content">
            <!-- Главная вкладка -->
            <div id="home" class="play-section tab-content active">
                <div class="controls">
                    <div class="combobox">
                        <label for="accounts">Аккаунты</label>
                        <select id="accounts">
                            <option>Player_1</option>
                            <option>Steve42</option>
                            <option>AlexMiner</option>
                            <option>CreeperHunter</option>
                        </select>
                    </div>
                    
                    <div class="combobox">
                        <label for="versions">Версии</label>
                        <select id="versions">
                            <option>1.20.1 (Latest)</option>
                            <option>1.19.4</option>
                            <option>1.18.2</option>
                            <option>1.17.1</option>
                            <option>1.16.5</option>
                        </select>
                    </div>
                    
                    <div class="action-buttons">
                        <button class="btn">
                            <i class="fas fa-sync-alt"></i>
                            Обновить версии
                        </button>
                        <button class="btn">
                            <i class="fas fa-download"></i>
                            Запрос версии
                        </button>
                        <button class="btn">
                            <i class="fas fa-clock"></i>
                            Отложенный запуск
                        </button>
                    </div>
                    
                    <button class="btn play">
                        <i class="fas fa-play"></i>
                        Играть
                    </button>
                </div>
            </div>
            
            <!-- Прогресс бар -->
            <div class="progress-section">
                <div class="progress-container">
                    <div class="progress-label">
                        <span>Загрузка ресурсов...</span>
                        <span>65%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill"></div>
                    </div>
                </div>
            </div>
            
            <!-- Заметки -->
            <div id="notes" class="tab-content">
                <h2><i class="fas fa-sticky-note"></i> Мои заметки</h2>
                <div class="content-grid">
                    <div class="card">
                        <h3><i class="fas fa-mountain"></i> Горная база</h3>
                        <p>Координаты: X: 120, Y: 72, Z: -340</p>
                        <p>Запасы: 32 алмаза, 64 железа, 128 угля</p>
                    </div>
                    <div class="card">
                        <h3><i class="fas fa-ship"></i> Корабль в океане</h3>
                        <p>Координаты: X: -540, Y: 62, Z: 780</p>
                        <p>Найдено: 5 сундуков, 3 спаунера скелетов</p>
                    </div>
                    <div class="card">
                        <h3><i class="fas fa-dungeon"></i> Подземная крепость</h3>
                        <p>Координаты: X: 230, Y: 24, Z: -650</p>
                        <p>Найдено: библиотека, портал в Энд</p>
                    </div>
                </div>
            </div>
            
            <!-- Новости -->
            <div id="news" class="tab-content">
                <h2><i class="fas fa-newspaper"></i> Последние новости Minecraft</h2>
                <div class="content-grid">
                    <div class="card">
                        <h3><i class="fas fa-cubes"></i> Обновление 1.20 вышло!</h3>
                        <p>Добавлены новые мобы, блоки и механизмы. Подробности на официальном сайте.</p>
                        <p><small>12 июня 2023</small></p>
                    </div>
                    <div class="card">
                        <h3><i class="fas fa-trophy"></i> Конкурс строителей</h3>
                        <p>Участвуйте в конкурсе на лучшую постройку! Призы: редкие скины и ключи к модам.</p>
                        <p><small>5 июня 2023</small></p>
                    </div>
                    <div class="card">
                        <h3><i class="fas fa-server"></i> Новый сервер SkyBlock</h3>
                        <p>Присоединяйтесь к нашему новому серверу SkyBlock с уникальными механиками и ивентами.</p>
                        <p><small>28 мая 2023</small></p>
                    </div>
                </div>
            </div>
            
            <!-- О нас -->
            <div id="about" class="tab-content">
                <h2><i class="fas fa-info-circle"></i> О нашем лаунчере</h2>
                <p>Добро пожаловать в улучшенный лаунчер Minecraft с уникальными функциями и удобным интерфейсом!</p>
                
                <h3><i class="fas fa-star"></i> Особенности:</h3>
                <ul style="margin: 15px 0 15px 30px; line-height: 1.8;">
                    <li>Управление всеми версиями Minecraft</li>
                    <li>Библиотека модов и сборок</li>
                    <li>Встроенный ассистент Cobalt</li>
                    <li>Инструменты для создания текстур и моделей</li>
                    <li>Система заметок и координат</li>
                </ul>
                
                <h3><i class="fas fa-cube"></i> Примеры блоков:</h3>
                <div style="margin: 15px 0;">
                    <div class="minecraft-block grass" title="Трава"></div>
                    <div class="minecraft-block dirt" title="Земля"></div>
                    <div class="minecraft-block stone" title="Камень"></div>
                    <div class="minecraft-block wood" title="Дерево"></div>
                    <div class="minecraft-block diamond" title="Алмаз"></div>
                    <div class="minecraft-block gold" title="Золото"></div>
                </div>
                
                <p>Версия лаунчера: 2.5.1</p>
                <p>© 2023 Minecraft Launcher Team. Все права защищены.</p>
            </div>
            
            <!-- Остальные вкладки -->
            <div id="logs" class="tab-content">
                <h2><i class="fas fa-clipboard-list"></i> Логи игры</h2>
                <p>Здесь будут отображаться последние логи запуска и игровые события.</p>
            </div>
            
            <div id="settings" class="tab-content">
                <h2><i class="fas fa-cog"></i> Настройки</h2>
                <p>Настройте параметры лаунчера и игры по вашему вкусу.</p>
            </div>
            
            <div id="tools" class="tab-content">
                <h2><i class="fas fa-tools"></i> Инструменты</h2>
                <p>Полезные инструменты для работы с Minecraft.</p>
            </div>
            
            <div id="cobalt" class="tab-content">
                <h2><i class="fas fa-robot"></i> Cobalt Ассистент</h2>
                <p>Ваш помощник в мире Minecraft. Задавайте вопросы и получайте советы.</p>
            </div>
            
            <div id="library" class="tab-content">
                <h2><i class="fas fa-book"></i> Библиотека</h2>
                <p>Ваши сохраненные миры, скины и текстуры.</p>
            </div>
            
            <div id="mods" class="tab-content">
                <h2><i class="fas fa-puzzle-piece"></i> Моды и сборки</h2>
                <p>Управляйте установленными модами и сборками.</p>
            </div>
            
            <div id="search" class="tab-content">
                <h2><i class="fas fa-search"></i> Поиск</h2>
                <p>Ищите моды, текстуры, серверы и игроков.</p>
            </div>
            
            <div id="projects" class="tab-content">
                <h2><i class="fas fa-folder"></i> Проекты</h2>
                <p>Ваши строительные проекты и чертежи.</p>
            </div>
        </div>
        
        <div class="footer">
            Minecraft Launcher v2.5.1 | © 2023 | Все права защищены
        </div>
    </div>

    <script>
        // Переключение вкладок
        document.querySelectorAll('.tab').forEach(tab => {
            tab.addEventListener('click', () => {
                // Удаляем активный класс у всех вкладок
                document.querySelectorAll('.tab').forEach(t => {
                    t.classList.remove('active');
                });
                
                // Добавляем активный класс текущей вкладке
                tab.classList.add('active');
                
                // Скрываем все содержимое вкладок
                document.querySelectorAll('.tab-content').forEach(content => {
                    content.classList.remove('active');
                });
                
                // Показываем выбранное содержимое
                const tabId = tab.getAttribute('data-tab');
                document.getElementById(tabId).classList.add('active');
            });
        });
        
        // Анимация прогресс-бара
        const progressFill = document.querySelector('.progress-fill');
        let progress = 65;
        
        setInterval(() => {
            progress = (progress + 1) % 100;
            progressFill.style.width = `${progress}%`;
            document.querySelector('.progress-label span:last-child').textContent = `${progress}%`;
        }, 2000);
        
        // Эффект при наведении на кнопки
        document.querySelectorAll('.btn').forEach(btn => {
            btn.addEventListener('mouseenter', () => {
                btn.style.transform = 'translateY(-3px)';
                btn.style.boxShadow = '0 6px 15px rgba(0, 0, 0, 0.4)';
            });
            
            btn.addEventListener('mouseleave', () => {
                btn.style.transform = 'translateY(0)';
                btn.style.boxShadow = '0 4px 10px rgba(0, 0, 0, 0.3)';
            });
        });
        
        // Кнопка "Играть"
        document.querySelector('.btn.play').addEventListener('click', function() {
            this.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Запуск...';
            this.disabled = true;
            
            setTimeout(() => {
                this.innerHTML = '<i class="fas fa-play"></i> Играть';
                this.disabled = false;
                alert('Minecraft запущен!');
            }, 3000);
        });
    </script>
</body>
</html>
