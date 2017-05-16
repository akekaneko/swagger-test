# Mark down お勉強

# 見出し１
## 見出し２
### 見出し３
#### 見出し４
##### 見出し5
###### 見出し6


## 水平線

---

***

___

## 引用

見出し見出し

>引用引用引用1行目
>
>>引用引用引用2行目
>>aaaa
>
>引用引用引用3行目
>
>引用4行目


## リンク

[YAHOO](http://yahoo.co.jp) YAHOOのホームページです

[Google](http://google.com) Googleのホームページです

[リンクテキスト][4]　あれやこれや

[Issueから相対リンクのテスト](../blob/issue-67/index.md)

## 簡単なリンク方法

<address@example.com>
<http://example.com/>


## 強調文字

**半角アスタリスク２つで囲む**


## 改行

行末に2つスペースをいれると改行されます  
スペースなし
すぺーすなし

## リスト

- 通常リスト2つスペースの場合
  - aaaa
    - bbbb
      - cccc
- 通常リスト3つスペースの場合
   - aaaa
      - bbbb
         - cccc
+ リスト
   + あああ
      + いいい

1. 数字リストは３つスペースでないと
   1. GitHubではエラーになります
   1. なので、通常リストも３つにすると統一感あるかもです
      1. aaaaa
      1. bbbbb
      - aaaaa
      - aaaaa
1. bbbbb
1. ccccc


## テーブル

|   あああ   |     goisu      |
|------------|----------------|
| aaa        | こんにちは     |
| さようなら | 日本語はだめか |
| これは便利 | あああ         |
| いいい     | ううう         |


| 左寄せ|中央寄せ|右寄せ|
|:--|:---:|---:|
| aaa        | こんにちは     |asdf|
| さようなら | 日本語はだめか |abc|
| abc | あああ         |vvvv|
| いいい     | ううう         |ccc|

※Dropboxではすべて左寄せになる


## コード

`1行の場合`


```javascript
  const ui = SwaggerUIBundle({
    url: "http://petstore.swagger.io/v2/swagger.json",
    dom_id: '#swagger-ui',
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIStandalonePreset
    ],
    plugins: [
      SwaggerUIBundle.plugins.DownloadUrl
    ],
    layout: "StandaloneLayout"
  })
```

行頭に半角スペース4つでも表現可能らしい

    aaaaa
    bbbbb
    ccccc


## 画像

![ALT属性](https://www.google.co.jp/logos/doodles/2017/cassini-spacecraft-dives-between-saturn-and-its-rings-5717425520640000-s.png)

<!--
![ALT属性](https://www.google.co.jp/logos/doodles/2017/cassini-spacecraft-dives-between-saturn-and-its-rings-5717425520640000-s.png　"Optional title")
※Dropboxではエラー
-->

## 画像（参照）

![ALT属性][2]


## 打ち消し線

~~テスト~~


## タスク一覧

- [ ] 朝、目覚める
- [x] 歯磨きをする
- [x] 電車に乗る

## 絵文字

:smile:
:+1:
:anger:
:bomb:
:musical_keyboard:
:blue_car:
:congratulations:

### 絵文字リスト
- https://www.webpagefx.com/tools/emoji-cheat-sheet/

## コメントアウト

HTMLと同様の方法で。

```
<!-- this is a comment. -->
```


## 参考
- https://guides.github.com/features/mastering-markdown/
- https://help.github.com/articles/basic-writing-and-formatting-syntax/




<!-- Links -->
[1]: https://www.google.co.jp/logos/doodles/2017/cassini-spacecraft-dives-between-saturn-and-its-rings-5717425520640000-law.gif "option タイトル"
[2]: https://www.google.co.jp/logos/doodles/2017/cassini-spacecraft-dives-between-saturn-and-its-rings-5717425520640000-s.png "kokoha nakutemo yoi"
[3]: https://www.google.co.jp/logos/doodles/2017/cassini-spacecraft-dives-between-saturn-and-its-rings-5717425520640000-s.png "optional title"
[4]: http://example.com/  "Optional Title Here"
