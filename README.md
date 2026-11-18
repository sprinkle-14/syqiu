# 孙雨秋 · GitHub Pages 个人主页

本文件夹包含一套**无需构建**的静态个人主页，适用于 GitHub Pages。网站内容按当前一页版中文简历编写。

## 文件说明

- `index.html`：网站首页（可直接编辑中文内容）
- `assets/style.css`：网站外观与手机端适配
- `resume.pdf`：一页简历，网页可预览/下载
- `.nojekyll`：让 GitHub Pages 原样发布静态文件

## 发布步骤（不需要编程）

1. 注册/登录 GitHub，记录自己的用户名。
2. 新建一个 **Public** 仓库，名称严格使用 `你的用户名.github.io`（例如用户名是 `example`，仓库名应为 `example.github.io`）。
3. 在仓库页面选择 **Add file → Upload files**。上传这个文件夹**里面**的 `index.html`、`resume.pdf`、`.nojekyll`、`assets` 文件夹下的 `style.css`，保持目录结构不变。注意 `.nojekyll` 以点开头。
4. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，选择 `main` 与 `/(root)`，点击 **Save**。
5. 发布成功后，访问 `https://你的用户名.github.io/`。简历下载地址为 `https://你的用户名.github.io/resume.pdf`。

也可以直接把整个文件夹内容通过 Git 客户端推送到该仓库的默认分支。

## 更新简历

把新的 PDF 命名为 `resume.pdf`，上传到仓库根目录并覆盖旧文件即可。网页的文字需要单独修改 `index.html`，不会自动从 PDF 同步。

## 公开发布前请注意

- 此主页默认仅公开学校邮箱，不在网页正文展示手机号码。
- **`resume.pdf` 中含有你的手机号码**，公开上传将允许任何人查看和下载。若不希望手机号公开，请先制作脱敏版本并替换 `resume.pdf`。
- DON 项目名称目前是描述性名称，若有导师确认的正式题目，建议替换网站与 PDF 中的名称。
- 项目原型与科研进展的表述应以实际已完成的工作为准。
