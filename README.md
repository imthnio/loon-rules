# loon-rules · Loon 分流规则

| 文件 | 内容 |
|---|---|
| `China.list` | 今日头条 / 抖音 / 豆包 / 剪映、哔哩哔哩等国内 App（直连） |
| `Highspeed.list` | GitHub、Reddit、Telegram、王者荣耀国际服（高速节点） |
| `Other.list` | VPS、论坛、格鲁吉亚 eSIM、接码平台、IP 检测等杂项 |
| `UnitedKingdom.list` | Google / YouTube、TikTok、Meta、Twitter、ChatGPT、交易所、海外银行、Wi-Fi Calling（英国节点） |
| `loon配置` | 完整 Loon 配置模板，含「中国版本」和「国外版本」两套 General 参数 |

## 用法

订阅单个规则文件（以 China.list 为例）：

```
https://raw.githubusercontent.com/imthnio/loon-rules/main/China.list
```

在 Loon「规则」里添加远程规则，绑定到对应策略组即可。
