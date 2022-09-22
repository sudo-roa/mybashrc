# mybashrc

## 概要
自分用.bashrcとその関係ファイル

## 使い方
```
$ git clone https://github.com/sudo-roa/mybashrc.git
```
設定ファイルを書き換えターミナルを再起動すれば反映される<br>

### .bash_profileがあり.bashrcがない場合
.bashrcを作成し、その中にmybash_aliasの内容をコピペ<br>
.bash_profileに以下を追加
```
[[ -f ~/.bashrc ]] . ~/.bashrc
```

### .bash_profileがなく.bashrcがある場合
.bashrcにmybash_aliasの内容をコピペ

### .bash_profileも.bashrcもない場合
.bashrcを作成し、その中にmybash_aliasの内容をコピペ



## author
- [sudo-roa](https://github.com/sudo-roa)

## license
MIT license

