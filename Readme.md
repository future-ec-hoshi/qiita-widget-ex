# Qiita Widget（改）

## オリジナル

オリジナルは下記です。

- Qiita Widget
  - https://github.com/suin/qiita-widget

## オリジナルとの差異

### IE11対応

IE11だと、スクリプト内でインラインフレームのDOM操作部分にて、アクセス拒否で
エラーが発生するため、ちょいと変更しました。

### 投稿取得数の指定

投稿の取得件数を指定することができるようになってます。

## 使い方

```html
<a class="qiita-timeline" href="https://qiita.com/users/{ユーザ名}" data-qiita-username="{ユーザ名}" data-qiita-itemcount="5">{ユーザ名}のtips</a>
<script src="https://raw.github.com/future-ec-hoshi/qiita-widget-ex/master/script.js"></script>
```

