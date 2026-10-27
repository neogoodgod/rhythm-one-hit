# 节奏一击

一个无需安装依赖、可在浏览器中直接游玩的单页节奏小游戏。

## 在线试玩

发布到 GitHub Pages 后，可通过以下地址访问：

https://neogoodgod.github.io/rhythm-one-hit/

## 本地运行

直接在浏览器中打开 `index.html` 即可。

## 游戏玩法

- 点击“开始游戏”后，听节拍并在每拍附近点击按钮，也可以按空格键。
- 每次失误会消耗一次机会；机会用完后游戏结束。
- 最高纪录保存在当前浏览器的本地存储中。

## 部署

推送到 `main` 分支后，GitHub Actions 会自动部署到 GitHub Pages。首次部署前，请在仓库的 **Settings → Pages → Build and deployment** 中将 **Source** 设为 **GitHub Actions**。
