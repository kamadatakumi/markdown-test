# 箇条書き
- item1
- item2
- item3
- {ctrl}+{shift}+{M}キー

もう一つの大見出し
===

中見出し
---

## h2タグのタイトル

### h3小見出し

###### h6まで使える。

hello.  
hello. hello. hello. hello. hello.
hello.

hello.

改行だけでは改行にならない。改行前にスペース２つ以上入れると改行になる。

# 引用
> quote,quote,quote

## 引用とは
他の著作物の一部を抜粋して、それについて述べたりすること、本文と明確に異なる書式にする。

# 区切り線

---

***

___

- - -

上に行があるとh2になってしまう。

# 強調表現

普通　*強調*　普通

normal *kyoutyou* normal

普通　**強調**　普通

nomal **kyoutyou** normal

# 箇条書き

- item1
- item2

    段下げした状態で文を記載できる。  
    前後に空行を入れて、４つ半角スペースを入れる。

- item3

# 連番リスト
1. 数字、ドット、スペース
2. 数字は何でもよい
1. これでも3になる。
1. よくやるのは、**すべて1**にする

# リンク
<http://dotinstall.com/>

http://dotinstall.com/

[リンクの文字](http://dotinstall.com/)

[ホバー](http://dotinstall.com/　”ドットインストール”)

利用したアセットへのりんくなどで活用するとよい。

# コードを見やすくする

function x() {
  return x;
}

```

文字内でコードを表す場合
`function`と書く

javascript

バックフォード3つの後ろに言語を現すつづりを書くと、その言語用のハイライトが行われる。
C#ならch,HTMLならhtml,C言語ならc

# 箇条書きのインデント
- 箇条書き
  - スペース2つで箇条書きで,段下げ
    - スペース4つでさらに下げる

# 画像
![ALT属性](http://dotinstall.com/img/logo_200x200.png "ドットインストール")

# 画像にリンク
[![ALT属性](http://dotinstall.com/img/logo_200x200.png "ドットインストール")](http://dotinstall.com/)

#マークダウンファイルと同じ場所へのリンク
- [いらすとや](http://www.irasutoya.com/)

![山菜ごはん](./food_sansai_gohan.png)
