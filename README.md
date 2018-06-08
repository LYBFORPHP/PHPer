# PHP开发知识结构

## 目录 
#### 顺序：基础 => 进阶 => 原理 => 架构 => 业务 => 软技能
* [开发工具](#开发工具)
* [环境搭建](#环境搭建)
* [编程语言](#编程语言)
* [代码质量](#代码质量)
* [PHP](#PHP)
* [安全](#安全)
* [数据库](#数据库)
* [NoSQL](#NoSQL)
* [框架](#框架)
* [推荐](#推荐)
* [计算机基础](#计算机基础)
* [编程知识储备](#编程知识储备)
* [架构](#架构)
* [业务](#业务)
* [文档规范](#文档规范)
* [开发流程](#开发流程)
* [软技能](#软技能)


## 开发工具
- 编辑器和IDE
    - [PhpStorm](https://www.jetbrains.com/phpstorm/)
    - [VIM](http://www.vim.org/)
    - [Sublime Text](http://www.sublimetext.com/)
    - [VS code](https://code.visualstudio.com/)
    - [Notepad++](https://notepad-plus-plus.org/)

- 服务器组件
    - [XAMPP](https://www.apachefriends.org/zh_cn/index.html)* 
    - [WampServer](http://www.wampserver.com)
    - [phpStudy](http://phpstudy.php.cn/)

- 调试工具
    - [xhprof](http://php.net/manual/zh/book.xhprof.php)
    - [xdebug](https://xdebug.org/index.php)
    - [Fiddler](https://www.telerik.com/fiddler)
    - [Chrome Dev Tools](https://developer.chrome.com/devtools)

- 版本管理
    - [Git](http://git-scm.com/)/[SVN](http://subversion.apache.org/)
    - [Github](https://github.com/)/[GitLab](https://about.gitlab.com/)

- Mysql
    - [Navicat for Mysql](https://www.navicat.com.cn/)
    - [PhpMyAdmin](https://www.phpmyadmin.net/)

## 环境搭建
- Linux
- Nginx
- Apache
- Mysql
- PHP

## 编程语言
- 前端：CSS/Html/JavaScript/bootstrap
- LNMP：Linux/Nginx/Apache/Mysql/PHP
- 前端框架：Vuejs/React
- Golang

## 代码质量
- 编码风格
    - [PSR](https://www.php-fig.org/psr/)
    - [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
    - [Clean Code PHP](https://github.com/php-cpm/clean-code-php)
- 单元测试
    - [PHPUnit](https://phpunit.de/)
- 自动化测试

## PHP
- PHP基础
- 自动加载
- 命名空间
- 依赖管理： [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/)
- [PHP标准库](http://php.net/manual/zh/book.spl.php)


## 安全
- [CSRF](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- [XSS](https://en.wikipedia.org/wiki/Cross-site_scripting)
- [Same-origin policy](https://en.wikipedia.org/wiki/Same-origin_policy)
- [Web 应用程序安全](http://phpsecurity.readthedocs.io/en/latest/index.html)
- 密码哈希: [加盐处理](https://en.wikipedia.org/wiki/Salt_(cryptography))/[password_hash](http://php.net/manual/zh/function.password-hash.php)
- 数据过滤
- 配置文件
- 注册全局变量
- 错误报告

## 数据库
- Mysql
  - SQL基本（SELECT、UPDATE、INSERT、DELETE、JOIN、子查询）
  - MySQL特性（表引擎、字段类型、函数、索引类型）
  - MySQL进阶（Explain查询优化、Profiler、索引优化、processlist管理、备份还原、主从复制）
  - MySQL命令行操作
  -使用PHP操作MySQL（PDO、Prepare、Bind）
- SQLite

## NoSQL
- Memcached
- Redis
- MongoDB

## 框架
- [Laravel](https://laravel.com/)
- [Yii](https://www.yiiframework.com/)
    - [权威指南](http://www.yiichina.com/doc/guide/2.0)
- [symfony](https://symfony.com/)
- [codeigniter](https://codeigniter.com/)
- [Phalcon](https://phalconphp.com/zh/)
- [ThinkPHP](http://www.thinkphp.cn/)
- [Swoole](https://www.swoole.com/)

## 推荐
- [PHP之道](https://laravel-china.github.io/php-the-right-way/#language_highlights)

## 计算机基础
- 编译原理
- 计算机网络
- 操作系统
- 算法原理
- 计算机组成原理

## 编程知识储备
- [数据结构](http://zh.wikipedia.org/wiki/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)
    - 数组（Array）
    - 堆栈（Stack）
    - 队列（Queue）
    - 链表（Linked List）
    - 树（Tree）
    - 图（Graph）
    - 堆（Heap）
    - 散列表（Hash）
- [OOP](https://zh.wikipedia.org/zh-hans/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)/[AOP](https://zh.wikipedia.org/wiki/%E9%9D%A2%E5%90%91%E4%BE%A7%E9%9D%A2%E7%9A%84%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)
- [闭包](http://www.jibbering.com/faq/notes/closures/)
- [编程范型](http://zh.wikipedia.org/wiki/%E7%BC%96%E7%A8%8B%E8%8C%83%E5%9E%8B)
- [设计模式](https://github.com/domnikl/DesignPatternsPHP)
- 并发
    - 多线程
    - 线程安全
    - 一致性、事务
    - 锁
- 操作系统
    - 计算机原理
    - CPU
    - 多级缓存
    - 进程
    - 线程
    - 携程

## 架构
- 高并发
- 高性能
- 高可用
- 中间件
    - Web Server
    - 缓存
    - 消息队列
    - 定时调度
    - RPC
    - 数据库中间件
    - 日志系统
    - 配置中心
    - API网关
- 分布式/集群

## 业务
- 搜索
    -  Sphinx
    -  Solr
    -  Elasticsearch

## 文档规范
- 文档
  - 设计交付文档
  - URL接口文档
  - 数据库文档
- 规范
  - [HTTP](https://zh.wikipedia.org/zh-hans/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)

## 开发流程
- 编码
- 测试
- 部署
- 监控 

## 软技能
- 沟通能力
- 责任感
- 逻辑思维
- 分析问题、解决问题
- 学习能力
- 团队合作
