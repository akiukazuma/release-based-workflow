### git操作をする上で大事なコマンド



**インターン用プロジェクトをクローン（PCに資源を持ってくる）**

###### **git clone https://github.com/akiukazuma/release-based-workflow.git**









**※以下コマンドは、git bash上でrelease-based-workflow のディレクトリにいる状態で使用してください。**





###### 〇作業用ブランチを作るとき

・**git branch ブランチ名　（例 git branch mikami）**





###### 〇作業用ブランチを切り替えるとき

**・git switch ブランチ名　（例 git switch mikami）**





###### 〇現在の作業用ブランチを確認したいとき

**・git branch --contains**





###### 〇ブランチを最新化したいとき

**・git pull**   （現在いるブランチを最新化する）



**※任意のブランチを最新化したいとき　→**　**git pull origin ブランチ名**





###### 〇別のブランチの更新を自分のブランチに取り込みたいとき（main→各作業ブランチ）

git branch　で各々の作業ブランチにいることを確認済みなら、以下を実行



・git merge main （mainブランチを各作業ブランチに反映する）



※もしマージをするときに上手く取り込めなかったら…？（コンフリクトが起きたら）

→ git merge --abort でマージをなかったことにして助けを呼ぶ







###### 〇修正分をコミット→プッシュしたいとき（一日の作業終わりに必ず実施してください！）

**① git status**　（modified:　で表示されているファイルが編集済みを示しており、後続のgit addの対象になるファイル）



**② git add** 　（修正したファイルをステージングエリアにあげる。ステージングエリアにあるものがコミットの対象になる）



**③ git commit "コミット名"　（例 git commit "トップページ作成"）**



**④** **git push origin ブランチ名　（例 git push origin takeyama）**

