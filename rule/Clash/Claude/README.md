# 🧸 Claude

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN与DOMAIN--KEYWORD合并-9cf) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

本 fork 的 Clash Claude 规则集补充 Claude 核心域名、MCP、认证、CDN、遥测、客服及 Anthropic IP/ASN。维护时同步更新 `Claude.list`、`Claude.yaml` 和 `Claude_No_Resolve.yaml`。规则参考 [Net.Coffee 域名清单](https://ip.net.coffee/claude/site.html)；采用清单不代表认可其风控结论。共享第三方域名和 `datadog`、`sentry`、`sift` 关键词也会匹配其他应用使用的同类服务。NTP 不提供时区，因此不纳入 Claude 分类。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2026-09-30 00:00:00

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN | 6 |
| DOMAIN-SUFFIX | 11 |
| DOMAIN-KEYWORD | 3 |
| IP-CIDR | 1 |
| IP-CIDR6 | 1 |
| IP-ASN | 1 |
| TOTAL | 23 |


## Clash 

#### 使用说明
- Claude.yaml，请使用 behavior: "classical"。
- Claude_No_Resolve.yaml，请使用 behavior: "classical"。

#### 配置建议
- Claude.yaml 单独使用。
- Claude_No_Resolve.yaml 单独使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/yaoxi-std/ios_rule_script/master/rule/Clash/Claude/Claude.yaml

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/yaoxi-std/ios_rule_script@master/rule/Clash/Claude/Claude.yaml

**MASTER分支 GHProxy (每日更新)**

https://ghproxy.com/https://raw.githubusercontent.com/yaoxi-std/ios_rule_script/master/rule/Clash/Claude/Claude.yaml

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Claude/Claude.yaml

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/Claude/Claude.yaml

**RELEASE分支 GHProxy (不定时更新)**

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Claude/Claude.yaml

## 子规则/排除规则


当前分流规则，未包含其他子规则。

## 数据来源

当前规则未直接引用数据源。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。