# itoken-config
分布式配置中心
## 服务检测Admin配置中报错解决
```$xslt
include: ["health","info"]
```
应改为
```$xslt
include: health,info
```
