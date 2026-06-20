# 软乎乎

一个手机优先、打开即玩的解压小游戏。按住或滑动揉捏软泥，也可以切换颜色、声音与震动。

## 本地预览

直接打开 `index.html` 即可，或在当前目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 公网发布

仓库已包含 GitHub Pages 自动发布配置。把这个目录作为独立仓库推送到 GitHub 后，在仓库设置中将 **Pages → Source** 设为 **GitHub Actions**；以后每次推送都会自动发布。

也可以直接部署到 Cloudflare Pages、Netlify 或 Vercel，无需构建命令。

`.gitignore` 采用默认拒绝规则，只有经过检查的游戏页面、说明和发布配置会进入仓库。
