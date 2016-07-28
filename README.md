**前端模块化项目模板（SPA单页）**

**基本框架：** fis3(构建工具) + vue（框架） + zepto（类库） + seaJs（模块化） + director（路由）

```bash
打開項目後，如下步驟運行：
npm install   安裝package.json內必要的褲
npm install -g fis3 安裝fis3


fis3 release -wL   啓動代碼自動部署監聽
                  （fis3 release過程中會遇到發佈失敗，需要一些依賴參見，按照提示安裝需要的插件即可）
fis3 server start  啓動fis3服務，預覽項目

```


目录结构如下：
```
project
  ├─ modules     工程模块
  │  ├─ common  公共模块
  │  │  └─ baseDialogPage 模态窗口基类
  │  │  └─ basePage       所有项目模块基类
  │  ├─ components         独立组件
  │  │  ├─ header
  │  │  └─ .....
  │  └─ pages               一般页面、弹框模块
  │     ├─ selectCity
  │     └─ home
  ├─ static      静态资源
  │  ├─ css     
  │  ├─ images  
  │  ├─ js      
  ├─ app.js         项目入口
  ├─ fis-conf.js    fis编译配置
  ├─ index.html     html页面
  ├─ package.json   npm配置文件 
  ...
```



 - [Vue官网](http://cn.vuejs.org/guide/installation.html) 
 - [Fis3官网](http://fis.baidu.com/) 
