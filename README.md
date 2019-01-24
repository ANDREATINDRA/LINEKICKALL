LINE KICK ALL BOT

具有迅速破壞LINE群組能力的BOT

# *要求* 

node >= v8.x.x

可通過 `node -v` 指令檢查

[升級nodejs](https://nodejs.org/en/)

# *警告*

> 此程序可能導致帳號作廢
> 
> 使用前請三思帳號是很珍貴的
> 
> 可用在用需解散之群組
> 
> 如不當使用後果自負

# 原生

前生 => [Line Alphat JS](https://github.com/alfathdirk/LineAlphatJS)

作者 => [@alfathdirk](https://instagram.com/alfathdirk)

# 修改內容

01/17 更新

- 移除管理員才可破壞
- 修正舊版一次全部取消改為一個個取消
- 修正全踢過度 getgroup 問題

01/24 更新

- 修正不踢自己、發號指令的
- 修正無法踢人錯誤

# 已知問題

由於版本過舊遭github刪除部分檔案

完整檔案 => [下載](https://keep.line.me/s/IhB5bRBqGpIVlgVaY-_vIyh-DU5DwiYDt4C0qcEsPxY)

備用檔案 => [文章鏈結](https://telegra.ph/LINE-%E7%A0%B4%E5%A3%9E-BOT-01-16)


# *使用方法*

## *第一步*：環境架設

### Android 手機

1. 下載並安裝[Termux](https://play.google.com/store/apps/details?id=com.termux&hl=zh_TW)

2. 下載並安裝[Termux:API](https://play.google.com/store/apps/details?id=com.termux.api&hl=zh_TW)

3. 安裝腳本

- `pkg install git`
- `pkg install unzip`

### 電腦

1. 下載並安裝[Node.js](https://nodejs.org/en/)

2. 下載並安裝[git](https://git-scm.com/downloads)

## *第二步*：檔案下載

### Android 手機

- `git clone https://github.com/Phyllis62418/LINEKICKALL.git`
- `cd LINEKICKALL`
- `unzip LINEKICKALL.zip`
- `cd LINEKICKALL`

### 電腦

- `git clone https://github.com/Phyllis62418/LINEKICKALL.git`
- `cd LINEKICKALL`
- (視窗不要關)
- 下載[7-ZIP](https://www.7-zip.org/download.html)
- 自行解壓縮
- `cd LINEKICKALL`

## *第三步*：程式運行(電腦或手機都一樣)

- `npm install`
- `npm start`

## *第四部*：登入帳號

- 將 line://au/q/.... 網址複製於手機並登入
- 在想破壞之群組輸入 kickAll 即可全踢除(注意大小寫)

# 程式簡易修改

為了避免防翻及過濾字串，於目錄`\src\main.js`下

第 127 行 可以變更破壞指令
