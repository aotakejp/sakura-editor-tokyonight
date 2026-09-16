# Sakura Editor TokyoNight Theme

[サクラエディタ](https://github.com/sakura-editor/sakura)用の **TokyoNight** カラーテーマおよび設定ファイルです。V2.4.3で確認。

## 収録ファイル

- **`colors/TokyoNight.col`**
  - **タイプ別設定** **カラー** タブ でインポートできるカラー設定ファイルです。
- **`examples/sakura.ini`**
  - カラー設定を、タイプ別設定一覧から各タイプへ反映（使いそうなところのみ）し、ダークモード、タブ、UI等を調整した設定ファイル（履歴等の個人情報は削除済み）です。
  - 設定フォント：[HackGen Console NF](https://github.com/yuru7/HackGen)

## 導入方法

カラーファイルを個々に適用するか、sakura.iniで全体を設定します。

### カラーファイルを個々に適用
1. **設定** ＞ **タイプ別設定** を開きます。
2. **カラー** タブを選択します。
3. **インポート** ボタンから、`colors/TokyoNight.col` を適用します。

### `sakura.ini`で全体を設定
1. フォントが入ってない場合は、インストールします。
2. `$HOME\AppData\Roaming\sakura\` に、`examples/sakura.ini` を配置します。
3. エディタを起動し、配色・フォント・UI等を確認します。

## ライセンス
[MIT License](LICENSE)
