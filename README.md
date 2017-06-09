# wechat-backend-app
How to install Wechat's backend platform as a desktop app


1. Download [Node.js](https://nodejs.org/en/download/)
2. Restart your computer
3. Open Node.js 's command prompt and install Nativefier.
```
npm install nativefier -g
```
4. Create a wrapper for Wechat's web app. Enter the following in Node.js
```
nativefier --name "Wechat" "https://mp.weixin.qq.com/"
```
5. Pin the app to your taskbar!
