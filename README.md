### intro

forked from [jiangmiao/autopairs](https://github.com/jiangmiao/auto-pairs), add the `g:AutoPairs_fileTypeExclude`
option and auto-indent in html tags.

+ disable autopairs in certain filetypes

```
let g:AutoPairs_fileTypeExclude = ['scheme', 'racket']
```

+ add auto-indent in html-tags

```
input:
<div>|</div> {press <CR> at |}

output: 
<div>
  |
</div>
```
