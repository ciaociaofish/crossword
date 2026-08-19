# 中文填字游戏

两个 15×15 的中文填字游戏，纯静态网页，无任何依赖。

- `index.html` — 首页
- `standard.html` — 标准版，60 条谜面
- `hardcore.html` — 硬核版，60 条谜面

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（Public），比如叫 `crossword`
2. 把这个文件夹里的三个 html 和本 README 上传上去（网页上点 **Add file → Upload files**，把文件拖进去，然后 Commit）
3. 进入仓库的 **Settings → Pages**
4. Source 选 **Deploy from a branch**，Branch 选 `main`、目录选 `/ (root)`，Save
5. 等 1–2 分钟，页面顶部会出现网址：`https://<你的用户名>.github.io/crossword/`

把这个网址发给朋友就能玩。

## 其他更快的办法

- **直接发文件**：这三个 html 是自包含的，微信/邮件发过去，对方双击就能在浏览器里玩，不联网也行
- **Cloudflare Pages / Vercel / Netlify**：注册后把文件夹拖进去，一分钟出网址，也支持自定义域名
