## 开源软件供应链点亮计划-暑期2022

### 开源软件供应链点亮计划-暑期2022”是什么？

“开源软件供应链点亮计划-暑期2022”（以下简称 暑期2022）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供项目，并向全球高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还将获取“开源软件供应链点亮计划-暑期2022”活动奖杯和奖金。

暑期 2020 活动信息请查阅：https://summer-ospp.ac.cn/2020/

暑期 2021 活动信息请查阅：https://summer-ospp.ac.cn/2021/

**“暑期2022”项目在今年（2022）第三次举办，与Google Summer of Code类似，可以看做中国版的GSoC。**

1. 官网：https://summer-ospp.ac.cn/
2. 新闻：https://segmentfault.com/a/1190000041695372

### 活动的组织方有哪些

本次活动由中国科学院软件研究所、openEuler 社区主办，当前是第三届。

### 活动的参与方以及角色有哪些

活动参与方主要角色为学生、社区和导师。

1. 学生：学生自由选择项目，与社区导师沟通实现方案并撰写项目计划书。被选中的学生将在社区导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
2. 社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
3. 导师：社区针对每一个项目指定一个社区导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。

### 项目的奖金是多少

学生可获得的奖金：

1. 进阶：奖金人民币 12000 元：优化类的任务，例如提高时间、降低内存占用、提供性能等
2. 基础：奖金人民币 8000 元：功能类的任务，例如为本社区开源项目增加一个或若干个重要特性等

难度分级由社区根据项目任务决定。

对于导师而言，无论何种难度，导师的奖金为每个项目税前 3000 元人民币，每位导师最多负责 1 个项目，即奖金最多为税前 3000 元人民币。

## Casbin开源项目介绍

Casbin是一个强大的、高效的开源访问控制框架。涉及到Go, Java, Node.js, Javascript (React), Python, PHP, .NET, Delphi, Rust等多种语言。Casbin由北京大学罗杨博士创立于2017年，核心维护团队有数十人。Casbin在业界具有广泛影响力。目前已经被Intel、VMware、Orange、RedHat、T-Mobile等公司开源使用，被腾讯云、Cisco、Verizon等公司闭源使用。具体详见Casbin主页。Casbin Go主项目目前GitHub 8800+ stars，加上所有语言的实现、插件等可达到15000+ stars。Casbin曾经在国际上多次宣讲：

1. 新加坡政府技术部门Open Government Products：https://www.youtube.com/watch?v=OTT84oplR9o
2. 俄罗斯最大在线旅游平台tutu.ru：https://www.youtube.com/watch?v=Z5dUxH4PqYM

具体请了解Casbin官网：https://casbin.org/

## 可选项目列表

下列所有项目都与Casbin一致，采用开源协议：[Apache 2.0 license](LICENSE)

- [Casbin核心权限库改进（Go + Java）](#casbin核心权限库改进go--java)
- [Casbin核心权限库改进（Go + .NET）](#casbin核心权限库改进go--net)
- [Casbin文档中文翻译 + 官网优化](#casbin文档中文翻译--官网优化)
- [Casbin.js核心前端库研发（前端Javascript + React + vue）](#casbinjs核心前端库研发前端javascript--react--vue)
- [Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）](#casdoor单点登录系统casnode社区系统前端react--js后端go)
- [Casbin-RS 生态完善（Rust）](#casbin-rs-生态完善rust)
- [Python/PHP-Casbin 生态完善（Python/PHP）](#pythonphp-casbin-生态完善pythonphp)
- [Casbin Mesh (Golang) ](#casbin-mesh-golang)
- [SwiftCasbin 开发（Swift）](#swiftcasbin-开发swift)
- [Casbin Web前端UI设计开发（React + Javascript）](#casbin-web前端ui设计开发react--javascript)

### Casbin核心权限库改进（Go + Java）
1. 项目名称：Casbin（Go + Java）
2. 项目主导师：[唐阳 (Yang Tang)](https://github.com/tangyang9464), tangyang9464 (AT) 163.com
3. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上： 1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求； 2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。 jCasbin是Casbin的Java版本，它需要及时跟踪Golang Casbin主库的最新feature并移植到Java版本中来。同时维护Java特有的生态
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization
6. 编程语言标签：Go, Java
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 跟踪Casbin-Go最新特性并移植到jCasbin，如实现WatcherEx:[casbin#943](https://github.com/casbin/casbin/issues/943)
   - 维护完善jCasbin的Java特有生态，如实现Play框架中间件：[jcasbin#104](https://github.com/casbin/jcasbin/issues/104)
   - 解决Casbin-Go和jCasbin以及相关仓库中的issues：[Casbin-Go](https://github.com/casbin/casbin/issues) & [jCasbin](https://github.com/casbin/jcasbin/issues)
8. 项目技术要求：
   - 熟悉Golang或Java语言
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/jcasbin


### Casbin核心权限库改进（Go + .NET）
1. 项目名称：Casbin（Go + .NET）
2. 项目主导师：[汤贤赫 (Sagilio)](https://github.com/sagilio), sagilio (AT) outlook.com
3. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上： 1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求； 2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。 Casbin.NET是Casbin的.NET版本，它需要及时跟踪Golang Casbin主库的最新feature并移植到.NET版本中来。并维护.NET特有的生态
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization
6. 编程语言标签：Go, C#(.NET)
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 跟踪Casbin-Go最新特性与BUG修复，并同步到Casbin.NET，如重构的RoleManager:[Casbin.NET#250](https://github.com/casbin/Casbin.NET/issues/250)
   - 完善Casbin.NET的特有生态, 1) 完善现有的aspnetcore中间件：https://github.com/casbin-net/casbin-aspnetcore; 2) 完善Casdoor.SDK的.NET版本: https://github.com/casdoor/casdoor-dotnet-sdk
   - 解决Casbin-Go和Casbin.NET以及相关仓库中的issues：[Casbin-Go](https://github.com/casbin/casbin/issues) & [Casbin.NET](https://github.com/casbin/Casbin.NET/issues)
8. 项目技术要求：
   - 熟悉Golang或C#语言
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/Casbin.NET

### Casbin文档中文翻译 + 官网优化

1. 项目标题：Casbin文档中文翻译 + 官网优化
2. 项目描述：Casbin官网（https://casbin.org/ ）基于开源文档工具[Docusaurus](https://docusaurus.io/ )构建（基于React），采用Docusaurus所集成的[CrowdIn](https://crowdin.com/project/casbin )在线翻译平台进行众包翻译。Casbin官网原始文档均为英文，由CrowdIn上的贡献者自愿将英文翻译为其他各语言（如中文，韩文等）。但是目前各语言的翻译率较低，中文翻译率目前仅有15%，不利于开源项目在国内推广。因此希望能够将中文翻译率提高到100%。并且该项目也会承担一部分Casbin社区推广（如Casbin官方微信公众号）文章的撰写编辑、公众号管理等临时任务。
3. 项目难度：中
4. 项目社区导师：[刘子轩 (nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 在CrowdIn翻译平台将Casbin官网英文内容翻译为中文，进度翻译至100%（目前为15%）
   - （可选）改进官网功能、优化内容排版，增加新的文档内容
   - （有时）撰写、编辑Casbin社区推广（如Casbin官方微信公众号）文章
   - 解决Casbin-website主仓库&相关仓库中的issues：https://github.com/casbin/casbin-website/issues
8. 项目技术要求：
   - 热爱并有能力撰写技术博客、文章
   - 了解React框架和NPM包管理
   - 了解Git、GitHub相关操作
   - 了解Casbin的工作原理
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-website
   - https://github.com/casbin/casbin.github.io

### Casbin.js核心前端库研发（前端Javascript + React + vue）

1. 项目标题：Casbin.js核心前端库研发（前端Javascript + React + vue）
2. 项目描述：Casbin本身专注于服务器端（后端）的访问控制、权限管理，然而Web App（前端）也有权限管理的需求：如列出当前登录用户有权访问的所有列表项，或当前用户无权进行删除帖子的操作，则把删除按钮变灰或隐藏等等。因此Casbin推出专门用于前端权限展示的开源库：[Casbin.js](https://github.com/casbin/casbin.js) 。该库主要实现2个功能：1）调用后端Casbin（可能是Go，也可能是Java等）提供的接口（RESTful或cookie等方式），获取当前登录用户的权限；2）将获取到的权限转换为列表、按钮的显示状态。Casbin.js在GSoC 2020期间已经研发了3个月，但是目前从功能、适配性、可用性等方面离最终完成还仍有很大距离。之前的研发文档、记录可从此处获得：https://github.com/casbin/casbin.js/issues 。
3. 项目难度：高
4. 项目社区导师：[刘梓晖 (kingiw)](https://github.com/kingiw)
5. 导师联系方式：kingiw (AT) hotmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 大规模重构、改造、完善[Casbin.js](https://github.com/casbin/casbin.js) ，从功能、适配性、可用性上达到类似CASL项目：https://github.com/stalniy/casl
   - 完成核心主库Casbin.js的开发，推送到NPM。同时类似CASL项目，包装出React、Vue等框架的适配器，方便React、Vue用户使用
   - 开发至少一种后端语言（如Go Casbin）的对接Casbin.js的API接口，从而使后端把权限传给前端的Casbin.js
   - 解决Casbin.js主仓库&相关仓库中的issues：https://github.com/casbin/casbin.js/issues
8. 项目技术要求：
   - 熟悉HTML、Javascript、CSS等前端技术
   - 熟悉React或Vue框架，两种都熟悉更好
   - 熟悉NPM包管理，熟悉Git、GitHub相关操作
   - 至少了解一种后端语言，如Go、Java、Python、Node.js、Rust等，有全栈工程师相关经验；
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin.js
   - https://github.com/casbin-js

### Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）

1. 项目名称：Casdoor单点登录系统、Casnode社区系统（前端React + JS，后端Go）
2. 项目主导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz), hsluoyz (AT) gmail.com
3. 项目描述：Casdoor是一套基于基于OAuth 2.0 / OIDC协议的统一身份认证（单点登录）系统。其支持多种第三方登录方式，如QQ、微信、Google, GitHub等。Casdoor具有Web管理界面，可以用来管理用户、角色、权限（基于Casbin）。Casbin社区目前采用QQ群（中文），Gitter（英文）进行社区交流，交流渠道比较有限。我们打算开发一个同时面向Casbin开发者和用户的官方论坛：casnode（https://github.com/casbin/casnode ）。该论坛开源，因此也欢迎其他开源社区使用。
4. 项目难度：进阶
5. 涉及技术领域标签：Micro Service
6. 编程语言标签：Go, JavaScript
7. 项目产出要求：
   - 扩展架构，添加更多的第三方登录支持
   - 优化、美化Web界面
   - 支持Casbin权限管理
   - 继续维护该项目，添加features，解决bugs，完善其邮件列表功能
   - 解决Casdoor主仓库&相关仓库中的issues：https://github.com/casbin/casdoor/issues
   - 解决Casnode&相关仓库中的issues：https://github.com/casbin/casnode/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casdoor/casdoor
   - https://github.com/casbin/casnode

### Casbin-RS 生态完善（Rust）

1. 项目标题：Casbin-RS 生态完善（Rust）
2. 项目描述：Casbin Rust 目前尚缺乏各个主流 Rust Web 框架的集成，以及对于 `Raft协议` 的完善。此议题希望学生独立完成对于 [Warp](https://github.com/seanmonstar/warp) 、[Tide](https://github.com/http-rs/tide) 框架的中间件集成；独立完成 [Casbin-Raft](https://github.com/casbin-rs/casbin-raft) 的重构实现。
3. 项目难度：高
4. 项目社区导师：[柴轶晟 (Hackerchai)](https://github.com/hackerchai)
5. 导师联系方式：i (AT) hackerchai.com
6. 合作导师联系方式（选填）：psiace (AT) outlook.com
7. 项目产出要求：
   - 针对 [Warp](https://github.com/seanmonstar/warp) 框架实现 casbin 中间件实现，包含正确，充足的单元/集成测试以及完备的文档说明，并且实现一个完备的实际应用样例
   - 针对 [Tide](https://github.com/http-rs/tide) 框架实现 casbin 中间件实现，包含正确，充足的单元/集成测试以及完备的文档说明，并且实现一个完备的实际应用样例
   - 完善 [Casbin-Raft](https://github.com/casbin-rs/casbin-raft) 实现   Rust 版本 [Casbin-Raft (Go)](https://github.com/casbin/casbin-raft) ,使用 [Raft-rs](https://github.com/tikv/raft-rs) 框架实现完备的  `Raft` 协议支持；参考 [hraft-dispatcher（Go）](https://github.com/casbin/hraft-dispatcher) 对 [Casbin-Raft（Go）](https://github.com/casbin-rs/casbin-raft) 进行重构，设计正确，充足的单元/集成测试以确保可用性，完成相应的文档工作。架构可以参考  [toshi（Rust）](https://github.com/toshi-search/Toshi) 或者 [MeiliSearch-Raft](https://github.com/meilisearch/MeiliSearch/tree/raft)；要求可以投入实际生产环境
   - 解决 Casbin Rust 主仓库和相关仓库中的 issues ：https://github.com/casbin/casbin-rs/issues
8. 项目技术要求：
   - 熟悉Rust语言
   - 熟悉Git、GitHub相关操作
   - 熟练掌握一种后端框架，对于中间件，数据库操作有一定了解
   - 熟悉 `RPC` 工作原理，了解一定的云原生开发
   - 熟悉 `Raft` 协议工作原理
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-rs
   - https://github.com/casbin-rs

### Python/PHP-Casbin 生态完善（Python/PHP）

1. 项目名称：Python/PHP-Casbin 生态完善（Python/PHP）
2. 项目主导师：[李强 (Jon Lee)](https://github.com/leeqvip), leeqvip (AT) gmail.com
3. 项目描述：Casbin 是一个强大的、高效的开源访问控制框架，对主流语言都有相关实现，包括Python、PHP版本的Casbin。Casbin在业界具有广泛影响力，社区活跃。目前，目前PyCasbin/PHP-Casbin主库主要功能虽然相对完善和稳定，但仍然需要不断迭代演进，特别是对Python和PHP生态内各种框架、插件的集成，代码质量和性能还有调优的可能，所以我们希望对主库及其周边生态系统进行完善和优化，以增强Casbin在脚本语言Python和PHP领域的应用场景，提高外部系统接入Casbin效率和成本，进而扩大Casbin在Python和PHP领域的生态圈，使其能更好更快的发展。
4. 项目难度：进阶
5. 涉及技术领域标签：Authorization、API
6. 编程语言标签：Python，PHP，Go
7. 项目产出要求：
   - 对分布式存储系统`ETCD`的适配`etcd-adapter`
   - 完善Py/PHP-Casbin的对Redis（`redis-adapter`）适配器
   - 对权限决策`enforce()`的过程做基准测试、弱点分析、性能优化
   - 增加`addPermissionsForUser()` API.
   - 增加对`g`方法的缓存, 参考: https://github.com/casbin/casbin/blob/master/util/builtin_operators.go#L333.
   - 实现和完善[WatcherEx](https://casbin.org/docs/en/watchers#watcherex)
   - 引入Casbin核心引擎[Casbin Core Engine (Golang)](https://github.com/casbin/casbin/releases)中的新功能
   - 对主流框架的支持增强，例如：如果在Python的`Django`的扩展中, 需要引入Django的`Middleware`, `Caching`, `Logging`, 集成`Django`的认证系统（authentication system）；而PHP主流框架Laravel中已有[Laravel-Authz](https://github.com/php-casbin/laravel-authz)，但需要引入Laravel的[Gates](https://laravel.com/docs/9.x/authorization#gates)等
   - 解决[PyCasbin](https://github.com/casbin/pycasbin)或[PHP-Casbin](https://github.com/php-casbin/php-casbin)主库以及相关仓库中的issues
8. 项目技术要求：
   - 熟悉Python、PHP任意一种语言即可
   - 熟悉Git、GitHub相关操作
9. 项目成果仓库：
   - https://github.com/casbin/pycasbin
   - https://github.com/pycasbin
   - https://github.com/php-casbin/php-casbin
   - https://github.com/php-casbin

### Casbin Mesh (Golang)

1. 项目标题：Casbin Mesh (Golang)
2. 项目描述：Casbin Mesh 是一个管理多个访问控制应用的系统，我们将会使用 Casbin + Raft 协议构建开箱即用、可伸缩的访问管理服务，用户可以在任意服务上更新、查找规则集以及检查规则。
3. 项目难度：高
4. 项目社区导师：[刘子轩 (nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 基于 Raft + TCP(with TLS) 提供可伸缩性服务
   - 正确，充足的单元/集成测试，确保程序运行的正确性
   - 支持在 Leader 或者 Follower 节点更新、查找规则集以及检查规则
   - 提供身份认证系统保护系统的安全，例如第三方客户端的接入
   - 提供 Go SDK 访问该系统
   - 提供 WEB/CLI 管理用户的访问控制应用
   - 提供安全审计

8. 项目技术要求：
   - 熟悉 Golang
   - 熟悉 Raft

9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/hraft-dispatcher

### SwiftCasbin 开发（Swift）

1. 项目标题：SwiftCasbin 开发（Swift）
2. 项目描述：开发Swift版本的Casbin，支持iOS App、Swift服务器端应用等生态。
3. 项目难度：高
4. 项目社区导师：[孟祥文 (cit117)](https://github.com/cit117)
5. 导师联系方式：cit117 (AT) me.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 实现 Casbin 的 Swift 版本
   - 实现纯数据库驱动的 adapter: PostgresQL, Mysql, Microsoft SQL Server, Oracle, SQLite, IBM Db2.
   - 解决 SwiftCasbin 主仓库&相关仓库中的 issues：https://github.com/casbin/SwiftCasbin/issues
8. 项目技术要求：
   - 熟悉 Swift 语言
   - 熟悉 iOS App 开发等
   - 熟悉 Git、GitHub 相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/SwiftCasbin
   - https://github.com/SwiftCasbin

### Casbin Web前端UI设计开发（React + Javascript）

1. 项目标题：Casbin 前端设计开发（React + Javascript）
2. 项目描述：目前Casbin社区有多个涉及Web前端的项目，如OA系统、Casnode论坛、Casdoor等。这些系统本身已经有一个功能完整的前端页面，但是UI比较简陋，因此需要较为专业的前端设计+开发实现更好的UI。
3. 项目难度：中
4. 项目社区导师：[刘子轩 (nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 改进Casbin社区各个项目的Web前端页面的设计，包括提供图片、切图，调整页面元素尺寸、布局，改进交互效果、动画效果等
   - 在现有的功能完整但UI较为简陋的代码基础上，修改React, Javascript代码，提升UI效果
8. 项目技术要求：
   - 熟悉Web前端设计，包括切图、布局、交互等
   - 熟悉HTML、CSS，能够编写React + Javascript代码来实现所提出的UI设计
   - 熟悉 Git、GitHub 相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casdoor
   - https://github.com/casbin/casnode
   - https://github.com/casbin/casbin-oa

所有可选项目详见：https://github.com/casbin/Summer2022#可选项目列表

## 候选人要求

### 工作职责：

- 每周与项目导师进行线上讨论，完成项目规定的开发任务。项目导师由开源项目创始人或其他核心成员担任；
- 积极参与开源社区的建设，参与代码提交、解决Issue、审核PR等日常工作；
- 配合完成官方要求的材料提交等事项，包括项目申请书撰写、社区反馈任务完成度追踪等。

### 职位要求：

- 本科、硕士或博士在读（已毕业、工作的无法参加）；
- 对开源软件、开源社区感兴趣；
- 熟悉一种或多种编程语言，有较强的工程能力，代码格式清晰规范，善于团队协作；
- 有一定英文读写能力，能够熟练运用英语在GitHub进行开发、协作；
- 较强的沟通能力和逻辑表达能力。

### 具有以下条件者优先：

- 熟悉计算机网络、网络安全，有相关项目经验；
- 熟悉Go, Rust等语言、分布式系统、微服务架构，有相关项目经验；
- 在GitHub较为活跃，有自己的开源项目，或参与过知名开源项目；
- 可以在项目结束后继续长期参与开源社区的开发、建设或维护。


## 投递要求

申请学生需要同时完成以下“联系社区”和“官网投递”两个环节：

### 1. 联系社区（即日起至2022年6月4日）

1. 发送【中文简历PDF】至Casbin社区官方邮箱：admin (AT) casbin.org 
2. 加入《Casbin访问控制社区群》（QQ大群）：[546057381](https://shang.qq.com/wpa/qunwpa?idkey=8ac8b91fc97ace3d383d0035f7aa06f7d670fd8e8d4837347354a31c18fac885)
3. 加入《Casbin明日之星预选生-Talent 2022-群》（QQ小群）：[540163681](https://qm.qq.com/cgi-bin/qm/qr?k=5MjIdZuPmAio6lfAr-NTxBY0CcoGL1yl&jump_from=webapi) ，联系导师，与导师沟通项目细节和方案，完善项目申请书
4. 选择技术写作题目“Casbin文档中文翻译 + 官网优化”的同学，还需要加入《Casbin文档题目申请》（QQ文档群）：[714309545](https://qm.qq.com/cgi-bin/qm/qr?k=T-hOJN1IzKN638y2N9rJJDdIT1fqpfua&jump_from=webapi)，并仔细阅读群公告，联系导师沟通项目细节

### 2. 官网投递（2022年5月21日至2022年6月4日）

详见：https://summer-ospp.ac.cn/help/
