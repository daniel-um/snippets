# snippets
handy snippets

example 1:
```bash
curl -L <url of snippet> | bash
```
  
example 2:
```bash
vim testfile
:r <url of snippet>
```

in bash, use unique urls if making frequent changes to snippet and caching becomes an issue:
```bash
<url of snippet>?any-var-name=$(date +%s)
```
