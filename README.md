# taikonauts-config

太鼓达人配置助手 在线更新通道。

- 只放发布清单 manifest.json 与安装包，不放源码。
- 每个版本一个 Release，tag 与程序版本一致（如 v1.4.15）。
- 安装包由发布者私钥签名的清单引用，客户端会校验 RSA 签名与 SHA-256。
