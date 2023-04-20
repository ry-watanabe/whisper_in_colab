# 概要
音声ファイルの文字起こしを行い、それを要約します。
45分の音声ファイルを文字起こしし、長文の要約を行うことができました。

# 事前準備
・ランタイムのタイプはGPUに変更してご利用ください。

・基本的には音声ファイルの文字起こしを想定しています。

# 実施手順
上から順にセルを実行するだけです。
1．モジュールのインストール
2．音声ファイルのアップロード
3．LamgChainの事前準備
4．音声ファイルから文字起こし（45分の音声ファイルで15分ほど）
5．文字起こししたテキストをファイルに保存
6．テキストを分割サイズ分で区切る
7．「要約＝要約＋残りのテキスト（1000文字ずつ）」で要約を行う
