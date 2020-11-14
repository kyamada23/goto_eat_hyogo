# goto_eat_hyogo

go to eat ひょうごキャンペーンの食事券が使える店のリストをgoogleマップにインポートできる形式で出力する<br>
https://gotoeat-hyogo.com/

google map (例)<br>
https://www.google.com/maps/d/edit?mid=1ENEY2G0o31B2Oj6hq4MoY7iSJLzFIbBM&usp=sharing

## 使い方
1. ↓に検索文字を入れて実行する
  search_words = ["(検索したい文字)"]<br>
  例：伊丹市の対象店舗を出力したい場合　>　「search_words=["神戸市"]」<br>
    複数word検索して出力したい場合　>　「search_words=["西宮市", "姫路市"]」
1. 出力したCSVファイルをgoogle mapで読み込む
