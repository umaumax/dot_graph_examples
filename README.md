# dot grapch examples

## how to generate
```
find . -name '*.dot' | xargs -L1 -I{} dot -Kdot -Tsvg "{}" "-o{}.svg"
```

## FMI
* [Graphvizとdot言語でグラフを描く方法のまとめ \- Qiita]( https://qiita.com/rubytomato@github/items/51779135bc4b77c8c20d )
