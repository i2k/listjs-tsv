# List.jsとTSVによる書誌検索「１万件」サンプルページ

## サンプルサイトURL
https://i2k.github.io/listjs-tsv/

## 概要
List.jsとTSVによる書誌1万件規模での書誌検索サイトのサンプルページである。
高速化のため書誌データをHTML中に記載するのではなく、TSVから読み込む方法をとった。

## 使用データ
NACSIS-CATの総合目録データベースのCC-BY書誌情報を使用した。
そのままだとRDFのため、大学図書館員のための図書館システム開発練習用データ( https://mbc.dl.itc.u-tokyo.ac.jp/data4librarysystem/ )の図書書誌TSVから、先頭１万件を抽出して使っている。
