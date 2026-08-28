最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/69518409.Shtml

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/79644886.Shtml

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/63815101.Shtml

原标题：golang es 更新文档注意版本冲突
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/29745113.Shtml

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/03907030.Shtml

原标题：动态定时任务业务调度实现
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/81601110.Shtml

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/82497248.Shtml

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/01824451.Shtml

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/66268875.Shtml

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/03505746.Shtml

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/72892862.Shtml

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/22169403.Shtml

原标题：快速入门YAML配置文件语法与示例
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/81059717.Shtml

原标题：异步异常捕获避免进程崩溃
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/34363000.Shtml

原标题：前端权限路由动态生成实现
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/02941720.Shtml

原标题：golang rsa 非对称加密签名验签
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/41091156.Shtml

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/52108307.Shtml

原标题：日志切割配置防止日志丢失
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/26228416.Shtml

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/39521290.Shtml

原标题：nodejs 定时任务生产环境避坑
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/16696825.Shtml

原标题：golang 系统设计异步化改造业务流程思路
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/89113570.Shtml

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/01836377.Shtml

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/40077088.Shtml

原标题：快速入门ORM，实现简单数据库增删改查
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/55376537.Shtml

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/81831910.Shtml

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/67189656.Shtml

原标题：golang mysql 连接泄漏检测方法
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/67016221.Shtml

原标题：golang mysql 批量导入数据实操
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/83308895.Shtml

原标题：站内邮件消息通知功能开发
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/64334451.Shtml

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/56982321.Shtml

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/68921321.Shtml

原标题：golang 系统设计消息幂等消费去重实现方案
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/56687430.Shtml

原标题：一次JWT令牌过期时间异常问题复盘
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/04658281.Shtml

原标题：Practice：实现接口幂等性多种方案对比实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/38865645.Shtml

原标题：架构笔记：高并发系统核心设计思路总结
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/71210958.Shtml

原标题：golang 系统设计缓存优化落地实操指南
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/93839930.Shtml

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/53561884.Shtml

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/11717406.Shtml

原标题：全局异常处理器接口返回统一
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/82409079.Shtml

原标题：nodejs 日志轮转生产环境配置
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/06603834.Shtml


二、踩坑排错｜Troubleshooting
原标题：golang 分布式锁 redis 实现
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/07479305.Shtml

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/42639032.Shtml

原标题：内存溢出问题现象识别排查
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/33404595.Shtml

原标题：golang 定时任务 cron 使用指南
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/97516428.Shtml

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/64259461.Shtml

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/48910944.Shtml

原标题：golang cron 定时任务防并发执行
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/15895350.Shtml

原标题：golang mongodb 分页性能优化技巧
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/97913235.Shtml

原标题：快速入门简单签名校验实现思路
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/44715020.Shtml

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/52333268.Shtml

原标题：golang 系统设计接口向前兼容改造实操
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/78415200.Shtml

原标题：golang 系统设计敏感数据加密存储方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/31859915.Shtml

原标题：golang 系统设计故障止损降级回滚执行原则
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/83264400.Shtml

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/01914591.Shtml

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/90102405.Shtml

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/82228844.Shtml

原标题：前端骨架屏提升页面体验
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/07244627.Shtml

原标题：golang mysql 连接泄漏检测方法
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/99497884.Shtml

原标题：缓存穿透防护保护数据库
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/29542430.Shtml

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/19722189.Shtml

原标题：golang lru 缓存淘汰算法编写
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/73999706.Shtml

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/20502828.Shtml

原标题：golang 系统设计并发控制协程池任务池实现
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/15667963.Shtml

原标题：时间同步修复令牌提前过期
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/32962250.Shtml

原标题：golang 系统设计参数校验统一处理方案
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/82651583.Shtml

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/00242252.Shtml

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/45733336.Shtml

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/33057026.Shtml

原标题：Architecture：配置中心架构，动态配置设计思路
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/35428129.Shtml

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/00941915.Shtml

原标题：项目实践：灰度发布简易方案落地实践
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/41601213.Shtml

原标题：golang http 服务性能优化调参
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/35381756.Shtml

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/37247642.Shtml

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/65373027.Shtml

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/01240861.Shtml

原标题：golang 系统设计缓存故障降级处理方案
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/41018005.Shtml

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/08449284.Shtml

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/62301265.Shtml

原标题：golang 系统设计异步化改造业务流程思路
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/64385441.Shtml

原标题：golang 系统设计定时任务分布式锁
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/54671933.Shtml

三、实战开发｜Practice
原标题：用户敏感数据脱敏代码实现
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/73205109.Shtml

原标题：Practice：模拟热点key，验证缓存防护策略
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/03876642.Shtml

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/85331105.Shtml

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/05544083.Shtml

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/68194157.Shtml

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/53578188.Shtml

原标题：前端大文件分片上传完整方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/02721141.Shtml

原标题：Shell 脚本自动化命令编写
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/10731541.Shtml

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/29609816.Shtml

原标题：服务器时钟同步任务错乱修复
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/46656544.Shtml

原标题：Git 误提交撤销回退实操教程
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/52053008.Shtml

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/49948915.Shtml

原标题：Hands‑on：简易链路追踪原型开发实践
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/27956045.Shtml

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/78283651.Shtml

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/07390437.Shtml

原标题：Docker 多阶段构建镜像瘦身
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/57254643.Shtml

原标题：golang 系统设计秒杀防超卖方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/86054259.Shtml

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/26797812.Shtml

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/90720117.Shtml

原标题：golang docker compose 部署 minio
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/59020818.Shtml

原标题：golang 系统设计回调重试幂等完整处理
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/93209044.Shtml

原标题：调优方案：Web服务内核socket参数调优
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/90574886.Shtml

原标题：实践：API版本控制多种策略落地对比实践
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/40184823.Shtml

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/21324559.Shtml

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/29072562.Shtml

原标题：部署实践：多实例服务部署无状态改造
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/16935032.Shtml

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/31846711.Shtml

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/00098285.Shtml

原标题：从零编写简易 CLI 命令行工具
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/73511685.Shtml

原标题：nodejs 集群模式多核利用实现
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/04842575.Shtml

原标题：磁盘 inode 耗尽文件创建失败
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/92815887.Shtml

原标题：golang http client 连接池调优
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/13979703.Shtml

原标题：golang base64 编码解码实操
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/33391488.Shtml

原标题：新手教程：Gittag版本标签打标签实操
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/60016219.Shtml

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/96219878.Shtml

原标题：ServiceWorker 缓存页面更新清理
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/45145583.Shtml

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/93458081.Shtml

原标题：golang 数据库慢查询监控实现
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/53664527.Shtml

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/31969593.Shtml

原标题：开源实践：开源项目如何写好PullRequest
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/45202957.Shtml

四、架构设计｜Architecture
原标题：快速入门YAML配置文件语法与示例
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/29229049.Shtml

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/85959556.Shtml

原标题：前端组件库按需加载性能优化
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/75555362.Shtml

原标题：实战：Docker资源监控查看容器状态实操
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/02318668.Shtml

原标题：golang 系统设计 README 开源文档模板
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/26637743.Shtml

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/45956468.Shtml

原标题：快速上手调试工具定位简单代码错误
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/64004342.Shtml

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/26046248.Shtml

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/23160233.Shtml

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/36192210.Shtml

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/30634008.Shtml

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/24440459.Shtml

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/99968036.Shtml

原标题：跨平台 uniapp 多端开发实操
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/78531133.Shtml

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/56303227.Shtml

原标题：golang 系统设计线上故障排查完整流程
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/28931088.Shtml

原标题：网关集成鉴权限流日志一体化
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/49471561.Shtml

原标题：golang 批量任务协程控制防雪崩
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://www.blog.nkafp.cn/jingyingl/93141172.Shtml

?
