# Taiwan OSINT tools 臺灣公開來源情資工具

## Google Dorking 查詢
```
"查詢系統" site:".tw"
"地理資訊" site:".tw"
"GIS" site:".tw"
"資訊查詢" site:".tw"
```

## 綜合網站
- [個人化資料自主運用(MyData)](https://mydata.nat.gov.tw/)
- [監理服務網 - 汽機車](https://www.mvdis.gov.tw/m3-emv/car/index#gsc.tab=0)
- [Data Station-開放數據](https://www.datastation.org.tw/opendata)
- [政府資料開放平臺](https://data.gov.tw/)
- [中華民國地政司](https://www.land.moi.gov.tw/chhtml/link1/42)
- [外部資訊查詢申辦 – 犯罪被害人保護協會](https://www.avs.org.tw/page/23005)
- [OpenData專區 - 財團法人金融聯合徵信中心](https://www.jcic.org.tw/main_ch/download_page.aspx?uid=213&pid=213)
- [後備軍人網路服務台](https://afrc.mnd.gov.tw/EFR/Default.aspx)

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
    - https://cctvn.freeway.gov.tw/abs2mjpg/bmjpg?camera=<監視器編號>
    - https://www.twipcam.com/
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

## 交通
- [GIS-T 台灣交通網路地理資訊](https://gist.transportdata.tw/gist_web/)
- [新北市即時交通資訊網](https://atis.ntpc.gov.tw/)
- [桃園市即時交通資訊網](https://tcc.tycg.gov.tw/ATISNew/)
- [高速公路即時路況](https://1968.freeway.gov.tw/)
- [高速公路電子收費欠費查詢](https://www.fetc.net.tw/)
- [桃園機場航班資訊](https://www.taoyuan-airport.com/flight_arrival)
- [交通違規查詢](https://www.mvdis.gov.tw/m3-emv/vil/index#gsc.tab=0)

### 乘車/交通工具相關
- [高鐵悠遊聯名卡電子車票證明查詢系統](https://queryweb.tscc.com.tw/thsrc_web/)
- [捷運悠遊卡加值證明/搭乘證明/常客累計資訊查詢系統](https://queryweb.tscc.com.tw/mrt_web/)
- [捷運一卡通加值/搭乘證明/常客累計資訊查詢系統](https://www.i-pass.com.tw/trtc/)
- [拾得人可領取拾得物資訊查詢](https://web.metro.taipei/losequery2019/querybypicker)

### 船隻/船舶
- [交通部航港局 公開服務](https://web02.mtnet.gov.tw/0/Info/Link/0)
    :::spoiler
    * 港區危險物品專責人員線上服務平臺
    * 臺灣遊艇入口網
    * 油化相關船舶QRCode
    * 動力浮具線上服務平臺
    * 船東責任保險公司分級查詢
    * 航路標識服務費
    * 遊艇入出境及特許申請
    * 登船作業人員健康監測表
    * 國輪船名掛號申請
    * 自由貿易港區專用車隊車證效期查詢
    * 商港服務費查詢系統
    * 中央氣象局「海象測報」
    * 高雄港船舶動態通報整合系統
    * 臺灣港棧服務網
    * 逾檢船舶公開資料查詢
    * 船舶／小船／遊艇線上預約檢丈申請
    * 線上預約檢丈申請進度查詢及取消預約
    * 航船布告
    * 船員智慧服務平臺
    * 航運業公司基本資料查詢
    * 船員查驗平臺 Seafarers Verification
    * iMarine航港發展資料庫
    * 數位學習暨試務管理系統會員申請
    * 線上船名預約取消
    * 國內固定船班資訊查詢
    :::
- [臺灣海域船舶動態資訊系統](https://mpbais.motcmpb.gov.tw/aismpb/)
- [船舶動態查詢 RSS](https://www.motcmpb.gov.tw/Information?siteId=1&nodeId=165)
- [逾期檢丈船舶查詢](https://web02.mtnet.gov.tw/0/Info/Link/0)

### 班機
- [班機即時離到站資訊](https://www.caa.gov.tw/ImmediateFlight.aspx?a=270&lang=1)
- [客機抵達-桃園國際機場](https://www.taoyuan-airport.com/flight_arrival)
[高雄國際航空站- 即時航班](https://www.kia.gov.tw/InstantScheduleC001110.aspx?ArrDep=2)
- [航班資訊|國際及兩岸航班|今日航班|台北松山機場](https://www.tsa.gov.tw/flights/international/today?culture=1)	
- [臺中國際機場 班機即時資訊](https://www.tca.gov.tw/cht/index.php?act=fids&code=now)
- [國內定期航線班機時刻表](https://www.caa.gov.tw/RegularFlight.aspx?a=268&lang=1)


### 交通事故
- [道路交通事故資料申請系統](https://tm2.npa.gov.tw/NM105-505ClientRWD2/TM02A01Q_01.jsp)
- [車輛行車事故鑑定查詢](https://www.mvdis.gov.tw/m3-emv-vil/cac/massQuery#gsc.tab=0)

### 網路
- [行動通訊網路涵蓋資訊查詢](https://www.ncc.gov.tw/chinese/news.aspx?site_content_sn=5678&is_history=0)
- [NCC頻率資料庫查詢系統 - freqdbo - 國家通訊傳播委員會](https://freqdbo.ncc.gov.tw/Portal/NCCB06Q_01v1.aspx)

## 旅遊
- [導遊＆領隊資訊查詢](https://travelagency.tad.gov.tw/DataQuery/Tour_GuideNow.aspx)
- [交通部觀光署露營區資訊查詢專區-合法露營場資料查詢](https://camp.tad.gov.tw/CMZ/legal.jsp)

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
- [新北市垃圾清運資訊查詢網](https://crd-rubbish.epd.ntpc.gov.tw)
- [列管污染源資料 (含裁處資訊) 查詢系統](https://prtr.moenv.gov.tw/index.html)
- [毒性及關注化學物質快速查詢](https://www.cha.gov.tw/sp-toch-list-1.html)

## 自然科學
### 海洋
- [國家海洋資料庫及共享平台](https://nodass.namr.gov.tw/data)


### 醫學
- [國家級人體生物資料庫整合平台](https://nbct.nhri.org.tw/docDetail.aspx?uid=36&pid=17&docid=10003&rn=25297)

## 健康/醫療/急救
- [全國癌症篩檢活動暨醫療院所資訊查詢](https://escreening.hpa.gov.tw/)
- [衛生福利部 緊急醫療管理系統](https://ems.mohw.gov.tw/)

## 考試
- [大學入學考試中心](https://ap.ceec.edu.tw/RegExam/ExamInfo)

## 學術系統
- [國科會 - 學術人才查詢](https://arspb.nstc.gov.tw/NSCWebFront/modules/talentSearch/talentSearch.do?action=initSearchList&LANG=ch)
- [國科會 - 統計資料庫](https://wsts.nstc.gov.tw/STSWeb/main/Main.aspx)
- [政府研究資訊系統 GRB](https://www.grb.gov.tw/search)
- [教育部大專校院校務資訊公開平臺](https://udb.moe.edu.tw/udata/)

## 政治
- [選舉及公投資料庫](https://db.cec.gov.tw/ElecTable/Election?type=President)

## 財政/金融
- [財政部全國統計資料庫](https://www.mof.gov.tw/htmlList/100)
- [金融監督管理委員會銀行局 金融統計資料庫動態查詢系統](https://survey.banking.gov.tw/statis/webMain.aspx?sys=100&funid=defqry)

## 司法/法律
- [司法院查詢服務](https://www.judicial.gov.tw/tw/np-117-1.html)
- [司法院資料開放平臺](https://opendata.judicial.gov.tw/)
- [法人及夫妻財產登記公告查詢](https://aomp109.judicial.gov.tw/judbp/whd6k/WHD6K01.htm)
- [案件相關查詢](https://www.judicial.gov.tw/tw/np-118-1.html)
- [裁判書查詢（含部分簡易案件）](https://judgment.judicial.gov.tw/FJUD/default.aspx)
- [全國法規資料庫](https://law.moj.gov.tw/)

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



