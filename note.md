# 常用按鍵

如果能夠快速反應以下操作如何使用, 代表已經對 SpaceVim 有基本認知了

## File Tree
* 打開檔案樹
* 將 nerdtree 的目錄設定為 pwd

## TabsManager
* 打開 TabsManager
* 展開 tab
* 建立新的 tab
* 刪除 tab
* 重新命名 tab

## Windows
* 水平/垂直分割視窗
* 任意移動到指定的視窗

## Buffers
* 建立新的緩衝區
* 刪除目前的緩衝區
* 任意移動到指定的緩衝區

## Plugin
* 更新 SpaceVim 以及 Plugin
* 重新安裝某個 Plugin
* 新增 Plugin (enable layers)

## Terminal
* 在 SpaceVim 中打開一個終端機
* 離開終端機
* 隱藏終端機視窗

## Search
* grep 搜尋整個 Buffer
* 取消已選取的文字 (:noh in SpaceVim)
* 在搜尋結果中來回移動 (next or previous result)


# Answer

以上操作的解答

## File Tree
* 打開檔案樹: `<F3>`
* 將 nerdtree 的目錄設定為 pwd: `CD`

## TabsManager
* 打開 TabsManager: `SPC t t`
* 展開 tab: `o`
* 建立新的 tab: `n`
* 刪除 tab: `x`
* 重新命名 tab: `r`

## Windows
* 水平/垂直分割視窗: `s g`/`s v`
* 任意移動到指定的視窗: `SPC [num]`

## Buffers
* 建立新的緩衝區: `SPC b N n`
* 刪除目前的緩衝區: `SPC b d`
* 任意移動到指定的緩衝區: `\ [num]`

## Plugin
* 更新 SpaceVim 以及 Plugin: `:SPUpdate`
* 重新安裝某個 Plugin: `SPReinstall [Plugin Name]`
* 新增 Plugin (enable layers): `SPC f v d` -> add [[layers]]...

## Terminal
* 在 SpaceVim 中打開一個終端機: `SPC '`
* 離開終端機: `CTRL arrow`
* 隱藏終端機視窗: `q`

## Search
* grep 搜尋整個 Buffer: `SPC s s`
* 取消已選取的文字 (:noh in SpaceVim): `SPC s c`(search clear)
* 在搜尋結果中來回移動 (next or previous result): `Tab`(next)/`Shift Tab`(previous)


# 小結

以上是最近學習的筆記, 官網還有很多操作可以學, 
不過經過這幾天玩下來, 我應該不會再深入研究了, 
感覺 vscode 還是略勝一籌, 但還是會用 SpaceVim 寫寫設定檔, 
畢竟界面比原生的 Vim 漂亮。
