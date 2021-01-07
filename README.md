## ts - An Interactive command line Translator and Basic Dictionary

### Wat is this?
This Translator is trans the input English sentences or words, output as Japanese. it's Translator dependences `Translate-shell`. it's need.
```bash
[Haskell@localhost ~]$ ts
--> Hello
Hello

こんにちは
(Kon'nichiwa)

Hello の定義
[ English -> 日本語 ]

感嘆詞
    もしもし！
        Hello!
    今日は!
        Hi!, Hello!, Good afternoon!, Good day!

Hello
    こんにちは, もしもし
0
--> Lysergic acid diethylamide
Lysergic acid diethylamide

リセルグ酸ジエチルアミド
(Riserugu san jiechiruamido)

「Lysergic acid diethylamide」の翻訳
[ English -> 日本語 ]

Lysergic acid diethylamide
    リセルグ酸ジエチルアミド, リゼルグ酸ジエチルアミド
0
--> 

```

### Future

- shell command run Function 

  ```bash
  --> :shell ls
  ```

- abolish use `Translator-shell` by Googletrans Module