# Web性能优化 

雅虎性能优化方法：https://developer.yahoo.com/performance/rules.html

### 性能不好原因

* 网页内容太多，文件太大

* 服务器性能不好（带宽、内存等）

* 请求太多

### 1.尽量减少HTTP请求次数

* 合并JS

* 合并CSS

* 图片sprite

### 2.延迟加载内容

* 图片懒加载

* 数据懒加载（点击查看更多）

* 功能懒加载（曝光加载或者点击后加载HTML模块、JS功能模块）

### 3.使用离线缓存

* 把常用的变动又少的JS、CSS、图片存储到localstorage