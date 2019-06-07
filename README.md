# dot grapch examples

## how to generate
```
find . -name '*.dot' | xargs -L1 -I{} dot -Kdot -Tsvg "{}" "-o{}.svg"
```
