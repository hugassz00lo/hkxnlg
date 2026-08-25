最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计高可用服务架构梳理
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://zhishi.g26g09.asia/blog/7406676.sHtMl

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://zhishi.g26g09.asia/blog/6050389.sHtMl

原标题：日志输出规范防止磁盘爆满
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/8843959.sHtMl

原标题：RPC 接口字段增减兼容处理
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://zhishi.g26g09.asia/blog/6421838.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://zhishi.g26g09.asia/blog/1249157.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://zhishi.g26g09.asia/blog/5897385.sHtMl

原标题：线上接口超时故障排查思路
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/3130574.sHtMl

原标题：不必要字符转义关闭业务异常
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://zhishi.g26g09.asia/blog/9836481.sHtMl

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://zhishi.g26g09.asia/blog/8985627.sHtMl

原标题：磁盘占满服务不可用清理方案
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://zhishi.g26g09.asia/blog/3125345.sHtMl

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/5406576.sHtMl

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://zhishi.g26g09.asia/blog/4218918.sHtMl

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://zhishi.g26g09.asia/blog/1664780.sHtMl

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://zhishi.g26g09.asia/blog/3005844.sHtMl

原标题：golang 系统设计容器 OOM 故障完整排查
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://zhishi.g26g09.asia/blog/3702202.sHtMl

原标题：入门实践：简单图片上传预览本地demo
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://zhishi.g26g09.asia/blog/7247459.sHtMl

原标题：golang 系统设计线程协程泄露定位方法
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.g26g09.asia/blog/2504642.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/2693930.sHtMl

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/2382456.sHtMl

原标题：golang 系统设计依赖版本升级风险评估
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://zhishi.g26g09.asia/blog/4149217.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://zhishi.g26g09.asia/blog/0532354.sHtMl

原标题：golang gin 框架接口开发实战
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://zhishi.g26g09.asia/blog/0549791.sHtMl

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://zhishi.g26g09.asia/blog/2316353.sHtMl

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://zhishi.g26g09.asia/blog/4098161.sHtMl

原标题：单元测试用例编写入门实操
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://zhishi.g26g09.asia/blog/2426313.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/2524315.sHtMl

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://zhishi.g26g09.asia/blog/9342160.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://zhishi.g26g09.asia/blog/9381889.sHtMl

原标题：golang 内存 pprof 定位内存泄漏
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://zhishi.g26g09.asia/blog/2667951.sHtMl

原标题：golang 日志脱敏敏感字段过滤
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://zhishi.g26g09.asia/blog/3679572.sHtMl

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://zhishi.g26g09.asia/blog/2364405.sHtMl

原标题：部署实践：HTTPS证书自动续期配置实践
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://zhishi.g26g09.asia/blog/2953642.sHtMl

原标题：golang redis 事务 multi exec 使用
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://zhishi.g26g09.asia/blog/9684933.sHtMl

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://zhishi.g26g09.asia/blog/1430313.sHtMl

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/8784249.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://zhishi.g26g09.asia/blog/8419068.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://zhishi.g26g09.asia/blog/9030508.sHtMl

原标题：golang redis 缓存穿透解决方案
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://zhishi.g26g09.asia/blog/6681684.sHtMl

原标题：golang http 服务性能优化调参
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://zhishi.g26g09.asia/blog/5134711.sHtMl

原标题：golang 系统设计防重复提交实现
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://zhishi.g26g09.asia/blog/3223946.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计数据库版本迁移回滚方案
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://zhishi.g26g09.asia/blog/5323724.sHtMl

原标题：golang 日志脱敏敏感字段过滤
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://zhishi.g26g09.asia/blog/4917940.sHtMl

原标题：DevOps：容器健康探针livenessreadiness配置
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://zhishi.g26g09.asia/blog/7136530.sHtMl

原标题：golang pprof 线上采集性能数据
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://zhishi.g26g09.asia/blog/4162056.sHtMl

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://zhishi.g26g09.asia/blog/6535556.sHtMl

原标题：大事务拆分回滚日志暴涨解决
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://zhishi.g26g09.asia/blog/4513065.sHtMl

原标题：golang mysql 连接泄漏检测方法
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://zhishi.g26g09.asia/blog/1543368.sHtMl

原标题：开源项目本地运行排错完整清单
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/0256137.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://zhishi.g26g09.asia/blog/2950088.sHtMl

原标题：Practice：实现跨机器文件同步脚本实践
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://zhishi.g26g09.asia/blog/3470981.sHtMl

原标题：文件分片上传断点续传功能
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://zhishi.g26g09.asia/blog/6137878.sHtMl

原标题：JWT 工具封装令牌刷新过期
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://zhishi.g26g09.asia/blog/3477271.sHtMl

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://zhishi.g26g09.asia/blog/8544506.sHtMl

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://zhishi.g26g09.asia/blog/9392044.sHtMl

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://zhishi.g26g09.asia/blog/0592785.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://zhishi.g26g09.asia/blog/3470616.sHtMl

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://zhishi.g26g09.asia/blog/6866103.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://zhishi.g26g09.asia/blog/8942078.sHtMl

原标题：系统时间同步定时任务偏移
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://zhishi.g26g09.asia/blog/8852633.sHtMl

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/8905050.sHtMl

原标题：golang 系统设计配置敏感信息加密存储方案
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://zhishi.g26g09.asia/blog/0019814.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://zhishi.g26g09.asia/blog/0243079.sHtMl

原标题：实战：搭建日志收集分析简易完整演示环境
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://zhishi.g26g09.asia/blog/5328217.sHtMl

原标题：golang 集成测试启动测试数据库
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://zhishi.g26g09.asia/blog/6029325.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://zhishi.g26g09.asia/blog/9317392.sHtMl

原标题：新手教程：Gittag版本标签打标签实操
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.g26g09.asia/blog/7793131.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://zhishi.g26g09.asia/blog/2068385.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://zhishi.g26g09.asia/blog/5386468.sHtMl

原标题：线上故障：慢查询拖垮整个数据库服务
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://zhishi.g26g09.asia/blog/7819596.sHtMl

原标题：golang 系统设计对象池复用减少内存分配
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://zhishi.g26g09.asia/blog/7830646.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://zhishi.g26g09.asia/blog/4173431.sHtMl

原标题：golang 分布式 ID 雪花算法实现
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/9196842.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://zhishi.g26g09.asia/blog/6133029.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://zhishi.g26g09.asia/blog/3236151.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://zhishi.g26g09.asia/blog/8650142.sHtMl

原标题：安全组端口开放网络访问
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://zhishi.g26g09.asia/blog/8900184.sHtMl

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/1639659.sHtMl

原标题：golang gitlab runner 部署与注册实操
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.g26g09.asia/blog/0991468.sHtMl

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://zhishi.g26g09.asia/blog/2624142.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://zhishi.g26g09.asia/blog/4118106.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://zhishi.g26g09.asia/blog/5282547.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://zhishi.g26g09.asia/blog/2221247.sHtMl

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://zhishi.g26g09.asia/blog/9095788.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://zhishi.g26g09.asia/blog/9024422.sHtMl

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://zhishi.g26g09.asia/blog/4729269.sHtMl

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://zhishi.g26g09.asia/blog/5573721.sHtMl

原标题：pnpm 包管理工具实战避坑指南
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://zhishi.g26g09.asia/blog/6598069.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://zhishi.g26g09.asia/blog/9630866.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://zhishi.g26g09.asia/blog/6359197.sHtMl

原标题：golang 单元测试 table‑driven
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://zhishi.g26g09.asia/blog/2082543.sHtMl

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://zhishi.g26g09.asia/blog/7548463.sHtMl

原标题：零基础理解HTTP常用请求头与状态码
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://zhishi.g26g09.asia/blog/3815096.sHtMl

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://zhishi.g26g09.asia/blog/9627473.sHtMl

原标题：项目实践：灰度发布简易方案落地实践
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://zhishi.g26g09.asia/blog/8946384.sHtMl

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://zhishi.g26g09.asia/blog/5649709.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://zhishi.g26g09.asia/blog/1067806.sHtMl

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://zhishi.g26g09.asia/blog/4688087.sHtMl

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://zhishi.g26g09.asia/blog/9628751.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://zhishi.g26g09.asia/blog/6110792.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://zhishi.g26g09.asia/blog/2542806.sHtMl

原标题：golang 链路 traceId 透传中间件
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.g26g09.asia/blog/1360945.sHtMl

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://zhishi.g26g09.asia/blog/3792424.sHtMl

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://zhishi.g26g09.asia/blog/9100645.sHtMl

原标题：golang k8s 持久化 pv pvc 使用实操
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://zhishi.g26g09.asia/blog/4337203.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://zhishi.g26g09.asia/blog/7740618.sHtMl

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://zhishi.g26g09.asia/blog/3071703.sHtMl

原标题：安全笔记：文件下载接口路径校验安全
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://zhishi.g26g09.asia/blog/2822734.sHtMl

原标题：全局本地依赖隔离冲突规避
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://zhishi.g26g09.asia/blog/9076192.sHtMl

原标题：防火墙 IP 白名单回调接口放行
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://zhishi.g26g09.asia/blog/0057064.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://zhishi.g26g09.asia/blog/5722069.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://zhishi.g26g09.asia/blog/1607503.sHtMl

原标题：Nginx 请求头大小上限调整
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://zhishi.g26g09.asia/blog/3172437.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://zhishi.g26g09.asia/blog/9017685.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.g26g09.asia/blog/2811828.sHtMl

原标题：浏览器缓存强制刷新方案
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://zhishi.g26g09.asia/blog/4288593.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://zhishi.g26g09.asia/blog/8203196.sHtMl

原标题：设计思考：系统幂等性整体架构层面保障
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://zhishi.g26g09.asia/blog/4469371.sHtMl

原标题：CI 流水线超时时间延长配置
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://zhishi.g26g09.asia/blog/1661654.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://zhishi.g26g09.asia/blog/8282055.sHtMl

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://zhishi.g26g09.asia/blog/5642617.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计数据库扩容几种方式
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://zhishi.g26g09.asia/blog/9764422.sHtMl

原标题：安全实践：备份文件访问权限安全管控
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.g26g09.asia/blog/9921126.sHtMl

原标题：golang 系统设计 README 开源文档模板
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://zhishi.g26g09.asia/blog/3449276.sHtMl

原标题：golang 系统设计 rest http 方法使用原则
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://zhishi.g26g09.asia/blog/8890472.sHtMl

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://zhishi.g26g09.asia/blog/5353684.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.g26g09.asia/blog/4254304.sHtMl

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.g26g09.asia/blog/8241421.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://zhishi.g26g09.asia/blog/6739611.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://zhishi.g26g09.asia/blog/9980782.sHtMl

原标题：golang 系统设计接口参数防篡改校验
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://zhishi.g26g09.asia/blog/5210789.sHtMl

原标题：golang redis 计数器防超卖示例
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://zhishi.g26g09.asia/blog/8613661.sHtMl

原标题：golang mysql 行锁表锁场景区分
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://zhishi.g26g09.asia/blog/1307801.sHtMl

原标题：golang cron 定时任务防并发执行
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://zhishi.g26g09.asia/blog/6706577.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://zhishi.g26g09.asia/blog/0695052.sHtMl

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://zhishi.g26g09.asia/blog/1927948.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.g26g09.asia/blog/6723460.sHtMl

原标题：前后端会话登录状态持久化
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://zhishi.g26g09.asia/blog/4631671.sHtMl

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://zhishi.g26g09.asia/blog/2416042.sHtMl

?
