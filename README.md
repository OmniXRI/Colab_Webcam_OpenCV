# Colab_Webcam_OpenCV

一般使用Google Colab時可以透過JavaScript程式和本地端網路攝影機連接，取得串流影像後透過網頁元件即可顯示。

目前Colab提供的「程式碼片段」範例可以連結本地端網路攝影機進行連續取像及顯示，但只能取得最後一張影像後，再以靜態方式（如OpenCV, PIL等）進行處理及顯示，無法於取像過程進行自定義影像處理。  

本範例 Colab_Webcam_OpenCV.ipynb 提供二種模式解決方案。  

模式一：使用網路攝影機連續取像並顯示，按下取像鍵後才使用OpenCV進行自定義影像處理及顯示結果。  

模式二：使用網路攝影機連續取像並顯示，在取像過程同時執行OpenCV自定義影像處理及顯示結果。  

點擊下列連結可直接以Google Colab開啟程式並執行。  
https://colab.research.google.com/github/OmniXRI/Colab_Webcam_OpenCV/blob/main/Colab_Webcam_OpenCV.ipynb
