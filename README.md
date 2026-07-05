# TatamiSQL
Official release repository for TatamiSQL. Download the latest versions here.

## Alpha release notes

TatamiSQL is currently an alpha release. Only MySQL is supported at this time, and its core features are functional.

The macOS app is ad-hoc signed, but it is not signed with an Apple Developer ID or notarized by Apple. As a result, macOS displays a warning when the app is opened for the first time.

### Opening TatamiSQL on macOS

Only continue if you downloaded the DMG from the official [TatamiSQL GitHub Releases](https://github.com/githiroshi/TatamiSQL/releases) page and accept the risks of running an unnotarized alpha application.

1. Open the DMG and drag `TatamiSQL.app` into the Applications folder.
2. Open `TatamiSQL.app`. When macOS displays a warning that Apple could not verify the app for malware, close the dialog.
3. Open **System Settings > Privacy & Security**.
4. Scroll down to the Security section and click **Open Anyway** for TatamiSQL.
5. Authenticate if prompted, then click **Open** in the confirmation dialog.

macOS saves this approval as an exception. Subsequent launches can be performed normally.

## 日本語

### アルファ版について

TatamiSQLは現在アルファ版。現時点ではMySQLのみ対応し、主要機能は動作する。

macOS版はad-hoc署名済みだが、Apple Developer IDによる署名とAppleの公証は未実施。そのため、初回起動時にmacOSの警告が表示される。

### macOSでTatamiSQLを開く方法

公式[TatamiSQL GitHub Releases](https://github.com/githiroshi/TatamiSQL/releases)からDMGをダウンロードし、未公証のアルファ版を実行するリスクを了承できる場合のみ、以下の手順を実行する。

1. DMGを開き、`TatamiSQL.app`を「アプリケーション」フォルダへドラッグする。
2. `TatamiSQL.app`を開く。Appleがアプリにマルウェアが含まれていないことを検証できない旨の警告が表示されたら、ダイアログを閉じる。
3. **システム設定 > プライバシーとセキュリティ**を開く。
4. 「セキュリティ」までスクロールし、TatamiSQLの**このまま開く**をクリックする。
5. 必要に応じて認証し、確認ダイアログの**開く**をクリックする。

承認内容はmacOSの例外として保存される。2回目以降は通常どおり起動可能。
