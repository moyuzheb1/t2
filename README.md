# Doll Weekend 静态网站

这是一个模仿 Doll Weekend 风格的二次元现代简约风格静态网站，专为手机端设计，适用于 GitHub Pages 部署。

## 文件结构

```
.
├── index.html          # 主页面
├── styles.css          # 样式文件
├── images/             # 图片资源目录
│   ├── hero.jpg        # 主页横幅图片
│   ├── video1.jpg      # 视频缩略图1
│   ├── video2.jpg      # 视频缩略图2
│   ├── video3.jpg      # 视频缩略图3
│   ├── video4.jpg      # 视频缩略图4
│   ├── video5.jpg      # 视频缩略图5
│   └── video6.jpg      # 视频缩略图6
└── README.md           # 说明文档
```

## 图片资源说明

请将以下图片放入 `images/` 目录：

- `hero.jpg` - 主页横幅图片（建议尺寸：750x400px）
- `video1.jpg` ~ `video6.jpg` - 视频缩略图（建议尺寸：750x400px）

## GitHub Pages 部署步骤

1. 将此文件夹上传到 GitHub 仓库
2. 进入仓库的 Settings 页面
3. 在左侧菜单中选择 "Pages"
4. 在 "Source" 下选择 "Deploy from a branch"
5. 选择 `main` 分支和 `/ (root)` 目录
6. 点击 "Save"
7. 等待几分钟后，你的网站将在 `https://yourusername.github.io/repository-name` 上线

## 设计特点

- **二次元现代简约风格**：采用柔和的渐变色彩和圆润的设计元素
- **手机端优化**：专为移动设备设计的响应式布局
- **流畅动画**：细腻的悬停效果和过渡动画
- **清晰的信息层级**：合理的内容组织和视觉引导

## 技术栈

- 纯 HTML5 + CSS3
- 无需 JavaScript
- 完全静态，加载速度快
- 支持所有现代浏览器

## 自定义修改

### 修改颜色主题

在 `styles.css` 中修改 CSS 变量：

```css
:root {
    --primary-color: #ff6b9d;
    --secondary-color: #c44569;
    --accent-color: #f8b500;
}
```

### 修改内容

直接编辑 `index.html` 文件中的文本内容即可。

## 浏览器支持

- Chrome (最新版)
- Safari (最新版)
- Firefox (最新版)
- Edge (最新版)
- 移动端浏览器