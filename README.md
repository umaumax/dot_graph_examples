# dot grapch examples

## how to generate
```
find . -name '*.dot' | xargs -L1 -I{} dot -Kdot -Tsvg "{}" "-o{}.svg"
```

## Q&A
* [Graphviz dot: How to change the colour of one record in multi\-record shape \- Stack Overflow]( https://stackoverflow.com/questions/17765301/graphviz-dot-how-to-change-the-colour-of-one-record-in-multi-record-shape )

> I'm pretty sure that it's not possible. Instead you should use HTML-style labels, that are a more developped form of record nodes.

## FMI
* [Graphvizとdot言語でグラフを描く方法のまとめ \- Qiita]( https://qiita.com/rubytomato@github/items/51779135bc4b77c8c20d )
