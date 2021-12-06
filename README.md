# w10delapp
Windows10で標準でインストールされてしまっているアプリで不要なものを消すためのPower Shellスクリプト

## 使い方

PowerShellを管理者モードで起動してスクリプトを実行してください

実行権限等で怒られたら

```powershell
Set-ExecutionPolicy RemoteSigned
```

でポリシーを変更して再度実行するか、下記のように一時的にポリシーを変更した子プロセスで実行してみてください

```powershell
PowerShell -ExecutionPolicy Bypass -Command .\deletefefaultapp.ps1
```

## 削除されるアプリ一覧

- 3Dビューアー (1809以降)
- Candy Crush Friends
- Candy Crush Saga
- Cortana (20H1以降)
- Farm Heroes Saga
- Xbox Game Bar (1809以降)
- Xbox Live (1809以降)
- Xbox 本体コンパニオン (1607以降)
- Xbox その他 (1607以降)
- Xbox その他 (1607以降)
- Xbox その他 (1607以降)
- Groove ミュージック
- Mixed Realityポータル
- Office
- OneNote
- People
- Print3D (1709以降)
- Skype
- Spotify (1709以降)
- アラーム＆クロック
- 映画 & テレビ
- カメラ
- 切り取り & スケッチ (1809以降)
- スマホ同期
- 天気
- 問い合わせ
- ヒント
- フィードバックHub
- フォト
- ペイント3D
- ボイスレコーダー
- マップ
- メール、カレンダー
- メッセージング
- モバイル通信プラン
- 付箋
