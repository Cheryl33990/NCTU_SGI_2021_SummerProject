# NCTU_SGI_2021_SummerProject
>陽明交大測量及空間資訊領域實習計畫  
>參考資料：khanhha/crack_segmentation https://github.com/khanhha/crack_segmentation  
## 點雲建模結合裂縫偵測應用於人行道現況評估
**研究動機**  
近年來台灣逐漸重視**步行環境建設與品質**，如新竹市的「步行城市計畫」與前瞻基礎建設「提升道路品質計畫」都能反應此趨勢。民眾步行外出的意願與人行道品質有明顯關係，但大部分區域並未有人行道的設置，縱使擁有人行道，也因長期未積極維護，使得表面產生裂縫，而堆放雜物、隨意停放機車等等，除了降低民眾行走意願，還提高危險性，因此我們想著手改善步行環境。然而步行空間之評估是相當複雜的作業，若能使用**簡易攝影測量方式**進行資料收集，是否能**協助評估工作的效率與準確性？**    

**研究目的**  
日前人行道評估使用**多層級、多項目**的方式進行評比，但缺乏整體性與量化資料，因此，本研究想使用**點雲建模**與**深度學習裂縫偵測**進行資料蒐集，用以改善評估的方式與評估工作的準確度，同時增進政府單位與民眾對人行道現況的了解。  

# 目前人行道環境設計與使用狀況評估方法 
>參考資料1：內政部營政署道路工程組 https://myway.cpami.gov.tw/wiki/wikiSession/401  
>參考資料2：內政部營政署道路工程組 https://myway.cpami.gov.tw/evaluate/evaluate-Plan.html  

## 市區道路養護管理暨人行環境無障礙考評計畫 - 作業說明  
>內容節錄自參考資料2，並自行編排。  

**一、考評對象及範圍**  
**(一)考評範圍**  
以22縣市政府各選取4個鄉鎮市區為原則（五萬以上人口之鄉鎮市區為優先選取，其次為三萬以上人口、人口密度每平方公里1,000人以上或受本部營建署相關計畫補助之鄉鎮市區、觀光勝地），亦可由受考評之縣市自行提報接受考評之鄉鎮市區，提報營建署後可納為候選區域之一，考評結果則以縣市為單位呈現。  
**(二)考評對象**  
包括臺北市、新北市、桃園市、臺中市、臺南市、高雄市、 基隆市、新竹市、嘉義市、宜蘭縣、新竹縣、苗栗縣、彰化縣、南投縣、雲 林縣、嘉義縣、屏東縣、花蓮縣、臺東縣、澎湖縣、金門縣及連江縣等 22 個 縣市。

**二、考評分組**  
分為三組，包含「直轄市型」、「縣市型」、「輔導型」。  

**三、考評委員組成**    
![考評項目委員組成示意圖.](https://myway.cpami.gov.tw/evaluate/images/evalue/108/PLAN-org.jpg)
![各考評項目委員建議組成名單與人數整理表.](https://myway.cpami.gov.tw/evaluate/images/evalue/108/PPL.jpg)  

**四、實際作為考評道路與區塊選取**  
![提供考評路段與抽樣數量之原則.](https://myway.cpami.gov.tw/evaluate/images/evalue/108/SESSIONS.jpg)  

**五、評分方式**  
![直轄市及縣市型評分方式示意圖](https://myway.cpami.gov.tw/evaluate/images/evalue/108/Type-Score.jpg)  

## 都市人本交通道路規劃設計
>內容節錄自參考資料1，並自行編排。  

**一、人行環境定義**  
**人行道** ：供行人通行之騎樓、走廊及劃設供行人行走之地面、道路、人行天橋及人行地下道。  
**行人穿越道** ：指在道路上以標線劃設，供行人穿越道路之地方。  
![人行環境示意圖](https://myway.cpami.gov.tw/images/wiki/Book01/photo04-01-01.jpg)    



# 深度學習裂縫偵測 訓練資料集
下載公開資料集：https://drive.google.com/file/d/1xrOqv0-3uMHjZyEUrerOYiYXW_E8SUMP/view
