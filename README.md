# 小小农场 · 在线试玩

这是 `chu-libu/farm-game` 私有开发仓库的公开试玩发行物。公开仓库只保存编译后的单文件页面，不复制私有开发源码目录、测试和开发文档。

## 直接试玩

部署完成后访问： https://chu-libu.github.io/farm-game-playtest/

## 操作

- 方向键或 WASD：移动角色
- Z 或空格：锄地、播种、浇水、收获
- X 或 Esc：取消提示
- 点击地块：移动过去
- 睡觉过天：推进生长并恢复体力

## 存档与隐私

游戏运行时不请求外部 API，不发送遥测。存档保存在当前浏览器、当前站点来源中；不同浏览器或设备之间不会自动同步。请使用游戏内的导出存档功能备份。公开页面中的前端 JavaScript 对网站访客可见，这是浏览器游戏的正常工作方式。

## 发布方式

GitHub Pages 由 `.github/workflows/deploy-pages.yml` 发布 `site/` 目录。首次部署前，需在仓库 Settings → Pages → Build and deployment → Source 中选择 **GitHub Actions**。

开发源码和版本任务以私有仓库为准： https://github.com/chu-libu/farm-game
