更新后知乎去广告脚本有可能仅支持Surge，请悉知。


部分自用Scripts。

部分自写部分整合。

hosts部分自行添加。

京东去广告、Banner
```
^https?://api\.m\.jd\.com/client\.action\?functionId=(start|myOrderInfo|orderTrackBusiness) requires-body=1,max-size=-1,script-path=https://gitee.com/zjw5734/ScriptsForSurge/raw/master/Scripts/JDAdRemove.js
```


Lightroom解锁订阅（越南大佬）

hostname = *.adobe.io
```
^https:\/\/photos\.adobe\.io\/v2\/accounts url script-response-body https://gitee.com/zjw5734/ScriptsForSurge/raw/master/Scripts/Lightroom.js
```

Photoshop解锁订阅（越南大佬）

```
http-response ^https://lcs-mobile-cops.adobe.io/mobile_profile/nul/v1 requires-body=1,script-path=https://gitee.com/zjw5734/ScriptsForSurge/raw/master/Scripts/Photoshop.js
```

淘宝历史价格，二合一修正（yichahucha）

hostname = *.taobao.com

```
^https?://(amdc|trade-acs)\.m\.taobao\.com/(amdc/mobileDispatch|gw/mtop\.taobao\.detail\.getdetail) url script-response-body https://gitee.com/zjw5734/ScriptsForSurge/raw/master/Scripts/TaobaoPrice.js
```

vsco 会员破解
更新时间 10.24.2021

hostname = api.revenuecat.com
```
^https:\/\/(api\.revenuecat\.com\/v\d\/subscribers|vsco\.co\/api\/subscriptions\/\d\.\d\/user-subscriptions)\/ url script-response-body https://gitee.com/zjw5734/ScriptsForQuanX/raw/master/Scripts/vsco.js
```

NoMo Cam 解锁订阅

hostname = nomo.dafork.com

```
^https?:\/\/nomo\.dafork\.com\/api\/v2\/iap\/ios_verify$ url script-request-body https://gitee.com/zjw5734/ScriptsForQuanX/raw/master/Scripts/nomocam.js
```

