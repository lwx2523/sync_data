# 目录

## 前端cursor rules

按照前端react 和vue两个框架，编写两套cursor rules.

### React cursor rules

| 文件                       | 描述                                  |
| ------------------------ | ----------------------------------- |
| 001-project-overview.mdc | 描述项目代码文件目录结构                        |
| 200-coding-style.mdc     | 描述前端代码的coding style确保生成代码的风格统一      |
| 300-react-guidelines.mdc | React 前端框架的规范                       |
| 400-api-standards.mdc    | 描述项目接口的规范，包括封装类的介绍，请求格式， 响应格式和代码实例。 |
| 999-ai-interaction.mdc   | 描述ai 应答时的规则和一些指令                    |

### Vue cursor rules

整体结构和React一致，部分规则按照Vue框架的特性做了调整

| 文件                       | 描述                                  |
| ------------------------ | ----------------------------------- |
| 001-project-overview.mdc | 描述项目代码文件目录结构                        |
| 200-coding-style.mdc     | 描述前端代码的coding style确保生成代码的风格统一      |
| 300-vue-guidelines.mdc   | Vue 前端框架的规范                         |
| 400-api-standards.mdc    | 描述项目接口的规范，包括封装类的介绍，请求格式， 响应格式和代码实例。 |
| 999-ai-interaction.mdc   | 描述ai 应答时的规则和一些指令                    |

## 后端cursor rules

按照rules的规则的不同，将规则分为语言规则，框架规则和项目规则。 如下列表中

- 2xx的文件：为语言规则，描述java语言的基本规范。

- 3xx的文件：为框架规则，描述基于spring boot +mybatis plus的规范。

- 4xx的文件：为项目规则，已公证项目为例，描述项目结构和项目中的DDD框架的功能。

### 规则文件介绍

| 文件                                           | 描述                                            |
| -------------------------------------------- | --------------------------------------------- |
| 201-java-general-guidelines.mdc              | Java最佳实践和模式，包括代码风格、面向对象设计、异常处理、集合操作、并发编程等     |
| 210-java-maven-best-practices.mdc            | Maven构建工具的最佳实践，包括依赖管理、构建配置、项目结构等              |
| 211-java-concurrency.mdc                     | Java并发编程指南，线程安全、同步机制、并发工具类使用等                 |
| 221-java-logging.mdc                         | Java日志记录规范，包括日志框架使用、日志级别、日志格式等                |
| 231-java-unit-testing.mdc                    | Java单元测试最佳实践，测试框架使用、测试策略、Mock技术等              |
| 301-frameworks-spring-boot.mdc               | Spring Boot框架基础规范，包括依赖注入、配置管理、MVC模式等          |
| 302-frameworks-spring-boot-rest.mdc          | Spring Boot REST API开发规范，RESTful设计、接口文档、异常处理等 |
| 302-frameworks-spring-boot-service.mdc       | Spring Boot服务层开发规范，业务逻辑处理、事务管理等               |
| 303-frameworks-spring-boot-respository.mdc   | Spring Boot数据访问层规范，MyBatis Plus使用、数据库操作等      |
| 304-frameworks-spring-boot-entity.mdc        | Spring Boot实体类设计规范，领域模型、数据库映射等                |
| 311-frameworks-spring-boot-slice-testing.mdc | Spring Boot切片测试规范，单元测试、集成测试策略等                |
| 401-project-stucture.mdc                     | 项目整体架构和目录结构，基于DDD的分层架构设计                      |
| 402-project-ddd-framework-guide.mdc          | DDD框架使用指南，领域聚合根、领域服务、XML配置和代码生成等              |
| 403-project-dto-conventions.mdc              | DTO约定和转换规范，数据传输对象设计、MapStruct使用等              |
| 404-project-code-generation-steps.mdc        | 代码生成步骤和规范，自动化代码生成流程                           |
| 500-sql.mdc                                  | SQL开发指南，包括命名约定、表设计、查询优化、索引策略、安全性等             |
