# スタート低レイヤーWiki

スタート低レイヤーへようこそ。

## 勉強会概要

みなさんなにげなく使っているprintf関数。その裏側で何が起きているのか知りたくないですか？

この勉強会は低レイヤーを理解するための初心者向け勉強会です。
printf関数をアプリケーションが呼び出した時に何が起きるのか、OSのソースコードとmanページを読みながら一歩一歩読解します。

だいたい学べる内容としましては以下となります。

* libcとの動的リンク
* ld.elf_so
* システムコール
* ユーザ空間=>カーネル空間へ
* シリアルデバイスドライバ
* 割り込み
* プロセススケジューラ 

対象とするOSは
[NetBSD](http://www.netbsd.org/)
です。

## Wiki

このリポジトリは勉強会のWikiです。
主なコンテンツは以下のURLにまとまっています。

[https://github.com/start-printf/wiki/wiki](https://github.com/start-printf/wiki/wiki)

## 雑多なファイル

Wikiでは管理しにくい雑多なファイルは本リポジトリに置く予定です。

* bus_space_trace.patch := whileprintのbus_space_write_1呼び出しbacktrace
* whileprint.objdump-S  := whileprintプログラムの逆アセンブル
