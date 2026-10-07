程舒涵生日网站 — 服务器部署说明

这是完整的纯静态网站，不需要 Node.js、数据库或安装依赖。

文件结构：
index.html：网页入口
style.css：UI 样式和手机适配
app.js：盲盒、幸运签、捉鬼、蜡烛和烟花互动
assets/：全部照片和界面图片

部署方法：
1. 解压 ZIP。
2. 把 index.html、style.css、app.js 和 assets 文件夹一起上传到网站根目录，保持目录结构。
3. 用你的域名访问 index.html。
支持 Nginx、Apache、宝塔或其他静态网站服务器。
也可以上传到子目录，例如 /birthday/，然后访问 https://你的域名/birthday/。

修改内容：
首页标题和生日日期在 index.html。
祝福内容和盲盒照片对应关系在 app.js 的 items 数组。
颜色、字体、布局在 style.css。
捉鬼奖励照片是 assets/caught.jpg。

所有图片已包含在本地 assets 文件夹，不依赖原来的图片网址。
网站不依赖 ChatGPT 登录或原来的托管服务。
网页提供点击及长按吹灭蜡烛，无须麦克风权限。
刷新网页后，盲盒和蜡烛会重置。
建议使用 HTTPS，并用手机实际打开检查。
