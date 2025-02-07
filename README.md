# Naoris_Bot 2.0 教程
## Naoris Protocol 早期项目

下载钱包并且注册：https://chromewebstore.google.com/detail/naoris-protocol-wallet/dbgibbbeebmbmmhmebogidfbfehejgfo

节点插件：https://chromewebstore.google.com/detail/cpikalnagknmlfhnilhfelifgbollmmp
打开：[https://naorisprotocol.network](https://naorisprotocol.network/testnet) 用钱包注册
邀请码：OjjTWg433XSZYK6f

### Naoris_Bot 2.0 配置
#### config配置
``accounts.json`` 用户配置
```json
[
    {
        "Address": "钱包地址1",
        "deviceHash": "hash 1"
    },
    {
        "Address": "钱包地址2",
        "deviceHash": "hash 2"
    }
]
```

``proxy.txt`` 代理配置
```txt
192.168.2.7:7000
http://192.168.2.7:7000
socks5://192.168.2.7:7000
http://user:pass@192.168.2.7:7000
socks5://user:pass@192.168.2.7:7000
```

#### 怎么抓取``accounts.json``内容
打开插件，在插件里面右键->检查->等待1分钟会出现

输入对应的数据，记得编辑``accounts.json``文件的时候最好用vscode，每次增加账号在{}里面增加。有些骚年在[]里面是不对的。json[]为大括号，{}为数据小括号！记得每个账号要逗号隔离，最后一个账号不需要逗号！切记切记！

![2025-02-07_12-53](https://github.com/user-attachments/assets/5b02bb73-6360-40bc-9cca-02b5e6f83c1d)



