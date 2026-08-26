最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计接口向前兼容改造实操
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/421790.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.bl1u1s.asia/arts/284665.Doc

原标题：golang 系统设计错误码体系完整设计
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.bl1u1s.asia/arts/011473.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.bl1u1s.asia/arts/410561.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/786151.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.bl1u1s.asia/arts/640244.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/239411.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/567084.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.bl1u1s.asia/arts/758403.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.bl1u1s.asia/arts/813798.Doc

原标题：golang docker compose 完整语法
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.bl1u1s.asia/arts/670611.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/057607.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.bl1u1s.asia/arts/600586.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.bl1u1s.asia/arts/348254.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.bl1u1s.asia/arts/649466.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/151314.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/495874.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/757767.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.bl1u1s.asia/arts/771430.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/500574.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.bl1u1s.asia/arts/828383.Doc

原标题：golang 限流熔断降级完整示例
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.bl1u1s.asia/arts/992905.Doc

原标题：golang 项目环境变量加载方案
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.bl1u1s.asia/arts/040533.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.bl1u1s.asia/arts/536779.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.bl1u1s.asia/arts/497099.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/997335.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.bl1u1s.asia/arts/535448.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.bl1u1s.asia/arts/843839.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/824822.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/016512.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.bl1u1s.asia/arts/561039.Doc

原标题：OpenAPI 自动接口文档生成
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.bl1u1s.asia/arts/485395.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.bl1u1s.asia/arts/380778.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/932490.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/309539.Doc

原标题：环境变量不生效问题修复
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.bl1u1s.asia/arts/159477.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/895412.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.bl1u1s.asia/arts/687788.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/151247.Doc

原标题：golang 容器健康检查接口开发
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.bl1u1s.asia/arts/051527.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：实现简单信号处理优雅停机实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/741856.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.bl1u1s.asia/arts/865773.Doc

原标题：golang 协程泄露问题排查方法
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.bl1u1s.asia/arts/882984.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/039247.Doc

原标题：golang docker 部署 es 本地开发
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.bl1u1s.asia/arts/727392.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.bl1u1s.asia/arts/413314.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.bl1u1s.asia/arts/726633.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.bl1u1s.asia/arts/895459.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.bl1u1s.asia/arts/657466.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.bl1u1s.asia/arts/300206.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.bl1u1s.asia/arts/011115.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.bl1u1s.asia/arts/614318.Doc

原标题：golang etcd watch 监听配置变更
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.bl1u1s.asia/arts/429904.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.bl1u1s.asia/arts/217742.Doc

原标题：golang traceId spanId 传递方案
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.bl1u1s.asia/arts/057536.Doc

原标题：golang 配置热更新不重启服务
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.bl1u1s.asia/arts/203083.Doc

原标题：环境变量不生效问题修复
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.bl1u1s.asia/arts/563253.Doc

原标题：CI 流水线超时时间延长配置
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/288770.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/939118.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.bl1u1s.asia/arts/062434.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.bl1u1s.asia/arts/640521.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.bl1u1s.asia/arts/155063.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.bl1u1s.asia/arts/501091.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.bl1u1s.asia/arts/822847.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.bl1u1s.asia/arts/026588.Doc

原标题：系统时间同步定时任务偏移
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/447217.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.bl1u1s.asia/arts/269611.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.bl1u1s.asia/arts/158169.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.bl1u1s.asia/arts/814446.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.bl1u1s.asia/arts/722279.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.bl1u1s.asia/arts/781954.Doc

原标题：nodejs 内存溢出问题排查修复
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.bl1u1s.asia/arts/166055.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.bl1u1s.asia/arts/354640.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.bl1u1s.asia/arts/314928.Doc

原标题：nodejs redis 缓存业务实战
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.bl1u1s.asia/arts/939837.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/392134.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.bl1u1s.asia/arts/417559.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.bl1u1s.asia/arts/380003.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.bl1u1s.asia/arts/835873.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/713163.Doc

三、实战开发｜Practice
原标题：Redis 内存淘汰策略数据防丢失
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.bl1u1s.asia/arts/302254.Doc

原标题：后端分页查询逻辑代码实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.bl1u1s.asia/arts/524503.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.bl1u1s.asia/arts/862107.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.bl1u1s.asia/arts/673197.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.bl1u1s.asia/arts/044135.Doc

原标题：前端权限路由动态生成实现
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.bl1u1s.asia/arts/257723.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.bl1u1s.asia/arts/597318.Doc

原标题：golang redis zset 延时队列实现
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.bl1u1s.asia/arts/916557.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.bl1u1s.asia/arts/687321.Doc

原标题：从零编写简易 CLI 命令行工具
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.bl1u1s.asia/arts/341095.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.bl1u1s.asia/arts/643254.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.bl1u1s.asia/arts/391592.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.bl1u1s.asia/arts/703475.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.bl1u1s.asia/arts/825218.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.bl1u1s.asia/arts/380322.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.bl1u1s.asia/arts/554948.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.bl1u1s.asia/arts/306111.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.bl1u1s.asia/arts/888099.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.bl1u1s.asia/arts/158436.Doc

原标题：极简方式搭建个人技术文档站点
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.bl1u1s.asia/arts/114692.Doc

原标题：多线程线程安全脏数据规避
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.bl1u1s.asia/arts/901743.Doc

原标题：golang grafana 监控面板简单配置
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.bl1u1s.asia/arts/362804.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.bl1u1s.asia/arts/273389.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.bl1u1s.asia/arts/451008.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.bl1u1s.asia/arts/381661.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/047329.Doc

原标题：golang minio 预签名 url 临时访问
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.bl1u1s.asia/arts/895484.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.bl1u1s.asia/arts/028051.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.bl1u1s.asia/arts/321035.Doc

原标题：golang docker compose 部署 minio
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.bl1u1s.asia/arts/206526.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.bl1u1s.asia/arts/438181.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.bl1u1s.asia/arts/798587.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.bl1u1s.asia/arts/388205.Doc

原标题：配置与镜像分离防止信息泄露
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.bl1u1s.asia/arts/754028.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.bl1u1s.asia/arts/373469.Doc

原标题：Fork 开源项目同步上游代码
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.bl1u1s.asia/arts/095615.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.bl1u1s.asia/arts/968873.Doc

原标题：golang context 上下文传参讲解
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.bl1u1s.asia/arts/379575.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/453746.Doc

原标题：golang mongodb 事务多文档使用
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.bl1u1s.asia/arts/235104.Doc

四、架构设计｜Architecture
原标题：实战项目：WebSocket消息广播房间分组实践
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.bl1u1s.asia/arts/260791.Doc

原标题：线上接口超时故障排查思路
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.bl1u1s.asia/arts/344791.Doc

原标题：golang mysql 事务回滚异常处理
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/071009.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.bl1u1s.asia/arts/373039.Doc

原标题：golang 分布式上下文传递方案
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.bl1u1s.asia/arts/305859.Doc

原标题：golang 参数校验业务接口处理
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.bl1u1s.asia/arts/676624.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.bl1u1s.asia/arts/153282.Doc

原标题：请求工具封装统一异常处理
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.bl1u1s.asia/arts/102281.Doc

原标题：调试工具断点调试变量查看技巧
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.bl1u1s.asia/arts/712157.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/888904.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.bl1u1s.asia/arts/128757.Doc

原标题：定时任务重复执行分布式锁
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.bl1u1s.asia/arts/087571.Doc

原标题：快速上手简单性能监控指标查看
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.bl1u1s.asia/arts/886208.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.bl1u1s.asia/arts/231483.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.bl1u1s.asia/arts/671023.Doc

原标题：golang es 查询语句 DSL 实操
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.bl1u1s.asia/arts/307662.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.bl1u1s.asia/arts/780777.Doc

原标题：golang 限流熔断降级完整示例
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.bl1u1s.asia/arts/970218.Doc

?
