# Debian 12 VPS 初始化脚本

这是一个用于 Debian 12 VPS 的一键初始化脚本，功能包括：

- 添加新用户并赋予 sudo 权限  
- 配置 SSH 公钥登录  
- 修改 SSH 端口，禁用 root 密码登录  
- 系统更新升级  
- ufw 防火墙设置（用户自定义端口）  
- 开启 BBR TCP 加速  

## 使用方法

在新的 Debian 12 VPS 上执行以下命令即可：

```bash
bash <(curl -fsSL sys.kosno.de)
```

检查主机名
```bash
sudo nano /etc/hosts
