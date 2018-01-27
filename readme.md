# Wizard 

Wizard是基于Laravel开发框架开发的一款开源项目（API）文档管理工具。

在线预览体验地址：http://wizard.aicode.cc/

![s-1](https://oayrssjpa.qnssl.com/s-1.jpg)

![s-2](https://oayrssjpa.qnssl.com/s-2.jpg)

![s-4](https://oayrssjpa.qnssl.com/s-4.jpg)

![s-5](https://oayrssjpa.qnssl.com/s-5.jpg)

![s-6](https://oayrssjpa.qnssl.com/s-6.jpg)

![s-70](https://oayrssjpa.qnssl.com/s-70.jpg)

![s-8](https://oayrssjpa.qnssl.com/s-8.jpg)


## 安装

安装依赖

    composer install --prefer-dist

安装配置数据库

    cp .env.example .env
    
    php artisan migrate:install
    php artisan migrate
    
文件上传支持需要执行以下命令

    php artisan storage:link
    
执行该命令后会在public目录下创建`storage/app/public`目录的符号链接。

## TODO

* [ ] 新版本更新
    * [ ] 自动检测是否有新版本
    * [ ] 无损更新版本
* [x] markdown编辑器增加json转换为markdown表格的功能
* [x] 项目功能
    * [x] 项目新增
    * [x] 项目配置
    * [x] 项目权限分配
    * [x] 项目删除
    * [ ] 支持对项目进行分组，首页分组展示
* [x] 文档历史管理，文档恢复
* [x] 操作日志记录
* [x] 国际化支持
* [x] markdown编辑器增加图片上传支持
* [x] 文档差异比较，文档历史版本差异比较
* [x] 文档多人编辑避免内容冲突覆盖
* [x] 文档管理
    * [x] 文档编辑
    * [x] 新增文档
    * [x] 支持Swagger格式文档
    * [x] 支持markdown文档
    * [x] 文档删除
* [x] 文档菜单支持折叠
* [x] 权限组，分组权限，管理员权限
    * [x] 项目按照分组分配读写权限
    * [x] 项目按照用户分配读写权限
* [ ] 文档模板管理
    * [x] 另存为模板
    * [x] 编辑器选择模板
    * [x] 模板列表
    * [ ] 模板更新
    * [ ] 模板删除
* [ ] 文档排序
* [x] 项目排序
* [ ] 文档标签
* [ ] 文档评论
    * [x] 实现最基本的评论功能
    * [x] 实现评论回复，带层级的评论
    * [x] 实现评论支持@某人
    * [ ] 实现评论支持@用户组下所有用户
* [ ] 消息通知功能
    * [x] 支持@某人后收到消息
    * [x] 支持消息列表
    * [x] 新的消息提示
    * [x] 消息全部已读，部分已读
    * [ ] 新消息邮件提醒
    * [ ] 消息接收配置（站内信，邮件，接收类型）
* [ ] 关注项目
    * [ ] 关注项目，取消关注
    * [ ] 已关注项目列表
    * [ ] 关注项目变更后接收消息通知
* [ ] 支持导出文件
    * [ ] 导出pdf
    * [ ] 导出markdown、swagger
    * [ ] 导出word
* [ ] 实现API接口管理，自动根据接口数据判断接口是否需要修改
* [ ] 对接postman，实现自动生成接口文档，接口测试
* [ ] 实现页面中之间互相引用
* [ ] 项目列表分页展示，增加按照项目标题搜索
* [ ] 文档增加标题搜索
* [x] 文档保存后弹框提示选择：继续编辑还是创建新文档
* [ ] 文档分享
    * [x] 分享链接
    * [x] 分享后的文档页面，单页面模式
    * [ ] 分享链接管理
    * [ ] 分享链接有效期设置
    * [ ] 分享链接删除
* [x] 文档附件
    * [x] 附件上传
    * [x] 附件展示
    * [x] 附件删除
    * [x] 附件重传（历史附件）
* [x] 用户管理
    * [x] 用户登录，注册，找回密码
    * [x] 基本信息修改
    * [x] 修改密码
    * [x] 管理员分配
    * [x] 用户分组管理
        * [x] 管理员管理分组
        * [x] 分组基础数据结构支持
    

