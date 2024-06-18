跳转后的页面地址栏，就是此文件的url

需要注意，这个文件的url默认打开是github的项目页面，要直接访问源文件需要以下处理：
在地址栏中的 url背后 拼接一个 ?raw=true ，并按下回车键访问此新地址。

观察并获取地址栏跳转后的真实地址
浏览器会自动从github.com/xxx/xxx.gif 跳转到 https://raw.githubusercontent.com/xxx/xxx.gif，
后面这个url就是图片文件的真实地址了，复制这个地址配置即可。
