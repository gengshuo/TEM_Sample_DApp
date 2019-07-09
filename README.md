# Web DApp 範例原始碼
## Taipei Ethereum Meetup - 區塊鏈基礎教育課程

### 複製這個專案到你的工作區
```shell
$> cd ~/to/your/workspace
$> git clone https:// ....
```

### 安裝node_module
```shell
$> cd ./TEM_Sample_DApp
$> npm install
```

### 在本機上運作這個網頁DApp
```shell
$> npm start
```
開啟Chrome輸入網址：http://localhost:8000

如果Windows無法連上請嘗試改用: http://localhost:8000/index.html

---

### 範例Web DApp想要展示的功能

- 連結使用者瀏覽器上的 Metamask 插件

- 隨著Metamask切換帳號(錢包地址)而改變頁面上的顯示

- 透過ABI與Contract Address與區塊鏈上的Smart Contract互動

- 設定合約中的字串

- 取得目前合約中的字串

---

### 延伸思考： 
- 為什麼要指定的Test Network去運作？
- 為什麼取得智能合約中的值，不需要進行交易？
- 怎麼確認交易真的成功了？

### 延伸練習：
- 試著修改原始碼，讓網頁上的字串在交易成功後，在畫面上即時顯示最新的值
- 提示1：做法可能不只一種，Polling當然是顯而易見的解法
- 提示2：可以在智能合約的函式觸發事件，至於怎麼監聽接收就留給大家自己去找找。

---

### 本課程範例使用以下的開源資源進行建構
- web3js - https://github.com/ethereum/web3.js/
- UI Framework ref: https://materializecss.com/ 

