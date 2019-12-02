### 安装事件

当你的 Service Worker 首次注册的时，或者你的 Service Worker 文件（/sw.js）在之后的任何时间被更新时（浏览器会自动检测这些更改），install 事件都将被触发。


### Fetch事件
Fetch 事件是在每次网页发出请求的时候触发的，触发该事件的时候 Service Worker 能够 '拦截' 请求，并决定返回内容 -- 是返回缓存的数据，还是返回真实请求响应的数据。

