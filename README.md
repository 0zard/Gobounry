# Gobounry
## 介绍

从 https://github.com/0zard/bounty-targets-data 拉取的各大漏洞赏金json文件中有的没有赏金。为了能够直接扫描出有赏金的漏洞，把他们分离开，可以使用此代码。结果会生成web-site
和wild-site。

## 用法

```
./Gobounty -f [name].json
```
如果name 是hackerone.json就会分离hackerone的有效域名，支持bugcrawd、hackerone、intigriti。
