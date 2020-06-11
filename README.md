# 基礎キャッチアップ感想

## Git

特に新しい発見はなし、わからないところもなし。

Gitに限らずRubyもそうみたいだけれど、バージョンの指定がない。
別に常に教材が最新のバージョンに対応する必要はないとは思うが、
教材内で使用するバージョンの指定がないのであれば、最新バージョンまで考慮した内容が必要だと感じる。
Gitの場合`v2.23`から`checkout`が`switch`と`restore`に分離されている。
教材の手順通りにインストールした場合、そのバージョンを使っていくことになるので、
そちらの説明も加える必要があると感じる。

## HTML・CSS



### HTML
4章ではナビゲーションはヘッダー領域内にあると説明しながらも、5章では
```html
    <header>
        <h1 class="headline">
            <a href="index.html">CARAVAN</a>
        </h1>
    </header>
    <nav>
        <ul class="nav-list">
            <li class="nav-list-item">
                <a href="index.html">Home</a>
            </li>
            <li class="nav-list-item">About</li>
            <li class="nav-list-item">Topic</li>
        </ul>
    </nav>
```
とナビゲーションバーが`<header>`要素の外にある。
また、5章の完成版ソースコードは`<header>`のインデントがおかしい。

### CSS
`flex`を差し置いて`float`を使ってるのが気になる。
もう`float`は使われなくなってくんじゃないかな。
```css
a {
    text-decoration: none;
}
```
`<a>`がリンクだと一目でわからないスタイルはデザイン的に最悪。
