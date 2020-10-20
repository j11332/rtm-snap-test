# How to test
## インストール
インストールが完了するとネームサーバが自動的に起動する。
```
$ sudo snap install --edge openrtm
```

## ConsoleIn/Out RTC
**別にrtshell/ RT System Editor による接続が必要**。
1. RTC を起動する
- Terminal #1 (w/ manager)
```
$ openrtm.ConsoleOutComp
```

- Terminal #2
```
$ openrtm.ConsoleInComp -d
```

2. **RT System Editor または rtshell などで RTC を接続**し，ConsoleIn 側に整数値を入力すると ConsoleOut RTC 側に表示される。