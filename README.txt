狗狗廁所紀錄（PWA）上架到 GitHub Pages 的步驟
================================================

一、建立網站
1. 登入 GitHub，右上角「+」→「New repository」。
2. Repository name 隨意，例如 dog-toilet；選 Public；按「Create repository」。
3. 在新頁面按「uploading an existing file」，把這個資料夾裡的 6 個檔案一次拖進去：
   index.html、manifest.webmanifest、sw.js、icon-192.png、icon-512.png、icon-maskable-512.png
   （不要放進子資料夾；README.txt 可放可不放）
4. 按「Commit changes」。
5. 到 Settings → Pages → Build and deployment：
   Source 選「Deploy from a branch」，Branch 選 main、資料夾選 / (root)，按 Save。
6. 等 1～2 分鐘，網址會是 https://你的帳號.github.io/dog-toilet/

二、安裝到手機
1. 用手機的 Chrome 打開上面的網址（要連網，第一次需要把檔案載進手機）。
2. 看到頁面下方的「📲 安裝到主畫面」按鈕就按它；沒有的話，點 Chrome 右上角「⋮」→「安裝應用程式」（或「加到主畫面」）。
3. 之後從主畫面圖示開啟，沒有網路也能用。

三、更新版本
改了 index.html 之後，要把 sw.js 第一行的版本號加 1（例如 dogpotty-v1 改成 dogpotty-v2），
重新上傳這兩個檔案。手機下次連網開啟時會更新，可能要開兩次才會看到新版。

四、備份（很重要）
資料只存在這支手機的 app 裡。換手機、清除 Chrome 資料、或解除安裝 app，紀錄都會消失。
請定期到頁面最下方按「下載 CSV」；要還原時按「匯入 CSV」，重複的紀錄會自動略過。
