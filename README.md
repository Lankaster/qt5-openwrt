# qt5-openwrt
QT 5.12.4 for Openwrt 19.07
=========================

Installation instructions
-------------------------

1. Add feeds in feeds.conf


```
src-git libqt https://github.com/petrov-adg/qt5-openwrt.git
```

2. Update & install feeds

```
./scripts/feeds update -a && ./scripts/feeds install -a
```

3. Now you can find QT libs in Libs->Qt5
