1 基本的なHTMLタグとサイトレイアウトについて
    <p>:段落の意味で、pタグで囲うと中の文字が表示
    <img>：イメージの略で画像表示に使用、終了タグ不要
    <src>:sourceの略で、srcに画像のURLを貼る
    alt属性：src属性で、設定した画像が、読み込み不可の時、文字を表示
        <img src="" alt="">:imgタグでは両属性が必須
    <a> Ankerの略で閉じタグ必須。URLを貼る。
        <a href="">◯◯</a>
        写真を押してリンクに飛ばすには
            〇〇の部分に <img src="" alt="">を入れる
    <div>:これ自体には特徴はないが、divisionの略で、ひとまとまりを作るためのタグ。共通処理を    したい時に使う。

    ①基本的なWebページのレイアウト
        ヘッダー　ファーストビュー（最初にユーザーに見える部分）　メインコンテンツ（サイトの内容）　フッター（会社の情報や各ページのリンクをユーザにわかりやすく伝える）

2 基本的なCSSまとめ
    <style></style>:CSSを入れるタグ
    <p class="">:HTML側に入れる属性。.class名 {}
    <color>:色をつけるタグ（カラーコードをブラウザで調べて入れるのが一般的）
    <width>:横幅を制御する　width: px;  
    <height>:高さ制御のためのCSSタグ
    <font-size>:文字の大きさを変更
    <margin>:top,bottom,left,rightなどで余白を調整する
    <padding>要素内の余白を調整
    <background-color>:背景色
    <background-image>:その要素の背景として画像を表示する。文字を重ねられる利点がある
    <fit-content>:文字と背景の長さを揃えたい時に入れる

3 横並びや好きな場所に配置するCSS
    <flex-box>:要素を横に整列させたり中央に寄せる技術
            display: flex;
        <justify-content>:横並びに均等に整列させたいときに使用する
        <flex-direction>:縦横の方向を制御する
    <position>:余白を考えず要素を移動させるだけ
        retative:自分を基準に移動
        absolute:親要素を基準に移動
    
4 サイト模写チャレンジ
    ①Git
        <git config>:gitの設定をするコマンド
        <global>:パソコン全体の設定ができる
            git config --global user.name ""
            git config --global user.email ""
        <git remote add origin URL>: