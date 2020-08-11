# touch

> 改變檔案的存取與修改時間。

- 建立新檔案，或更新現存檔案的存取與修改時間：

`touch {{檔案名稱}}`

- 將存取與修改時間設定為指定時刻：

`touch -t {{西元年份月份日期小時分鐘.秒鐘}} {{檔案名稱}}`

- 以其中一個檔案的存取與修改時間為基準，設定另一個檔案的存取與修改時間：

`touch -r {{來源檔案名稱}} {{目標檔案名稱}}`