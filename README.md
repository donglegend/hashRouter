# [hashRouter 预览demo](http://donglegend.com/effects/hashRouter/index.html)
自己写了一个 hash 路由，目前还不懂 h5 history有什么关系，再研究.

HashRoute 是挂在在全局的 window，不可被实例化，直接使用。

## methods
### maps
批量注册 路由和处理方法

### add
添加路由 
HashRoute.add('paht', function (path){})
### remove
删除 路由 HashRoute.remove(path)
### clear
全部清空 HashRoute.clear()
### go
跳转到 HashRoute.go(path)
### redirect
重定向，类似于 go


