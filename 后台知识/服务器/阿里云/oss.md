### 存储库(oss)注意事项
1. "读写权限"可以设置成`公共读`, 写入安全, 读取方便;
2. 绑定用户域名后, 可以方便地写 url;

### 配置ssl
* `域名管理 > 某一域名 > 证书托管 > 申请签发证书(如果没有证书,免费版一年)`;
* `(几分钟后签发完成) > 下载nginx版证书 > 填写公钥(.pem格式) > 填写私钥(.key格式) > 保存(几分钟后生效)`;