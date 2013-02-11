BXptool パッケージバンドル
===========================

(This file is encoded in UTF-8,)

pLaTeX 用のパッケージについて、欧文 LaTeX／XeLaTeX でも使用可能な改変版を
作る試みである。特に和文処理に関係ない機能はそのまま取り込み、和文に関連
するものは XeLaTeX での対応を試みる。  
（pLaTeX 系でも使用可能。）

### パッケージ一覧

  - bxascmac パッケージ： ascmac 改変版
  - bxjsverb パッケージ： jsverb、okuverb 改変版
  - bxokumacro パッケージ： okumacro 改変版

### 前提環境

  - 処理系： LaTeX 汎用

### インストール

TDS 1.1 に従ったシステムでは、各ファイルを次の場所に移動する。

  - `*.sty`, `*.def`  → $TEXMF/tex/latex/BXptool/

W32TeX を C:\usr\local にインストールした場合は次のようになる。

  - `*.sty`, `*.def`  → C:\usr\local\share\texmf-local\tex\latex\BXptool

各パッケージの解説
------------------

まだ解説が書けておりません…。基本的な機能の説明については以下の Web
ページで行っていますのでそちらを参照してください。

  - [BXptool パッケージ]
    (http://zrbabbler.sp.land.to/bxptool.html)

ライセンス
----------

修正 BSD ライセンス。詳しくは LICENSE ファイルを参照。

更新履歴
--------

  * Version 0.3  <2013/02/13>
      - pict2e に対応させた
      - 角丸四角枠を描く際の線のパラメタが何故か理想値から外れていた
        のを一致させた。

  * Version 0.2  <2009/12/14>
      - 最初の公開版

--------------------
Takayuki YATO (aka. "ZR")  
http://zrbabbler.sp.land.to/
