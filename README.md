# 软乎乎

一个手机优先、打开即玩的解压小游戏。按住或滑动揉捏软泥，也可以切换颜色、声音与震动。

## 本地预览

直接打开 `index.html` 即可，或在当前目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 公网发布

当前仓库使用 GitHub Pages 从 `main` 分支根目录直接发布；更新 `index.html` 后即可自动重新发布。

也可以直接部署到 Cloudflare Pages、Netlify 或 Vercel，无需构建命令。

`.gitignore` 采用默认拒绝规则，只有经过检查的游戏页面、说明和发布配置会进入仓库。
