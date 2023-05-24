## **台股歷史資料庫**
[![Version](https://img.shields.io/badge/version-1.0.0-orange.svg?logo=)]() 
[![Status](https://img.shields.io/badge/status-stable-brightgreen.svg?logo=)]() 
[![Powered by](https://img.shields.io/badge/powered_by-FinMac-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://www.facebook.com/groups/tw.tradingview) 
[![Join](https://img.shields.io/badge/join-QuantHero-blue.svg?logo=facebook)](https://www.facebook.com/groups/data.analysis.investment) 

QuantHero免費提供台股金融數據(項目持續更新中)，包含

* 技術面 : 每日收盤價、開盤價、成交股數
* 基本面 : 當月營收
* 籌碼面 : 外資買賣超股數、投信買賣超股數

`每日更新資料庫，不需自行蒐集數據即可開始分析`

--------

## **快速開始**

```py
import pandas as pd

# 取得台股數據
c = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/close.pkl') # 收盤價
o = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/open.pkl') # 開盤價
v = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/volume.pkl') # 成交股數
fi = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/foreign_investors.pkl') # 外資買賣超股數
it = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/investment_trust.pkl') # 投信買賣超股數
rev = pd.read_pickle('https://github.com/QuantHero-python/twstock_db/raw/main/rev.pkl') # 當月營收
```

------

## **免責聲明**
資料庫提供的所有內容均用於程式教學、非商業用途。資料僅供參考，使用者依本資料交易發生交易損失需自行負責，本團隊不對資料內容錯誤、更新延誤或傳輸中斷負任何責任。
