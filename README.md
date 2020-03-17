# Windows/macOS 版 Wpress-Extractor
Wpress-Extractor 是能讓使用者解壓縮由 WWordPress 外掛 All-in-One WP Migration 產生的 .wpress 檔案的簡易 Windows 應用程式。

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

## 我並不熟悉相關技術，那該如何使用這個程式？
### Windows 版程式使用說明

僅需下載 Windows 版解壓縮程式，並將要解壓縮的 .wpress 檔案拖放至這個解壓縮程式執行檔 (Wpress-extractor.exe)。

[感謝 hughc 協助](https://github.com/hughc)!)


OR



1. Download the extractor 
2. Create a directory where you wish your files to be extracted to
3. Copy the downloaded extractor to that directory
4. Copy your .wpress file to that directory as well
5. Open up a command prompt
6. CD into the directory you just created, let's say its C:\Wordpress-Backup. The command you'll run would be `cd C:\Wordpress-Backup`
7. Now run the following command `wpress-extractor <name-of-your.wpress file>`. For example my .wpress file was fifthsegment.wpress so the command I ran was `wpress-extractor fifthsegment.wpress`.
8. You'll find your files extracted into the same directory where the extractor was run. In my case it was `C:\Wordpress-Backup`


