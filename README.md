# AUTO GACHA - R.E.P.O. コスメ自動ガチャ Mod

コスメティックガチャマシンに近づいて **`O` キー** を押すと、トークンがなくなるまで自動で回し続けます。もう一度押すと停止。

## 使い方

1. ショップのガチャマシンに近づく
2. 画面下中央に「AUTO GACHA」UIが表示される
3. **`O` キー** で開始 → トークンが尽きるか、もう一度 `O` で停止

## インストール

`BepInEx/plugins/REPOAutoGACHA.dll` に配置するだけ。

## Config

`BepInEx/config/dev.yourname.repoautogacha.cfg` で変更可能：

```ini
[General]
PullDelaySeconds = 0.15
HotKey = O
```
