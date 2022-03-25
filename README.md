# dnscrypt-proxy2

### 修改 /files/dnscrypt-proxy.toml

修改内容：

1. 启用监听IPV6端口.
2. 调整IPV4,IPV6监听端口为7053.

### 修改 /Makefile

修改内容：

1. 注释48,55,56行。
2. 49行增加：$(INSTALL_CONF) ./files/dnscrypt-proxy.toml $(1)/etc/dnscrypt-proxy2/dnscrypt-proxy.toml （直接copy本地配置文件）
