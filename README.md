# AMB82-Mini 3D PCB 及外殼製作 
### Noted: 
### 此開源STL file 已移除Logo, 以免誤導
### 此開源STL files 僅供個人使用, 請勿商業販售
### 此開源STL files 並無提供天線固定板

<img width="947" alt="image" src="https://user-images.githubusercontent.com/14821404/225515373-697c5b50-3d29-4d05-9168-84e320ced42a.png">

---

## 0-1、前言
   **最近購買了兩片Realtek出品的AMB82-Mini，這是由iCShop代理發售的IOT視覺開發板。據稱，它的影像效能可以輕易輾壓ESP32-Cam，我對此非常感興趣，並期待它帶來的效益。
然而，當我進行實驗測試時，總覺裸板容易因短路或靜電干擾而出現麻煩。儘管我嘗試在網路、論壇和臉書上尋找AMB82-Mini PCB的3D模型和外殼，但徒勞無功。因此，只好先放下功能測試，轉而著手繪製PCB的3D模型和外殼設計。** 

---

## 1-1、AMB82-Mini 簡介
   **Ameba 是一個易於編程的平台，用於開發各種物聯網應用程序。 AMB82 MINI配備豐富的外圍接口，包括WiFi、BLE、GPIO INT、I2C、UART、SPI、PWM、ADC。通過這些接口，AMB82 MINI可以連接LED、開關、壓力計、濕度計、PM2.5粉塵傳感器等電子元器件。此外，AMB82 MINI 具有 3 個主要功能，音頻編解碼器、視頻編解碼器和 NN（內置 NPU，用於 AIoT）。**


## 1-2、AMB82-Mini GPIO Pin 
![](https://i.imgur.com/OJ3cHYd.png)


## 1-3、AMB82-Mini 相關資源網站
   
[MB82-Mini各項資源連結](https://www.amebaiot.com/zh/ameba-arduino-summary/?fbclid=IwAR3egVAu4DMTtHzt4R31GiRRCqC15gZ0QDZg-C6S1O3NHGe2dtnVOD6ZLgc)

[Getting start](https://www.amebaiot.com/zh/amebapro2-amb82-mini-arduino-getting-started/)

[Youtube 教學連結](https://www.youtube.com/@amebaiot7033)



---
## 2-1、AMB82-Mini PCB 3D 圖檔
![](https://i.imgur.com/P4PGDFQ.png)
**繪製外殼的方式有兩種:**
 **1. 直接繪製外殼：用游標卡尺先對PCB板量測,再重複修改列印,直到最佳狀態, 不過會浪費很多3D 列印測試材料及時間.**
 **2. 先繪製PCB 3D模型： 小弟選擇這種方式, 當廠商沒有提供PCB 3D圖檔時, 可以自行製作, 不需要把細節做出來, 只要關鍵尺寸夠拿來建外殼即可, 例如下圖的各項元件高度要有一定精準度.**


![](https://i.imgur.com/1csGNte.png)



## 2-2、繪製外殼3D 圖檔

 **1. 直接匯入PCB 3D 圖檔, 並在上面量測繪製結構, 這樣就不需再手動用游標卡尺量測, 又可以在上面做組裝調整外觀顏色.**
 ![](https://i.imgur.com/Vez7B5J.png)

 
 **2. 接下來就可以依序完成並模擬組裝測試**
![](https://i.imgur.com/ObXAtC0.png)


---




**由左至右依順改出3款**
![](https://i.imgur.com/qFOG24N.jpg)

**總算完成第一版的外殼**

![](https://i.imgur.com/mKc0Pze.jpg)


**全磁吸外殼設計, 前後蓋加後背共9 顆(3x6mm)的磁鐵**

![](https://i.imgur.com/2caIb1T.jpg)

![](https://i.imgur.com/OcSTwfh.jpg)

**辦公室的partition 可以輕易磁吸固定, 方便做實驗~**
![](https://i.imgur.com/fBlyFL3.jpg)



---

## 4-1、零件細項

| 項次. 品名	 |  組數	|
| -------- | -------- | 
| 1. 3DP 外殼正面  |  1    | 
| 2. 3DP 外殼背板   |   1   | 
| 3. 3DP 鏡頭外飾 | 1  | 
| 4. (3x6mm)的磁鐵  | 9 顆 | 


## 4-2、安裝方式

![](https://i.imgur.com/G6b7UZK.jpg)

**請確保磁鐵的方向性.**
![](https://i.imgur.com/QFn7YG0.jpg)

![](https://i.imgur.com/Q1r7WsZ.jpg)
**當一面完成後, 請將另外3顆磁鐵吸在已經完成的那一面, 並用手輕輕壓進另一側, 之後再用鉗子壓緊.**
![](https://i.imgur.com/F9nS9qz.jpg)

![](https://i.imgur.com/9plXym9.jpg)

![](https://i.imgur.com/kVPdfki.jpg)
**裝上飾板.**
![](https://i.imgur.com/NwuehoA.jpg)

![](https://i.imgur.com/GM5Qfe6.jpg)

![](https://i.imgur.com/ETYJD2Z.jpg)
**將天線放入天線固定板內.**
![](https://i.imgur.com/3FVxrke.jpg)

![](https://i.imgur.com/U029sSx.jpg)


## 5、Show Time
**感受RGB同時亮起的氣氛.**

![](https://i.imgur.com/07SuzAN.png)

![](https://i.imgur.com/9uhe0ZQ.jpg)

![](https://i.imgur.com/rVNIJIR.jpg)

![](https://i.imgur.com/Z22oTSa.jpg)

![](https://i.imgur.com/6vjMNpK.jpg)
