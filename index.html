<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>用户与内容管理系统</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #c5c1c9 0%, #747475 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            width: 100%;
            max-width: 900px;
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(to right, #ecebee, #b9a3cc);
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 28px;
            margin-bottom: 5px;
        }
        
        .header p {
            opacity: 0.8;
        }
        
        .content {
            padding: 30px;
        }
        
        .view {
            display: none;
        }
        
        .active {
            display: block;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #333;
        }
        
        input, textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border 0.3s;
        }
        
        input:focus, textarea:focus {
            border-color: #c4b2e9;
            outline: none;
        }
        
        button {
            background: linear-gradient(to right, #dacef3, #c1bbc7);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        
        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .btn-secondary {
            background: linear-gradient(to right, #8e9eab, #eef2f3);
            color: #333;
        }
        
        .btn-danger {
            background: linear-gradient(to right, #ebb1bf, #cec0be);
        }
        
        .btn-success {
            background: linear-gradient(to right, #00b09b, #ddecc4);
        }
        
        .btn-group {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }
        
        .btn-group button {
            flex: 1;
        }
        
        .tabs {
            display: flex;
            margin-bottom: 20px;
            border-bottom: 1px solid #ddd;
        }
        
        .tab {
            padding: 10px 20px;
            cursor: pointer;
            font-weight: 600;
            color: #666;
            transition: color 0.3s;
        }
        
        .tab.active {
            color: #dad1ec;
            border-bottom: 3px solid #d6cfe4;
        }
        
        .content-list {
            margin-top: 20px;
        }
        
        .content-item {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
            border-left: 4px solid #ab9ec4;
        }
        
        .content-item h3 {
            margin-bottom: 10px;
            color: #333;
        }
        
        .content-item p {
            color: #666;
            margin-bottom: 10px;
        }
        
        .content-item .actions {
            display: flex;
            gap: 10px;
        }
        
        .message {
            padding: 10px;
            border-radius: 8px;
            margin-bottom: 20px;
            text-align: center;
            font-weight: 600;
        }
        
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        
        .user-info {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f0f0f0;
            border-radius: 8px;
        }
        
        .logout-btn {
            background: linear-gradient(to right, #ff416c, #ff4b2b);
        }
        
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }
            
            .content {
                padding: 20px;
            }
            
            .btn-group {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>用户与内容管理系统</h1>
            <p>登录、注册并管理您的内容</p>
        </div>
        
        <div class="content">
            <!-- 登录/注册视图 -->
            <div id="auth-view" class="view active">
                <div class="tabs">
                    <div class="tab active" onclick="switchTab('login')">登录</div>
                    <div class="tab" onclick="switchTab('register')">注册</div>
                </div>
                
                <div id="login-form" class="auth-form">
                    <div class="form-group">
                        <label for="login-username">用户名</label>
                        <input type="text" id="login-username" placeholder="请输入用户名">
                    </div>
                    <div class="form-group">
                        <label for="login-password">密码</label>
                        <input type="password" id="login-password" placeholder="请输入密码">
                    </div>
                    <button onclick="login()">登录</button>
                </div>
                
                <div id="register-form" class="auth-form" style="display: none;">
                    <div class="form-group">
                        <label for="register-username">用户名</label>
                        <input type="text" id="register-username" placeholder="请输入用户名">
                    </div>
                    <div class="form-group">
                        <label for="register-password">密码</label>
                        <input type="password" id="register-password" placeholder="请输入密码">
                    </div>
                    <div class="form-group">
                        <label for="register-email">邮箱</label>
                        <input type="email" id="register-email" placeholder="请输入邮箱">
                    </div>
                    <button onclick="register()">注册</button>
                </div>
            </div>
            
            <!-- 内容管理视图 -->
            <div id="content-view" class="view">
                <div class="user-info">
                    <div>欢迎, <span id="current-user">用户</span></div>
                    <button class="logout-btn" onclick="logout()">退出登录</button>
                </div>
                
                <div class="tabs">
                    <div class="tab active" onclick="switchContentTab('list')">内容列表</div>
                    <div class="tab" onclick="switchContentTab('add')">添加内容</div>
                </div>
                
                <div id="content-list" class="content-tab">
                    <div id="content-items" class="content-list">
                        <!-- 内容将动态加载到这里 -->
                    </div>
                </div>
                
                <div id="content-add" class="content-tab" style="display: none;">
                    <div class="form-group">
                        <label for="content-title">标题</label>
                        <input type="text" id="content-title" placeholder="请输入标题">
                    </div>
                    <div class="form-group">
                        <label for="content-body">内容</label>
                        <textarea id="content-body" rows="5" placeholder="请输入内容"></textarea>
                    </div>
                    <div class="btn-group">
                        <button onclick="addContent()">添加内容</button>
                        <button class="btn-secondary" onclick="switchContentTab('list')">返回列表</button>
                    </div>
                </div>
                
                <div id="content-edit" class="content-tab" style="display: none;">
                    <div class="form-group">
                        <label for="edit-title">标题</label>
                        <input type="text" id="edit-title" placeholder="请输入标题">
                    </div>
                    <div class="form-group">
                        <label for="edit-body">内容</label>
                        <textarea id="edit-body" rows="5" placeholder="请输入内容"></textarea>
                    </div>
                    <div class="btn-group">
                        <button class="btn-success" onclick="updateContent()">更新内容</button>
                        <button class="btn-secondary" onclick="switchContentTab('list')">取消</button>
                    </div>
                </div>
            </div>
            
            <div id="message" class="message" style="display: none;"></div>
        </div>
    </div>

    <script>
        // 初始化数据
        let users = JSON.parse(localStorage.getItem('users')) || [];
        let contents = JSON.parse(localStorage.getItem('contents')) || [];
        let currentUser = null;
        let editingContentId = null;
        
        // 检查是否已登录
        window.onload = function() {
            const savedUser = localStorage.getItem('currentUser');
            if (savedUser) {
                currentUser = JSON.parse(savedUser);
                showContentView();
            }
        };
        
        // 切换登录/注册标签
        function switchTab(tab) {
            document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
            document.getElementById('login-form').style.display = 'none';
            document.getElementById('register-form').style.display = 'none';
            
            if (tab === 'login') {
                document.querySelector('.tab:first-child').classList.add('active');
                document.getElementById('login-form').style.display = 'block';
            } else {
                document.querySelector('.tab:last-child').classList.add('active');
                document.getElementById('register-form').style.display = 'block';
            }
        }
        
        // 切换内容管理标签
        function switchContentTab(tab) {
            document.querySelectorAll('.content-tab').forEach(t => t.style.display = 'none');
            document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
            
            if (tab === 'list') {
                document.querySelector('.tab:first-child').classList.add('active');
                document.getElementById('content-list').style.display = 'block';
                loadContentList();
            } else if (tab === 'add') {
                document.querySelector('.tab:last-child').classList.add('active');
                document.getElementById('content-add').style.display = 'block';
                document.getElementById('content-title').value = '';
                document.getElementById('content-body').value = '';
            } else if (tab === 'edit') {
                document.getElementById('content-edit').style.display = 'block';
            }
        }
        
        // 显示消息
        function showMessage(message, type) {
            const messageEl = document.getElementById('message');
            messageEl.textContent = message;
            messageEl.className = `message ${type}`;
            messageEl.style.display = 'block';
            
            setTimeout(() => {
                messageEl.style.display = 'none';
            }, 3000);
        }
        
        // 注册功能
        function register() {
            const username = document.getElementById('register-username').value;
            const password = document.getElementById('register-password').value;
            const email = document.getElementById('register-email').value;
            
            if (!username || !password || !email) {
                showMessage('请填写所有字段', 'error');
                return;
            }
            
            if (users.find(user => user.username === username)) {
                showMessage('用户名已存在', 'error');
                return;
            }
            
            const newUser = {
                id: Date.now(),
                username,
                password,
                email
            };
            
            users.push(newUser);
            localStorage.setItem('users', JSON.stringify(users));
            
            showMessage('注册成功，请登录', 'success');
            switchTab('login');
            document.getElementById('register-username').value = '';
            document.getElementById('register-password').value = '';
            document.getElementById('register-email').value = '';
        }
        
        // 登录功能
        function login() {
            const username = document.getElementById('login-username').value;
            const password = document.getElementById('login-password').value;
            
            if (!username || !password) {
                showMessage('请填写用户名和密码', 'error');
                return;
            }
            
            const user = users.find(u => u.username === username && u.password === password);
            
            if (user) {
                currentUser = user;
                localStorage.setItem('currentUser', JSON.stringify(currentUser));
                showContentView();
                showMessage('登录成功', 'success');
            } else {
                showMessage('用户名或密码错误', 'error');
            }
        }
        
        // 显示内容管理视图
        function showContentView() {
            document.getElementById('auth-view').classList.remove('active');
            document.getElementById('content-view').classList.add('active');
            document.getElementById('current-user').textContent = currentUser.username;
            loadContentList();
        }
        
        // 退出登录
        function logout() {
            currentUser = null;
            localStorage.removeItem('currentUser');
            document.getElementById('content-view').classList.remove('active');
            document.getElementById('auth-view').classList.add('active');
            showMessage('已退出登录', 'success');
        }
        
        // 加载内容列表
        function loadContentList() {
            const contentItemsEl = document.getElementById('content-items');
            const userContents = contents.filter(content => content.userId === currentUser.id);
            
            if (userContents.length === 0) {
                contentItemsEl.innerHTML = '<p style="text-align: center; color: #666;">暂无内容，点击"添加内容"开始创建</p>';
                return;
            }
            
            contentItemsEl.innerHTML = userContents.map(content => `
                <div class="content-item">
                    <h3>${content.title}</h3>
                    <p>${content.body}</p>
                    <div class="actions">
                        <button class="btn-success" onclick="editContent(${content.id})">编辑</button>
                        <button class="btn-danger" onclick="deleteContent(${content.id})">删除</button>
                    </div>
                </div>
            `).join('');
        }
        
        // 添加内容
        function addContent() {
            const title = document.getElementById('content-title').value;
            const body = document.getElementById('content-body').value;
            
            if (!title || !body) {
                showMessage('请填写标题和内容', 'error');
                return;
            }
            
            const newContent = {
                id: Date.now(),
                userId: currentUser.id,
                title,
                body,
                createdAt: new Date().toLocaleString()
            };
            
            contents.push(newContent);
            localStorage.setItem('contents', JSON.stringify(contents));
            
            showMessage('内容添加成功', 'success');
            switchContentTab('list');
        }
        
        // 编辑内容
        function editContent(id) {
            const content = contents.find(c => c.id === id);
            if (content) {
                editingContentId = id;
                document.getElementById('edit-title').value = content.title;
                document.getElementById('edit-body').value = content.body;
                switchContentTab('edit');
            }
        }
        
        // 更新内容
        function updateContent() {
            const title = document.getElementById('edit-title').value;
            const body = document.getElementById('edit-body').value;
            
            if (!title || !body) {
                showMessage('请填写标题和内容', 'error');
                return;
            }
            
            const contentIndex = contents.findIndex(c => c.id === editingContentId);
            if (contentIndex !== -1) {
                contents[contentIndex].title = title;
                contents[contentIndex].body = body;
                localStorage.setItem('contents', JSON.stringify(contents));
                
                showMessage('内容更新成功', 'success');
                switchContentTab('list');
                editingContentId = null;
            }
        }
        
        // 删除内容
        function deleteContent(id) {
            if (confirm('确定要删除此内容吗？')) {
                contents = contents.filter(c => c.id !== id);
                localStorage.setItem('contents', JSON.stringify(contents));
                loadContentList();
                showMessage('内容删除成功', 'success');
            }
        }
    </script>
</body>
</html>
