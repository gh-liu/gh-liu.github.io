---
id: 1774320076-EXAM
title: "书籍列表"
createdAt: 2026-03-11
updatedAt: 2026-03-25 21:45:42
draft: true
---

# 开发环节书籍

需求 -> 设计 -> 编码 -> 测试

业务需求 → 系统架构 → 功能模块 → 接口定义 → 代码实现 / 重构 ⇄ 测试用例（TDD 下测试先行，两者在红-绿-重构循环中交替推进）

| 开发环节 | 子主题         | 书名                                                             | 内容备注总结                                                                               | 作者                                                     |
|----------|----------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------|
| 需求     | 需求探索       | *Exploring Requirements*                                         | 需求探索方法论，强调提问、发现约束、识别假设和澄清歧义，适合项目早期做需求挖掘与问题定义。 | Donald C. Gause, Gerald M. Weinberg                      |
| 需求     | 需求工程       | *Software Requirements, 3rd Ed*                                  | 需求工程工业级参考书，系统覆盖需求获取、分析、规格说明与管理的全过程。                     | Karl Wiegers, Joy Beatty                                 |
| 需求     | 示例驱动规格   | *Specification by Example*                                       | 用具体示例表达需求和验收标准，将模糊需求转为可验证的业务场景，适合 BDD 实践。              | Gojko Adzic                                              |
| 需求     | 用户故事       | *User Stories Applied*                                           | 用户故事经典入门，讲故事写法、拆分、估算与验收，适合敏捷团队建立需求管理方式。             | Mike Cohn                                                |
| 需求     | 用户故事地图   | *User Story Mapping*                                             | 从用户活动全景组织需求，通过故事地图梳理用户旅程、MVP 与发布切片，适合产品规划。           | Jeff Patton                                              |
| 设计     | 设计模式       | *Design Patterns: Elements of Reusable Object-Oriented Software* | GoF 设计模式奠基之作，系统化 23 种经典模式，建立对象间职责与协作的通用解法。               | Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides |
| 设计     | OO 建模        | *Object Design: Roles, Responsibilities, and Collaborations*     | 责任驱动设计经典，强调对象职责分配与协作关系，而非只画类图。                               | Rebecca Wirfs-Brock, Brian Wilkerson, Lauren Wiener      |
| 设计     | 领域驱动设计   | [[1773468681-NQHZ\|Domain-Driven Design]]                        | DDD 奠基之作，介绍统一语言、限界上下文、聚合、实体与值对象，适合复杂业务系统建模。         | Eric Evans                                               |
| 设计     | 企业应用架构   | *Patterns of Enterprise Application Architecture*                | 企业应用架构模式大全，覆盖领域模型、事务脚本、仓储、服务层与数据映射等。                   | Martin Fowler                                            |
| 设计     | 整洁架构       | *Clean Architecture*                                             | 依赖规则与架构边界，强调组件内聚/耦合原则和插件式架构，隔离业务逻辑与外部细节。            | Robert C. Martin                                         |
| 设计     | 架构基础       | *Fundamentals of Software Architecture: An Engineering Approach* | 现代架构教材，覆盖架构风格、架构决策、工程权衡与演化式架构，适合体系化入门。               | Mark Richards, Neal Ford                                 |
| 设计     | 数据密集型系统 | [[1774321392-MVBX\|Designing Data-Intensive Applications]]       | 系统讲解存储、复制、分区、一致性、流处理与批处理，理解分布式数据系统的必读书。             | Martin Kleppmann                                         |
| 设计     | 功能模块       | [[1773469069-APOSD\|A Philosophy of Software Design]]            | 讲模块分解与复杂度管理，深模块 vs 浅模块，直接指导功能模块的职责划分与接口设计。           | John Ousterhout                                          |
| 设计     | 接口定义       | [[1774337384-QNWU\|API Design Patterns]]                         | API 契约设计的模式化参考，覆盖命名、资源布局、版本控制与兼容性演进等通用模式。             | JJ Geewax                                                |
| 设计     | 接口定义       | [[1774337469-CZIN\|The Design of Web APIs]]                      | 从用户视角设计 Web API，强调易用性、一致性与开发者体验，适合 RESTful API 设计实践。        | Arnaud Lauret                                            |
| 设计     | 生产稳定性     | *Release It!, 2nd Ed*                                            | 生产环境稳定性模式（断路器、超时、舱壁、背压），聚焦系统韧性与运维实践。                   | Michael T. Nygard                                        |
| 编码     | 编码构建       | *Code Complete, 2nd Ed*                                          | 编码实践百科全书，覆盖变量命名、控制流、协作开发与代码调优，建立全面编码素养。             | Steve McConnell                                          |
| 编码     | 重构           | [[1774322895-BXVS\|Refactoring]]                                 | 重构权威著作，讲代码坏味道识别与小步安全重构，提升可读性、可维护性和设计质量。             | Martin Fowler                                            |
| 编码     | 测试驱动开发   | [[1774318604-FUEZ\|Test-Driven Development: By Example]]         | TDD 经典，围绕"红-绿-重构"循环说明如何通过测试驱动代码设计，强调快速反馈与简单设计。       | Kent Beck                                                |
| 编码     | TDD+OO 实战    | *Growing Object-Oriented Software, Guided by Tests*              | TDD 与 OO 设计结合，通过完整项目演示从外到内的测试驱动开发，偏实战集成。                   | Steve Freeman, Nat Pryce                                 |
| 编码     | 遗留代码治理   | *Working Effectively with Legacy Code*                           | 遗留代码治理必读书，讲如何在缺乏测试的旧系统中安全修改代码，引入测试并逐步重构。           | Michael Feathers                                         |
| 测试     | 敏捷测试       | *Agile Testing: A Practical Guide for Testers and Agile Teams*   | 敏捷团队协作视角讲测试，强调质量是全团队责任，覆盖测试左移、探索性测试与验收测试。         | Lisa Crispin, Janet Gregory                              |
| 测试     | 敏捷测试进阶   | *More Agile Testing: Learning Journeys for the Whole Team*       | 前作延伸，更强调团队成长、持续改进和测试实践演进，适合已有敏捷测试基础的团队。             | Lisa Crispin, Janet Gregory                              |
| 测试     | 单元测试模式   | *xUnit Test Patterns: Refactoring Test Code*                     | 单元测试模式与反模式大全，系统讲解测试代码结构、夹具设计、异味识别与重构。                 | Gerard Meszaros                                          |
| 测试     | 现代测试实践   | *Effective Software Testing*                                     | 现代视角讲单元/集成/契约测试与结构化测试设计，比 xUnit Patterns 更贴近当下实践。           | Mauricio Aniche                                          |
| 测试     | 测试经验       | *Lessons Learned in Software Testing*                            | 总结软件测试中的经验、策略与思维，偏实践智慧，帮助形成成熟的测试判断力。                   | Cem Kaner, James Bach, Bret Pettichord                   |

# CS 基础书籍

| 领域     | 子主题         | 书名                                                             | 内容备注总结                                                                               | 作者                                                     |
|----------|----------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------|
| CS 基础  | 计算机系统     | [[1774363812-LZCG\|Computer Systems: A Programmer's Perspective]] | CSAPP，从程序员视角讲计算机系统，覆盖数据表示、汇编、存储层次、链接、异常控制流与并发。    | Randal E. Bryant, David R. O'Hallaron                    |
| CS 基础  | 程序构造       | [[1774363699-ZENC\|Structure and Interpretation of Computer Programs]] | SICP，以 Scheme 为载体讲抽象、递归、高阶函数、元循环求值器与编译器，编程思维启蒙经典。     | Harold Abelson, Gerald Jay Sussman                       |
| CS 基础  | 算法           | [[1773381583-HECG\|Grokking Algorithms]]                        | 图解算法入门，用大量插图直观讲解搜索、排序、图算法、动态规划等核心算法概念。               | Aditya Bhargava                                          |
| CS 基础  | 算法           | *The Art of Computer Programming*                                | 算法圣经，计算机科学最权威的算法百科全书，覆盖基本算法、排序、搜索与组合数学。             | Donald E. Knuth                                          |
| CS 基础  | 算法           | *Introduction to Algorithms (CLRS)*                              | 算法标准教材，系统覆盖分治、动态规划、图算法、数据结构与复杂度分析。                       | Cormen, Leiserson, Rivest, Stein                         |
| CS 基础  | 操作系统       | [[1774445208-GNYH\|Operating Systems: Three Easy Pieces]]                   | 操作系统最佳入门，以虚拟化、并发、持久化三大主题讲解 OS 核心概念，免费在线。               | Remzi H. Arpaci-Dusseau, Andrea C. Arpaci-Dusseau       |
| CS 基础  | 计算机网络     | *Computer Networking: A Top-Down Approach*                       | 网络经典教材，从应用层到物理层自顶向下讲解协议栈，配合实验理解网络原理。                   | James Kurose, Keith Ross                                 |
| CS 基础  | 编译原理       | *Compilers: Principles, Techniques, and Tools*                   | 龙书，编译原理奠基之作，覆盖词法分析、语法分析、语义分析、中间代码生成与优化。             | Aho, Lam, Sethi, Ullman                                  |

# 编程思想 / 工程素养书籍

| 领域         | 子主题         | 书名                                                             | 内容备注总结                                                                               | 作者                                                     |
|--------------|----------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------|
| 工程素养     | 软件工程管理   | *The Mythical Man-Month*                                         | 软件工程管理永恒经典，"向进度落后的项目增加人手只会使其更落后"，探讨大型系统开发的本质困难。 | Frederick P. Brooks Jr.                                  |
| 工程素养     | 程序员通识     | [[1773383787-LAVJ\|The Pragmatic Programmer]]                    | 程序员通识经典，覆盖务实哲学、工具使用、代码灵活性与职业成长，建立全面工程素养。           | Andrew Hunt, David Thomas                                |
| 工程素养     | 编码规范       | [[1774334472-HUUJ\|Clean Code]]                                  | 编码规范经典，讲命名、函数、注释、格式与错误处理的最佳实践，提升代码可读性。               | Robert C. Martin                                         |

# 学习方法书籍

| 领域         | 子主题         | 书名                                                             | 内容备注总结                                                                               | 作者                                                     |
|--------------|----------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------|
| 学习方法     | 阅读方法       | [[1773383276-TQQR\|How to Read a Book]]                          | 阅读方法论经典，将阅读分为基础、检视、分析、主题四层次，建立系统化阅读能力。               | Mortimer J. Adler, Charles Van Doren                     |
