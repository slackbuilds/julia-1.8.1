## Julia

A julia-1.8.1 build script.

```
bash-5.1$ diff julia.SlackBuild.orig julia.SlackBuild
28c28
< VERSION=${VERSION:-1.3.1}
---
> VERSION=${VERSION:-1.8.1}
104c104
< cat $CWD/$PRGNAM.info > $PKG/usr/doc/$PRGNAM-$VERSION/$PRGNAM.info
---
> # cat $CWD/$PRGNAM.info > $PKG/usr/doc/$PRGNAM-$VERSION/$PRGNAM.info
106a107
> rm -rf $PKG/usr/share/{appdata,applications}
110c111
< cat $CWD/doinst.sh > $PKG/install/doinst.sh
---
> # cat $CWD/doinst.sh > $PKG/install/doinst.sh
bash-5.1$
```
