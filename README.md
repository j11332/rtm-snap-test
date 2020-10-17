# How to test
## インストール
インストールが完了するとネームサーバが自動的に起動する。
```
$ sudo snap install ./rtm_0.1_amd64.snap
```

## ConsoleIn/Out RTC
**別にrtshell/ RT System Editor による接続が必要**。
- Terminal #1 (w/ manager)
```
$ rtm.ConsoleInComp -d
```

- Terminal #2
```
$ rtm.ConsoleOutComp
```
