## 使用说明
1. 需要在 [高德开放平台](https://lbs.amap.com/) 注册账号，并在 [我的应用](https://console.amap.com/dev/key/app]) 创建 api key

2. 在cursor中配置mcp服务器，示例如下：

   ```json
   {
     "mcpServers": {
       "gaode": {
         "command": "uvx",
         "args": [
           "gaode-mcp-server",
           "--key",
           "第一步创建的api key"
         ]
       }
     }
   }
   ```