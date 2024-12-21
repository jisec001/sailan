#### 赛蓝企业管理系统 GetJSFile存在任意文件读取漏洞

![image-20241220153351984](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20241220153351984.png)

```
描述:某蓝企业管理系统 GetJSFile 接口处存在任意文件读取漏洞，未经身份验证攻击者可通过该漏洞读取系统重要文件（如数据库配置文件、系统配置文件）、数据库配置文件等等，导致网站处于极度不安全状态。
网络fofa: body="www.cailsoft.com" || body="赛蓝企业管理系统"
```

