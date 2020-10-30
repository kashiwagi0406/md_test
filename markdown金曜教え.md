金曜日に実演できれば

GitHub Flavored Markdown
`GitHub Flavored Markdown`

# 金曜にギットハブの readme に使える程度のマークダウンの書き方を教える

金曜にギットハブの readme に使える程度のマークダウンの書き方を教えるの 30 分の説明ぐらい。

</br>

厳密に教えるのは `GitHub Flavored Markdown` という Markdown が掛かれている。

- チートシート [Markdown 記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
- 参考ページその２ [メモ書きやドキュメント作成に便利な「Markdown 記法」を使ってみよう](https://www.asobou.co.jp/blog/bussiness/markdown#:~:text=Markdown%EF%BC%88%E3%83%9E%E3%83%BC%E3%82%AF%E3%83%80%E3%82%A6%E3%83%B3%EF%BC%89%E3%81%A8%E3%81%AF,%E4%BB%A5%E4%B8%8B%E3%81%AE%E7%89%B9%E5%BE%B4%E3%81%8C%E3%81%82%E3%82%8A%E3%81%BE%E3%81%99%E3%80%82)

## 教える内容

- 見出し系
  - [見出し](https://qiita.com/tbpgr/items/989c6badefff69377da7#%E8%A6%8B%E5%87%BA%E3%81%97)
- リスト系
  - [箇条書きリスト](https://qiita.com/tbpgr/items/989c6badefff69377da7#%E7%AE%87%E6%9D%A1%E6%9B%B8%E3%81%8D%E3%83%AA%E3%82%B9%E3%83%88)
- `> 引用`
  - [引用](https://qiita.com/tbpgr/items/989c6badefff69377da7#%E5%BC%95%E7%94%A8)
- コードプレビュ
- 強調系
- リンク([外へのリンク](https://qiita.com/tbpgr/items/989c6badefff69377da7))
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
改行のタグ後のに改行して、code記法にならない場合もある->`こことか`

改行

改行１

改行 2

> 引用
>
> > 引用２
> >
> > > 引用 3

###### シャープ 6 語

####### シャープ 7 語

############################## シャープ 31 語

1. 1-1
1. 1-2
1. 1-3
1. 1-4

上下一行開け、タブか半角空白でブロックコードになるらしい、知らなかった。

    class Hoge
      def hoge
        print 'hoge'
      end
    end


バッククォート×3でやった方が安全？シンタックスハイライト使えるし？
```ruby
    class Hoge
      def hoge
        print 'hoge'
      end
    end
```
