# はじめに
これから Python を書いていきます。

## 10/31 追記

練習問題と総合演習の解答を掲載しました。
誤植をしている可能性もあるので、気になる点があれば 63180@aikogakuen.net まで連絡をください。誤植の報告だけでなく、不明点や分からないところの質問などでも OK です。

- [練習問題の解答](./answer.md)
- [総合演習の解答](./answer_advanced.md)

ただしメールを送る際は口頭でも良いので一度 **担当の情報の先生に一言連絡する** ようにしてくれると助かります。

## (以下授業当日のテキスト)
Web テキストにも同じ内容を書いていますが、全員の環境をそろえるために Google Colab を用いることにしました。ノートブックを開きましょう。

なお、内容をよく理解していて聞く必要がないという方は[総合演習](https://colab.research.google.com/github/aiko-63180/notebooks/blob/main/problems.ipynb)として、少しタフな考察やプログラムを書く必要のある問題を用意しましたので腕試ししてみてください。


[前半のノートブックを開く](https://colab.research.google.com/github/aiko-63180/notebooks/blob/main/text1.ipynb)

内容

- `print`関数による出力
- コメントアウト
- 変数

[後半のノートブックを開く](https://colab.research.google.com/github/aiko-63180/notebooks/blob/main/text2.ipynb)

内容

- 条件分岐
- ループ (念のため用意したがたぶんここはやらない)


[デモで使用したAIのソースコード](https://github.com/aiko-63180/racing)

AI の作成で用いた $Q$-学習とその理論的な基礎であるマルコフ決定過程については以下を参照。

- [マルコフ決定過程の基礎理論](../others/mdp.md)
- [$Q$-学習](../others/q_learning.md)
- [今回のAIのチューニング方法について](../others/reward.md)