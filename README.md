# 冯雨晨个人主页

这是一个可直接部署到 GitHub Pages 的静态个人主页，包含个人简介、代表作品、工作经历、教育背景和联系方式。

## 文件结构

- `index.html`：页面内容与作品链接
- `styles.css`：视觉样式与响应式布局
- `script.js`：页脚年份等轻量交互
- `assets/profile.jpg`：个人形象照
- `.nojekyll`：让 GitHub Pages 按静态文件直接发布

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `personal-homepage`。
2. 将本文件夹内所有文件上传到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 保存后等待 GitHub Pages 发布完成。

发布地址通常会是：

```text
https://你的GitHub用户名.github.io/personal-homepage/
```

如果仓库名是 `你的GitHub用户名.github.io`，发布地址会是：

```text
https://你的GitHub用户名.github.io/
```

## 后续修改

- 替换照片：把新照片命名为 `profile.jpg`，覆盖 `assets/profile.jpg`。
- 修改文字或作品：编辑 `index.html`。
- 调整视觉风格：编辑 `styles.css`。
