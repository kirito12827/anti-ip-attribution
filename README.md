# anti-ip-attribution

针对部分网站显示 IP 归属地的流量分流规则

项目作者无法保证配置文件一定能起到作用，有可能会触发账号风控。

## 使用之前

请在使用前详细阅读`rules.yaml`内容，内部注释包含部分可选规则，请酌情参考。

强烈建议 Fork 自己的一份配置文件，不要直接使用最新的。

## 关于自动生成

本仓库使用 GitHub Actions 从`rules.yaml`中生成配置文件，详见`generate.py`。

## PR & 贡献

仓库所有者和开发者的能力不能保证持续、高效维护地此仓库。如若发现改进或更好的方案，欢迎 PR。

只需要修改`rules.yaml`，其余配置文件会自动生成。

如果您对项目改进有兴趣，欢迎 Email 联系我获取 Collaborator 权限。

## 使用提示

不建议使用手机客户端访问这些网站，应用可能会包含难以寻找的 API 地址获取信息。

## 免责声明

本项目仅用于学习交流，请在遵守所在地法律法规的前提下使用。

本项目记录的 API 域名地址信息可以被任何人通过开发人员工具获取，没有经过逆向工程或网络攻击，不构成入侵计算机系统。

请不要在中华人民共和国境内使用此项目。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=lwd-temp/anti-ip-attribution&type=Date)](https://star-history.com/#lwd-temp/anti-ip-attribution&Date)
