# 我的 Vibe 小产品

用 AI 结对编程（vibe coding），把想法一个一个变成能用的网页小产品。
纯前端、无需后端，手机和电脑浏览器都能直接打开。

## 产品清单

| 产品 | 状态 | 目录 |
|---|---|---|
| 英伦腔调 British Buddy（英式英语翻译学习） | v1 已完成 | `apps/british-buddy/` |
| 艺术疗愈小工具 | 构思中 | `apps/art-healing/` |
| 学习生活 / 艺术追踪器 | 构思中 | `apps/life-art-tracker/` |

## 访问入口

- 网站根目录（`index.html`）会自动跳转到英伦腔调 App。
- 产品集合页保留在 `hub.html`，以后产品多了可以当导航用。

## 本地运行

直接用浏览器双击打开 `index.html` 即可；
或者在项目根目录运行 `python3 -m http.server`，再访问 http://localhost:8000。

## 发到 GitHub（免费上线）

1. 注册并登录 github.com，新建仓库（比如叫 `vibe-apps`），先不要勾选 README。
2. 在本机项目目录执行：
   ```
   git init
   git add -A
   git commit -m "v1"
   git branch -M main
   git remote add origin https://github.com/你的用户名/vibe-apps.git
   git push -u origin main
   ```
3. 仓库页面 → Settings → Pages → Deploy from a branch → main / root，保存。
   几分钟后访问 `https://你的用户名.github.io/vibe-apps/` 即可。

## Vibe coding 玩法

- 你用自然语言描述想要的功能（比如"加个随机测验模式"）。
- AI 直接改代码，你刷新浏览器看效果。
- 满意就 `git commit` 存一版，不满意就继续提需求。
