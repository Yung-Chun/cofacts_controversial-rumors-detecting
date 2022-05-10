# cofacts_controversial-rumors-detecting

## cofacts_01_define rumor
同一篇回報會有不同的查證結果，有時不一定一致；針對每篇查證，社群使用者可以like or dislike  
因此將like/dislike與查證結果加權，以決定查證結果不一致時須採用何者作為最終結果  
比對常規化後的結果仍然一致
常規化後的truth score可以比較不同篇回報的真實指數  

## cofacts_02_cleansing and clustering
將斷詞後的檔案輸入並清理  
簡轉繁、刪除英文與數字組成的segment（因此只能處理中文）  
分群方法結合HAC與KNN演算法  
文獻參考 https://medinform.jmir.org/2021/11/e30467  

## cofacts_03_sort_rumor
indicator 1: 每群裡面有幾種變體  
indicator 2: 每篇文章在特定區間內有多少查詢瀏覽量  
indicator 3: 每群文章在特定區間內有多少查詢瀏覽量  

## cofacts_04_visualization_rumor
針對不同需求、種類視覺化  
