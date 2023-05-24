## CSS Chapter 17
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## CSS Chapter 17
   Quick Concept outline
   中文摘要說明與重點提問

###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Starter Code
        初始設定說明

###  4. Viewport meta tag
        說明 <meta name="viewport" content="width=device-width, initial-scale=1.0">

###  5. Syntax of a media query
        media query 語法說明:
        @media media type and (condition: breakpoint) {
            // CSS rules
        }

###  6. Think mobile first
        設定 media type 為 screen， condition 為 min-width，breakpoint 為 481px

###  7. Other query types and breakpoints
        (1)設定 media type 為 screen，
        condition 為 orientation，breakpoint 為 landscape，畫面可以由垂直轉為水平
        (2)設定 media type 為 screen，
        condition 為 min-aspect-ratio，breakpoint 為 16 / 9
        (3)設定 media type 為 screen，
        condition 為 min-aspect-ratio，breakpoint 為 7 / 4

###  8. How to choose breakpoints
        Markdown All in One
        說明 常用Media Query, Bootstrap, Tailwind 的 breakpoint

###  9. Build a basic page layout
        (1)在 body 中，設定 background-color 為 #475569，背景色為灰色
        (2)設定 background-image 為 radial-gradient(whitesmoke, #475569)
        (3)設定 display 為 flex，flex-direction 為 column
        (4)在 header, nav, main, footer 中，
        設定 display 為 grid，place-content 為 center
        (5)在 header, footer 中，
        設定 position 為 sticky，background-color 為 #1e293b，color 為 whitesmoke
        (6)在 header 設定 top 為 0，footer 設定 bottom 為 0
        (7)在 main 設定 flex-grow 為 1，填滿 Nav 和 Footer 間的區域
        (8)在 nav 設定白色背景，黑色文字，padding 為 0.5rem，border-bottom 為 2px solid #000
        (9)在 header, nav, main, footer 中，
        設定 grid-template-columns 為 100%，文字置中

### 10. Add a media query
        新增 media query 最小寬度為 576px 時，
        背景為綠色，背景圖片為白煙色和綠色的放射漸層。
        nav 不顯示。

### 11. Use dev tools to view different screen sizes
        使用 Google Chrome 開發工具瀏覽視窗螢幕尺寸不同和水平垂直的變化

### 12. Add all media queries
        (1)新增 media query 最小寬度為 768px 時，
        背景為金色，背景圖片為白煙色和金色的放射漸層。

        (2)新增 media query 最小寬度為 992px 時，
        背景為火磚色，背景圖片為白煙色和火磚色的放射漸層。

        (3)新增 media query 最小寬度為 1200px 時，
        背景為 rebeccapurple ，背景圖片為白煙色和 rebeccapurple 的放射漸層。
        
        (4)新增 media query 最高高度為 425px 和最小圖像縱橫比為 7 / 4 時，
        背景為 dodgerblue，背景圖片為白煙色和 dodgerblue 的放射漸層。
        h1 和 h2 的字體大小為1.5rem，nav 不顯示。

### 13. View each breakpoint change
        使用 Google Chrome 開發工具瀏覽視窗，螢幕尺寸不同、手機設備和水平垂直的變化。
