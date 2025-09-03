### git操作をする上で大事なコマンド







###### 〇作業用ブランチを作るとき

・**git branch ブランチ名　（例 git branch topPage）**





###### 〇作業用ブランチを切り替えるとき

**・git switch ブランチ名　（例 git switch topPage）**





###### 〇現在の作業用ブランチを確認したいとき

**・git branch --contains**





###### 〇ブランチを最新化したいとき

**・git** pull   （現在いるブランチを最新化する）



**※任意のブランチを最新化したいとき　→**　git pull origin ブランチ名







###### 〇修正分をコミット→プッシュしたいとき

**① git** status　（modified:　で表示されているファイルが編集済みを示しており、後続のgit addの対象になるファイル。）



**② git add ファイル名**　（修正したファイルをステージングエリアにあげる。ステージングエリアにあるものがコミットの対象になる）



**③ git commit "コミット名"　（例 git commit "トップページの修正"）**



**④** **git push origin ブランチ名　（例 git push origin topPage）**

