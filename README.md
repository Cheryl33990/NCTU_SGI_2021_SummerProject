# NCTU_SGI_2021_SummerProject
>陽明交大測量及空間資訊領域實習計畫  
>參考資料：khanhha/crack_segmentation https://github.com/khanhha/crack_segmentation  
## 人能弘道-AI人行道巡檢
**研究動機**  
步行環境品質與人行設施建設狀況在台灣逐漸受到重視，**新竹市的「步行城市計畫」**與**前瞻基礎建設「提升道路品質計畫」** 都能反應此趨勢。
但是回顧自身行走的經驗，使用人行道的意願與其品質有明顯關係，若人行道長期未積極維護，就容易使鋪面產生裂縫和突起，造成行走不便和危險；人行道也常常被堆放雜物、停放機車等等，進而產生阻礙降
低民眾的步行意願。改善步行環境需要對現有人行空間進行資勘查與評估，檢視目前台灣
對人行環境的評估方式，可以看到**部分現有的評估指標評分方式過於主觀或缺乏全面性**，
屬於定性評估，較缺乏定量評估。本研究之研究動機是探討以攝影測量及 AI 技術，建立人行道量化評估指標。  
**點雲資料**可以由光達與攝影測量兩種方式產生，前者的產製時間較快但需要專門的裝置才能建模，而且光達的價格較為昂貴目前尚未普及，僅有較高階的消費行裝置設有光達相機。另一方面，消費行裝置隨著相機鏡頭的進步，**使用手機進行攝影測量建模**已經相當成熟，如 SCANN3D 等 APP 應用程式就能直接在手機上影像拍攝進行模型建置，大大的降低攝影測量的操作門檻。使用**深度學習偵測人行道二維圖像裂縫**，可以清楚辨識裂縫位置，結合點雲資料就能獲得具有真實尺度的裂縫資料，方便進行後續分析，並能夠以**視覺化方式直觀呈現**。結合攝影測量自動化產製三維點雲及影像 AI 智慧化判識的優點，可結合兩者的成果建立人行道量化評估指標。

**研究目的**  
本研究**針對台灣人行環境評估的方式進行改善**，使用點雲建模與深度學習裂縫偵測，將原評估方式中較為主觀與片面的指標改為較為全面且客觀的指標；本研究將使用較常見的**消費型裝置蒐集資料**，挑戰以**低成本**的方式將人行道的環境還原重現。此模式將能使決策單位有效對人行道進行資料收集與評估，也可以採用群眾外包（Crowdsourcing）的方式由使用者進行資料收集，**建立完善的人行道資料庫**。

