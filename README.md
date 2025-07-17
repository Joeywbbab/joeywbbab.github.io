# Joey的个人网站

这是一个使用纯HTML、CSS和JavaScript构建的个人网站，可以免费部署到GitHub Pages。

## 网站特色

- 📝 文章展示
- 🚀 产品展示
- 💼 作品集
- 📱 响应式设计
- 🎨 现代化界面

## 文件结构

```
├── index.html          # 主页
├── style.css           # 样式文件
├── articles/           # 文章目录
│   ├── article1.html
│   └── article2.html
└── README.md          # 说明文件
```

## 部署到GitHub Pages

### 1. 创建GitHub仓库

1. 登录GitHub
2. 创建一个新仓库，命名为 `username.github.io`（将username替换为你的GitHub用户名）
3. 选择Public仓库

### 2. 上传网站文件

1. 将所有文件上传到仓库根目录
2. 或者使用Git命令：

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### 3. 启用GitHub Pages

1. 进入仓库的Settings页面
2. 找到Pages选项
3. 在Source下选择"Deploy from a branch"
4. 选择"main"分支
5. 点击Save

### 4. 访问网站

几分钟后，你的网站就会在 `https://username.github.io` 上线。

## 自定义内容

### 修改个人信息

1. 编辑 `index.html` 中的个人介绍
2. 更新联系方式
3. 替换网站标题

### 添加新文章

1. 在 `articles/` 目录下创建新的HTML文件
2. 参考 `article1.html` 的格式
3. 在 `index.html` 中添加文章链接

### 自定义样式

编辑 `style.css` 文件来修改：
- 颜色主题
- 字体样式
- 布局设计
- 响应式断点

## 技术栈

- HTML5
- CSS3
- 原生JavaScript
- 响应式设计

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT License - 可自由使用和修改