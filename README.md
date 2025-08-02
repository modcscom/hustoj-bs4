# HUST OJ bs4 template
这是HUSTOJ使用的模板。

目前正在sungil-oj网站上使用中。

部分页面正在修改中。如有需要反馈的内容，请通过以下邮箱联系我们。
网站：
https://code.juwon.info
https://www.sjcode.net

使用此模板时，会连接到bs4admin目录的管理文件。

在oj-header.php中
$OJ_ADMIN = "bs4admin"
可以修改此项（默认目录是admin）

模板导航栏的基本颜色在oj-header.php中
$OJ_MAIN_COLOR = "info"; //info success danger warning primary
可以修改此项（默认目录是admin）

本皮肤仅限教育用途+非商业用途使用，遵循GPL 2.0许可证。
此皮肤是在hustoj的原始源代码基础上修改制作的。
修改者：Leejunghwan(bigdipper81@nate.com)
"朱元啊，大自然本来就是慢的。"

安装方法指南：

将bs4/目录复制到hustoj > template目录

将核心文件（problemset.php, notice.php）复制到hustoj目录（务必先备份）

将bs4admin/目录复制到hustoj目录

设置bs4admin/msg.txt文件的chmod为707

变更的功能：

顶部header部分整合改为oj-header.php

大幅修改了原本很糟糕的problemset.php搜索功能（需要更改核心）

部分库替换为CDN

更改了图表设计

常见问题-编译器信息从服务器获取并输出

使用fontawsome

尝试按照网页标准制作管理员页面

在问题注册画面添加了scrollspy

改进了比赛注册UI

改进了单行公告(msg.txt)。可以使用html。

改善了移动端响应性

修改了问题查看页面设计

新增功能：

管理员-可以通过网页修改db_config.php

管理员-可以通过网页修改lang.ko.php

更换了编辑器 - 可以粘贴图片（需要修改字段类型）

添加了系统信息输出功能

显示排名

制作了公告页面

使用的库：

chart.js

jQuery 3.6

fontawsome

bootstrap 4.6

tinyMCE

提供帮助的人：

李朱元（喜欢火车、公交车、飞机、吃肉）

newnnewer（主种族虫族）

hebelle（帅气racer）

未删除曾经使用过的不必要文件...
