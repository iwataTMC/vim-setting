# vim-setting

# vimを最新にする
デフォルトで入っているvimは最新ではないので，以下のコマンドで最新のバージョンをインストールする

```
brew install vim
```

# vimの設定ファイル
- 設定ファイル`.vimrc`を作成する
```
touch ~/.vimrc
```

- 設定ファイル`.vimrc`に下記の内容を書き込んでいくことで、vim設定の変更を行えます
```
set [設定項目]
```

## 参考
[設定項目の一覧](https://lecu1012.com/vim_editer_customize/)


# プラグインを入れる
- 以下のコマンドを実行し，ディレクトリを作成する
```
mkdir ~/.vim/bundle
```
- プラグインマネージャをいれる

今回使うのは"Vundle"
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

- 好きなプラグインを入れる
vimを実行して以下のコマンドを実行するとインストールされる
```
:PluginInstall
```

## 参考
[Vundle](https://github.com/VundleVim/Vundle.vim)

