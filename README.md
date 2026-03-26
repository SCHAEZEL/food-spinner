# 🍳 今日吃什么转盘

让命运决定你的晚餐！一个简单有趣的随机选餐工具。

**🌐 在线地址**：https://schaezel.github.io/food-spinner/

**📂 GitHub**：https://github.com/SCHAEZEL/food-spinner

## 功能

- 🎡 **大转盘**：Canvas 绘制，点击即转
- 📝 **菜谱管理**：添加/编辑/删除菜品
- ⚖️ **权重系统**：热门菜品更高概率被转到
- 📊 **难度分类**：简单/中等/困难
- 📜 **做饭记录**：记录今天做了哪些菜
- 🔐 **Firebase 账号系统**：数据隔离，仅自己可见

## 快速开始

### 1. 创建 Firebase 项目

1. 访问 [Firebase Console](https://console.firebase.google.com/)
2. 创建新项目
3. 启用 **Authentication** → 启用 **Google 登录**
4. 启用 **Firestore Database** → 创建数据库（测试模式即可）
5. 在「项目设置」中获取你的 Firebase 配置

### 2. 配置 Firebase

当前已配置 `hippie-food-spinner` 项目。如需使用自己的 Firebase 项目，编辑 `index.html` 和 `docs/index.html` 中的 `firebaseConfig` 对象，替换为你的配置。

### 3. 部署

项目已托管在 GitHub Pages，地址见顶部链接。如需更新，编辑后推送到 GitHub 即可自动部署。

**GitHub Pages 访问地址：**
https://schaezel.github.io/food-spinner/

## 技术栈

- 单 HTML 文件（所有 CSS/JS 内联）
- Firebase v9 (CDN)
- HTML5 Canvas
- GitHub Pages

## 免费托管方案对比

| 方案 | 流量 | 私有仓库 | 自动部署 | 绑定信用卡 |
|------|------|---------|---------|-----------|
| **GitHub Pages** | 无限 | ❌ | ✅ | ❌ |
| **Vercel** | 100GB/月 | ✅ | ✅ | ⚠️ 需绑定 |
| **Cloudflare Pages** | 无限 | ✅ | ✅ | ❌ |
| **Netlify** | 100GB/月 | ✅ | ✅ | ⚠️ 需绑定 |

> 当前使用 **GitHub Pages**，免费无限流量，无需信用卡。

## 界面预览

- 🎨 深棕黑背景 + 橙/红橙配色
- 📱 移动端优先设计
- ✨ 弹跳动画 + 平滑旋转
