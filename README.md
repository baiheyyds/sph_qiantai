# 尚品汇商城项目

## 使用的技术/包

1、Vue/cli 脚手架创建项目以及基本的配置（vue.config.js）

2、vuex、store（将不同模块的数据存储到不同的仓库中，善用 getters 简化获取仓库数据的过程）

3、vue-router，全局前置守卫、路由中添加 meta 属性用来实现不同页面 footer 是否显示

4、element-ui，全局挂载常用组件（message.button 等）

5、mock.js 模拟数据，实现在后端接口出来前进行开发

6、vue-lazyload 实现图片的延迟加载

7、利用 uuid 生成一个临时 token，用于非支付页面的访问

8、nprogress、在 axios 的二次封装时，在请求拦截器和响应拦截器时添加一个进度条的加载效果

9、用 swiper 快速实现轮播图图的创建，以及善用$nexTick 来实现在 dom 渲染完成后再生成轮播图

10、
