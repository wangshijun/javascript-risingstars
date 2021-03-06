しばらくの間「フロントエンドフレームワーク」は熾烈なバトルフィールの様相を呈するカテゴリでしたが、いまや事態は沈静化し、３強がゲームを支配している状況です。

### ３強：Vue, React, Angular

UI フレームワーク３強はご想像通り、 {vuejs} 、{react}、{angular} です。いま、ひとまとめに「フレームワーク」と呼びましたが、厳密には、フレームワークは {angular} のみで、{vuejs} と {react} は「ライブラリ」と呼ばれるものです。 

別のところで（訳註：リンク追加のこと）、{vuejs} とそのアプローチがうまくいった理由について考えました。{vuejs} と比較すると、{react} のアプローチはまだ統一されていないので、view レイヤーにまつわる次のような問題について、開発者は慎重に選択しなければなりません。

* ページ間のルーティング
* データをどのように取得するか？
* フォームとデータをどのようにバインドするか？
* アプリケーションの状態（ステート）をどのように保持するか？

これとは対照的に、{angular} のエコシステムは制約がもっと強くて、より堅牢です。いわば「Angular の流儀」が存在します。おそらくこのことが  {angular} に「コーポレート」なイメージを与えているのかもしれません。また、バックエンド開発者にお馴染みの C# や Java を連想させる、{typescript} の静的型付けがこのイメージを強調してきました。

### レス・イズ・モア

このカテゴリで３強を追う４位となったのは、{preact} という興味深い結果です。{preact} は {react} のコンパクトなオルタナです。{react} と同じ ES6 API を完全にサポートしつつ、サイズが 3KB 未満と軽量です。{preact} を含めたフレームワークの多くが３強との差別化で強調するのは、少ないメモリーで、高速にブラウザ上で動作する点です。この典型例が {hyperapp} です。いま熱いプロジェクトのひとつです。関数型のパラダイムを取り入れ、{react} の JSX シンタックスを採用し、{redux} にインスパイヤされた状態管理システムを備えています。
