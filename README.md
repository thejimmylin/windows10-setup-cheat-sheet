# Windows 10 setup cheat sheet

## Explorer

- 資料夾選項 > 顯示附檔名
- 檔案總管 > 把 C:\Users\user 訂選到快速存取
- 檔案總管 > 資料夾選項 > 開啟檔案總管以 > 本機器
- 檔案總管 > 資料夾選項 > 一般 > 在快速存取中顯示最近使用的檔案 > 取消
- 檔案總管 > 資料夾選項 > 一般 > 在快速存取中顯示經常使用的資料夾 > 取消
- 顯示附檔名、顯示隱藏的檔案

## Browser

- Create directory "Installed Software" and put all the installer in it.
- edge > download chrome
- set chrome as default browser

## Uninstall

- OneDrive

## Appearance

- 工具列 > 工作檢視 > 不顯示
- 工具列 > 搜尋 > 顯示搜尋圖片
- 取消訂選工作列上的所有東西
- 訂選檔案總管、Chrome

## Shell

- Powershell > execute as admin > Set-ExecutionPolicy RemoteSigned > All

## Install Chocolatey

- Install chocolatey with command:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Install all the shell-related things by chocolatey

- Install python3.8.2 with choco command:
```
choco install python3 --version=3.8.2
```

- Install git2.27.0 with choco command:
```
choco install git
```

## Install other GUI things

- Download VSCode and install it from its website

- Download Github desktop and install it from its website

## Appearance & preference

- 右下角輸入法 > 右鍵 > 內容 > 一般設定 > 預設輸入模式 > 英數模式

- 資源回收桶 > 右鍵 > 內容 > 顯示確認刪除的對話方塊

- 個人化 > 背景 > 純色 > 更多 > #2b3137

- 個人化 > 色彩 > 輔色 > 更多 > #808080

- 電源設定 > 永不休眠

- Chrome > 設定 > 密碼 > 顯示儲存密碼的選項 > X

- Chrome > 設定 > 翻譯 > 翻譯語言 > X

## Auto update

- win+R > gpedit > 電腦設定 > 系統管理範本 > Windows元件 > Windows Update > 不包含 Windows 更新的驅動程式 > 已啟用 > 確定

## Notification

- 右下角通知中心 > 專注輔助 > 僅允許鬧鐘
