> API 参考文档：https://cloud.google.com/nodejs/docs/reference/local-auth/latest

第一步申请 
申请地址：https://console.cloud.google.com/apis/credentials?project=engaged-precept-376916&supportedpurview=project

image.png

credentials.json


第二步
修改下载的 json 为 .credentials.json

`pnpm dev` 会调起 google 授权页面，用同样的 google 账户授权认证
会生成 token.json