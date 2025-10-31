# 練習問題の解答
練習問題の解答例を載せておきます。

## よくあったトラブル
- 各練習問題のセルの冒頭にある
```python
%%tee student_output
# --- この下に課題のコードを書いてください ---
```
は **消さないでください**。 なお、この冒頭部分は解答例では省略しています。

- マジックコマンド `%%` は Python コードより前に各必要があるので、例えば
```python
import re
%%tee student_output
# --- この下に課題のコードを書いてください ---
```
などと書いていると **動かない** ので注意してください。

- 各テキスト冒頭にある採点用プログラムは **一番最初に実行** してください。

- 採点をする場合は **先に採点をしたいコードを実行** してから、採点用のプログラムを実行してください。


## 前半
### 練習問題1.
```python
print("Hello, World!")
```

### 練習問題2.
```python
my_name = "もり" # 名前は今回は「もり」にしているがなんでもいい
print(my_name + "です、こんにちは！")
```

### 練習問題3.
```python
apple = 150
banana = 100
grape = 200
print("タイムセール前の値段")
print(f"りんご:{apple}円")
print(f"バナナ:{banana}円")
print(f"ぶどう:{grape}円")

# 以下の式の右辺に適当な式を入れてタイムセール中値段に更新しよう！
apple = apple * 0.7
banana = banana * 0.5
grape = grape * 0.8
print("\nタイムセール中の値段")
print(f"りんご:{apple}円")
print(f"バナナ:{banana}円")
print(f"ぶどう:{grape}円")
```

### 練習問題4.
```python
a1 = 2
a2 = 3
a3 = 2 * a2 + a1
a4 = 2 * a3 + a2
a5 = 2 * a4 + a3
```

## 後半
### 練習問題1.
```python
age = 22 # ここは 22 以外の数字でもOK
if age > 17:
  print("あなたは工藤新一より年上です。")
elif age == 17:
  print("あなたは工藤新一と同い年です。")
else:
  print("あなたは工藤新一より年下です。")
```

### 練習問題2.
```python
for i in range(1, 21):
    print(i)
```
あるいは以下のようにしてもOK。
```python
for i in range(20):
    print(i+1)
```

### 練習問題3.
```python
counter = 0
while counter < 5:
    print("Hello, World!")
    counter = counter + 1
```