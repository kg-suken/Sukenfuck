# Sukenfuck
BrainfuckをSuken仕様にしたもの。


## 対応表
| 命令 (Brainfuck) | 命令 (Sukenfuck)| 読み方 | 動作 |
|--------------|------|--------|------|
| `+`          | е    | (U+0435): キリル文字の小文字「е」 | 現在のメモリをインクリメントする。 |
| `-`          | ɘ    | (U+0258): 逆転した e (逆 e, IPA) | 現在のメモリをデクリメントする。 |
| `>`          | é    | (U+00E9): アキュートアクセント付き e | 命令ポインタを1つ右に移動させる。 |
| `<`          | è    | (U+00E8): グレイヴアクセント付き e | 命令ポインタを1つ左に移動させる。 |
| `.`          | ē    | (U+0113): マクロン付き e | 現在のメモリの値を文字コードとみなし出力する。 |
| `,`          | ę    | (U+0119): オゴネク付き e | 入力を求め、入力された値を現在のメモリに代入する。 |
| `[`          | ё    | (U+0451): キリル文字の小文字「ё」 | 現在のメモリの値が0なら、対応するėにジャンプする。 |
| `]`          | ė    | (U+0117): ドット付き e | 現在のメモリの値が0でないなら、対応するёにジャンプする。 |


## アイデア&構想
**sskrc**  
**DETERMINATION**

---
ミスなどありましたらIssueなどを通してご連絡ください
