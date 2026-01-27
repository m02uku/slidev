---
marp: true
lang: ja
theme: canyon
---

<!-- markdownlint-disable -->

<!-- _class: title -->

# 国試対策＜言語学③＞

---

<!-- _class: twoColumns -->

# キーワード


  <div>

  - 統語論
    - 樹構造
    - 構造的曖昧性
    - 句構造規則
    - 節

  </div>
  <div>

  - 言語類型論
    - 形態的な類型
    - 統語的な類型
    - 文字の類型

  </div>
</div>

---

<!-- _class: twoColumns -->

<!-- header: 統語論 -->

Q. 「ごはんを食べる」を２つに分けるとすると、どっち？

<div>

<svg viewBox="0 0 500 200" xmlns="http://www.w3.org/2000/svg">
  <line x1="250" y1="20" x2="150" y2="140" style="stroke:#999; stroke-width:2;" />
  <line x1="250" y1="20" x2="300" y2="80"  style="stroke:#999; stroke-width:2;" />
  <line x1="300" y1="80" x2="250" y2="140" style="stroke:#999; stroke-width:2;" />
  <line x1="300" y1="80" x2="350" y2="140" style="stroke:#999; stroke-width:2;" />
  <text x="100" y="30" text-anchor="start">a.</text>
  <text x="150" y="180" text-anchor="middle">ごはん</text>
  <text x="250" y="180" text-anchor="middle">を</text>
  <text x="350" y="180" text-anchor="middle">食べる</text>
</svg>

</div>

<div>

  <svg viewBox="0 0 500 200" xmlns="http://www.w3.org/2000/svg">
    <line x1="250" y1="20" x2="150" y2="140" style="stroke:#999; stroke-width:2;" />
    <line x1="250" y1="20" x2="300" y2="80"  style="stroke:#999; stroke-width:2;" />
    <line x1="200" y1="80" x2="250" y2="140" style="stroke:#999; stroke-width:2;" />
    <line x1="300" y1="80" x2="350" y2="140" style="stroke:#999; stroke-width:2;" />
    <text x="100" y="30" text-anchor="start">b.</text>
    <text x="150" y="180" text-anchor="middle">ごはん</text>
    <text x="250" y="180" text-anchor="middle">を</text>
    <text x="350" y="180" text-anchor="middle">食べる</text>
  </svg>

</div>

<br>

何を食べるの？→ :o: ごはん。／ :o: ごはんを。
ごはんをどうするの？ → :o: 食べる。／ :x: を食べる。
:o: パン、そしてごはんを食べる。／ :o: パンを、そしてごはんを食べる。
:o: ごはんを作り、そして食べる。／ :x: ごはんを作り、そしてを食べる。

→ <u>b の方が正しい</u>

---

<!-- header: 統語論 ＞ 構造的曖昧性 -->

**構造的曖昧性**：２つの解釈が可能 ＝ ２つの統語構造が仮定できる

<br>

<div class="columns">
  <div>
    <svg viewBox="0 0 500 200">
      <line x1=250 y1=20 x2=100 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=250 y1=20 x2=400 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=300 y1=60 x2=200 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=250 y1=100 x2=300 y2=140 style="stroke:#999;stroke-width:2;"/>
      <text x=50 y=30 text-anchor="start">a.</text>
      <text x=100 y=170 fill="black" font-size=0.7em text-anchor="middle">美しい</text>
      <text x=200 y=170 fill="black" font-size=0.7em text-anchor="middle">アルプス</text>
      <text x=300 y=170 fill="black" font-size=0.7em text-anchor="middle">の</text>
      <text x=400 y=170 fill="black" font-size=0.7em text-anchor="middle">少女</text>
    </svg>
  </div>
  <div>
    <svg class="col" viewBox="0 0 500 200">
      <line x1=250 y1=20 x2=100 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=250 y1=20 x2=400 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=200 y1=60 x2=300 y2=140 style="stroke:#999;stroke-width:2;"/>
      <line x1=150 y1=100 x2=200 y2=140 style="stroke:#999;stroke-width:2;"/>
      <text x=50 y=30 text-anchor="start">b.</text>
      <text x=100 y=170 fill="black" font-size=0.7em text-anchor="middle">美しい</text>
      <text x=200 y=170 fill="black" font-size=0.7em text-anchor="middle">アルプス</text>
      <text x=300 y=170 fill="black" font-size=0.7em text-anchor="middle">の</text>
      <text x=400 y=170 fill="black" font-size=0.7em text-anchor="middle">少女</text>
    </svg>
  </div>
</div>

<br>

→「美しいアルプスの少女」は２つの解釈が可能だが、これはこの文が２種類の統語構造で書き表されうるからである。

---

<!-- _class twiColumns -->

<!-- header: 統語論 ＞ 句構造規則 -->

<div>

![](./images/psr.png)

</div>
<div>

##この文は次のような**句構造規則**で形成されている

<hr>

S$\quad\,\,$→$\quad\!$PP$\quad\!$VP
PP$\quad\!$→$\quad\!$N$\quad\!$P
VP$\quad\!$→$\quad\!$PP$\quad\!$V
VP$\quad\!$→$\quad\!$PP$\quad\!$VP

→ 文を産出するために必要な語の組み合わせの規則（＝**文法**）を最小限に書き表せる

</div>

---

<!-- header: 節 -->

**節**：主語と述語からなる単位。一つの節からなる文を**単文**、複数の節からなる文を**複文**と呼ぶ。

<div class="columns">
<div>

### 構造による分類
- **主節**：文の中で最も中心的な節（普通、文末に位置する）
- **従属節**：主節以外の節

</div>
<div>

### 機能による分類（従属節）
- **連体節**：名詞（体言）を修飾する節  
  例：［この小説を書いた］作家

- **連用節**：述語（用言）を修飾する節  
  例：［時間があれば］出席する

</div>
</div>

---

<!-- header: 言語類型論 -->

**言語類型論**：複数の言語を比較し、言語間の類似点や相違点を明らかにしようとする分野
→ 言語の比較から、人間言語の本質を探ろうとする

<u>類型は、様々な観点から見出すことができる</u>
  - 形態的な類型
  - 統語的な類型
  - 文字の類型
 
---

<!-- header: 言語類型論 ＞ 形態的な類型 -->

## 形態的な類型

**膠着語**：実質的な意味を持つ語の語幹に接辞がつくという構造を持ち、その切れ目がはっきりしている言語  
例：日本語、韓国語、モンゴル語、トルコ語など

**屈折語**：語そのものが変化することによって示され、その境界がはっきりしない言語  
例：ラテン語、ギリシャ語など

**孤立語**：語が語形変化を持たない言語  
例：中国語など

---

<!-- header: 言語類型論 ＞ 形態的な類型 -->

## 格の表し方

**日本語（膠着語）**：名詞に助詞をつけることで表す  
例：私が、私を、彼が、彼を

**英語（屈折語）**：語（形態素）そのものが変化することで表す  
例：I、me、he、him

**中国語（孤立語）**：語形は変化しない  
例：我、我、他、他  
→ 語順で格を表す（SVO言語なので、動詞の前後どちらにあるかで格がわかる）

---

<!-- header: 言語類型論 ＞ 形態的な類型 -->

## 時制の表し方

**日本語（膠着語）**：語幹に語尾をつけることで表す  
例：行く、行った

**英語（屈折語）**：語（形態素）そのものが変化することで表す  
例：go、went

**中国語（孤立語）**：語形は変化しない  
例：去、去

> <u>注意点</u> 
> １つの言語の中でも他の類型の性質を持っている場合があるので、全てがその特徴に当てはまるわけではない  
> 例：中国語で「〜の」は「〜的」と書くのは膠着語的な性質

---

<!-- header: 言語類型論 ＞ 統語的な類型 -->

## 統語的な類型

- 文（他動詞文）に必要不可欠な**3つの要素の語順**に注目して言語を分類  
  - **S**：主語 (Subject) ／**O**：目的語 (Object) ／**V**：動詞 (Verb)

### SOV型
- 日本語・韓国語・モンゴル語・トルコ語・ヒンディー語など  
- 例：私は ピザを 食べる  
- **主要部後置型**／**後置詞**を持つことが多い

### SVO型
- 英語・中国語・タイ語・フランス語など  
- 例：I eat pizza.  
- **主要部前置型**／**前置詞**が多い  

---

<!-- header: 言語類型論 ＞ 文字の類型 -->

## 文字の類型

- 世界で使われる文字にも**いくつかの類型**がある

### 表意文字
- それ自体が**意味**を表す文字

### 表音文字
- それ自体が**音**を表す文字  
  - **音素文字**  
  - **音節文字**（音節＝子音＋母音）

---

<!-- header: 言語類型論 ＞ 文字の類型 -->

## 文字の分類例

| 文字 | 類型 |
|----|----|
| ひらがな | 音節文字 |
| ローマ字 | 音素文字 |
| アルファベット | 音素文字 |
| 漢字 | 表意文字（＋音節的要素） |
| 万葉仮名 | 音節文字 |


