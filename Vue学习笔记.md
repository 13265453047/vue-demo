## 开发前准备

### 安装Vue工具 `Vue CLi` 

+ `Vue CLi` Vue.js开发的标准工具，`Vue CLi` 是一个基于 Vue.js 进行快速开发完整系统

  > `npm install -g @vue/cli ` 或者 `cnpm install -g @vue/cli`
  >
  >  -g:全局安装
  >
  > 安装之后，你就可以在命令行中访问`vue` 命令。例如使用`vue --version` 验证是否安装成功

###  创建一个项目 

1. `vue create my-project`

> 温馨提示
>
> 1、项目名称不能含有大写字母
>
> 2、在控制台中，可以用上下键调整选项
>
> 在控制台中，可以用空格（spacebar）选择是否选中和取消选中

可选择默认项目模板，或者选“手动选择特性”来选取需要的特性

![1679897587533](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679897587533.png)

我们选择Babel和Progressive Web App (PWA) Support两个选项即可

> 温馨提示：
>
> 在学习期间，不要选中 `Linter/Formatter` （严格要求书写规范）以避免不必要的错误提示（我们选择1、3）

![1679897910263](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679897910263.png)

2. 版本的选择

Vue目前有两个主流大版本`vue2`和`vue3`，我们选择`vue3`最新版本

![1679897927652](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679897927652.png)

3. 配置文件放在那里？`In dedicated config files` 专用配置文件或者`In package.json` 在package.json

选择第一个（转用配置文件）

![1679898122528](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679898122528.png)



4. 是否保存前面的配置选项

![](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679898182438.png)

5. 项目创建成功

![1679898313010](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679898313010.png)



### 运行项目

1. 第一步L进入项目根目录 `cd vue-demo`
2. 第二步：运行`npm run server`启动项目

![1679899063048](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679899063048.png)

3. 浏览器输入 `localhost:8080`

> 项目中的这些内容都可以认为是配置信息

![](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679899177842.png)



![1679899908581](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679899908581.png)

> assets 文件夹：存放静态文件
>
> components文件夹：存放公共组件
>
> `App.vue` 文件根组件，所有的组件都是从这里引入来显示的，组件入口
>
> `main.js` 主入口文件
>
> `registerServiceWorker.js`这个文件不用管，可以理解为监听文件，项目做到那里了等等

### 安装Vue高亮插件

VSCode中安装`vetur` 或者`volar `（插件）都可，前者针对Vue2版本，后者针对Vue3版本



### 模板语法

![1679900453342](1.%E6%A8%A1%E6%9D%BF%E8%AF%AD%E6%B3%95/vue-demo/src/assets/md/1679900453342.png)



`template` 写HTML文件的

`script` 写业务逻辑的

















