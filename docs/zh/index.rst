欢迎来到 Doctrine 2 ORM 文档!
==========================================

Doctrine的文档由教程, 用例等从不同的角度讲解对象关系如何映射

Doctrine的DBAL包和Common包也有它们各的文档

入门
---------------

* **入门**:
  :doc:`doctrine 入门 <tutorials/getting-started>`

* **安装**:
  :doc:`安装 & 配置 <reference/configuration>`

对象映射
-------------------------------

* **映射**:
  :doc:`对象映射 <reference/basic-mapping>` |
  :doc:`关联映射 <reference/association-mapping>` |
  :doc:`继承映射 <reference/inheritance-mapping>`

* **映射驱动**:
  :doc:`注释驱动 <reference/annotations-reference>` |
  :doc:`XML驱动 <reference/xml-mapping>` |
  :doc:`YAML驱动 <reference/yaml-mapping>` |
  :doc:`PHP驱动 <reference/php-mapping>`

对象用例
--------------------

* **对象用例**:
  :doc:`实体 <reference/working-with-objects>` |
  :doc:`关联 <reference/working-with-associations>` |
  :doc:`事件 <reference/events>`

* **查询用例**:
  :doc:`DQL查询语言 <reference/dql-doctrine-query-language>` |
  :doc:`查询构造器 <reference/query-builder>` |
  :doc:`自定义SQL  <reference/native-sql>`

* **内部实现**:
  :doc:`原理解释 <reference/unitofwork>` |
  :doc:`关联分析 <reference/unitofwork-associations>`

拓展主题
---------------

* :doc:`架构 <reference/architecture>`
* :doc:`配置进阶 <reference/advanced-configuration>`
* :doc:`限制和不足 <reference/limitations-and-known-issues>`
* :doc:`命令行工具 <reference/tools>`
* :doc:`事务和并发 <reference/transactions-and-concurrency>`
* :doc:`过滤器 <reference/filters>`
* :doc:`命名规则 <reference/namingstrategy>`
* :doc:`性能优化 <reference/improving-performance>`
* :doc:`缓存 <reference/caching>`
* :doc:`缺陷对象 <reference/partial-objects>`
* :doc:`对象行为监听策略 <reference/change-tracking-policies>`
* :doc:`最佳实践 <reference/best-practices>`
* :doc:`元数据驱动器 <reference/metadata-drivers>`
* :doc:`批处理 <reference/batch-processing>`
* :doc:`二级缓存 <reference/second-level-cache>`

教程
---------

* :doc:`索引关联 <tutorials/working-with-indexed-associations>`
* :doc:`关联的超懒加载 <tutorials/extra-lazy-associations>`
* :doc:`复合主键 <tutorials/composite-primary-keys>`
* :doc:`关联排序 <tutorials/ordered-associations>`
* :doc:`分页 <tutorials/pagination>`
* :doc:`在子类中重写字段和关联的映射 <tutorials/override-field-association-mappings-in-subclasses>`
* :doc:`嵌入值 <tutorials/embeddables>`

用例
--------

* **设计模式**:
  :doc:`聚合字段 <cookbook/aggregate-fields>` |
  :doc:`装饰器模式 <cookbook/decorator-pattern>` |
  :doc:`策略模式 <cookbook/strategy-cookbook-introduction>` 

* **DQL 扩展**:
  :doc:`DQL Custom Walkers <cookbook/dql-custom-walkers>` |
  :doc:`DQL 自定义函数 <cookbook/dql-user-defined-functions>`

* **实现**:
  :doc:`数组访问 <cookbook/implementing-arrayaccess-for-domain-objects>` |
  :doc:`通知监听例子 <cookbook/implementing-the-notify-changetracking-policy>` |
  :doc:`Using Wakeup Or Clone <cookbook/implementing-wakeup-or-clone>` |
  :doc:`使用DataTime <cookbook/working-with-datetime>` |
  :doc:`校验器 <cookbook/validation-of-entities>` |
  :doc:`会话实体 <cookbook/entities-in-session>` |
  :doc:`如何保持项目中模块独立 <cookbook/resolve-target-entity-listener>`

* **集成到框架**
  :doc:`CodeIgniter框架 <cookbook/integrating-with-codeigniter>`

* **容易忽略的**
  :doc:`表前缀 <cookbook/sql-table-prefixes>`

* **自定义数据类型**
  :doc:`MySQL 枚举 <cookbook/mysql-enums>`
  :doc:`字段高级转换 <cookbook/advanced-field-value-conversion-using-custom-mapping-types>`

.. include:: toc.rst
