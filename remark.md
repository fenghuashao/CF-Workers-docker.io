## 操作步骤
部署cf workres，自定义域名时
使用域名dns 解析里的域名别名子域名解析
cf workres 提供官方服务地址
 ## 发现 问题
子域名如果超过三级如 docker-hub.proxy.fenghuashao.top
则访问docker hub首没问题，但是点击搜索时就会跳转到错误页面
![image](https://github.com/user-attachments/assets/d202d63c-60f2-4189-9792-28a1447af6c4)
## 猜测
可能时cf不支持超过三级域名的证书ssl覆盖原因
使用 三级子域名转发时则政策
![image](https://github.com/user-attachments/assets/9d94e156-dfe7-4dc1-bdac-f1c586db63f4)
