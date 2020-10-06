# 3D-AR-校園導覽
### 簡介 : 利用360相機結合PhotoShop完成所需素材，再透過Unity實現3D校園街景導覽
### 示意動畫如下:
<img src="readme圖庫/示意 (1)-min.gif" width="400"/><br>
### 本次欲導覽的地方為東海大學圖書館至文理大道(下) :
Start:起始地點 ，End:結束地點，C:創意學院，LAW:法學院，AG:農學院 <br>
<img src="readme圖庫/螢幕擷取畫面 2020-10-06 165119.png" width="400"/> 
# 前置步驟: 蒐集素材->後製素材
1. 利用RICOH THETA V 360°環景攝影機至欲拍攝的地點拍攝<br>
<img src="readme圖庫/360相機.jpg" width="200"/><br>
2. 蒐集完後，會有許多未經加工的原始素材。因有上架腳做拍攝，避免每張照片因高度不同拚結實有斷層感，故每張照片底部都有拍到腳架。示意圖如下:<br>
<img src="readme圖庫/未後製原圖.jpg" width="400"/><br>
3. 我們需要將圖裡腳架移除，因圖形是長方形不方便我們作業，故利用PhotoShop將圖片轉換成圓形。示意圖如下:<br>
<img src="readme圖庫/未後製1.jpg" width="400"/><br>
4. 接著利用PhotoShop技巧，將腳架抹除。示意圖如下:<br>
<img src="readme圖庫/已後製.jpg" width="400"/><br>
5. 再將修改好後的圓形圖片轉換為原來的長方形，所以最後圖片會從這樣:<br>
<img src="原始全景圖檔/R0010115_20181208153909.JPG" width="400"/><br>
變成這樣 : )<br>
<img src="後製全景圖檔/1.JPG" width="400"/><br>
# 將素材匯進Unity:<br>
接下來的步驟呢? 嗯...有點小複雜，總之就是無止盡的寫腳本，串接個張圖檔，點擊按鈕會觸發什麼東西之類的，在這邊我是將全景圖部屬到Unity Sphere的3D空間內，在3D空間內進行操作，這樣使用者看起來才會有3D的感覺，彷彿自身其中。實際怎實作，大家可以載來研究看看。這專案2018年做的，筆者很久沒使用Unity拉 ~~ 可能不太熟悉了😂😂<br>
# 
