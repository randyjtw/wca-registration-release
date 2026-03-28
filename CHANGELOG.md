# Changelog

## [1.01] - 2026-03-28

### Added
- 操作頁新增「報名時間」控制，僅在開始前 5 分鐘到開始後 5 分鐘內執行。
- 支援多人資料併發執行（非依序逐一）。
- 報名網址欄位提示調整為：`報名網址（Registration頁結尾為：/registration）`。
- 人員頁支援刪除人員 2 之後的分頁，人員 1 固定保留。
- 流程對齊 Python：進入 `/registration/select` 後輸入 WCA ID，並點擊 `GO!`。
- 到達報名頁與表單頁時，自動保存 HTML 快照至 `analysis_snapshots/` 供下次分析。
- checkbox 勾選邏輯調整為只勾選第一個可見且未勾選項目。

### Changed
- 降低終端機輸出噪音：不再持續列印 `/api/job/{id}` 輪詢心跳請求。

## [1.00] - 2026-03-27

### Added
- 初版 Go WebUI 發布（Mac / Windows 執行檔）。
