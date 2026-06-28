# AUTO GACHA - R.E.P.O. コスメ自動ガチャ Mod

コスメティックガチャマシンに近づくと画面下中央にUIが表示されます。
**`O` キー** で開始、**`P` キー** で停止。トークンがなくなると自動で終了します。

## 使い方

1. ショップのガチャマシンに近づく
2. 画面下中央に「AUTO GACHA　[O] 開始」と表示される
3. **`O` キー** で開始
4. 止めたいときは **`P` キー** で停止
5. トークンが尽きると自動停止

## インストール

`BepInEx/plugins/REPOAutoGACHA.dll` に配置するだけ。

## Config

`BepInEx/config/dev.yourname.repoautogacha.cfg` で変更可能：

```ini
[General]
PullDelaySeconds = 0.15
StartKey = O
StopKey = P
```
