# huayangzi-studio
A Different Style of WORDS.But for FREE


# 花漾字

当前开发版本：**v2.0.0**（2026-10-15）

一款为朋友圈和日常分享设计的花体字 PWA。它把两种容易混淆的需求分开处理：

- **图片花字**：可使用内置色彩风格或选择自己的图片，自由搭配日期、印章、短句等艺术元素，并导出高清 PNG。
- **可复制花字**：内置 50 款中英文风格，其中 21 款为原创组合；中文通过符号和排版装饰，英文字母与数字可转换为 Unicode 花体，复制后可直接粘贴。

整个项目都在当前文件夹内，不会在其他目录创建运行文件。应用无需账号，文字、收藏和作品记录只保存在浏览器本机。

## 最简单的使用方式

最稳妥的方式是双击项目文件夹里的 `打开花漾字.html`。它是完整的单文件离线版，不会跳转网站，不需要登录、安装或启动服务器，Mac 与 Windows 的 Chrome / Edge 均可直接打开。

网络允许访问时，也可以打开在线版：

https://gentle-daffodil-1ac2c5.netlify.app/

- **Mac / Windows**：双击 `打开花漾字.html`。
- **iPhone / iPad**：用 Safari 打开上方网址即可使用；想放到桌面时，点“分享”→“添加到主屏幕”。
- **Android**：用 Chrome 打开上方网址，点右上角菜单→“安装应用”或“添加到主屏幕”。

离线 HTML 不需要安装，整个应用都包含在这一个文件里。在线版的“安装”只是在桌面增加一个方便打开的图标。

作品会保存在当前浏览器和当前文件路径下。建议把整个项目文件夹固定在一个位置；如果移动或重命名 HTML，原位置保存的作品不会自动跟过去。

## 开发预览

普通使用请直接双击根目录的 `打开花漾字.html`。只有在调试 `dist/` 中的在线 PWA 版本时，才需要运行本地服务器：

    python3 -m http.server 4173 --directory dist

然后访问 http://localhost:4173。

## 验证

    npm run release:check

项目没有第三方运行依赖。dist/ 是可直接部署的静态站点；tests/ 与 scripts/ 只用于验证。

## 修改与发布新版本

网页源文件集中在 `dist/`：

- 页面结构：`dist/index.html`
- 页面样式：`dist/styles.css`
- 交互功能：`dist/app.js`
- 花字样式：`dist/transformer.js`

修改完成后，先更新 `package.json`、`dist/version.json` 和 `dist/sw.js` 中的版本号，再运行 `npm run release:check`。详细操作见 [DEPLOY.md](./DEPLOY.md)。

Netlify 手动发布时，进入原来的 `gentle-daffodil-1ac2c5` 项目，在 **Deploys** 页面上传 `dist/` 文件夹，或者上传 `releases/` 中对应版本的 Netlify ZIP。不要新建站点，否则网址会改变。

## 设备安装

PWA 安装需要使用上方 HTTPS 在线网址；`打开花漾字.html` 是免安装的单文件离线版。

- iPhone / iPad：用 Safari 打开，点“分享”→“添加到主屏幕”。
- Android：用 Chrome 打开，点右上角菜单→“安装应用”或“添加到主屏幕”。
- Mac / Windows：用 Chrome 或 Edge 打开，点地址栏右侧的安装图标。

首次在线打开后，核心编辑、复制和图片导出可离线使用。

如图所示：
首先打开浏览器；
输入我给的网址；（https://gentle-daffodil-1ac2c5.netlify.app/）
点击左下角三个横线（或者右上角，这取决于你的系统，我是ios27）；
点击共享；
点击“添加到主平面”；
点击添加；
然后结束！！！
<img width="1206" height="719" alt="74e9e21f1d6a80b850d7708780da5770" src="https://github.com/user-attachments/assets/d971d8d0-4ca4-4ffd-b5ad-453d319cfac4" />
<img width="603" height="1311" alt="5a09ef304b61e9ad6d41fd1fe0e0a377" src="https://github.com/user-attachments/assets/ffb2901d-0fa0-479a-a191-418b929148c9" />
<img width="1206" height="2622" alt="68bb98f899eabceea3634e88d6ffae04" src="https://github.com/user-attachments/assets/17a8a1bf-0f7b-4947-b848-feb2dd31ebc4" />
<img width="1206" height="2622" alt="0e04b73ae51a32a5f93775ebdeea9c01" src="https://github.com/user-attachments/assets/9594ba0a-1658-4ad0-87ea-1cf6174635f0" />
<img width="1206" height="2622" alt="113866b4247725f400f3653690e7732d" src="https://github.com/user-attachments/assets/fb9e606d-d5c4-4974-91c8-642e781622e3" />
<img width="1206" height="2622" alt="1ec6feb84d3f00f3da4b50f105c4fc72" src="https://github.com/user-attachments/assets/0ab9195a-2f8a-4717-b04e-b9e691f7fe5b" />


小弹窗关闭：

<img width="1206" height="2622" alt="a109f7ae101bc7e99a476fb503455de9" src="https://github.com/user-attachments/assets/b22cc8fa-e178-4405-9f3d-54aee0bc5814" />
<img width="1206" height="2622" alt="23b3f51cb7d19bf199a9ef3f5a47bbae" src="https://github.com/user-attachments/assets/92f6aab0-efe6-472b-be8e-30039b67abd5" />


## 分享给别人

直接把上面的 Netlify 网址发给对方即可

## 祝各位食用愉快😀
