最新前沿技术资讯

一、入门教程｜Getting Started
原标题：新手向：开源项目fork与同步上游代码
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.iculmp.asia/blog/5253029.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.iculmp.asia/blog/4810913.sHtMl

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.iculmp.asia/blog/4225080.sHtMl

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.iculmp.asia/blog/3544504.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.iculmp.asia/blog/6129050.sHtMl

原标题：golang 系统设计技术文档编写最佳实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.iculmp.asia/blog/0451682.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.iculmp.asia/blog/3847767.sHtMl

原标题：方案对比：几种分布式限流算法架构适用性
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.iculmp.asia/blog/4090322.sHtMl

原标题：golang 重试退避机制代码实现
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.iculmp.asia/blog/4915540.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.iculmp.asia/blog/7446244.sHtMl

原标题：golang es 索引生命周期管理思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.iculmp.asia/blog/5066163.sHtMl

原标题：golang ip 限流黑名单实现方案
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.iculmp.asia/blog/8151881.sHtMl

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.iculmp.asia/blog/8406857.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.iculmp.asia/blog/0540162.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.iculmp.asia/blog/1712351.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.iculmp.asia/blog/8206007.sHtMl

原标题：静态网页 HTML CSS 快速入门实战
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.iculmp.asia/blog/1866279.sHtMl

原标题：golang 系统设计性能优化通用思路方法论
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.iculmp.asia/blog/9660579.sHtMl

原标题：golang 系统设计会话共享多实例部署
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.iculmp.asia/blog/5685628.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.iculmp.asia/blog/1862383.sHtMl

原标题：golang redis 地理位置 geo 使用
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.iculmp.asia/blog/4930302.sHtMl

原标题：golang mysql 悲观锁乐观锁实现
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.iculmp.asia/blog/7945496.sHtMl

原标题：golang 系统设计容量评估简单方法论
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.iculmp.asia/blog/6223453.sHtMl

原标题：单元测试用例编写入门实操
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.iculmp.asia/blog/8618356.sHtMl

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.iculmp.asia/blog/1274630.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.iculmp.asia/blog/5630055.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.iculmp.asia/blog/1655495.sHtMl

原标题：nodejs http 服务性能调优实战
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.iculmp.asia/blog/4278542.sHtMl

原标题：设计思考：分布式锁选型、风险、业务约束
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.iculmp.asia/blog/7428088.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.iculmp.asia/blog/2410341.sHtMl

原标题：golang 单例模式实现几种方式
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.iculmp.asia/blog/9088437.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.iculmp.asia/blog/7679569.sHtMl

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.iculmp.asia/blog/5516797.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.iculmp.asia/blog/4947373.sHtMl

原标题：项目构建脚本编译打包解析
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.iculmp.asia/blog/4278322.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.iculmp.asia/blog/5033803.sHtMl

原标题：DevOps：WSL2生产环境使用风险提示
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.iculmp.asia/blog/6822167.sHtMl

原标题：数据库死锁成因规避方案
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.iculmp.asia/blog/5659197.sHtMl

原标题：golang es 更新文档注意版本冲突
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.iculmp.asia/blog/2105280.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.iculmp.asia/blog/6100682.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.iculmp.asia/blog/4339026.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.iculmp.asia/blog/3992169.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.iculmp.asia/blog/3753821.sHtMl

原标题：golang es 查询语句 DSL 实操
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.iculmp.asia/blog/6359723.sHtMl

原标题：golang 系统设计网络超时故障排查思路
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.iculmp.asia/blog/5000236.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.iculmp.asia/blog/7027582.sHtMl

原标题：golang 系统设计内存高占用排查思路
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.iculmp.asia/blog/2394973.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.iculmp.asia/blog/4934661.sHtMl

原标题：零基础理解进程、线程基础概念区别
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.iculmp.asia/blog/4646979.sHtMl

原标题：golang gitlab ci 配置自动构建镜像
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.iculmp.asia/blog/1615722.sHtMl

原标题：线程调度优化减少上下文切换
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.iculmp.asia/blog/9690883.sHtMl

原标题：golang kafka 消息顺序性保证方案
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.iculmp.asia/blog/0892597.sHtMl

原标题：大文件导出内存溢出防护
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.iculmp.asia/blog/1341906.sHtMl

原标题：golang 配置文件多环境加载
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.iculmp.asia/blog/6050916.sHtMl

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.iculmp.asia/blog/1083216.sHtMl

原标题：日志切割配置防止日志丢失
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.iculmp.asia/blog/2274742.sHtMl

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.iculmp.asia/blog/4191310.sHtMl

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.iculmp.asia/blog/7049087.sHtMl

原标题：golang jaeger 链路追踪 go 接入
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.iculmp.asia/blog/9084379.sHtMl

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.iculmp.asia/blog/5917897.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.iculmp.asia/blog/3199477.sHtMl

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.iculmp.asia/blog/9322829.sHtMl

原标题：站内邮件消息通知功能开发
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.iculmp.asia/blog/9090835.sHtMl

原标题：记一次限流组件误配置把正常用户拦截
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.iculmp.asia/blog/9338326.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.iculmp.asia/blog/0844028.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.iculmp.asia/blog/5997698.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.iculmp.asia/blog/5991506.sHtMl

原标题：golang docker 容器资源限制设置
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.iculmp.asia/blog/6682751.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.iculmp.asia/blog/0145169.sHtMl

原标题：DevOps：制品仓库管理二进制产物版本
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.iculmp.asia/blog/0327898.sHtMl

原标题：前端打包产物体积压缩优化
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.iculmp.asia/blog/5679496.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.iculmp.asia/blog/1952457.sHtMl

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.iculmp.asia/blog/5523325.sHtMl

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.iculmp.asia/blog/2322883.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.iculmp.asia/blog/0149166.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.iculmp.asia/blog/1505381.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.iculmp.asia/blog/2866930.sHtMl

原标题：Practice：数据库分表简单实现方案与代码示例
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.iculmp.asia/blog/0358273.sHtMl

原标题：复盘总结：技术方案文档模板架构设计文档
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.iculmp.asia/blog/8289875.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.iculmp.asia/blog/0791962.sHtMl

三、实战开发｜Practice
原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.iculmp.asia/blog/1907824.sHtMl

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.iculmp.asia/blog/9719817.sHtMl

原标题：快速上手简单信号处理脚本编写
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.iculmp.asia/blog/2365044.sHtMl

原标题：服务健康检查告警监控体系
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.iculmp.asia/blog/8374973.sHtMl

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.iculmp.asia/blog/2591109.sHtMl

原标题：CI/CD 流水线自动构建部署落地
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.iculmp.asia/blog/7671735.sHtMl

原标题：git rebase 整理提交历史实操
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.iculmp.asia/blog/5917798.sHtMl

原标题：优化实践：预加载与懒加载业务场景取舍
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.iculmp.asia/blog/4576269.sHtMl

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.iculmp.asia/blog/7886907.sHtMl

原标题：echarts 大数据渲染性能调优
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.iculmp.asia/blog/6728086.sHtMl

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.iculmp.asia/blog/7997311.sHtMl

原标题：从零搭建简单Mock接口服务
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.iculmp.asia/blog/1307249.sHtMl

原标题：golang 系统设计秒杀防超卖方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.iculmp.asia/blog/5948758.sHtMl

原标题：前端打包分包加载提速方案
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.iculmp.asia/blog/3861833.sHtMl

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.iculmp.asia/blog/0252496.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.iculmp.asia/blog/3198903.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.iculmp.asia/blog/1276248.sHtMl

原标题：hosts 配置本地回环访问修复
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.iculmp.asia/blog/5090511.sHtMl

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.iculmp.asia/blog/6316800.sHtMl

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.iculmp.asia/blog/1287416.sHtMl

原标题：golang 系统设计 canary 金丝雀部署实操
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.iculmp.asia/blog/6893347.sHtMl

原标题：golang http grpc 全链路埋点示例
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.iculmp.asia/blog/8009109.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.iculmp.asia/blog/7219482.sHtMl

原标题：项目实践：分布式会话Redis存储落地实践
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.iculmp.asia/blog/0547893.sHtMl

原标题：golang ci 流水线自动部署 k8s 示例
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.iculmp.asia/blog/5324118.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.iculmp.asia/blog/8909750.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.iculmp.asia/blog/6430032.sHtMl

原标题：静态资源 404 路径打包修复
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.iculmp.asia/blog/1582748.sHtMl

原标题：Performance：JSON序列化性能优化实践
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.iculmp.asia/blog/3182204.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.iculmp.asia/blog/0599049.sHtMl

原标题：时间同步修复令牌提前过期
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.iculmp.asia/blog/2990631.sHtMl

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.iculmp.asia/blog/4507363.sHtMl

原标题：接口幂等性防重复请求实现
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.iculmp.asia/blog/4576169.sHtMl

原标题：部署实践：内网开发环境代理配置实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.iculmp.asia/blog/1231879.sHtMl

原标题：nodejs 项目 pm2 部署运维指南
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.iculmp.asia/blog/0122416.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.iculmp.asia/blog/7805298.sHtMl

原标题：Architecture：服务注册发现架构原理与选型
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.iculmp.asia/blog/2719596.sHtMl

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.iculmp.asia/blog/6847798.sHtMl

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.iculmp.asia/blog/7169288.sHtMl

原标题：golang prometheus 指标暴露实现
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.iculmp.asia/blog/8985321.sHtMl

四、架构设计｜Architecture
原标题：磁盘占满服务不可用清理方案
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.iculmp.asia/blog/7644902.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.iculmp.asia/blog/2295554.sHtMl

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.iculmp.asia/blog/7587998.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.iculmp.asia/blog/0183102.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.iculmp.asia/blog/5993847.sHtMl

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.iculmp.asia/blog/2085092.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.iculmp.asia/blog/7432328.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.iculmp.asia/blog/8612401.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.iculmp.asia/blog/2154566.sHtMl

原标题：记一次限流组件误配置把正常用户拦截
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.iculmp.asia/blog/4202230.sHtMl

原标题：golang 表单文件大小限制配置
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.iculmp.asia/blog/9045524.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.iculmp.asia/blog/7990375.sHtMl

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.iculmp.asia/blog/7427382.sHtMl

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.iculmp.asia/blog/7827942.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.iculmp.asia/blog/6084020.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.iculmp.asia/blog/0538025.sHtMl

原标题：golang 系统设计排行榜几种实现
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.iculmp.asia/blog/2358861.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.iculmp.asia/blog/1380626.sHtMl

?
