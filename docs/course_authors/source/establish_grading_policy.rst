************
建立評分標準  
************
  

簡介 
****
  
  
在 edX 中成績是基於作業以及測驗所計算出來的。


在 Studio 中設定成績的計算方式有許多步驟，這些步驟將會在接下來的課程中詳細解釋。
要跳到詳細資訊，請點擊下面的連結。 
  

1. 建立一個整體評分標準，請參考 :ref:`設定分數級距 <Set-Grade-Brackets>`.
          
.. image:: Images/image139.png

這部份需於課程內部的 **課程設定** 選單完成。
  
再來您要建立課程的評分方式為及格與否或是等第制，同時設定每個等第之間的級距。     

建立課程課程的作業練習，並為每次的作業設定評分的比重。
舉例來說，您可以設定一共有十次的作業，這些作業佔期末總分的50%；三次考試，每次佔期末總分的10%以及一次佔20%的期末考。
Studio 預設會為您的課程產生：回家作業、實作、期中以及期末考試等四種不同的作業類型。
您可以建立額外的評分方式，例如小考。
    
            
2. 在課程中建立一個包含評分作業的小節，請參考 :ref:`建立包含評分作業的小節 <Create-Graded-Subsections>`.


.. image:: Images/image135.png


您課程中的每一個小節都可以被設計在您的評分機制標準當中，學生必須完成該小節指定的作業才能得到分數。
您也可以指定小節的發佈日期以及截止日期。
  
  
.. note::
	
		您可以直接在 Studio 建立一個問題而不必指定此問題隸屬於哪個小節，然而除非此問題屬於某個小節，不然無法列入評分機制的計算範圍中。

有關如何建立問題更多資訊，請參考 `創建問題 <create_problem.html>`_ 文件中的說明。 
 
3. 在作業小節中，創建個別的問題。 

.. image:: Images/image137.png
  
  
您可以稍後為這些問題做設定，包含了需要每題學生可以嘗試的次數、問題的分數以及權重等。

當評分標準建立以後，學生在進度列中可以看到針對問題的得分、完成的比例以及目前的評比結果。

此外，身為老師的您可以存取所有學生的分數以及問題的答案。
在 Edge 上已經發佈的頁面上 (不是 Studio 中的預覽頁面) 點選教師的分頁，您可以檢視或是下載目前評分的內容。  
於教師的分頁上，您同時可以檢視所有學生個別的進度、成績已經尚未評分的問題。
若需要更詳細的資訊，請參考 `檢查學生的進度以及證書核發 <checking_student_progress.html>`_ 文件中的說明。

  
.. _Set-Grade-Brackets:

設定分數級距
++++++++++++
  
設定課程評分的等級
    
1. 在導覽列點擊 **課程設定** ，接著點擊 **評分** 。
  
2. 在 **總體等級範圍** ，點擊並拖曳評分分級之間的分數條以移動分數上下界線。
  
.. note::

	預設的評分分級為及格與不及格。 要增加更多評分分級 (例如 A, B, C, 及 D)，請點擊加號 (+)。
    
  
.. image:: Images/image133.png    

要移除評分分級，用滑鼠滑過評分分級 (如上圖所示) 接著點擊出現在評分分級上的 **移除** 連結。


.. _Set-Grace-Period:

設定寬限期 
++++++++++
    
您可以為您的學生設定一個寬限期，允許他們遲交作業。
請注意，寬限期會套用到整門課程上，您無法單獨為一次作業設定寬限期。  
  
1. 在導覽列點擊 **課程設定** ，接著點擊 **評分** 。
  
  
2. 在 **截止日期的寬限時間** 框中的 **評分規則與策略** 輸入數值。
  
  
創建作業類別
++++++++++++
  
  
當您創建課程時，Studio 預設會包含四種作業類型：回家作業、實作、期中以及期末考試。 
您可以設定每種類別於學生整體分數所佔的比重。
  
  
要設定一個作業類別：
  
  
1. 在導覽列點擊 **課程設定** ，接著點擊 **評分** 。
  
  
2. 在 **作業類別** 找到您要的作業類別設定。
  
  
若您想要創建新的作業類別，捲動到頁面底部，點擊 **新增作業類別** 。
  
  
3. 輸入下列方格中的數值。
  
  
**作業類別名稱** 
這邊列出了常見的測驗類別 (回家作業、考試、練習等)。
所有相同類別的作業在分數評分上有一樣的權重，這邊定義的名稱將會顯示給學生作為參考。
  
  
**簡稱** 
這是會顯示在學生的 **進度** 分頁旁的短名(請見下圖)。
  
.. image:: Images/image141.png
      
  
**在總分中的權重** 
作業在總分計算中所佔的權重可以百分比的形式設定在 **在總分中的權重** 裡。
  
  
**作業總量** 
您想呈現在課程中的作業類別的數量。
  
  
**可拋棄的數量**
(選項)：指定評分程式可以拋棄的數量，評分程式會從最低分的成績開始拋棄。
  
  
例如，以下的課程有兩種作業類別。整個課程的成績分為40%回家作業及60%期末考試，其中回家作業一共有八次。
評分程式會從最後成績中拋棄獲得最低分的作業，因此，剩下的七次作業佔據期末總分的比例就從原本 40/8 = 5% 變成 40/7 = 5.8%。
  
.. image:: Images/image143.png
          
故障排除
++++++++
   
若您創建作業類別時發生問題，嘗試下列方法排除問題。
        
在 **在總分中的權重** 欄位，請忽略 % 百分比符號。
同時確定所有問題中 **在總分中的權重** 欄位最後加總起來為一百。


.. raw:: latex
  
      \newpage %

.. _Create-Graded-Subsections:

創建包含評分作業的小節
**********************
   
在您建立您的課程評分標準之後，您可以開始建立評分作業或是測驗。
要開始之前，您必須先創建一個小節並設定其評分，包含設定作業類型、開始時間以及截止時間
  

.. note::

	當您設定截止日期時，請注意學生可能來自世界各地不同時區。
	系統預設使用 UTC 表示時間，當您設定時間為 5 PM 的時候，請提醒學生是 5 PM UTC，以防他們錯過作業或是測驗的繳交時間。
      
  
另外，您可以參考 :ref:`設定寬限期 <Set-Grace-Period>` 的教學設定寬限期，防止有任何誤會發生時無法彌補。
舉例來說，若您設定寬限期為一天，那您的課程中所有的評分作業都會套用這個設定值，無一例外。
      
請記住一個小節中只能有一種作業類別。
若您想為某一主題創建一個回家作業以及實作，您可以為這個主題建立兩個小節。
您可以設定其中一個小節為「回家作業」類型，另外一個為「實作」類型，兩個小節可以有完全不一樣的說明及問題，如何應用由您自己決定。

由於所有的作業都會分享該種作業的評分權重，因此若是一個回家作業包含了十個艱難的問題，其權重跟另一個回家作業包含五個簡單的問題是一樣的。
請於設定時考量難易度分配題目數量，或是利用建立多次作業來分散分數。  


1. 在導覽列點擊 **課程內容** ，接著點擊 **大綱** 。
  
  
.. image:: Images/image145.png

      
2. 在 **課程大綱** 中找到您想要增加作業的章節。
  
3. 在章節名稱區塊中，點擊 **建立新小節** 。
       
4. 在文字方塊中，以您的小節名稱取代 **建立新小節** ，接著點擊 **儲存** 。
      
點擊您要編輯的小節，開啟此小節的編輯頁面。
在頁面的右上角，找到 **小節設定** 對話框。


.. image:: Images/image147.png     
      
設定作業類別，請參考下圖，找到 **當前評分方式** 旁的藍色連結。
因為所有小節都預設設為 **不評分** ，所以目前此連結顯示的文字是 **不評分** 。

.. image:: Images/image149.png  
    
點選此連結，您會看到一個清單顯示目前所有的作業類別，您可以從中點選您要的類別。
  
  
.. image:: Images/image151.png   

設定作業的發佈日期及時間。請點擊 **發佈日期** 欄位，接著在出現的月曆中選取您要的發佈日期。
要設定發佈時間，點擊時間輸入欄位，接著指定您要的時間。
       
要為作業設定截止日期。請點擊藍色 **設定截止日期** 連結，接著點擊 **截止日期** 對話框，接著在出現的月曆中選取您要的截止日期。
要設定截止時間，點擊時間輸入欄位，接著指定您要的時間。

修改小節的作業類別
++++++++++++++++++
  
要為一個小節設定作業類別：
  
1. 在導覽列點擊 **課程內容** 接著點擊 **課程大綱** 。

2. 在 **課程大綱** 中找到您要的小節。
  
3. 注意畫面右側，點擊小節的藍色圈選方格，並選取作業分類。
  
.. image:: Images/image153.png   

.. note::

	若您在評分頁裡修改了作業分類名稱，您需要確定其依然與課程大綱裡的作業類別名稱一致。
