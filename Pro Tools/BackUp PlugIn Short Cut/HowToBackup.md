## Avid ProTools
### Protools設定ファイル（Pro Tools Prefs） 概要

`$HOME/Library/Preferences/Avid/Pro Tools/Pro Tools Prefs`

**【Pro Tools Prefs】**は、Protoolsの以下の項目を一括管理しているファイル。

- 初期設定
- トラックカラー
- プラグインショートカット登録

もし設定がリセットされた場合は、下記（※01）のスクリプトを叩く。





### 設定がリセットされた場合（Dropboxのバックアップ =>コピー）※01
```bash
cp -i "$HOME/Dropbox/Various DAW Setting Folder/Pro Tools/BackUp PlugIn Short Cut/Pro Tools Prefs" "$HOME/Library/Preferences/Avid/Pro\ Tools/"
```
### 現在の設定をDropboxにバックアップしたい場合
```bash
cp -i "$HOME/Library/Preferences/Avid/Pro Tools/Pro Tools Prefs" "${HOME}/Dropbox/Various DAW Setting Folder/Pro Tools/BackUp PlugIn Short Cut/Pro Tools Prefs"
```

UAD 設定ファイルのシンボリックリンク 作成

```bash
ln -s "$HOME/Dropbox/Various DAW Setting Folder/Universal Audio" "$HOME/Documents/Universal Audio"
```




Protools 設定ファイルのシンボリックリンク 作成
```bash
ln -s "$HOME/Dropbox/Various DAW Setting Folder/Pro Tools" "$HOME/Documents/Pro Tools" 
```

