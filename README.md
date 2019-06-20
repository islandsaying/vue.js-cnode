### 关于预览页面的生成
1. 在cmd中输入npm run build(前置条件是npm install)
2. 项目根目录会出现dist文件,打开index.html发现空白
3. 打开config中的index.js文件将　assetsPublicPath: ‘/‘,　改为　assetsPublicPath: ‘./‘,
4. 重新npm run build,再次点击index.html---成功!
5. 部署到github,生成的连接后面加上/dist即成功
