# 绒绒花境 - 游戏策划文档

## 文件结构说明

为了确保网站正常显示，请确保以下文件结构：

```
rongronghuajing/
├── index.html          # 主页面文件
├── .nojekyll          # 禁用 Jekyll 处理（已创建）
├── images/            # 图片和视频文件夹
│   ├── background.jpg  # 主页面背景图片
│   ├── welcome-bg.jpg # 欢迎页面背景图片
│   ├── 按钮.jpg       # 按钮图片
│   ├── 启发视频.mp4   # 灵感启发视频（或 inspiration-video.mp4）
│   └── [其他图片文件]  # 其他需要的图片文件
└── README.md          # 本说明文件
```

## 重要提示

### 1. 图片文件命名
- 图片文件名应使用横线连接，例如：`游戏概念图-绒绒花境主视觉.jpg`
- 支持的图片格式：`.jpg`, `.jpeg`, `.png`, `.webp`

### 2. 视频文件
- 视频文件名可以是：`启发视频.mp4` 或 `inspiration-video.mp4`
- 支持的视频格式：`.mp4`, `.webm`
- 视频文件应放在 `images/` 文件夹中

### 3. GitHub Pages 部署
- 已创建 `.nojekyll` 文件，禁用 Jekyll 处理
- 确保所有文件都提交到 GitHub 仓库
- 在 GitHub 仓库设置中启用 GitHub Pages

### 4. 路径问题
- 代码已自动处理 GitHub Pages 的子路径问题
- 如果图片或视频不显示，请检查：
  1. 文件是否存在于 `images/` 文件夹中
  2. 文件名是否与代码中的名称匹配
  3. 文件是否已提交到 GitHub 仓库

## 部署步骤

1. 将所有文件提交到 GitHub 仓库
2. 在仓库设置中，进入 "Pages" 设置
3. 选择分支（通常是 `main` 或 `master`）
4. 选择文件夹（通常是 `/root`）
5. 保存设置，等待部署完成

部署完成后，访问：`https://12345saw.github.io/rongronghuajing/`

## 故障排除

如果图片或视频不显示：
1. 打开浏览器开发者工具（F12）
2. 查看 Console 标签页中的错误信息
3. 查看 Network 标签页，检查文件是否成功加载
4. 确认文件路径是否正确

