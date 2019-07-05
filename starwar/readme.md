## emet 快捷输入
vscode 来自微软 . 内置了emet插件
.使用了css选择器来快速的语法
   1.类选择器 . className
   2.>父子选择器
   3.+兄弟
   4.[]属性选择器
   .starwars-demo>img*2[src="./images/]

   .starwars-demo>img.
   .定位
     css 布局的一种
     position：absolute；
     position：relative；body 是最顶层的定位
     父级或一直往外查找，如果有定位元素，
     相对最近的长辈元素定位，否则就是body
     .starwars-demo>img*2[src="./images/star.svg" class="star"]+h2[class="byLine"]>span*15

    -transform
       变形属性 translate 移动 |scale 缩放| rotate 旋转
       三维世界 perspective 视点（眼睛）与屏幕的距离
       transform-style:prespective;
       

    -npm node的工具包管理
         live-server 静态网页提供了web-server 热更新（自动刷新页面）
         npm install -g 全局安装一个live-server
         js 的命令行工具 让js可以运行在服务器端
