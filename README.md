# cokio
CentOS one key install OpenVPN bash

# 安装完毕

安装完成后，为了连接安全和配置文件不输出错误信息，请打开客户端配置文件 ``cipher AES-256-CBC`` 更改为 ``--data-ciphers-fallback 'AES-256-CBC'``

在这行代码下方加入(确保交换密钥不被缓存泄露)

``auth-nocache``
