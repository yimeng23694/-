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
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/styles/github-dark.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/marked/4.3.0/marked.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/highlight.min.js"></script>
    <style>
        :root {
            --primary: #0cf;
            --secondary: #a64dff;
            --dark-bg: #0a0a16;
            --darker-bg: #050510;
            --card-bg: #13132b;
            --text: #ffffff;
            --text-secondary: #b8b8d2;
            --sidebar-width: 320px;
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
            display: flex;
            flex-direction: column;
        }
        
        .container {
            display: flex;
            flex: 1;
            overflow: hidden;
        }
        
        header {
            padding: 1.2rem 2rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            background: rgba(10, 10, 22, 0.95);
            backdrop-filter: blur(10px);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            font-size: 1.5rem;
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
        
        .btn-outline {
            background: transparent;
            border: 1px solid var(--primary);
            color: var(--primary);
        }
        
        .btn-outline:hover {
            background: rgba(0, 204, 255, 0.1);
        }
        
        /* 侧边栏样式 */
        .sidebar {
            width: var(--sidebar-width);
            background: var(--darker-bg);
            border-right: 1px solid rgba(255, 255, 255, 0.1);
            padding: 1.5rem;
            overflow-y: auto;
            display: flex;
            flex-direction: column;
        }
        
        .categories {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
            margin-bottom: 1.5rem;
        }
        
        .category {
            background: var(--card-bg);
            padding: 0.8rem 1.2rem;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
        
        .category:hover, .category.active {
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
        }
        
        .app-list {
            flex: 1;
            overflow-y: auto;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        
        .app-item {
            background: var(--card-bg);
            padding: 1rem;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .app-item:hover {
            border-color: var(--primary);
            transform: translateX(5px);
        }
        
        .app-item.active {
            border-color: var(--primary);
            background: rgba(0, 204, 255, 0.1);
        }
        
        .app-item-header {
            display: flex;
            align-items: center;
            gap: 0.8rem;
            margin-bottom: 0.8rem;
        }
        
        .app-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }
        
        .app-title {
            font-weight: 600;
            font-size: 1.1rem;
        }
        
        .app-description {
            color: var(--text-secondary);
            font-size: 0.9rem;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
            margin-bottom: 0.8rem;
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
        
        /* 主内容区域样式 */
        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }
        
        .app-detail {
            flex: 1;
            padding: 2rem;
            overflow-y: auto;
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }
        
        .app-hero {
            display: flex;
            gap: 2rem;
            margin-bottom: 1.5rem;
        }
        
        .app-hero-image {
            width: 120px;
            height: 120px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
        }
        
        .app-hero-info {
            flex: 1;
        }
        
        .app-hero-title {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .app-hero-description {
            color: var(--text-secondary);
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
            max-width: 600px;
        }
        
        .app-hero-actions {
            display: flex;
            gap: 1rem;
        }
        
        .app-detail-section {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 1.5rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .section-title {
            font-size: 1.3rem;
            margin-bottom: 1.2rem;
            padding-bottom: 0.5rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
        
        /* Markdown 内容样式 */
        .markdown-content {
            line-height: 1.6;
        }
        
        .markdown-content h1,
        .markdown-content h2,
        .markdown-content h3 {
            margin: 1.5rem 0 1rem;
            color: var(--primary);
        }
        
        .markdown-content h1 {
            font-size: 1.8rem;
            border-bottom: 2px solid var(--primary);
            padding-bottom: 0.5rem;
        }
        
        .markdown-content h2 {
            font-size: 1.5rem;
        }
        
        .markdown-content h3 {
            font-size: 1.3rem;
        }
        
        .markdown-content p {
            margin-bottom: 1rem;
        }
        
        .markdown-content ul, 
        .markdown-content ol {
            margin-left: 1.5rem;
            margin-bottom: 1rem;
        }
        
        .markdown-content li {
            margin-bottom: 0.5rem;
        }
        
        .markdown-content code {
            background: rgba(255, 255, 255, 0.1);
            padding: 0.2rem 0.4rem;
            border-radius: 4px;
            font-family: 'Fira Code', monospace;
            font-size: 0.9rem;
        }
        
        .markdown-content pre {
            background: var(--darker-bg);
            padding: 1rem;
            border-radius: 8px;
            overflow-x: auto;
            margin-bottom: 1rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .markdown-content pre code {
            background: transparent;
            padding: 0;
        }
        
        .markdown-content blockquote {
            border-left: 4px solid var(--primary);
            padding-left: 1rem;
            margin-left: 0;
            color: var(--text-secondary);
        }
        
        .markdown-content table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 1rem;
        }
        
        .markdown-content th, 
        .markdown-content td {
            padding: 0.75rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .markdown-content th {
            background: rgba(0, 0, 0, 0.2);
        }
        
        .markdown-content a {
            color: var(--primary);
            text-decoration: none;
        }
        
        .markdown-content a:hover {
            text-decoration: underline;
        }
        
        /* 响应式设计 */
        @media (max-width: 900px) {
            .container {
                flex-direction: column;
            }
            
            .sidebar {
                width: 100%;
                border-right: none;
                border-bottom: 1px solid rgba(255, 255, 255, 0.1);
                max-height: 40vh;
            }
            
            .app-hero {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            
            .search-bar {
                width: 100%;
                max-width: 300px;
            }
        }
        
        /* 滚动条样式 */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: rgba(255, 255, 255, 0.05);
        }
        
        ::-webkit-scrollbar-thumb {
            background: var(--primary);
            border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: var(--secondary);
        }
    </style>
</head>
<body>
    <header>
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
    </header>
    
    <div class="container">
        <div class="sidebar">
            <div class="categories">
                <div class="category active">
                    <i class="fas fa-th"></i>
                    <span>全部应用</span>
                </div>
                <div class="category">
                    <i class="fas fa-gamepad"></i>
                    <span>游戏</span>
                </div>
                <div class="category">
                    <i class="fas fa-tools"></i>
                    <span>工具</span>
                </div>
                <div class="category">
                    <i class="fas fa-comments"></i>
                    <span>社交</span>
                </div>
                <div class="category">
                    <i class="fas fa-music"></i>
                    <span>娱乐</span>
                </div>
            </div>
            
            <div class="app-list">
                <div class="app-item active">
                    <div class="app-item-header">
                        <div class="app-icon">
                            <i class="fab fa-chrome"></i>
                        </div>
                        <div class="app-title">Web Explorer</div>
                    </div>
                    <div class="app-description">高速、安全的网页浏览器，提供无缝上网体验</div>
                    <div class="app-meta">
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <span>4.8</span>
                        </div>
                        <div class="app-size">82 MB</div>
                    </div>
                </div>
                
                <div class="app-item">
                    <div class="app-item-header">
                        <div class="app-icon">
                            <i class="fas fa-photo-video"></i>
                        </div>
                        <div class="app-title">MediaPro</div>
                    </div>
                    <div class="app-description">高级视频和图片编辑工具，支持多种格式</div>
                    <div class="app-meta">
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <span>4.6</span>
                        </div>
                        <div class="app-size">142 MB</div>
                    </div>
                </div>
                
                <div class="app-item">
                    <div class="app-item-header">
                        <div class="app-icon">
                            <i class="fas fa-gamepad"></i>
                        </div>
                        <div class="app-title">Cyber Quest</div>
                    </div>
                    <div class="app-description">沉浸式动作冒险游戏，探索未来世界</div>
                    <div class="app-meta">
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <span>4.9</span>
                        </div>
                        <div class="app-size">324 MB</div>
                    </div>
                </div>
                
                <div class="app-item">
                    <div class="app-item-header">
                        <div class="app-icon">
                            <i class="fas fa-music"></i>
                        </div>
                        <div class="app-title">AudioWave</div>
                    </div>
                    <div class="app-description">高品质音乐播放器，支持所有主流格式</div>
                    <div class="app-meta">
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <span>4.7</span>
                        </div>
                        <div class="app-size">58 MB</div>
                    </div>
                </div>
                
                <div class="app-item">
                    <div class="app-item-header">
                        <div class="app-icon">
                            <i class="fas fa-cloud"></i>
                        </div>
                        <div class="app-title">CloudSync</div>
                    </div>
                    <div class="app-description">安全云存储解决方案，跨设备文件同步</div>
                    <div class="app-meta">
                        <div class="app-rating">
                            <i class="fas fa-star"></i>
                            <span>4.5</span>
                        </div>
                        <div class="app-size">76 MB</div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="main-content">
            <div class="app-detail">
                <div class="app-hero">
                    <div class="app-hero-image">
                        <i class="fab fa-chrome"></i>
                    </div>
                    <div class="app-hero-info">
                        <h1 class="app-hero-title">Web Explorer</h1>
                        <p class="app-hero-description">高速、安全的网页浏览器，提供无缝上网体验。基于最新浏览器引擎打造，支持所有现代Web标准。</p>
                        <div class="app-hero-actions">
                            <button class="btn"><i class="fas fa-download"></i> 安装应用</button>
                            <button class="btn btn-outline"><i class="fas fa-star"></i> 添加到收藏</button>
                        </div>
                    </div>
                </div>
                
                <div class="app-detail-section">
                    <h2 class="section-title">
                        <i class="fas fa-file-alt"></i>
                        <span>应用说明</span>
                    </h2>
                    <div id="readme-content" class="markdown-content">
                        <!-- Markdown内容将通过JavaScript动态渲染 -->
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // 配置marked和语法高亮
        marked.setOptions({
            highlight: function(code, lang) {
                if (lang && hljs.getLanguage(lang)) {
                    return hljs.highlight(code, { language: lang }).value;
                }
                return hljs.highlightAuto(code).value;
            }
        });
        
        // 示例Markdown内容（模拟README.md）
        const markdownContent = `# Web Explorer 浏览器

## 简介
Web Explorer是一款基于Chromium内核开发的高速、安全网页浏览器。它提供了现代化的用户界面和无缝的上网体验，支持所有最新的Web标准。

## 功能特性

### 极速浏览
- 采用最新的浏览器引擎，页面加载速度提升40%
- 智能预加载技术，预测您将要访问的页面
- 硬件加速渲染，流畅播放4K视频

### 隐私保护
- 增强型跟踪保护，阻止广告商跟踪您的在线活动
- 内置VPN功能，加密您的网络连接
- 隐私浏览模式，不留任何历史记录

### 个性化体验
- 可自定义的新标签页
- 丰富的主题和扩展库
- 智能书签和密码管理

## 系统要求

| 操作系统 | 最低版本 | 推荐版本 |
|----------|----------|----------|
| Windows | 10 | 11 |
| macOS | 10.14 | 12.0 |
| Linux | Ubuntu 18.04 | Ubuntu 20.04 |

## 安装指南

### Windows安装
\`\`\`bash
# 下载安装程序
winget install WebExplorer

# 或者使用 Chocolatey
choco install webexplorer
\`\`\`

### macOS安装
\`\`\`bash
# 使用 Homebrew
brew install --cask web-explorer
\`\`\`

### Linux安装
\`\`\`bash
# Ubuntu/Debian
sudo apt install web-explorer

# Fedora
sudo dnf install web-explorer
\`\`\`

## 使用说明

1. **启动浏览器**：安装完成后，从应用程序菜单启动Web Explorer
2. **初始设置**：首次启动时会引导您进行基本设置
3. **导入数据**：可以从其他浏览器导入书签和设置
4. **开始浏览**：在地址栏输入网址或使用搜索框开始浏览

## 常见问题

### 如何启用硬件加速？
转到**设置** > **系统** > **启用硬件加速**（需要重启浏览器）

### 如何安装扩展？
1. 点击菜单按钮选择**扩展**
2. 访问Web Explorer扩展商店
3. 搜索并安装您需要的扩展

## 技术支持

如果您遇到任何问题，请通过以下方式联系我们：

- 官方论坛: [https://forum.webexplorer.com](https://forum.webexplorer.com)
- 电子邮件: support@webexplorer.com
- 文档: [https://docs.webexplorer.com](https://docs.webexplorer.com)

## 版本历史

### v2.1.0 (2023-06-15)
- 新增标签页分组功能
- 改进密码管理器
- 修复安全漏洞

### v2.0.0 (2023-03-10)
- 全新UI设计
- 内置VPN功能
- 性能优化

## 开源许可

Web Explorer基于开源项目构建，遵循MIT许可证。详情请查看[LICENSE](https://github.com/webexplorer/browser/blob/main/LICENSE)文件。
`;
        
        // 渲染Markdown内容
        document.getElementById('readme-content').innerHTML = marked.parse(markdownContent);
        
        // 应用列表交互
        const appItems = document.querySelectorAll('.app-item');
        appItems.forEach(item => {
            item.addEventListener('click', () => {
                appItems.forEach(i => i.classList.remove('active'));
                item.classList.add('active');
                
                // 这里可以加载对应应用的README内容
                // 目前仅做示例，所以只显示同一个README
                document.getElementById('readme-content').innerHTML = marked.parse(markdownContent);
            });
        });
        
        // 分类交互
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
