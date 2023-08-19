# flow-sheet
あすぱるが作ったディベートのフローシートを保管する場所です。

- [CDS-Project 納涼杯 2023 フォーマット](./cds-noryo-2023-format.html) (A3 x 2枚)



### 開発に必要なもの

使用しているフォントがローカルにインストールされている必要があります。
- Madera
- Noto Sans JP
- ゴスペル
- 筑紫AMゴシックS
- 筑紫ゴシック Pro

### あると便利なもの
[live-server](https://www.npmjs.com/package/live-server)とかでホストすると、
CSSとか変えたときに自動で更新されてしあわせ。
```
live-server --port=3000 --no-css-inject
```

### 今後やりたいこと
- pdf化をCI/CDでやれるようにする (フォントの関係で難しそうだけど……)
- TSXとかで再実装して、自分でフォーマット決めて作れるようにする (Webサービス化)

