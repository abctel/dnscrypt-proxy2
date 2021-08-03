# dnscrypt-proxy2

/files/dnscrypt-proxy.toml

1.启用监听IPV6端口.
2.调整IPV4,IPV6监听端口为8053.

/Makefile

1.注释48,55,56行。
2.49行增加：$(INSTALL_CONF) ./files/dnscrypt-proxy.toml $(1)/etc/dnscrypt-proxy2/dnscrypt-proxy.toml （直接copy本地配置文件）
