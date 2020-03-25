# canal
原项目地址：https://github.com/alibaba/canal

## 修改介绍
项目基于v1.1.5-alpha-1版本进行改动（tag：canal-1.1.5-alpha-1）。主要改动模块是ES7Adaptor相关

另外，没有合并最新Master分支，因为太乱了，配置不兼容

0. 项目删减了一下配置文件
1. ES同步，连表查询支持非外键关联表的删改同步，具体配置可以参考teacher-join.yml。