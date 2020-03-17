# Windows/macOS 版 Wpress-Extractor
Wpress-Extractor 是能讓使用者解壓縮由 WordPress 外掛 All-in-One WP Migration 產生的 .wpress 檔案的簡易 Windows 應用程式。

## 致謝
解壓縮程式原始程式碼：[https://github.com/yani-/wpress](https://github.com/yani-/wpress)

這個 GitHub 專案的原開發者 [fifthsegment](https://github.com/fifthsegment) 對原始程式碼進行小幅修改，讓引用專案中的 reader.go 檔案能執行於 Windows 作業系統。

## 下載連結
[下載 Windows 版](https://github.com/fifthsegment/Wpress-Extractor/raw/master/dist/wpress-extractor.exe)

[下載 macOS 版](https://github.com/fifthsegment/Wpress-Extractor/blob/master/dist/mac/wpress_extractor?raw=true)

*macOS 使用者注意事項：請記得在 [終端機] 中先對之前下載的編譯檔下達 `chmod +x wpress_extractor` 指令。

## 解壓縮/開啟 .wpress 檔案的方式
將下載的 .wpress 檔案的路徑作為程式的第一個命令引數。

例如：`./wpress_extractor /path/to/my/backup.wpress`

## 我並不熟悉相關技術，該如何使用這個程式？
### Windows 版程式使用說明

僅需下載 Windows 版解壓縮程式，並將要解壓縮的 .wpress 檔案拖放至 Wpress-extractor.exe 這個解壓縮程式執行檔 [感謝 hughc 協助](https://github.com/hughc)。

或依照以下步驟：

1. 下載解壓縮程式。 
2. 建立儲存解壓縮結果的資料夾。
3. 將下載的解壓縮程式複製至步驟 2 建立的資料夾。
4. 將 .wpress 檔案複製至步驟 2 建立的資料夾。
5. 開啟 \[命令提示字元\]。
6. 透過 cd 命令瀏覽至步驟 2 建立的資料夾，例如 C:\Wordpress-Backup。命令範例：`cd C:\Wordpress-Backup`。
7. 執行命令 `wpress-extractor <name-of-your.wpress 檔案>`。如果此時的 .wpress 檔案為 `fifthsegment.wpress`，命令範例便會是 `wpress-extractor fifthsegment.wpress`。
8. 檔案解壓縮完成後，解壓縮的檔案便會儲存在同一個資料夾中，在這個範例中則是 `C:\Wordpress-Backup`。
