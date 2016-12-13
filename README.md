# RequireFramework
这是运用require框架搭建的页面模板

---index.html  是页面的入口html文件
---static  存放的是页面所需要的静态文件 包括css js 图片等

---compress-css.bat  编译less文件以及压缩css文件的合并命令 利用gulp同步进行 使用前应该先 npm install 安装编译、压缩所依赖的npm包文件。编译的文件放到css对应的文件夹中,压缩的文件放到css_build对应的文件夹中

---compress.bat  利用r.js压缩js的命令 压缩的文件放到js_build对应的文件夹中