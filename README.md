訓練管理整合平台 (Training Management Integration Platform)
這是一個現代化、極簡風格的單頁式應用程式 (SPA) 入口網站，專為訓練中心或機關單位設計。此頁面作為核心樞紐，整合了「訓練流路管理」與「場地借用管理」兩大子系統，提供統一的導航介面。
![alt text](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

![alt text](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

![alt text](https://img.shields.io/badge/Status-Live-success)
🌟 網頁特色
集中式導航：將分散的系統整合於單一入口，提升使用者體驗。
視覺化卡片設計：
訓練流路系統：以藍色系為主色調，象徵規劃與流程。
場地借用系統：以靛紫色為主色調，象徵空間與管理。
RWD 響應式設計：完美支援桌機、平板與手機瀏覽，卡片在小螢幕上會自動調整排列。
互動微效：滑鼠懸停 (Hover) 時具備卡片上浮與陰影加深效果，增加操作回饋感。
🧩 整合系統說明
此入口網頁預設連結至以下兩個子系統：
訓練流路管理系統 (Training Flow System)
功能：年度訓練課程規劃、消防/非消防人員班期安排、自動化甘特圖繪製、A3 報表輸出。
連結識別：藍色圖示 (ri-flow-chart)。
場地借用管理系統 (Venue Booking System)
功能：線上場地預約、衝突檢核、Google Calendar 同步、使用前後照片紀錄上傳。
連結識別：靛紫色圖示 (ri-building-2-fill)。
🛠️ 技術棧
本頁面為純靜態網頁 (Static Web Page)，無需後端伺服器即可運作。
結構: HTML5
樣式: Tailwind CSS (透過 CDN 引入，無需編譯)
圖標: Remix Icon (透過 CDN 引入)
字體: Google Fonts (Inter, Noto Sans TC)
🚀 安裝與設定指南
步驟 1：下載檔案
將 index.html 下載至您的專案資料夾中。
步驟 2：修改系統連結 (重要 ⚠️)
由於目前的程式碼連結到範例網址，您必須將其修改為您實際部署的系統網址。
使用文字編輯器開啟 index.html。
搜尋 System 1 區塊，找到 href 屬性並修改：
code
Html
<!-- 原本的程式碼 -->
<a href="https://sorryxx24.github.io/testhtml/" class="...">

<!-- 修改為您的流路系統網址 -->
<a href="https://您的帳號.github.io/您的流路系統專案/" class="...">
搜尋 System 2 區塊，找到 href 屬性並修改：
code
Html
<!-- 原本的程式碼 -->
<a href="https://sorryxx18.github.io/justtesthtml/" class="...">

<!-- 修改為您的場地系統網址 -->
<a href="https://您的帳號.github.io/您的場地系統專案/" class="...">
步驟 3：客製化內容 (選填)
您可以修改標題與頁尾以符合您的單位名稱：
修改標題：搜尋 <h1>訓練管理整合平台</h1> 進行修改。
修改單位：搜尋 <p class="text-slate-500">臺北市政府消防局教育訓練科</p> 修改為您的單位。
修改頁尾：搜尋 footer 區域的版權宣告文字。
步驟 4：部署
將修改後的 index.html 上傳至 GitHub Pages 或任何網頁伺服器即可使用。
