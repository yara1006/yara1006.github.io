# 个人主页 · Personal Portfolio

杨韩冰的个人主页 - AI Product Manager Portfolio

## 预览效果

深色主题 + 毛玻璃效果 + 终端风格 + 动态交互 + **中英文切换**

## 部署到 GitHub Pages

### 方法一：直接推送（推荐）

```bash
# 进入个人主页目录
cd personal-site

# 初始化 git（如果还没有）
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit: personal portfolio"

# 创建 GitHub 仓库（在 GitHub 网站上创建名为 yara1006.github.io 的仓库）
# 然后关联远程仓库
git remote add origin https://github.com/yara1006/yara1006.github.io.git

# 推送到 main 分支
git branch -M main
git push -u origin main
```

### 方法二：作为子目录部署

如果你想在 `github.com/yara1006` 下部署，而不是单独的仓库：

1. 将 `personal-site` 文件夹内容复制到你的 GitHub 仓库根目录
2. 在仓库 Settings → Pages 中设置部署源为 `main` 分支根目录
3. 访问 `https://yara1006.github.io` 即可看到效果

## 自定义修改

### 修改内容
- `index.html` - 所有文字内容直接编辑
- `photo.jpg` - 替换为你的新照片（保持文件名）

### 修改样式
- 主色调：修改 CSS 中的 `--accent: #6366f1`（紫色）
- 背景色：修改 `--bg-primary: #0a0a0f`
- 字体：中文使用 Noto Sans SC，英文使用 Inter

## 功能特性

- ✅ **中英文一键切换**（右上角按钮）
- ✅ 响应式设计（手机/平板/桌面）
- ✅ 平滑滚动导航
- ✅ 滚动淡入动画
- ✅ 悬浮卡片效果
- ✅ 终端风格展示
- ✅ 深色主题
- ✅ 毛玻璃背景效果
- ✅ 动态光晕动画

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript
- Google Fonts (Noto Sans SC, Inter, JetBrains Mono)
- GitHub Pages 托管

## 设计参考

- Glassmorphism 毛玻璃效果
- Terminal 终端美学
- Modern Dark Theme
- Micro-interactions 微交互
- Bilingual (中文默认 / English toggle)

---

Built with ❤️ by 杨韩冰
