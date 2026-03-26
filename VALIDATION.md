# VALIDATION.md

## 验证清单

### 功能验证

- [x] 转盘 Canvas 绘制完成
- [x] 旋转动画使用 CSS transform + cubic-bezier easeOut
- [x] 弹跳动画 (bounceIn keyframe) 在结果弹窗显示时触发
- [x] 扇形颜色从 COLORS 调色板轮询
- [x] 装饰 emoji 围绕转盘
- [x] Firebase Google 登录
- [x] Firestore dishes 集合，字段包含 id, name, difficulty, time, category, weight, createdAt
- [x] 未登录时显示"请先登录"提示
- [x] onSnapshot 实时同步
- [x] 菜谱列表：名称、难度标签、时间、分类
- [x] 添加/编辑/删除菜品
- [x] 权重字段
- [x] 结果弹窗卡片
- [x] "就做这个！"按钮记录到 history 集合

### 设计验证

- [x] 主色 #f4a261 / #e76f51
- [x] 背景 #1a1008
- [x] 卡片 #2d1f0f
- [x] 圆润卡片、圆角按钮
- [x] 食物 emoji 装饰
- [x] 移动端优先

### 技术验证

- [x] 单 HTML 文件（CSS/JS 内联）
- [x] Firebase v9 CDN 模块化 SDK
- [x] Canvas 绘制转盘
- [x] GitHub Pages (docs/ 目录)
- [x] Firebase 配置占位符 + TODO 注释

### 文件结构

- [x] `index.html` 存在
- [x] `docs/index.html` 存在（GitHub Pages 版本）
- [x] `README.md` 存在
- [x] `VALIDATION.md` 存在

### GitHub 部署

- [ ] 首次需在 GitHub Settings → Pages → Source 设为 `main` / `docs folder`
