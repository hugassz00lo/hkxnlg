最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 分布式上下文传递方案
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.fywybz.asia/blog/8567018.sHtMl

原标题：golang docker 多阶段构建 go 镜像
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.fywybz.asia/blog/3318460.sHtMl

原标题：新手指南：读懂项目构建脚本作用
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.fywybz.asia/blog/3976060.sHtMl

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.fywybz.asia/blog/1252538.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.fywybz.asia/blog/4522840.sHtMl

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.fywybz.asia/blog/7964464.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.fywybz.asia/blog/0757540.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.fywybz.asia/blog/6843993.sHtMl

原标题：架构复盘：慢查询治理架构层面优化手段
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.fywybz.asia/blog/9860089.sHtMl

原标题：模拟登录鉴权权限判断示例
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.fywybz.asia/blog/0033138.sHtMl

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.fywybz.asia/blog/0619135.sHtMl

原标题：零基础理解内存溢出基础现象与表现
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.fywybz.asia/blog/3738171.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.fywybz.asia/blog/1570939.sHtMl

原标题：golang url 参数编码处理方案
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.fywybz.asia/blog/7429447.sHtMl

原标题：容器资源限制防止宿主机过载
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.fywybz.asia/blog/5348458.sHtMl

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.fywybz.asia/blog/0050933.sHtMl

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.fywybz.asia/blog/5692902.sHtMl

原标题：入门实践：简单错误码设计与使用规范
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.fywybz.asia/blog/8250894.sHtMl

原标题：golang kafka 监控指标简单梳理
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.fywybz.asia/blog/2620667.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.fywybz.asia/blog/2631705.sHtMl

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.fywybz.asia/blog/2346149.sHtMl

原标题：golang 配置文件多环境加载
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.fywybz.asia/blog/5485492.sHtMl

原标题：golang 系统设计接口频率限制业务落地
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.fywybz.asia/blog/8591121.sHtMl

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.fywybz.asia/blog/6069364.sHtMl

原标题：golang github actions 发布 release 包
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.fywybz.asia/blog/6129241.sHtMl

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.fywybz.asia/blog/7418494.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.fywybz.asia/blog/4649518.sHtMl

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.fywybz.asia/blog/2084507.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.fywybz.asia/blog/7711863.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.fywybz.asia/blog/2051531.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.fywybz.asia/blog/7729103.sHtMl

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.fywybz.asia/blog/3326638.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.fywybz.asia/blog/7100264.sHtMl

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.fywybz.asia/blog/9319002.sHtMl

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.fywybz.asia/blog/2762543.sHtMl

原标题：文件监控服务自动重启开发
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.fywybz.asia/blog/7715691.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.fywybz.asia/blog/5996422.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.fywybz.asia/blog/3771035.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.fywybz.asia/blog/2202142.sHtMl

原标题：部署复盘：静态站点部署CDN完整流程
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.fywybz.asia/blog/3271584.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计代码仓库权限管理方案
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.fywybz.asia/blog/9428345.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.fywybz.asia/blog/5914644.sHtMl

原标题：短信服务封装失败自动重试
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.fywybz.asia/blog/5974615.sHtMl

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.fywybz.asia/blog/8755137.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.fywybz.asia/blog/2387499.sHtMl

原标题：DevOps：WSL2生产环境使用风险提示
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.fywybz.asia/blog/8949646.sHtMl

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.fywybz.asia/blog/5374722.sHtMl

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.fywybz.asia/blog/9885454.sHtMl

原标题：golang 大文件 http 下载服务
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.fywybz.asia/blog/5506194.sHtMl

原标题：手写简易 RPC 服务通信原型
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.fywybz.asia/blog/9504563.sHtMl

原标题：golang mysql 批量导入数据实操
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.fywybz.asia/blog/5212807.sHtMl

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.fywybz.asia/blog/8521895.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.fywybz.asia/blog/4427880.sHtMl

原标题：golang 系统设计 gob msgpack 序列化对比
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.fywybz.asia/blog/7738881.sHtMl

原标题：Docker 容器网络不通排查
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.fywybz.asia/blog/4264879.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.fywybz.asia/blog/1884636.sHtMl

原标题：golang es 高亮搜索结果实现方案
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.fywybz.asia/blog/3256509.sHtMl

原标题：golang minio 存储桶权限管控配置
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.fywybz.asia/blog/1323675.sHtMl

原标题：golang 系统设计内部服务契约测试简单思路
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.fywybz.asia/blog/5976224.sHtMl

原标题：golang k8s 网络策略网络隔离设置
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.fywybz.asia/blog/1879714.sHtMl

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.fywybz.asia/blog/6624025.sHtMl

原标题：golang 批量任务协程控制防雪崩
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.fywybz.asia/blog/5029895.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.fywybz.asia/blog/7046677.sHtMl

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.fywybz.asia/blog/8971376.sHtMl

原标题：本地简易配置中心动态管理
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.fywybz.asia/blog/8639243.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.fywybz.asia/blog/8442014.sHtMl

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.fywybz.asia/blog/9311301.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.fywybz.asia/blog/7249105.sHtMl

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.fywybz.asia/blog/9757516.sHtMl

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.fywybz.asia/blog/1345611.sHtMl

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.fywybz.asia/blog/3815970.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.fywybz.asia/blog/1531045.sHtMl

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.fywybz.asia/blog/4525928.sHtMl

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.fywybz.asia/blog/9911207.sHtMl

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.fywybz.asia/blog/3518204.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.fywybz.asia/blog/4366571.sHtMl

原标题：golang jwt 鉴权中间件完整示例
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.fywybz.asia/blog/5869610.sHtMl

原标题：YAML 配置文件语法快速上手
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.fywybz.asia/blog/0896893.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.fywybz.asia/blog/5525306.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.fywybz.asia/blog/4005237.sHtMl

三、实战开发｜Practice
原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.fywybz.asia/blog/2679975.sHtMl

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.fywybz.asia/blog/7014729.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.fywybz.asia/blog/1332467.sHtMl

原标题：手写简易 MQ 理解消息存储消费
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.fywybz.asia/blog/1522909.sHtMl

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.fywybz.asia/blog/2733092.sHtMl

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.fywybz.asia/blog/6330465.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.fywybz.asia/blog/4608257.sHtMl

原标题：Debug：序列化反序列化版本不一致解析失败
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.fywybz.asia/blog/3807869.sHtMl

原标题：从零编写简易 CLI 命令行工具
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.fywybz.asia/blog/5017172.sHtMl

原标题：快速入门日志打印与日志分级基础用法
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.fywybz.asia/blog/4471301.sHtMl

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.fywybz.asia/blog/8387946.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.fywybz.asia/blog/9028486.sHtMl

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.fywybz.asia/blog/6013961.sHtMl

原标题：开发环境变量配置全平台教程
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.fywybz.asia/blog/5648676.sHtMl

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.fywybz.asia/blog/8595860.sHtMl

原标题：数据库读写分离性能优化
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.fywybz.asia/blog/8327679.sHtMl

原标题：Nginx 透传真实客户端 IP 配置
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.fywybz.asia/blog/9083321.sHtMl

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.fywybz.asia/blog/0193654.sHtMl

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.fywybz.asia/blog/7216846.sHtMl

原标题：golang 多协程任务池并发控制
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.fywybz.asia/blog/4266124.sHtMl

原标题：零基础理解读写分离基础思想
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.fywybz.asia/blog/1241051.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.fywybz.asia/blog/8956565.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.fywybz.asia/blog/9602670.sHtMl

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.fywybz.asia/blog/4889502.sHtMl

原标题：文件描述符优化进程卡死修复
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.fywybz.asia/blog/7726159.sHtMl

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.fywybz.asia/blog/8591730.sHtMl

原标题：新手指南：如何读懂开源项目报错日志
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.fywybz.asia/blog/4293298.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.fywybz.asia/blog/7263341.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.fywybz.asia/blog/7533287.sHtMl

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.fywybz.asia/blog/2307968.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.fywybz.asia/blog/1578681.sHtMl

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.fywybz.asia/blog/0190862.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.fywybz.asia/blog/9219903.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.fywybz.asia/blog/0839324.sHtMl

原标题：golang 项目目录分层规范设计
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.fywybz.asia/blog/3377681.sHtMl

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.fywybz.asia/blog/7388087.sHtMl

原标题：多操作系统开发兼容处理
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.fywybz.asia/blog/9075538.sHtMl

原标题：golang 结构体深拷贝几种实现
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.fywybz.asia/blog/3420030.sHtMl

原标题：项目目录结构规范化最佳实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.fywybz.asia/blog/9021949.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.fywybz.asia/blog/7276026.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计日志系统架构思路
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.fywybz.asia/blog/2996544.sHtMl

原标题：批量操作分批处理防止 OOM
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.fywybz.asia/blog/1372338.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.fywybz.asia/blog/0809439.sHtMl

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.fywybz.asia/blog/8522791.sHtMl

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.fywybz.asia/blog/9655233.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.fywybz.asia/blog/6940936.sHtMl

原标题：golang 系统设计 mq 消息丢失完整防护
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.fywybz.asia/blog/1486041.sHtMl

原标题：golang k8s liveness readiness 探针
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.fywybz.asia/blog/9769217.sHtMl

原标题：从零搭建简单定时任务demo
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.fywybz.asia/blog/9725022.sHtMl

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.fywybz.asia/blog/3337124.sHtMl

原标题：express 请求参数校验处理
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.fywybz.asia/blog/0781643.sHtMl

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.fywybz.asia/blog/3427569.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.fywybz.asia/blog/8647123.sHtMl

原标题：本地运行正常线上报错排查
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.fywybz.asia/blog/5637849.sHtMl

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.fywybz.asia/blog/4054198.sHtMl

原标题：入门实践：简易导出导入文件功能实现
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.fywybz.asia/blog/3692462.sHtMl

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.fywybz.asia/blog/7285736.sHtMl

原标题：项目实践：定时任务防重复执行落地实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.fywybz.asia/blog/0174751.sHtMl

?
