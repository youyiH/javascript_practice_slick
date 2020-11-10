# javascript_practice_slick
JS基礎練習

# 範例
 https://youyih.github.io/javascript_practice_slick/
 
 # 使用說明

 ## CDN

```
<!-- CSS-放head -->
<link rel="stylesheet" href="https://youyih.github.io/javascript_practice_slick/.style.css">
<!-- JS放body最下方 -->
<script src="https://youyih.github.io/javascript_practice_slick/.script.js"></script>
```
## 架構

```
    <!-- data-slider-duration 自動播放時間 -->
    <div id="kid-slider" data-slider-duration="3000">

        <!-- 輪播圖項目:根據需求複製貼上 active 只有一組 -->
        <div class="kid-item kid-active">
            <img src="./photo/1.jpg" alt="">
            <h1>WHITE</h1>
        </div>

        <div class="kid-item">
            <img src="./photo/2.jpg" alt="">
            <h1>SNOW</h1>
        </div>

        <div class="kid-item">
            <img src="./photo/3.jpg" alt="">
            <h1>EVERYTHING</h1>
        </div>

        <!-- 大顆按扭區塊 -->
        <div id="kid-prev"></div>
        <div id="kid-next"></div>

        <!-- 小顆按鈕區塊:根據需求複製貼上 active 只有一組  -->
        <!-- item可增加,但編號必須接續上面編號(2-3新增一個則為4) -->
        <div id="kid-buttons">
            <div class="kid-button kid-button-active " data-slider-item="1"></div>
            <div class="kid-button" data-slider-item="2"></div>
            <div class="kid-button" data-slider-item="3"></div>
        </div>

    </div>
