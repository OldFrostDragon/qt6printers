# qt6printers

LLDB pretty printers for Qt6 types based on the original [KDevelop](https://invent.kde.org/kdevelop/kdevelop) printers.

## How to use LLDB printers

Create `~/.lldbinit` file and add the following lines to it

```
settings set target.load-script-from-symbol-file true

command script import ~/<path-to-cloned-repo>/lldb/qt.py
```

## Supported types

- [x] QVector
- [x] QList
- [x] QStack
- [x] QQueue
- [x] QMap
- [x] QMultiMap
- [x] QHash
- [ ] QMultiHash
- [x] QSet
- [x] QString
- [x] QStringList
- [x] QByteArray
- [ ] QVariant
- [ ] QDate
- [ ] QTime
- [ ] QDateTime
- [x] QUrl
- [x] QUuid
- [ ] QCache
