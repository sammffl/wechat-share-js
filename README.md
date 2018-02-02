# wechat-share-js
微信分享配置 不依赖任何插件

`yarn add conf-share-js`


```javascript
import wxInit from 'conf-share-js';

/**
* @param params 分享内容
* @param isDebug 是否开启微信debug模式，不传参默认false
*/
new wxInit({
    title: '分享标题',
    desc: '分享内容',
    link: '分享链接',
    imgUrl: '分享图片',
}, true);
```
