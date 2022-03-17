
Here are some tbox build tools(extract from xmake) can help you build tbox where xmake is not installed.

Use like below.

```
cd src/tbox
# put tbox source here
cp -r $TBOX_SOURCE_ROOT tbox
export PRO_DIR='the project location'
export PLAT='linux/msys/mingw etc.'
make
```