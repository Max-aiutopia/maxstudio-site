# maxstudio.biz 官網（原始檔）

單一 `index.html`（中英切換，預設照瀏覽器語言，網址加 `?lang=en` 強制英文）＋ `favicon.svg`。
2026-10-12 Max 定位：**律師事務所的前端團隊**（同業研究、定位規劃、內容製作、導流與線上課程、月報）。不放 AI、不放廣告投放的東西。暗底雜誌風（Bodoni Moda＋Noto Serif TC），參考 artie.com.tw、finpo.com.tw 的全螢幕選單和分區。字標用 `03_內容產線/設計系統_MAXSTUDIO/upload/maxstudio-tag.svg`。

- 線上：GitHub repo `Max-aiutopia/maxstudio-site`，GitHub Pages 從 main 根目錄發布。預覽 https://max-aiutopia.github.io/maxstudio-site/ ；正式網域 maxstudio.biz（CNAME 檔）。
- 案例內容來源：`20_接案_Studio/03_Clients/Taiwan Legacy - IG Organic Content/`（規劃頁 `00_Scope/2026-10-10_taiwanlegacy_proposal_brief/`、對標 `02_Process/2026-10-10_taiwanlegacy_benchmark_asia_v02.md`、合約 v01）。網站上事務所匿名、不放數字以外的客戶資料、題目卡是示意題不是客戶的題目表。
- 改完：`git -C <這個資料夾> add -A && git commit -m "..." && git push`，Pages 一兩分鐘後更新。
- 2026-10-12 建，給 Claude for Startups 申請當公司網站用。

## 廣告投放版 `ads/`（2026-10-15）

Max 10/15 要的第二個版本：**電商與課程品牌的廣告投放團隊**，同一套暗色雜誌版型，案例用水果電商和頭家校院那兩類。網址是主站底下的 `/ads/`（預覽 https://max-aiutopia.github.io/maxstudio-site/ads/ ，英文 `?lang=en`）。主站沒改、沒連過來；ads 版的選單和聯絡區有連回主站的連結。

- 數字來源：`new ADS way/clients/bigmicfruit/_結案數據_截至2026-09-18/README.md`（NT$444,001、989 購、ROAS 4.01、逐月表）和 `_封存_maxstudio舊案/客戶見證/`（四帳號總表、stories.json 的切角與沒成的案子、2,895 個交付檔）。客戶一律匿名（台灣生鮮水果電商、企業主培訓機構、成人保健電商、居家香氛品牌），照客戶見證 README 的對照表；客戶的損益線、毛利率、CPA 上限不放。
- 頭家校院那段寫的是「以內容規劃師身分進駐」，工作內容照備份碟上的交接文件（90 天拆解、7／2／1 選題、13 支廣告腳本、資格表、週報四指標），沒有成效數字，因為 Mac 上沒有。
- 水果案的角色寫法照客戶見證的界線：策略、素材、判讀是我們，媒體採買由合作投放端執行。Max 之後自己投放的話這句要改。
- 沒放客戶的廣告素材圖，放了會認得出是哪家；要放先問客戶。
