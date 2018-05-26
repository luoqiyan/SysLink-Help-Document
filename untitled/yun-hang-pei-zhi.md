# 运行配置

## SysLink服务器运行配置

\(1\). SysLink服务器安装完成后，打开C:\Windows\SysWOW64\CAEModelDBS\tomcat\webapps\ROOT\WEB-INF\classes\[默认安装路径\]下的application.properties，修改其中的gogsHostPath（位于62行）和HostPath（位于64行）为当前服务器IP。

{% code-tabs %}
{% code-tabs-item title="application.properties" %}
```text
gogsHostPath = 192.168.52.128:3001

HostPath = 192.168.52.128:8080
```
{% endcode-tabs-item %}
{% endcode-tabs %}



