# 夏末-宗长计算器

#### 介绍
夏末-宗长计算器summerendffxiv.club-foxcalculator

根据绝杀宗长表格数据构建的快速查询计算器

#### 架构

非常非常原始的前端三件套，挑几个重点说

根据原表格，数据分为4组（A、B、C、D）之后旋转4个方向，共16组数据。
6✖️6的按钮组的ID定义规则：
    在html中根据从左到右，从上到下的顺序，依次将按钮ID定义为11到66，对应坐标（1，1）--> （6，6），后续只需要进行除法和取余就能获取坐标值，如34/10=3，34%10=4.

![输入图片说明](https://foruda.gitee.com/images/1685171519327816496/63a39410_10069853.png "719ebafe4e8eb7340d71b8471949ada7.png")

确定是那个数据组：




#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
