# 🧸 去广告精简版

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-移除无法解析的域名-important) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN与DOMAIN--KEYWORD合并-9cf) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) ![](https://shields.io/badge/-MITM--HOSTNAME合并-brightgreen) 

去广告精简版规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则说明
可能存在部分误拦截，建议搭配放行规则进行修正。

## 规则统计

最后更新时间：2025-07-28 02:03:32

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN | 23753  | 
| DOMAIN-KEYWORD | 187  | 
| DOMAIN-SUFFIX | 13936  | 
| IP-CIDR | 186  | 
| IP-CIDR6 | 1  | 
| TOTAL | 38063  | 


## Clash 

#### 使用说明
- AdvertisingLite.yaml，请使用 behavior: "classical"。
- AdvertisingLite_Resolve.yaml，请使用 behavior: "classical"。
- AdvertisingLite_Classical.yaml，请使用 behavior: "classical"。
- AdvertisingLite_Domain.yaml，请使用 behavior: "domain"。

#### 配置建议
- AdvertisingLite_Classical.yaml 单独使用。
- AdvertisingLite.yaml、AdvertisingLite_Domain.yaml 共同使用。
- AdvertisingLite_Resolve.yaml、AdvertisingLite_Domain.yaml 共同使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

**MASTER分支 GHProxy (每日更新)**

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

**RELEASE分支 GHProxy (不定时更新)**

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite_Classical.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite_Domain.txt

## 子规则/排除规则


当前分流规则，未包含其他子规则。

当前分流规则，已排除以下规则：
| 排除规则  |  | 
| ---- | ----  |
| Hijacking | Privacy  | 

## 数据来源

《去广告精简版》的数据来自以下链接，如与本项目的《去广告精简版》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/Advertising.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/LianXiangJia/LianXiangJia.list
- https://raw.githubusercontent.com/yjqiang/surge_scripts/main/modules/hupu/hupu.sgmodule


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。