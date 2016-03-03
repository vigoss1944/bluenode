##view
###view/partials/prime  
* 这个里面主要是存放一些可以重用的html，在不同页面都可以引用
* {{>prime/taskflow}}就是给任务流的一些弹出窗口用的，{{>xxx}}是handlebars的定义
##grunt打包
* 目前页面引用的都是dist/*，全部都是grunt打包过的
* 改了js，css，测的时候可以改页面html引用原始的
* 也可以用grunt uglify： xxxx
*         grunt cssmin： XXXX，分别给css，js打包，打包后就不用改html了
* node根目录有个gruntfile.js 里面定义哥xxxx，改了哪个xxxx就对应执行哪个


##2016/3/3
###几个问题： 

