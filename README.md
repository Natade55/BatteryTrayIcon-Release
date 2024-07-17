# BatteryTrayIcon
BatteryTrayIconは、Windowsのシステムトレイにバッテリー残量を数値で表示するシンプルなツールです。

主な特徴：
- システムトレイにバッテリー残量をパーセンテージ(%)で表示
- カスタマイズ可能な更新間隔
- テキスト色の変更機能
- Windows起動時の自動起動オプション
- 軽量動作

使い方：
- アプリケーションを起動すると、システムトレイにバッテリー残量が整数値で表示されます。
- システムトレイアイコンを右クリックして「BatteryTrayIconのプロパティ」を選択すると、設定画面が開きます。
- 設定画面で更新間隔、テキスト色、自動起動の有無を変更できます。

注意事項：
- このツールはWindows 10またはWindows 11環境でのみ動作します。
- バッテリーを搭載していないデスクトップPCなどでは正常に動作しない可能性があります。
- 初回起動時「Windows によって PC が保護されました」と表示される場合がありますが、「詳細情報」ボタンをクリックした後「実行」ボタンをクリックすることで実行することができます。以後このウィンドウは表示されなくなります。
- 更新間隔を極端に短く設定すると、システムのパフォーマンスに影響を与える可能性があります。
- Windows起動時の自動起動オプションを有効にする場合、セキュリティソフトウェアによってブロックされる可能性があります。その場合は、セキュリティソフトの設定で許可してください。
- テキスト色をタスクバーの色と同じまたは近い色に設定すると、表示が見えにくくなる可能性があります。その場合は、タスクバーの補色に近い色に設定してください。
- このツールは公式のバッテリー管理ソフトウェアではありません。重要なバッテリー管理機能については、お使いのPCの公式ツールをご利用ください。
- BatteryTrayIconProperty.exeと同じディレクトリに自動で生成される設定ファイル（BatteryTrayIconProperty.txt）を手動で編集すると、ツールが正常に動作しなくなる可能性があります。設定の変更は必ずアプリケーション内の設定画面から行ってください。
