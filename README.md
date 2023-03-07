# sub_rules
subconvertor 规则，生成时会merge进最终结果

> 规则写法和 V2Ray 保持一致， 不过不需要最后的 PROXY，DIRECT，REJECT 代理组名称了  

```
.
├── direct.list # 直连规则
├── proxy.list # 代理规则
└── reject.list # 拒绝规则
```

## example

* 比如需要 Spotify 走代理
1. 先打开 https://github.com/tindy2013/subconverter/blob/master/base/rules/ACL4SSR/Clash/Ruleset/Spotify.list
2. 侧边栏进行查询
3. 然后找到合适的复制到 proxy.txt (direct.txt 同理)
4. commit
5. 发起 PR
6. MERGED
7. 更新订阅即可
