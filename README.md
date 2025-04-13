# Clash 订阅转换模板合集


项目施工中！尚不完善

本项目为 [Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules) 项目的衍生项目，目的在其他 Clash 软件中实现相近的使用体验。

本项目部分模板文件由上游模板文件自动生成，均不存在 DNS 泄露。  

请务必在支持 GeoSite 数据库的 Clash 软件中使用。  

GeoSite 和 GeoIP 数据库，请务必使用[Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) 的数据库。  

匆忙制作，没有太多精力维护，可能存在尚不完善，甚至严重报错。  
上报问题会修复。  

移动端使用建议：“漏网之鱼”建议设置直连，避免扫码支付的时候因为冷门域名的问题导致支付页面无法打开

- Full 全分组模板  

  规则全面，完全和上游仓库的标准模板相同，由上游项目规则自动生成，适合在性能强劲无续航需求（如 PC）等设备上使用。  
  适合所有需求的用户。  
  
- Lite 轻量化模板  
  
  由全分组版精简而来，只包含基本的国内外分流规则内容，属于国内白名单，实现简单的国内直连功能，适合单节点用户使用。  
  适合没有流媒体解锁等特殊分流需求的用户。  
  
- GFW 轻量化模板  

  仅包含 gfwlist 规则和少量 IP 直连规则(如 Telegram 规则)，属其余网站全部直连。  
  适合需求不高、流量较少、节点较慢的用户。  
  
- iOS 模板  
  
  由全分组版精简而来，针对 iOS 使用环境设置规则，去除了移动端用不到的一些规则（如游戏平台、国内媒体）等规则。  
  
- Android 模板  
  
  由全分组版精简而来，针对 Android 使用环境设置规则，去除了移动端用不到的一些规则（如游戏平台、国内媒体）等规则。  
  (由于维护者已经多年不使用 Android，因此 Android 模板的规则内容纯靠脑补制作)  
  
- iOS BackHome 回家模板  
  
  针对使用“回家节点”进行科学上网的 iOS 用户制作的规则模板。  
  
- Android BackHome 回家模板  
  
  针对使用“回家节点”进行科学上网的 Android 用户制作的规则模板。  
  (由于维护者已经多年不使用 Android，因此 Android 模板的规则内容纯靠脑补制作)  
