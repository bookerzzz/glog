# glog

Leveled execution logs for Go.

This is a shim for use with [logrus](https://github.com/Sirupsen/logrus); it needs to be initialised as in:

```go

glog.Log = logrus.New()
glog.Verbosity = 1
```
