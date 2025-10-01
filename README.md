# 什麼是 git, GitHub, gist 與 cmsimde?
2025 10 01

I. Git 
   
<img width="310" height="163" alt="image" src="https://github.com/user-attachments/assets/1d93a98d-b940-475f-987e-3035c1002ce9" />

一種 分散式版本控制系統 (VCS)。

主要用來追蹤程式碼或檔案的變化。

每個開發者電腦上都可以有完整的專案歷史（不是只有在伺服器）。

核心功能：

1.commit：記錄檔案當下的版本

2.branch：分支，方便多人開發或嘗試不同功能

3.merge：合併不同分支的修改

4.clone / pull / push：從遠端下載或上傳專案


II. GitHub

 <img width="369" height="136" alt="image" src="https://github.com/user-attachments/assets/423f6f1e-ee10-49c7-86db-b408a965ee67" />
 
一個基於 Git 的 雲端程式碼託管平台。

你可以把專案放到 GitHub 上，方便協作與分享。

附加功能：

1.Issue / PR（Pull Request）協作機制

2.權限管理（Collaborators、Organizations）

3.CI/CD 整合（自動測試、部署）

4.社群功能（追蹤、star、fork）

主要差別：Git 是工具，GitHub 是平台。

III. Gist

   <img width="1355" height="1025" alt="image" src="https://github.com/user-attachments/assets/f36d50af-b85a-4a29-a061-4edc50fbf95f" />


GitHub 提供的一個 迷你 Git 儲存庫。

用來快速分享小段程式碼、設定檔、筆記。

支援版本控制，甚至可以是「公開」或「私密」。

常見用途：

1.分享程式範例

2.存放設定檔

3.Markdown 筆記

IV. cmsimde

cmsimde是一個 專案名稱。cmsimde = Content Management System in Markdown and Dropbox Environment。

用於靜態網站生成，搭配 Markdown 來寫內容，並透過 GitHub Pages 發佈。

特點：

用 Markdown 寫文章 → 轉成 HTML → 自動變成網站

靠 Git/GitHub 管理版本

cmsimde 是一個結合 GitHub Pages + Markdown 的輕量級 CMS（內容管理系統）。
