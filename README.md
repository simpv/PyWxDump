## SharpWxDump

**支持功能**
1. 支持微信多开场景，获取多用户信息等
2. 微信需要登录状态才能获取数据库密钥
3. 没有动态获取功能，已将偏移地址写入代码内，会不定期更新，如有需要的版本请Issues

![image](https://user-images.githubusercontent.com/33925462/179410099-c0f52c1c-b552-4a51-9822-7440b097bca4.png)

**版本差异**
1. 版本 < 3.7.0.30 只运行不登录能获取个人信息，登录后可以获取数据库密钥
2. 版本 > 3.7.0.30 只运行不登录不能获取个人信息，登录后都能获取

**利用场景**
1. 钓鱼攻击(通过钓鱼控到的机器通常都是登录状态)
2. 渗透到运维机器(有些运维机器会日常登录自己的微信)
3. 某些工作需要取证(数据库需要拷贝到本地)
4. 自行备份(日常备份自己留存)
5. 等等...............

**数据库解密**

解密后可拖入数据库工具查找敏感信息

![image](https://user-images.githubusercontent.com/33925462/179410883-10deefb3-793d-4e15-8475-a74954fafe19.png)


## 免责声明
本项目仅允许在授权情况下对数据库进行备份，严禁用于非法目的，否则自行承担所有相关责任。使用该工具则代表默认同意该条款;

请勿利用本项目的相关技术从事非法测试，如因此产生的一切不良后果与项目作者无关。
