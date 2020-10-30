金曜日に実演できれば

GitHub Flavored Markdown
`GitHub Flavored Markdown` 

# 金曜にギットハブの readme に使える程度のマークダウンの書き方を教える

金曜にギットハブの readme に使える程度のマークダウンの書き方を教えるの 30 分の説明ぐらい。

</br>

厳密に教えるのは `GitHub Flavored Markdown` というMarkdownが掛かれている。

- チートシート [Markdown 記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
- 参考ページその２ [メモ書きやドキュメント作成に便利な「Markdown 記法」を使ってみよう](https://www.asobou.co.jp/blog/bussiness/markdown#:~:text=Markdown%EF%BC%88%E3%83%9E%E3%83%BC%E3%82%AF%E3%83%80%E3%82%A6%E3%83%B3%EF%BC%89%E3%81%A8%E3%81%AF,%E4%BB%A5%E4%B8%8B%E3%81%AE%E7%89%B9%E5%BE%B4%E3%81%8C%E3%81%82%E3%82%8A%E3%81%BE%E3%81%99%E3%80%82)

## 教える内容

- 見出し系
- リスト系
- `> 引用`
- コードプレビュ
- 強調系
- リンク(外へのリンク)
- html タグをそのまま書ける。

## html タグをそのまま書ける実演

<script>alert('JavaScriptのalert関数の実行');</script>
<script>console.log('コンソールログも動く？');</script>

```js
<script>alert('javaScriptのalert関数の実行');</script>
```

で js は実行できるかも？実行できるとセキュリティー上の問題が発生するが......

```php
<?php
5+5
```

<details>
    <summary>折り畳み</summary>
```html
<details>
    <summary>折り畳み</summary>
    <b>折り</b>た<i>た</i>まれる本文
</details>
 ```
   </br>
    <b>折り</b>た<i>た</i>まれる本文
</details>

記法法のそれぞれの拡張。上記 5 つの他の場所での使用例。

</br>
code記法にならない場合もある->`こことか`