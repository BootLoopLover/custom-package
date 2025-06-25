Custom Package 
--------------

How to build
#Open Terminal

```
echo >> feeds.conf.default
echo 'src-git custompackage https://github.com/BootLoopLover/custom-package.git' >> feeds.conf.default
```

#Update Feeds
```
./scripts/feeds update -a
./scripts/feeds install -a
```
----------
