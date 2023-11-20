# log

erpc 的日志库


使用
## 直接使用
```
log.Debug("hello %s", "world")
```

## 自定义logger
```
l := log.Logger()
log.SetDefaultLogger(l)
log.Debug("hello %s", "world")
```
