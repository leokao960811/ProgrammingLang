# ProgrammingLang
## 授課教師：蔡芸琤老師
- 姓名：高郁城
- 系級：科技系大二

## 課堂練習
各週使用的Google Sheet: https://docs.google.com/spreadsheets/d/1au_UL4MpOzO9ln_6cuIC6Oa_Kozuel3nBtIadjy5Xr4/edit?usp=sharing

聊天機器人: https://colab.research.google.com/drive/1RoaOZU88DyzQ3XKQP93PVe9nDryPbkLp?usp=sharing


- Week 2: https://colab.research.google.com/drive/18fT0RoWwn-Pe6aqgFZyGN3iAdwVgUyNt?usp=sharing

這週所做：Google Sheets I/O, 基本DataFrame操作
  
- Week 3: https://colab.research.google.com/drive/1SHKo2CZjsvXIqplwO56W47cSXEutBt5Q?usp=sharing

這週所做：Gemini API串接、csv輸入Gemini並分析
  
- Week 5: https://colab.research.google.com/drive/1h_PVg9ERh6TnDJESAwNMO008XZAmdAJw?usp=sharing

這週所做：運用plotly繪長條、折線圖

- Week 7: https://colab.research.google.com/drive/1lVezV72nr_U31FddDYFQTl_fT_62JLnk?usp=sharing

這週所做：文字斷句(Jieba、nltk)，句子分析

## 作業連結
- HW 1/Week 4: https://colab.research.google.com/drive/1w5l1xS98GjFkyBqqeR37sSrIjyQIcwOY?usp=sharing

這週所做：讓AI玩1A2B遊戲，並輸出進csv檔中，包含1A2B的判斷函式
  
- HW 2/Week 6: https://colab.research.google.com/drive/1O_7DQWiicZlCvuldUSYR3y4ANMINi7cY?usp=sharing

這週所做：csv讀入並擷取、整理數據，用plotly繪製成圖表，交由ChatGPT分析、運用KMeans分群進行分析

- HW 3/Week 6: https://colab.research.google.com/drive/1O_7DQWiicZlCvuldUSYR3y4ANMINi7cY?usp=sharing

  - KMeans 分析:

![newplot (1)](https://github.com/user-attachments/assets/857709ae-c146-4220-bace-46a65257f523)

    - 這張圖表的聚類基於產品的1星與5星評價數量來進行，觀察不同產品類型的評價模式。
    
    - 分析與趨勢：
    1. 聚類結果顯示四個主要群組
     - 黃色（Cluster 3）：這群數據點主要集中在 **左上角**，顯示這些產品可能有較多的 5 星評論，可能代表「受歡迎的產品」。
     - 橘色（Cluster 2）：這群點分佈較為分散，顯示其評價可能較為均衡，既有 1 星也有 5 星，代表「評價兩極化的產品」。
     - 紫色與深藍色（Cluster 1 & 0）：這些點主要分佈在 較低的主成分 1 值，可能代表 1 星評價較多，屬於「低評價產品」。

     2. 受歡迎產品 vs. 低評價產品
     - 黃色群組（Cluster 3） 主要集中在主成分 1 的 **左側與上方**，可能是高品質、廣受好評的產品。
     - 紫色與深藍色（Cluster 1 & 0） 分佈在 **下方與右側**，這些產品可能是低品質或有較多負面評價的產品。

     3. 兩極化產品的特徵
     - 橙色群組（Cluster 2） 主要位於 **中間區域**，這些產品可能同時擁有大量 1 星和 5 星評價。例如，某些電子產品或消費性產品可能因「品質不穩定」或「特定需求不滿足」導致兩極化評價。

     4. 產品間差異不明顯
     - K-Means 分析後形成的群組沒有特別集中，可能是這些資料本來就很相似。
     
     可能的商業應用
      1. 識別高評價產品 
     - 企業可以根據 Cluster 3（黃色） 來找到受歡迎的產品，進一步分析其特點，作為推廣或生產方向。
   
      2. 分析負評產品
     - Cluster 1 & 0（紫色、深藍色）的產品可能是品質較差或消費者不滿意的產品，可作為改善目標，例如提升品質、改進功能或優化客服體驗。

      3. 注意評價兩極化的產品
     - Cluster 2（橙色） 代表的產品可能具有較大爭議，企業應該關注這些產品的問題，分析為何有極端好評與極端負評，是否為產品品質不穩定或客戶期望錯位等問題。

      結論

      這張 K-Means 聚類圖表顯示了產品在 1 星與 5 星評價上的模式，並透過 PCA 降維讓不同群組的分佈更直觀。企業可以透過這樣的分析來識別受歡迎的產品、
      找出低評價產品的問題，以及處理兩極化評價的產品，以便做出更好的市場決策。

- HW 4/Week 7: https://colab.research.google.com/drive/1lVezV72nr_U31FddDYFQTl_fT_62JLnk?usp=sharing
   - 文字雲/詞頻圖分析：
     ![newplot (5)](https://github.com/user-attachments/assets/daef55c5-2cb8-49d7-a1a5-b8074aece7f3)
     ![newplot (4)](https://github.com/user-attachments/assets/2e9bb965-1ec0-4be4-af46-48fc0b109c2e)

      - 這是第一份資料，內容是一個人在100天內寫的日記節錄。
      - 整體資料相對來說較零碎，但詞頻中feel、feeling次數最多，能推測這個日記主要是書寫自己當日的情緒

     ![newplot (3)](https://github.com/user-attachments/assets/4f4dd1a2-7ffa-4b44-ab0a-40c5ce35efe7)
     ![newplot (2)](https://github.com/user-attachments/assets/7d269784-78a0-4647-a70a-3c0147c2e3a3)

      - 這是第二份資料，內容是中國新聞連播2016至2018-10-09的新聞內容，皆有先經過簡轉繁處理。
      - 內容中，"發展"、"合作"、"經濟"、"建設"這些字出現率高，我會推測國家發展這部分是重要的關注項目。
      - 也因為這是中國的新聞，像是"中央"、"中國"、"習近平"等跟政府有關的字詞出現率也是很高。


## 專題連結
