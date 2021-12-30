## 一、目录结构
```text
api:
    按照后端服务分类存放请求
plugins:
    插件
router:
    路由
    已配置自动加载共用布局下的所有路由组件
store:
    全局变量
utils:
    自定义工具类
views:
    页面
    其中的router.js代表当前路由组件的路由结构
        需要默认指定根路由重定向的子路由
        meta中的auth属性代表页面跳转时是否需要访问权限判定
        meta中的breadcrumb属性是面包屑列表，不需要可以不指定
```