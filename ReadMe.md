更新后知乎去广告脚本有可能仅支持Surge


部分自用Scripts

hosts部分自行添加

京东去广告、Banner
```
^https?://api\.m\.jd\.com/client\.action\?functionId=(start|myOrderInfo|orderTrackBusiness) url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/JDAdRemove.js
```

Lightroom解锁订阅（越南大佬）

hostname = *.adobe.io
```
^https:\/\/photos\.adobe\.io\/v2\/accounts url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/Lightroom.js
```

Photoshop解锁订阅（越南大佬）

```
^https://lcs-mobile-cops.adobe.io/mobile_profile/nul/v1 url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/Photoshop.js
```

淘宝历史价格，二合一修正（yichahucha）

hostname = *.taobao.com

```
^https?://(amdc|trade-acs)\.m\.taobao\.com/(amdc/mobileDispatch|gw/mtop\.taobao\.detail\.getdetail) url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/TaobaoPrice.js
```

vsco 会员破解
更新时间 10.24.2021

hostname = api.revenuecat.com
```
^https:\/\/(api\.revenuecat\.com\/v\d\/subscribers|vsco\.co\/api\/subscriptions\/\d\.\d\/user-subscriptions)\/ url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/vsco.js
```

NoMo Cam 解锁订阅 （暂不支持1.5.133版本）

hostname = nomo.dafork.com

```
^https?:\/\/nomo\.dafork\.com\/api\/v2\/iap\/ios_verify$ url script-request-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/nomocam.js
```

Polarr泼辣修图 解锁特权 (需恢复购买)

hostname = api.polaxiong.com

```
^https:\/\/api\.polaxiong\.com\/v1\/payments\/appleiap\/receipts\/confirmation url script-response-body https://raw.githubusercontent.com/jiaw-Zh/ScriptsForQuanX/master/Scripts/Polarr.js
```