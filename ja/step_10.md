## メニューバーのスタイリング

- CSSは、メニューバーの見ためをよいものにすることができます。 styles.cssファイルをもう一度開きます（魔法が起きる場所！）変更するたびに、RunをクリックしてWebサイトの外観を確認します。

- `nav ul` セレクタを見つけて、次のようにルールを追加します。

   ```css
   nav ul {
    background-color: tomato;
    border-style: solid;
    border-color: MediumVioletRed;
    border-width: 2px;
    padding: 10px;
   }
   ```

   `padding` プロパティは余白を追加します。 他のプロパティのそれぞれが何をしているのか考えることができますか？ いろいろな色とピクセル数で試してみてください。 ![](images/egMenuBarMoreStyle.png)

- リンクの下線を取り除くには、`nav ul li` のルールを `{}` の中に次のコードを追加します。

   関連するものは、まとめておくほうがいいですね！

     ```css
     nav ul li a {
      text-decoration: none;
     }
     ```

  上のルールは、ナビゲーション\(`<nav>`\)セクション中にある、番号なしリスト中の item にある、リンク\(`<a>`\)に対して反映されます！4つのセレクタを組み合わせています！ ![](images/egMenuBarNoUnderline.png)

- リストアイテム中のリンクタグを削除することによって、クリックしたアイテムを簡単に知ることができますよね?  リンクしていない文字と同じく、リンクの文字色を変えてみましょう!  `nav ul li a` の `color` プロパティを追加することにより、メニューのリンク文字の色を変えることができます。

   ```css
      color: PapayaWhip;
   ```

   あなたの好きな色を入れてください！

   `nav ul li a` の `color` プロパティを追加することにより、メニューのリンク文字の色を変えることができます。

- カドはどうでしょうか? nav ul に、`border-radius: 10px;` を追加してどうなるか試してみましょう。

   `border-radius` プロパティは、とても簡単にカドをカッコよくすることができます! さらに、このルールを画像にも適用することができます。img セレクタに、`border-radius` ルールを追加してください 

- 以下は、今回のスタイルシートとウェブページがどのように見えるかの例になります。 
  ![](images/MenuBarFullStyles.png)



