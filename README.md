# cookies-chrome-plugin

主页面需要先发送 message 给插件, 缓存页面 tabId
```javascript
window.parent.postMessage({type: 'tab', level: 'main'}, '*');
```