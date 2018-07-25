---
description: 用户管理包括创建用户、编辑用户、删除用户、编辑个人角色、编辑个人权限和目录控制。
---

# 用户管理



## 创建用户

在“系统管理”页面中点击“用户管理”项，进入“用户管理”页面，可以在右侧查看用户列表信息。

![&#x7528;&#x6237;&#x5217;&#x8868;](../../.gitbook/assets/xin-zeng-yong-hu-1.png)

在左侧部门树上选中一部门如“工程部”，则在右侧可以看到选中部门下的人员列表。

![&#x67E5;&#x770B;&#x9009;&#x4E2D;&#x90E8;&#x95E8;&#x7684;&#x7528;&#x6237;&#x5217;&#x8868;](../../.gitbook/assets/xin-zeng-yong-hu-2.png)

点击“新增”按钮，弹出“新增”对话框。

![&#x201C;&#x65B0;&#x589E;&#x201D;&#x5BF9;&#x8BDD;&#x6846;](../../.gitbook/assets/chuang-jian-yong-hu-3.png)

在“新增”对话框中设置用户的用户名、真实姓名、密码、邮箱、部门和角色等信息，其中带\*项为必填项。这里设置用户名如为“A”，真实姓名为“A”，邮箱为“A@syslink.com”，部门为“工程部”，角色为“一般用户”，接着设置密码和确认密码。若密码选择为空，则默认为“111111”。

![&#x65B0;&#x589E;&#x7528;&#x6237;](../../.gitbook/assets/xin-zeng-yong-hu-4.png)

点击“提交”按钮，提示添加用户成功，接着在人员列表中可看到新创建的用户信息。

![&#x65B0;&#x589E;&#x7528;&#x6237;&#x540E;&#x7684;&#x6548;&#x679C;](../../.gitbook/assets/xin-zeng-yong-hu-5.png)

## 编辑用户

对选中的用户进行编辑操作，包括部门、真实姓名、邮箱、密码和是否禁止登录等信息。

在人员列表中选中一用户如新增的“A”，接着在“选项”下拉菜单中选择“编辑”，弹出“编辑用户信息”对话框。

![&#x201C;&#x7F16;&#x8F91;&#x7528;&#x6237;&#x4FE1;&#x606F;&#x201D;&#x5BF9;&#x8BDD;&#x6846;](../../.gitbook/assets/bian-ji-ge-ren-jiao-se-1%20%281%29.png)

在“编辑用户信息”对话框中修改选中用户的部门、真实名称、邮箱、密码和是否被禁止等信息，如这里将部门设置为“测试组”。

![&#x7F16;&#x8F91;&#x7528;&#x6237;&#x4FE1;&#x606F;](../../.gitbook/assets/bian-ji-yong-hu-02.png)

点击“提交”按钮，提示编辑用户成功。接着在人员列表中可看到用户“A”编辑后的信息，如下图所示。

![&#x7F16;&#x8F91;&#x7528;&#x6237;&#x540E;&#x7684;&#x6548;&#x679C;](../../.gitbook/assets/bian-ji-yong-hu-2%20%281%29.png)

## 删除用户

在人员列表中，选中一用户如新增的“A”，接着在“选项”下拉菜单中选择“删除”，弹出是否删除用户的确认框。

![&#x662F;&#x5426;&#x5220;&#x9664;&#x7528;&#x6237;](../../.gitbook/assets/shan-chu-yong-hu-1.png)

点击“确认”按钮，删除选中的用户；点击“取消”按钮，取消人员的删除操作。

## 编辑个人角色

在人员列表中选中一用户如“A”，接着在“选项”下拉菜单中选择“分配角色”，弹出“分配角色”窗口。

![&#x201C;&#x5206;&#x914D;&#x89D2;&#x8272;&#x201D;&#x5BF9;&#x8BDD;&#x6846;](../../.gitbook/assets/bian-ji-ge-ren-jiao-se-1.png)

“分配角色”对话框右侧为选中用户当前拥有的角色，将角色从左侧移至右侧表示加角色，从右侧移至左侧表示减角色。这里以给用户“A”添加“安全管理员”的角色为例，勾选左侧的“安全管理员”角色，接着点击“分配”按钮，则选中的角色移至右侧。

![&#x7F16;&#x8F91;&#x4E2A;&#x4EBA;&#x89D2;&#x8272;](../../.gitbook/assets/bian-ji-ge-ren-jiao-se-2.png)

若要删除该角色，则在右侧将其勾选，点击“移除”按钮即可。

系统同时支持勾选多个用户后，点击下方“批量操作”下拉菜单中的“分配角色”，对多个用户进行角色分配操作。

## 编辑个人权限

在人员列表中选中一用户，这里仍以“A”为例。在“选项”下拉菜单中选择“分配权限”，弹出“分配权限”对话框。在“分配权限”对话框中勾选/取消勾选一权限，则选中用户拥有或者取消拥有该权限。

![&#x5206;&#x914D;&#x6743;&#x9650;](../../.gitbook/assets/bian-ji-ge-ren-quan-xian.png)

系统同时支持勾选多个用户后，点击下方“批量操作”下拉菜单中的“分配权限”，对多个用户进行权限分配操作。

## 目录控制

设置用户对公有仓库分类目录的控制权限，包括可读、读/写、完全。若为“可读”，则仅允许用户对公有仓库分类目录下的仓库进行查看和下载操作；若为“读/写”，则在“可读”的基础上新增移动操作；若为“完全”，则在“读/写”的基础上新增删除操作。

在人员列表中选中一用户，这里仍以“A”为例。在“选项”下拉菜单中选择“目录控制”，弹出“目录控制”对话框。

![&#x76EE;&#x5F55;&#x63A7;&#x5236;](../../.gitbook/assets/mu-lu-kong-zhi-1%20%281%29.png)

在“目录控制”对话框中设置选中用户对公有仓库分类目录的控制权限，点击“提交“按钮即可。系统同时支持勾选多个用户后，点击下方“批量操作”下拉菜单中的“目录控制”，对多个用户进行目录控制操作。
