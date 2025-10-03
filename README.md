// 参考CM大佬的代码，略作修改，去掉了env和html前端页面，用于snipaste部署。
// 可以手动自定义CFDoH路径和GGDoH路径，代码里我给的是默认值
// snipaste部署后，在域名后面加上自定义的路径地址就可以自动切换对应的dns源: https://[你的域名]/[自定义路径]
// 例如，你部署的域名是：dns.123456.xyz, 那么你的doh地址（CF源）就是：https://dns.123456.xyz/cloudflare-doh

```js
let CFDoH路径 = 'cloudflare-doh'; // 使用CF的DNS源，路径名称随意，但不要与其他路径冲突
let GGDoH路径 = 'google-doh'; // 使用谷歌的DNS源，路径名称随意，但不要与其他路径冲突
```
