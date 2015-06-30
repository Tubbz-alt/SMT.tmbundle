# smt.tmbundle



#SMT TextMate Bundle

This is a TextMate support for viewing and editing version 2.5 of [SMT-LIB2.](http://smtlib.cs.uiowa.edu/papers/smt-lib-reference-v2.5-r150528.pdf)

### TextMate 2 Development Instructions.

The [FAQ](https://github.com/textmate/textmate/wiki/FAQ) says the following:


If you wish to edit the bundles and share your changes you should install (git clone) them to:
```
~/Library/Application Support/Avian/Bundles
```

This way, TextMate won’t create delta files (which aren’t useful for sharing).

If you manually install bundles and they do not show up, your file
system may lack support for fs-events. If this is the case, you will
need to delete the cache and relaunch TextMate:

```
rm ~/Library/Caches/com.macromates.TextMate/BundlesIndex.plist
```




