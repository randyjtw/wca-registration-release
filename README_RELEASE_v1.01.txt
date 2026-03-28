WCA 報名 Release 1.01

檔案說明：
1) wca_registration_v1.01_mac_arm64
   - 適用：Apple Silicon Mac (M1/M2/M3)

2) wca_registration_v1.01_mac_amd64
   - 適用：Intel Mac

3) wca_registration_v1.01_win_x64.exe
   - 適用：Windows 64-bit (x64)

使用方式：
- 執行對應平台檔案後，開啟瀏覽器進入：
  http://127.0.0.1:18080

主要功能：
- 操作頁統一設定「報名網址（Registration頁結尾為：/registration）」
- 人員 1 不可刪除；人員 2 之後可移除
- 併發執行多人報名流程（非依序）
- 報名時間窗控制：開始前 5 分鐘到開始後 5 分鐘
- 新增輸入 WCA ID 後點擊 GO!。
- 進入報名頁與表單頁時自動儲存 HTML 快照到 analysis_snapshots/
- 降低終端機輪詢噪音：不再持續列印 GET /api/job/... 心跳請求

注意：
- 報名網址需為 registration 頁，且以 /registration 結尾。
- 請自行填入實際活動報名網址。
