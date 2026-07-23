# Luo Wenbo - Academic Website

极简学术个人网站，PanleBarwick 风格。

## 文件结构

```
.
├── index.html           # 首页
├── publications.html    # 发表论文
├── research.html        # 研究方向
├── style.css            # 样式文件
├── papers/              # 论文 PDF 文件夹
├── files/               # CV 等文件
└── images/              # 图片文件夹
```

## 如何使用

### 1. 添加个人照片

把你的照片放到 `images/` 文件夹，命名为 `profile.jpg`，然后修改 `index.html` 中的引用。

### 2. 添加 CV

把你的 CV.pdf 放到 `files/` 文件夹。

### 3. 添加论文

把论文 PDF 放到 `papers/` 文件夹，然后在 `publications.html` 中添加链接。

### 4. 修改个人信息

直接编辑各个 `.html` 文件中的内容。

## 推送到 GitHub

```bash
git add .
git commit -m "Update website"
git push
```

访问：https://luomrme-cpu.github.io
