# Example of prh

See Also 

- [vvakame/prh](https://github.com/vvakame/prh "vvakame/prh")
- [azu/textlint-rule-prh](https://github.com/azu/textlint-rule-prh "azu/textlint-rule-prh")

## Check wrong word

JQuery should be jQuery 

## Ignore word in link title

[jquery.com](http://jquery.com/) is ignored 

## Usage


### textlint + prh

textlint + prh can check text as Markdown.

[azu/textlint-rule-prh](https://github.com/azu/textlint-rule-prh "azu/textlint-rule-prh")

```
npm run textlint

> textlint README.md

/Users/azu/.ghq/github.com/azu/prh-textlint-example/README.md
  10:1  ✓ error  JQuery => jQuery  prh

✖ 1 problem (1 error, 0 warnings)
✓ 1 fixable problem.
Try to run: $ textlint --fix [file]
```


### prh

[vvakame/prh](https://github.com/vvakame/prh "vvakame/prh") check text as plain text.

```
npm run prh
```

dry-run results.