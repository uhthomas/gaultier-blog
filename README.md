https://gaultier.github.io/blog/


## Quickstart

```
apt install parallel cmark
make
```

Generating table of contents (not sure if there is a better way):

```
pandoc -s --toc input.md -o /tmp/output.md
```
