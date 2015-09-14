# prhのサンプル

サンプルプロジェクト

- [vvakame/prh](https://github.com/vvakame/prh "vvakame/prh")
- [azu/textlint-rule-prh](https://github.com/azu/textlint-rule-prh "azu/textlint-rule-prh")

## 間違った単語のチェック

JQuery は jQuery が正しいはずだ。

## リンクの単語は無視される

[jquery.com](http://jquery.com/) というリンクの文字列は無視できる。 

## 確認方法

### prh

[vvakame/prh](https://github.com/vvakame/prh "vvakame/prh")

```
npm run prh
```

(dry-runで変換された結果が表示されます)

### textlint

[azu/textlint-rule-prh](https://github.com/azu/textlint-rule-prh "azu/textlint-rule-prh")

```
npm run textlint
```

Lint結果が表示されます。