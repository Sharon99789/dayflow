日序 Dayflow · 第一版

快速体验：解压 ZIP，双击 index.html，用浏览器打开。
任务会保存在当前浏览器 localStorage 中。

安装为 PWA：需要通过 HTTPS 网站部署（例如 GitHub Pages），或本机 localhost 访问。
部署到 GitHub Pages：新建公开仓库，上传 index.html、manifest.webmanifest、icon.svg、sw.js 到仓库根目录，在 Settings > Pages 中选择 Deploy from a branch，选择 main 和 /(root)，等待发布，使用生成的 HTTPS 地址访问。
Chrome/Edge 桌面端可通过地址栏的安装按钮安装；手机浏览器可选择“添加到主屏幕”（具体入口因浏览器而异）。

注意：当前版本仅本机浏览器保存，不支持多设备实时同步。请定期使用“导出备份”。不要在无备份情况下清除网站数据。
