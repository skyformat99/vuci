# vuci

![](https://img.shields.io/badge/license-GPLV3-brightgreen.svg?style=plastic "License")

VUCI - OpenWrt后台管理框架，基于[vuejs2](https://github.com/vuejs/vue)和[element-ui](https://github.com/ElemeFE/element).

`请保持关注以获取最新的项目动态`

# 如何使用
在"feeds.conf.default"里面添加新的feed:
    
    src-git vuci https://github.com/zhaojh329/vuci.git

安装vuci软件包:
    
    ./scripts/feeds update
    ./scripts/feeds install -a -p vuci

在menuconfig里面选择vuci软件包然后编译新固件.

    VUCI  --->
        <*> vuci-ui-base.......................................... VUCI Web Interface</*>


# 如何开发和调试
首选进入OpenWrt源码目录，然后执行如下命令：

	$ cd feeds/vuci/vuci-ui-base/src/
	$ npm install

根据自己的环境修改配置：

	vi config/index.js

然后执行如下命令运行调试服务器

	npm run dev

# 贡献代码
如果你想帮助[vuci](https://github.com/zhaojh329/vuci) 变得更好，请参考
[CONTRIBUTING_ZH.md](https://github.com/zhaojh329/vuci/blob/master/CONTRIBUTING_ZH.md)。

# 技术交流
QQ群：153530783