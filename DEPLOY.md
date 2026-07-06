# 喵喵大小写转换器 - 部署指南

## 📦 一键部署到 GitHub Pages

### 第 1 步：创建 GitHub 仓库

1. 打开 https://github.com/new
2. Repository name 填写：`case-converter`
3. **不要勾选** "Add a README file"
4. **不要勾选** ".gitignore"
5. 点击 "Create repository"

### 第 2 步：推送代码

在你电脑上打开终端（CMD 或 PowerShell），复制粘贴以下命令：

```bash
cd "C:\Users\张子娴\Desktop\case-converter"
git push -u origin master
```

### 第 3 步：启用 GitHub Pages

1. 打开 https://github.com/364552746-ship-it/case-converter/settings/pages
2. Source 选择 "Deploy from a branch"
3. Branch 选择 `master`，目录选 `/ (root)`
4. 点击 Save

### 第 4 步：访问你的应用！

等待 1-2 分钟后访问：

👉 **https://364552746-ship-it.github.io/case-converter/**

---

## 🔄 以后更新代码

```bash
cd "C:\Users\张子娴\Desktop\case-converter"
git add -A
git commit -m "描述你的改动"
git push
```

推送后 GitHub Pages 会自动更新。
