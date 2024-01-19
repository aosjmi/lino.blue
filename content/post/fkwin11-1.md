---
title: mdファイルのテキストエディタを変更
description: win11の無意味な仕様を無効化する
image: https://i.gyazo.com/7070cd0de2254e9a238a5bfc3459f422.png
slug: fkwin11-1
date: 2024-01-19T13:48:07+09:00
categories:
    - pc
tags: [win11]
---

  - mdファイルのエディタが変更不可となり、win11のくそったれテキストエディタを強制されます。
  - 他の拡張子は変更可能なのにmdファイルだけ不可、一体なぜ？
  ## 解決方法
  - https://www.winhelponline.com/blog/cant-associate-jpg-png-files-default-apps/
  - 詳しくは上記リンクをば
    - ①filetypemanをダウンロードする
      - https://www.nirsoft.net/utils/file_types_manager.html
    - ②起動
    - ③Extensionの列にある「.md」を右クリックして「Open File Type in RegEdit」をクリック
      - [![Image from Gyazo](https://i.gyazo.com/df1d20d07efc2707fb2cc1e8e6ebbd44.png)](https://gyazo.com/df1d20d07efc2707fb2cc1e8e6ebbd44)
    - ④「NoOpenWith」を右クリックで削除
   - 以上
  - まさかの真相は「NoOpenWithで変更させないだけの意図的な嫌がらせプログラムを仕込んでいた」ということなのでした。
  - 他にも仕組まれているかもしれないので、適宜同じ方法で開放していきましょう。
