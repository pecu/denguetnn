# denguetnn
台南市登革熱查詢
本來想做一個針對台南市登革熱即時查詢的系統，並轉成Android APP，
但是只要台南市政府的登革熱開放資料更新上傳，其ID值就會改變，
而ID值又是讀取資料的必要條件，所以目前程式開發到一半就停止了，
雖然程式只開發到一半，但是ajax、d3.js地圖等功能都有加入，
於是把它放上來備存，以後如有類似的應用，就可以參考。

在D3.js的地圖上，每個紅點就是一個登革熱確診患者，由地圖可知範圍，
可能會有部份的紅點不在區域上，有部份可能是原始資料有誤或是誤差值過大。

傳染病防治法規定須保障病患隱私，所以台南市政府的病例座標有經過調整，
估計約有150M到200M的誤差值，這是守法保護病患隱私應有的作法。
