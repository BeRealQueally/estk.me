---
description: 配置ECASD管理域的行为
---

# ECASD Mode

ECASD是一个特殊的管理域，与ISD-R不同，ECASD保存着eUICC最关键的证书与密钥数据，可以理解为是eUICC的后端，通常情况下，除了eSE的制造方，无需访问ECASD域。

配置ECASD是一个可靠操作，这意味着：

1. 你可以自由尝试该功能。
2. 该操作的结果是可逆的，或至少有一种恢复先前状态的方法。

&#x20;“ECASD选择菜单”具有“< >”或“<\*>”字符表示的前缀，其中“<\*>”前缀代表的是当前激活的配置。

当前可供选择的ECASD模式

1. Enabled：默认模式，ECASD被正常访问。
2. Virtual EID：应用虚拟EID模式，即使是通过ECASD也无法读取真实EID。
3. Disabled：禁用模式，在此状态下，终端设备无法访问ECASD域。
