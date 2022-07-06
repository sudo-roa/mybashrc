# mybashrc

## 概要
自分用.bashrcとその関係ファイル

## 使い方
```
$ git clone https://github.com/sudo-roa/mybashrc.git
$ cd mybashrc
$ ./install.sh
```

### .bash_profileがある場合
.bash_profileに以下を追加
```
[[ -f ~/.mybash_alias ]] && . ~/.mybash_alias
```

### .bash_profileがなく.bashrcがある場合
.bashrcに以下を追加
```
[[ -f ~/.mybash_alias ]] && . ~/.mybash_alias
```

### .bash_profileも.bashrcもない場合
.bashrcを作成し、その中に以下を追加
```
[[ -f ~/.mybash_alias ]] && . ~/.mybash_alias
```


## author
- [sudo-roa](https://github.com/sudo-roa)

## license
MIT license

