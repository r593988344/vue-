```
1.$mount 的实现
对于 complier 版本 对el进行一系列处理
当 this.$options 没有定义 render 函数，尝试获取 render 函数，
将获取 templete 最终将其编译为 render函数
执行完 $mount 后调用 mountComponent 方法 最终生成 updateComponent 函数，
通过渲染 Watcher 调用 updateComponent
```
