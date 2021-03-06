# 运行配置

## SysLink服务器运行配置

\(1\). SysLink服务器安装完成后，打开“C:\Windows\SysWOW64\CAEModelDBS\tomcat\webapps\ROOT\WEB-INF\classes”\[默认安装路径\]下的“application.properties”，修改其中的“gogsHostPath”（位于62行）和“HostPath”（位于64行）为当前服务器IP。

```text
gogsHostPath = 192.168.52.128:3001

HostPath = 192.168.52.128:8080
```

\(2\). 修改“C:\Windows\SysWOW64\CAEModelDBS\tomcat\webapps\ROOT\WEB-INF\classes\static\assets\js”\[默认安装路径\]下“app.442745aca11fdf64a966.js”中的“HostPath”（位于112111行）为当前服务器IP。

```text
var HostPath = "192.168.52.128";
```

\(3\). 修改“C:\Windows\SysWOW64\CAEModelDBS\tomcat\webapps\ROOT\WEB-INF\classes\static\assets\js”\[默认安装路径\]下“app.442745aca11fdf64a966.js.map”中的“HostPath”为当前服务器IP。

```text
const HostPath = \"192.168.52.128\"\r\n
```

\(4\). 首次启动SysLink服务器时需要对数据库mysql进行配置，运行开始菜单“CAEModelDBS”下的update.bat即可。

\(5\). 接着或者非首次启动SysLink服务器，运行开始菜单“CAEModelDBS”下的nginx.exe启动nginx服务器，接着运行Startup.bat启动tomcat服务器。

![&#x542F;&#x52A8;tomcat](../.gitbook/assets/qi-dong-tomcat.png)

\(6\). 接着在浏览器中输入“syslink.com”，按下Enter键启动SysLink web端登录界面。

![&#x542F;&#x52A8;SysLink web&#x7AEF;&#x767B;&#x5F55;&#x754C;&#x9762;](../.gitbook/assets/qi-dong-syslink.png)

## SysLink客户端运行配置

双击桌面上的快捷方式MWorks，即启动SysLink客户端。

![&#x542F;&#x52A8;&#x5BA2;&#x6237;&#x7AEF;](../.gitbook/assets/qi-dong-ke-hu-duan.png)

接着对服务器地址和端口号进行配置，点击菜单“工具→选项”，弹出“选项”对话框，切换至“Syslink→登录”项。

![Syslink&#x2192;&#x767B;&#x5F55;](../.gitbook/assets/pei-zhi-fu-wu-qi-di-zhi-he-duan-kou.png)

输入正确的用户名、密码、服务器地址和端口号，接着点击“验证”按钮，提示登录成功。

![&#x63D0;&#x793A;&#x767B;&#x5F55;&#x6210;&#x529F;](../.gitbook/assets/ti-shi-deng-lu-cheng-gong.png)



