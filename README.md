---
marp: true
theme: yutori
size: "16:9"
paginate: true
headingDivider: 2
---

# Yutori

<!-- _class: center -->

"Yutori" は日本語もコードもすっきりと余裕を持って表示される Marp テーマです。

本文には [M PLUS 2](https://mplusfonts.github.io/) 、ソースコードには [Roboto Mono](https://github.com/googlefonts/RobotoMono) を採用しています。

主に技術的な発表をするために作ったので、LTなどにぜひお使いください。

## Usage: VSCode

`.vscode/settings.json` に `markdown.marp.themes` の項目を追加してください。

```json
{
  "markdown.marp.themes": [
    "https://raw.githubusercontent.com/amaotone/marp-theme-yutori/main/theme/yutori.css"
  ]
}
```

`.md` ファイルのヘッダー部分に `theme: yutori` を追加してください。

```yaml
---
marp: true
theme: yutori
---
```

## Usage: Marp CLI

[`theme/yutori.css`](https://raw.githubusercontent.com/amaotone/marp-theme-yutori/main/theme/yutori.css) をダウンロードして、適切な場所に置いてください。

以下のコマンドでビルドしてください。

```bash
$ marp [path/to/markdown] --theme [path/to/theme]
```

## Additional Classes

|名前|使いみち|
|:--|:--|
|center|中央揃えになります（表紙やアイキャッチに使います）|
|outline|スライドの縁を塗ります（付録ページに使います）|

## Contribution

<!-- _class: outline -->

Issue もしくは Pull Request を出してください
