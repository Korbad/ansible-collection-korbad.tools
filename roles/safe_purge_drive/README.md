# Safe Purge drive

```sudo find . -type l ! -exec test -e {} \; -delete```

```sudo find . -type d -empty -exec rmdir {} \;```
do this a few times ^
