# golang 学习资料汇总

## 基本知识

### 官方资料

[The Go Programming Language Specification](https://golang.org/ref/spec#Keywords)

[官方 go 仓库](https://github.com/golang/go)

### 优质学习资料

[Go 语言设计与实现](https://draveness.me/golang/)

[深入解析 GO](https://docs.kilvn.com/go-internals/01.0.html)

### Interface 实现

[Go Interface 源码剖析](http://legendtkl.com/2017/07/01/golang-interface-implement/)

## 高级知识

### net 开发

[Package http](https://golang.org/pkg/net/http/)

### 反射

[The Laws of Reflection](https://blog.golang.org/laws-of-reflection)

### goroutine 调度

[调度器](https://draveness.me/golang/docs/part3-runtime/ch06-concurrency/golang-goroutine/)

[Go: g0, Special Goroutine](https://medium.com/a-journey-with-go/go-g0-special-goroutine-8c778c6704d8)

[Scheduling In Go : Part III - Concurrency](https://www.ardanlabs.com/blog/2018/12/scheduling-in-go-part3.html)

[Go's work-stealing scheduler](https://rakyll.org/scheduler/)

### GC 实现

[Getting to Go: The Journey of Go's Garbage Collector](https://blog.golang.org/ismmkeynote)

[Garbage Collection In Go : Part I - Semantics](https://www.ardanlabs.com/blog/2018/12/garbage-collection-in-go-part1-semantics.html)

[深入理解 Go 语言-GC 与逃逸分析](https://zhuanlan.zhihu.com/p/103056375)

[深入理解 Go-垃圾回收机制](https://juejin.cn/post/6844903940186701831)

[内存管理](https://draveness.me/golang/docs/part3-runtime/ch07-memory/golang-memory-allocator/)

## 其他相关

### 依赖库版本管理

#### dep

目前官方推荐使用 modules，所以 dep 的没多少人使用了。

#### Modules

[Using Go Modules](https://blog.golang.org/using-go-modules)

[Modules](https://github.com/golang/go/wiki/Modules)

[Go Modules 详解](https://www.sulinehk.com/post/go-modules-details/)

[Go modules：最小版本选择](https://tonybai.com/2019/12/21/go-modules-minimal-version-selection/)

### Profiling

[Profiling Go Programs](https://blog.golang.org/pprof)

[Package pprof](https://golang.org/pkg/net/http/pprof/)

[Diagnostics](https://golang.org/doc/diagnostics.html)

[Profiling and optimizing Go web applications](https://artem.krylysov.com/blog/2017/03/13/profiling-and-optimizing-go-web-applications/)

[Go 性能调优](https://www.liwenzhou.com/posts/Go/performance_optimisation/)

[Golang FlameGraph（火焰图）](https://www.jianshu.com/p/1e784c387f45)

#### 逃逸分析

[Golang 内存逃逸是什么？怎么避免内存逃逸？](https://studygolang.com/articles/22875)

[Go Escape Analysis Flaws](https://docs.google.com/document/d/1CxgUBPlx9iJzkz9JWkb6tIpTe5q32QDmz8l0BouG0Cw/view)

## 推荐 Github 学习仓库

[over-golang](https://github.com/overnote/over-golang)

[ultimate-go](https://github.com/hoanhan101/ultimate-go)

[设计模式 Golang 实现－《研磨设计模式》读书笔记](https://github.com/senghoo/golang-design-pattern)

[awesome-go](https://github.com/avelino/awesome-go)
