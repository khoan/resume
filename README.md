# Steps

## publish

```
$ git checkout master
$ hugo # compile
$ git checkout gh-pages
$ ditto public/* .
$ git add .
$ git commit -m "xxx"
$ git push
