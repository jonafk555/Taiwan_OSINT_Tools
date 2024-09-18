# Taiwan OSINT tools 臺灣公開來源情資工具

## Google Dorking 查詢
```
"查詢系統" site:"gov.tw"
"地理資訊" site:"gov.tw"
"GIS" site:"gov.tw"
```

## 綜合網站
- [監理服務網- 汽機車](https://www.mvdis.gov.tw/m3-emv/car/index#gsc.tab=0)
- [Data Station-開放數據](https://www.datastation.org.tw/opendata)
- [政府資料開放平臺](https://data.gov.tw/)

## 找車子/車主
- [公路監理資料有償利用服務網 - 駕駛人與車輛查詢](https://mvdvan.mvdis.gov.tw/mvdvan/mvdvan)
- [車輛竊盜、車牌失竊(含計程車)資料查詢](https://od.moi.gov.tw/adm/veh/query_veh)
    - http://od.moi.gov.tw/adm/veh/query_veh?_m=query&vehType={vehType}&vehNumber={vehNumber}
    - 參數使用說明如下所示：
        - {vehType} = 牌照種類：A(汽車)、B(重機車)、C(輕機車)、G(動力機械車)。
        - {vehNumber} = 牌照號碼。
- [環境部機車定期檢驗資訊管理系統-車籍資料](https://mobile.moenv.gov.tw/Motor/query/Query_Check.aspx)
- [既有車型編號查詢](https://b2c.vscc.org.tw/CarTypeInformation/CarTypeInformation)

## 影像分析
- [即時影像監視器](https://tw.live/)
- 違規罰單分析：
    - ![image](https://hackmd.io/_uploads/ry6qJCXaA.png)
    - > 出處：https://www.tad.ntpc.gov.tw/uploads/%E4%BA%A4%E9%80%9A%E9%81%95%E8%A6%8F%E7%94%B3%E8%A8%B4_%E5%9C%96%E7%A4%BA%E7%AF%84%E4%BE%8B.pdf
    - 右下字串：`012+51KXX+01400`，編碼方式為：<車牌前三位>+<車牌後四位>+<罰緩金額>


## 地理位置/地理資訊分析

### 座標/定位/開放地圖
- [台灣電力公司電桿坐標及桿號](https://data.gov.tw/dataset/33305)
- [台電圖號座標定位系統](https://service.taipower.com.tw/psvs1/tpcemap/#/psvs1/home)
- [e-GNSS即時動態定位系 - 衛星資料查詢
](https://egnss.nlsc.gov.tw/rinexquery.aspx)
- [開放街圖](https://www.openstreetmap.org/)
### 水文地理
- [水利地理資訊中心](https://gic.wra.gov.tw/gis/)
### 經濟地理
- [離岸風場區塊開發地理資訊系統](https://pro.twtpo.org.tw/geoservergis/default.aspx)
- [經濟地理圖資中心](https://egis.moea.gov.tw/MoeaEGPortal/)
- [國發會-景氣指標查詢系統-景氣對策信號](https://index.ndc.gov.tw/n/zh_tw#/)
### 人文/宗教
- [宗教地景GIS](https://gisrl.ascdc.sinica.edu.tw/religiontw/)
### 國土/環境/地質
- [地籍圖資網路便民服務系統](https://easymap.land.moi.gov.tw/P02/Index)
- [內政部地政司 - 新舊地號查詢](https://www.land.moi.gov.tw/chhtml/landnoqry/51)
- [國土規劃地理資訊系統](https://nsp.tcd.gov.tw/ngis/)
- [村里街路門牌查詢](https://www.ris.gov.tw/app/portal/3053)
- [內政地理資訊圖資雲整合服務平台](https://www.tgos.tw/tgos/NgdaMap)
- [民生公共物聯網-資料服務平台](https://ci.taiwan.gov.tw/dsp/)
- [環境圖資整合應用平臺](https://geoser.moenv.gov.tw/moenvgis/map.html)
- [活動斷層GIS查詢系統](https://faultgis.gsmma.gov.tw/gis/)
- [土壤液化潛勢查詢系統](https://www.liquid.net.tw/cgs/public/)
- 調出任意土地地籍圖與第二類土地謄本：https://blog.gtwang.org/life/online-apply-for-electronic-cadastral-copy-tutorial/
    - 土地所有權人住址
    - 姓氏
    - 身份證前幾碼
    - 該土地債務抵押狀況
    - ...

### 交通
- [GIS-T 台灣交通網路地理資訊](https://gist.transportdata.tw/gist_web/)
### 歷史/史地
- [中研院百年歷史地圖](https://gis.sinica.edu.tw/tileserver)
- [國史館臺灣文獻館](https://www.th.gov.tw/new_site/01archives/01file_archives/)
    - [國史館臺灣文獻館文獻檔案查詢系統](https://onlinearchives.th.gov.tw/index.php?act=Archive)

## 電力
- [停電查詢](https://service.taipower.com.tw/nds/ndsWeb/ndft112.aspx)

## 智慧財產
- [智慧局商標檢索系統](https://cloud.tipo.gov.tw/S282/OS0/OS0101.jsp)

## 稅務
- [營業稅申報案件公告查詢](https://www.etax.nat.gov.tw/etwmain/etw113w4)

## 郵政
- [郵件查詢 - 中華郵政](https://postserv.post.gov.tw/pstmail/main_mail.html)
- [郵遞區號查詢](https://www.post.gov.tw/post/internet/Postal/index.jsp?ID=208)

## 建築/土木
- [建築工程履歷查詢系統](https://cpabm.cpami.gov.tw/cers/Welcome.do)

## 環境汙染/毒物
- [列管污染源資料 (含裁處資訊) 查詢系統](https://prtr.moenv.gov.tw/index.html)
- [毒性及關注化學物質快速查詢
](https://www.cha.gov.tw/sp-toch-list-1.html)

## 學術系統
- [國科會 - 學術人才查詢](https://arspb.nstc.gov.tw/NSCWebFront/modules/talentSearch/talentSearch.do?action=initSearchList&LANG=ch)
- [國科會 - 統計資料庫](https://wsts.nstc.gov.tw/STSWeb/main/Main.aspx)
- [政府研究資訊系統 GRB](https://www.grb.gov.tw/search)
- [教育部大專校院校務資訊公開平臺](https://udb.moe.edu.tw/udata/)

## 司法/法律
- [司法院查詢服務](https://www.judicial.gov.tw/tw/np-117-1.html)
- [司法院資料開放平臺](https://opendata.judicial.gov.tw/)
- [法人及夫妻財產登記公告查詢](https://aomp109.judicial.gov.tw/judbp/whd6k/WHD6K01.htm)
- [案件相關查詢](https://www.judicial.gov.tw/tw/np-118-1.html)
- [裁判書查詢（含部分簡易案件）](https://judgment.judicial.gov.tw/FJUD/default.aspx)

## 犯罪/偵查/刑事紀錄
- [調查局 - 外逃通緝犯查詢系統](https://www.mjib.gov.tw/Crimes/Crimes_List)
- [通緝犯資料查詢(公告)平台](https://www.thcw.moj.gov.tw/CriminalWanted/default.html)
- [非法業者違規記錄查詢](https://agent.wda.gov.tw/agentext/agent/QryOther.jsp)
- [各教育場域不適任人員通報及查詢系統](https://unfitinfo.moe.gov.tw/query/logon.jsp)

## 事實查核
- [蘭姆酒吐司](https://rumtoast.com/)
- [台灣事實查核中心 | Taiwan FactCheck Center](https://tfc-taiwan.org.tw/)
- [Line事實查核](https://fact-checker.line.me/)
- [My go Pen](https://www.mygopen.com/)
- [Cofacts真的假的](https://cofacts.g0v.tw/)
- [趨勢科技防詐達人：破解假訊息中的釣魚網址](https://www.nexone.io/zh-tw/product/getdr)

## 惡意程式分析
- [Virus Check](https://viruscheck.tw/)



