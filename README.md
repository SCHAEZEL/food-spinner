# 🍳 今日吃什么转盘

让命运决定你的晚餐！一个简单有趣的随机选餐工具。

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

编辑 `index.html` 和 `docs/index.html`，找到这行注释：

```javascript
// TODO: 填入你的 Firebase 配置
```

将占位符替换为你的 Firebase 配置：

```javascript
const firebaseConfig = {
  apiKey: "你的 API Key",
  authDomain: "你的 Auth Domain",
  projectId: "你的 Project ID",
  storageBucket: "你的 Storage Bucket",
  messagingSenderId: "你的 Messaging Sender ID",
  appId: "你的 App ID"
};
```

### 3. 部署

项目已配置好 GitHub Pages，直接推送到 GitHub 即可。

**GitHub Pages 访问地址：**
`https://SCHAEZEL.github.io/food-spinner/`

## 技术栈

- 单 HTML 文件（所有 CSS/JS 内联）
- Firebase v9 (CDN)
- HTML5 Canvas
- GitHub Pages

## 界面预览

- 🎨 深棕黑背景 + 橙/红橙配色
- 📱 移动端优先设计
- ✨ 弹跳动画 + 平滑旋转
