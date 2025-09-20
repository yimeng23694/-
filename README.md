🧪 Chromium CI Snapshot Portal
## 简介
>
>从2025年9月20号开始记录每个好用的软件。<br>
## 好用的下载中心
## 网站跳转链接如下
>
>
### 一、Chromium
**下载地址** <https://commondatastorage.googleapis.com/chromium-browser-snapshots/index.html?prefix=Win_x64/>
## Chromium项目的自动化构建通道，获取由官方CI服务器编译的每一次二进制文件。

## 二、RAR 解锁器
**RAR Unlocker** <https://ramensoftware.com/rar-unlocker>
## 删除 RAR 档案锁定属性，让你修改锁定的文档。

## 其他下站点请点击展开查看其它
<details>
<summary>展开</summary>
### 5.40
**32 位：** <http://www.win-rar.com/fileadmin/winrar-versions/sc20160819/wrr/wrar540sc.exe>  
**64 位：** <http://www.win-rar.com/fileadmin/winrar-versions/sc20160819/wrr/winrar-x64-540sc.exe>  
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechStore - 科技软件商店</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #0cf;
            --secondary: #a64dff;
            --dark-bg: #0a0a16;
            --darker-bg: #050510;
            --card-bg: #13132b;
            --text: #ffffff;
            --text-secondary: #b8b8d2;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, var(--darker-bg) 0%, var(--dark-bg) 100%);
            color: var(--text);
            min-height: 100vh;
            padding-bottom: 2rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }
        
        header {
            padding: 1.5rem 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            background: rgba(10, 10, 22, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .search-bar {
            display: flex;
            align-items: center;
            background: rgba(255, 255, 255, 0.08);
            border-radius: 50px;
            padding: 0.6rem 1.2rem;
            width: 400px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }
        
        .search-bar:focus-within {
            border-color: var(--primary);
            box-shadow: 0 0 15px rgba(0, 204, 255, 0.3);
        }
        
        .search-bar input {
            background: transparent;
            border: none;
            color: var(--text);
            width: 100%;
            font-size: 1rem;
            padding: 0.2rem 0.5rem;
            outline: none;
        }
        
        .user-actions {
            display: flex;
            gap: 1.2rem;
            align-items: center;
        }
        
        .btn {
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            border: none;
            padding: 0.6rem 1.2rem;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 204, 255, 0.4);
        }
        
        .categories {
            display: flex;
            gap: 1rem;
            margin: 2rem 0;
            overflow-x: auto;
            padding-bottom: 0.5rem;
        }
        
        .categories::-webkit-scrollbar {
            height: 4px;
        }
        
        .categories::-webkit-scrollbar-thumb {
            background: var(--primary);
            border-radius: 4px;
        }
        
        .category {
            background: var(--card-bg);
            padding: 0.6rem 1.5rem;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            white-space: nowrap;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .category:hover, .category.active {
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
        }
        
        .view-options {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
        }
        
        .view-toggle {
            display: flex;
            gap: 0.5rem;
            background: var(--card-bg);
            padding: 0.4rem;
            border-radius: 8px;
        }
        
        .view-toggle button {
            background: transparent;
            border: none;
            color: var(--text-secondary);
            padding: 0.5rem;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .view-toggle button.active {
            background: rgba(0, 204, 255, 0.2);
            color: var(--primary);
        }
        
        .apps-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        
        .app-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
        }
        
        .app-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            border-color: var(--primary);
        }
        
        .app-image {
            height: 160px;
            background: linear-gradient(45deg, #2b2b4a, #1a1a33);
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }
        
        .app-image i {
            font-size: 3.5rem;
            color: var(--primary);
            z-index: 2;
        }
        
        .app-image::after {
            content: '';
            position: absolute;
            width: 150%;
            height: 50%;
            background: linear-gradient(45deg, var(--primary), transparent);
            transform: rotate(-15deg) translateY(100%);
            animation: shine 3s infinite;
        }
        
        @keyframes shine {
            0% { transform: rotate(-15deg) translateY(100%); }
            20% { transform: rotate(-15deg) translateY(-50%); }
            100% { transform: rotate(-15deg) translateY(-50%); }
        }
        
        .app-info {
            padding: 1.2rem;
        }
        
        .app-name {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .app-description {
            color: var(--text-secondary);
            font-size: 0.9rem;
            margin-bottom: 1rem;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        .app-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .app-rating {
            display: flex;
            align-items: center;
            gap: 0.3rem;
            color: gold;
        }
        
        .app-size {
            color: var(--text-secondary);
            font-size: 0.9rem;
        }
        
        .app-card .btn {
            padding: 0.5rem 1rem;
            font-size: 0.9rem;
            width: 100%;
            text-align: center;
            margin-top: 1rem;
        }
        
        .apps-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1rem;
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .apps-table th, .apps-table td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .apps-table th {
            background: rgba(0, 0, 0, 0.2);
            font-weight: 600;
            color: var(--primary);
        }
        
        .apps-table tr:last-child td {
            border-bottom: none;
        }
        
        .apps-table tr:hover {
            background: rgba(255, 255, 255, 0.05);
        }
        
        .table-app-name {
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
        
        .table-app-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .table-app-icon i {
            font-size: 1.2rem;
        }
        
        .hidden {
            display: none;
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 1rem;
            }
            
            .search-bar {
                width: 100%;
            }
            
            .apps-grid {
                grid-template-columns: 1fr;
            }
            
            .apps-table {
                display: block;
                overflow-x: auto;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-store"></i>
                    <span>TechStore</span>
                </div>
                
                <div class="search-bar">
                    <i class="fas fa-search"></i>
                    <input type="text" placeholder="搜索应用、游戏、工具...">
                </div>
                
                <div class="user-actions">
                    <button class="btn"><i class="fas fa-user"></i> 登录</button>
                </div>
            </div>
        </div>
    </header>
    
    <main class="container">
        <div class="categories">
            <div class="category active">全部应用</div>
            <div class="category">游戏</div>
            <div class="category">工具</div>
            <div class="category">社交</div>
            <div class="category">娱乐</div>
            <div class="category">教育</div>
            <div class="category">生产力</div>
            <div class="category">创意</div>
            <div class="category">健康</div>
            <div class="category">新闻</div>
        </div>
        
        <div class="view-options">
            <h2>热门应用</h2>
            
            <div class="view-toggle">
                <button id="grid-view" class="active"><i class="fas fa-th"></i></button>
                <button id="list-view"><i class="fas fa-list"></i></button>
            </div>
        </div>
        
        <div id="grid-container">
            <div class="apps-grid">
                <div class="app-card">
                    <div class="app-image">
                        <i class="fab fa-chrome"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">Web Explorer</h3>
                        <p class="app-description">高速、安全的网页浏览器，提供无缝上网体验</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.8</span>
                            </div>
                            <div class="app-size">82 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
                
                <div class="app-card">
                    <div class="app-image">
                        <i class="fas fa-photo-video"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">MediaPro</h3>
                        <p class="app-description">高级视频和图片编辑工具，支持多种格式</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.6</span>
                            </div>
                            <div class="app-size">142 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
                
                <div class="app-card">
                    <div class="app-image">
                        <i class="fas fa-gamepad"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">Cyber Quest</h3>
                        <p class="app-description">沉浸式动作冒险游戏，探索未来世界</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.9</span>
                            </div>
                            <div class="app-size">324 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
                
                <div class="app-card">
                    <div class="app-image">
                        <i class="fas fa-music"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">AudioWave</h3>
                        <p class="app-description">高品质音乐播放器，支持所有主流格式</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.7</span>
                            </div>
                            <div class="app-size">58 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
                
                <div class="app-card">
                    <div class="app-image">
                        <i class="fas fa-cloud"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">CloudSync</h3>
                        <p class="app-description">安全云存储解决方案，跨设备文件同步</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.5</span>
                            </div>
                            <div class="app-size">76 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
                
                <div class="app-card">
                    <div class="app-image">
                        <i class="fas fa-lock"></i>
                    </div>
                    <div class="app-info">
                        <h3 class="app-name">SecureVault</h3>
                        <p class="app-description">高级密码管理器，保护您的数字身份</p>
                        <div class="app-meta">
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.8</span>
                            </div>
                            <div class="app-size">43 MB</div>
                        </div>
                        <button class="btn">安装</button>
                    </div>
                </div>
            </div>
        </div>
        
        <div id="list-container" class="hidden">
            <table class="apps-table">
                <thead>
                    <tr>
                        <th>应用名称</th>
                        <th>类别</th>
                        <th>评分</th>
                        <th>大小</th>
                        <th>操作</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fab fa-chrome"></i>
                                </div>
                                <div>
                                    <div>Web Explorer</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">浏览器</div>
                                </div>
                            </div>
                        </td>
                        <td>工具</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.8</span>
                            </div>
                        </td>
                        <td>82 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                    
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fas fa-photo-video"></i>
                                </div>
                                <div>
                                    <div>MediaPro</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">媒体编辑</div>
                                </div>
                            </div>
                        </td>
                        <td>创意</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.6</span>
                            </div>
                        </td>
                        <td>142 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                    
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fas fa-gamepad"></i>
                                </div>
                                <div>
                                    <div>Cyber Quest</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">动作游戏</div>
                                </div>
                            </div>
                        </td>
                        <td>游戏</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.9</span>
                            </div>
                        </td>
                        <td>324 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                    
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fas fa-music"></i>
                                </div>
                                <div>
                                    <div>AudioWave</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">音乐播放器</div>
                                </div>
                            </div>
                        </td>
                        <td>娱乐</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.7</span>
                            </div>
                        </td>
                        <td>58 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                    
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fas fa-cloud"></i>
                                </div>
                                <div>
                                    <div>CloudSync</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">云存储</div>
                                </div>
                            </div>
                        </td>
                        <td>工具</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.5</span>
                            </div>
                        <td>76 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                    
                    <tr>
                        <td>
                            <div class="table-app-name">
                                <div class="table-app-icon">
                                    <i class="fas fa-lock"></i>
                                </div>
                                <div>
                                    <div>SecureVault</div>
                                    <div style="color: var(--text-secondary); font-size: 0.9rem;">安全工具</div>
                                </div>
                            </div>
                        </td>
                        <td>工具</td>
                        <td>
                            <div class="app-rating">
                                <i class="fas fa-star"></i>
                                <span>4.8</span>
                            </div>
                        </td>
                        <td>43 MB</td>
                        <td><button class="btn">安装</button></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </main>

    <script>
        // 视图切换功能
        const gridViewBtn = document.getElementById('grid-view');
        const listViewBtn = document.getElementById('list-view');
        const gridContainer = document.getElementById('grid-container');
        const listContainer = document.getElementById('list-container');
        
        gridViewBtn.addEventListener('click', () => {
            gridViewBtn.classList.add('active');
            listViewBtn.classList.remove('active');
            gridContainer.classList.remove('hidden');
            listContainer.classList.add('hidden');
        });
        
        listViewBtn.addEventListener('click', () => {
            listViewBtn.classList.add('active');
            gridViewBtn.classList.remove('active');
            listContainer.classList.remove('hidden');
            gridContainer.classList.add('hidden');
        });
        
        // 类别选择功能
        const categories = document.querySelectorAll('.category');
        categories.forEach(category => {
            category.addEventListener('click', () => {
                categories.forEach(c => c.classList.remove('active'));
                category.classList.add('active');
            });
        });
        
        // 搜索功能
        const searchInput = document.querySelector('.search-bar input');
        searchInput.addEventListener('focus', () => {
            document.querySelector('.search-bar').style.boxShadow = '0 0 15px rgba(0, 204, 255, 0.3)';
        });
        
        searchInput.addEventListener('blur', () => {
            document.querySelector('.search-bar').style.boxShadow = 'none';
        });
    </script>
</body>
</html>
