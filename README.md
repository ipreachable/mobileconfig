# mobileconfig
[てくろぐ](http://techlog.iij.ad.jp/archives/1574)で話題になった、au系のmvnoをiOS8以降で利用するためのプロファイル

[blogram](http://blogram.net/2015/07/13/mobileconfig/)さんのmobileconfigをau版iPhone5sで安定させるための手順(単純にプロファイルを読み込みだけではすぐに1xや圏外になってしまう。)

1. プロファイルのインストール
2. ネットワーク設定のリセット (設定アプリの "一般" -> "リセット" -> "ネットワーク設定をリセット")
3. 1.と同じプロファイルを再度インストール
4. ネットワーク設定のリセット

実際に試して確認したのはUQMobileのプロファイルで、mineoのほうは動くかは確認してません。

[blogram]さんのもののコピー
* [mineo-cellular.mobileconfig](https://raw.githubusercontent.com/ipreachable/mobileconfig/master/mineo-cellular.mobileconfig)
* [UQmobile-cellular.mobileconfig](https://raw.githubusercontent.com/ipreachable/mobileconfig/master/UQmobile-cellular.mobileconfig)
