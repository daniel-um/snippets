# snippets
handy snippets

example 1:
```bash
curl <url of snippet> | bash
```
  
example 2:
```bash
vim testfile
:r <url of snippet>
```

consider adding the following to the end of the url if making frequent changes to snippet, and caching becomes an issue:
```
?any-var-name=$(date +%s)
```
