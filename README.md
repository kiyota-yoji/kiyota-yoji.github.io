# kiyota-yoji.github.io
Code4Lib JAPAN Conference 2022のチュートリアルで作ったWebサイトです。

# お知らせ

- ページを公開しました。
  - 箇条書きのテスト
- [動画](/event.html)をアップロードしました。

# 書籍リスト

<div>
  <ul>
    <!-- _data フォルダの books.csv からデータを取り出す -->
    {% for book in site.data.books %}
      <li>
        <!-- books.csv の title 列を表示、 url 列をリンク先に設定 -->
        <p class="title"><a href="{{ book.url }}">{{ book.title }}</a></p>
      </li>
    {% endfor %}
  </ul>
</div>
