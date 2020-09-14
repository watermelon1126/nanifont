「何某手寫體」是基於[おつとめフォント](http://rooms.webcrow.jp/)的開放原始碼中文字型。與原作者的主要差異是調整部件寫法、新增中文字、增加為5個字重、增加一些符號。可以免費商用，歡迎大家自由應用、自由優化、自由改作！

![何某手寫體](https://github.com/max32002/nanifont/raw/master/preview/welcome.png)

目前補字中，進度大約70%，預期還要好幾天才會補完，現在是搶鮮版本。

已公開的 ver 1.003 版文字和符號總數大約：12,100個。目前補的中文字數約 3,200 個，預期還有 1,500 個字還在補字中。


## 字體特色

### 彌補繁體中文常用字缺字缺憾

部份口語的中文字缺字，Max補上了這些中文字，例如：喵嗝屌粿璀摳摀憨尪孬憋。

附註： 由於是「非原作者」的補字，新加入的字在風格上，雖然盡力求一致，難免會與原作者會有一些不同。有一些字補的「超級醜」的，如果有好心人有重做那些醜到爆的字，請再分享給我，感謝。

### 5種字重(Style)

* Light
* DemiLight
* Regular (原作者的字重)
* Medium
* SemiBold

原本的おつとめフォント放在Regular 字重裡，透過程式自動產生Light、DemiLight、Medium、SemiBold 新的字重。

在ExtraLight和Light字重是把原本的Otsutome Font微微調細一點點。在Light的字重裡，可能會因為筆劃太細造成某些筆畫消失。

在Medium和SemiBold的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用SemiBold字重看看，如果發現效果不如預期，再改用Medium字重。

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以「不是在Regular字重」裡的筆劃可能會消失。

### 調整標點符號位置

おつとめフォント的全形標點符號針對日本做設計，調整為台灣常見的置中用法。

## 更新日誌
[點擊此處](https://github.com/max32002/nanifont/blob/master/change_log.md) 查看更新記錄。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

WebFont可以服用下面的css:
```
@font-face {
  font-family: nanifont;
  src: url(https://cdn.jsdelivr.net/gh/max32002/nanifont@1.0/webfont/NaniFont-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/nanifont@1.0/webfont/NaniFont-Regular.woff) format("woff");
}
```

## 附註

* 補的缺字，效果差強人意，聊勝於無。
* 「豬」、「箸」日文漢字中的「者」有多一點，大多應該都被Max刪掉了。
* 「戶」部件，目前大多沿用日文寫法「戸」，沒有改成台灣用法「戶」。

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造何某亭所開發、發表的「[Otsutome Font (おつとめフォント)](http://rooms.webcrow.jp/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。
    

## 字體的應用範例

* 汪喵星球 https://www.facebook.com/dogcatstar/posts/3294367807291857


## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

獅尾黑體家族：
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇，如果你覺得這篇文章寫的很好，想打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
