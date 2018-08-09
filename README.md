# springBootDemo

#### 项目介绍
使用maven+springboot+各种与springboot整合的技术搭建的架构
以技术为核心,以模拟业务为测试

#### 项目技术

    假设你已经掌握了以下的技术,如果想了解更多本项目所用到的技术,请点击相应链接
    
- [JDK1.8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)  运行环境
- [springMVC](https://docs.spring.io/spring/docs/4.3.16.RELEASE/spring-framework-reference/htmlsingle/) 基础框架
- [springboot](https://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/)  基础框架
- [mybatis:](http://www.mybatis.org/mybatis-3/zh/index.html) 数据库映射和操作组件
- [mysql](https://dev.mysql.com/doc/refman/5.7/en/) 数据库链接驱动
- [maven ](https://www.yiibai.com/maven/create-a-project-with-maven-template.html) 项目构建工具
- [springfox-swagger2 2.8.0](http://springfox.github.io/springfox/docs/current/)   API文档生成组件


#### 软件架构
> 软件架构说明

    |---file 文件
        |pic 图片
        |sql-script 项目所用到的各种脚本(数据库sql脚本等)
    |---logs 日志
    |template-business 业务模块(当然还包括其他模块)
    |template-common   公共模块(禁止与一切业务逻辑有关)
        |qianpen-cache 自定义的redis缓存框架支持
        |qianpen-db    公用的数据库相关类，包括mybatis插件、druid配置等
        |qianpen-sms   公用的短信发送类
        |qianpen-spring 公用的spring相关配置、切面、异常处理等插件类
        |qianpen-zuul-ext: 网关公用的一些帮助类(未实现)
        |qianpen-core  公用的pojo、帮助类、异常类等
            |utils    工具类
            |config 配置
                | swaggerConfig 在线API文档配置
                | WebMvcConfig 拦截器配置
                | ApplicationStartUp 项目启动配置
    |template-web   web模块
        |src
            |main
                |java
                    |com.qianpen.templateweb
                            |api 对外提供API
                            |config
                            |controller
                            |service
                            |dao
                |resource资源文件根目录  
                    |static静态文件
                    |application.yml springboot配置文件
            |test 测试包 
    |REDME.md 项目使用说明文档
#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

1. xxxx
2. xxxx
3. xxxx

#### 参与贡献

1. Fork 本项目
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

####GitHub

- 本项目GitHub地址:[https://github.com/SZMOFEI/code-template.git](https://github.com/SZMOFEI/code-template.git)

- 本项目码云地址:[https://gitee.com/mohaoyang/code-template.git](https://gitee.com/mohaoyang/code-template.git)
#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [http://git.mydoc.io/](http://git.mydoc.io/)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)