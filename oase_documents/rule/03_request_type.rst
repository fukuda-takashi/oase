===========================================
3 OASE ステージングとプロダクションについて
===========================================

| 本章では、ステージングとプロダクションについて説明します。


3.1 ステージングとは
^^^^^^^^^^^^^^^^^^^^
| ステージングとは、本番環境と同じテスト用の環境です。
| OASEでは、テストリクエストを使用し、REST APIからルールマッチング結果までを行い、
| ディシジョンテーブルファイルに記載された内容に問題ないかの確認を実施しています。
| なお、ステージングではアクションの実行は行いません。


3.2 プロダクションとは
^^^^^^^^^^^^^^^^^^^^^^
| プロダクションとは本番環境のことです。
| 運用監視ツールからイベント情報を受け取り、ルールマッチング結果によりアクションの実行を行います。

