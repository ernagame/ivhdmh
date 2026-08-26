最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/189796.Doc

原标题：开源项目本地运行排错完整清单
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/218301.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.1d3jeg.asia/arts/024733.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.1d3jeg.asia/arts/823325.Doc

原标题：DNS TTL 配置域名切换生效
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.1d3jeg.asia/arts/259459.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.1d3jeg.asia/arts/003268.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.1d3jeg.asia/arts/358696.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.1d3jeg.asia/arts/290227.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/416039.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.1d3jeg.asia/arts/206239.Doc

原标题：接口限流逻辑简单模拟实现
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/098924.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.1d3jeg.asia/arts/155600.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/491199.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/723102.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/010712.Doc

原标题：RPC 接口字段增减兼容处理
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/223747.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.1d3jeg.asia/arts/899029.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/603806.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.1d3jeg.asia/arts/510112.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/825731.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/802725.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/147621.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.1d3jeg.asia/arts/737917.Doc

原标题：ICMP 放通网络丢包问题修复
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/321939.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/371572.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/457534.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.1d3jeg.asia/arts/941720.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/548459.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/013123.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.1d3jeg.asia/arts/017589.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.1d3jeg.asia/arts/643314.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/055319.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.1d3jeg.asia/arts/514235.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.1d3jeg.asia/arts/968511.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.1d3jeg.asia/arts/358432.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/803436.Doc

原标题：GET POST 接口请求参数处理
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.1d3jeg.asia/arts/689987.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.1d3jeg.asia/arts/646911.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.1d3jeg.asia/arts/206511.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/717859.Doc


二、踩坑排错｜Troubleshooting
原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.1d3jeg.asia/arts/315659.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.1d3jeg.asia/arts/166278.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.1d3jeg.asia/arts/581541.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.1d3jeg.asia/arts/117469.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.1d3jeg.asia/arts/270017.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/298761.Doc

原标题：golang docker 部署 es 本地开发
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.1d3jeg.asia/arts/784553.Doc

原标题：golang traceId spanId 传递方案
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/813164.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.1d3jeg.asia/arts/619043.Doc

原标题：golang redis set 集合去重业务
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/397812.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/465836.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/254349.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/411633.Doc

原标题：golang 消息死信处理业务逻辑
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.1d3jeg.asia/arts/513723.Doc

原标题：Docker 容器时区错误修复方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.1d3jeg.asia/arts/643895.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/697537.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/564992.Doc

原标题：Nginx 请求头大小上限调整
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.1d3jeg.asia/arts/349379.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/763099.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/603650.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.1d3jeg.asia/arts/966589.Doc

原标题：日志驱动异常日志不输出修复
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/679554.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.1d3jeg.asia/arts/906215.Doc

原标题：axios 二次封装请求拦截处理
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/921578.Doc

原标题：golang 表单文件大小限制配置
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.1d3jeg.asia/arts/102166.Doc

原标题：超大数据集分页性能优化方案
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/595305.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.1d3jeg.asia/arts/892016.Doc

原标题：数据库分表路由写入分片修正
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/530044.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.1d3jeg.asia/arts/880410.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.1d3jeg.asia/arts/614686.Doc

原标题：语义化版本依赖管理防错乱
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.1d3jeg.asia/arts/606186.Doc

原标题：golang 限流熔断降级完整示例
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.1d3jeg.asia/arts/243089.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/065317.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.1d3jeg.asia/arts/255724.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.1d3jeg.asia/arts/798598.Doc

原标题：golang 开发环境快速搭建指南
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/755302.Doc

原标题：多线程线程安全脏数据规避
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.1d3jeg.asia/arts/186807.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.1d3jeg.asia/arts/877062.Doc

原标题：前端错误监控上报系统搭建
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/469327.Doc

原标题：网络读取超时设置连接挂起防护
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/324149.Doc

三、实战开发｜Practice
原标题：golang 系统设计告警风暴抑制方案实现
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/509632.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.1d3jeg.asia/arts/525186.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.1d3jeg.asia/arts/465285.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.1d3jeg.asia/arts/189070.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.1d3jeg.asia/arts/947466.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.1d3jeg.asia/arts/654507.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.1d3jeg.asia/arts/403136.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/592539.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/261518.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.1d3jeg.asia/arts/999950.Doc

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/636970.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/307700.Doc

原标题：golang pprof 线上采集性能数据
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/536088.Doc

原标题：golang redis 计数器防超卖示例
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.1d3jeg.asia/arts/195592.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/655950.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/762061.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.1d3jeg.asia/arts/724874.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.1d3jeg.asia/arts/643467.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/892724.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/447915.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/862275.Doc

原标题：多版本开发环境共存配置
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/902438.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.1d3jeg.asia/arts/549134.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/884867.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.1d3jeg.asia/arts/633085.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.1d3jeg.asia/arts/265948.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/294061.Doc

原标题：golang 项目环境变量加载方案
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.1d3jeg.asia/arts/777831.Doc

原标题：网关集成鉴权限流日志一体化
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.1d3jeg.asia/arts/522694.Doc

原标题：后端大文件分片上传接口开发
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/600709.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/310561.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.1d3jeg.asia/arts/391262.Doc

原标题：接口签名验签完整安全方案
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.1d3jeg.asia/arts/244705.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.1d3jeg.asia/arts/054587.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/270480.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.1d3jeg.asia/arts/319176.Doc

原标题：跨平台 uniapp 多端开发实操
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.1d3jeg.asia/arts/656904.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/640716.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/578400.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/939534.Doc

四、架构设计｜Architecture
原标题：golang 系统设计数据库慢查询治理方案
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.1d3jeg.asia/arts/840756.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.1d3jeg.asia/arts/549320.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.1d3jeg.asia/arts/028916.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/773820.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.1d3jeg.asia/arts/307094.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/756030.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.1d3jeg.asia/arts/606383.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.1d3jeg.asia/arts/007090.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/442754.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/700285.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.1d3jeg.asia/arts/775490.Doc

原标题：文件描述符优化进程卡死修复
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.1d3jeg.asia/arts/481001.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/530186.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.1d3jeg.asia/arts/548631.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/569801.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.1d3jeg.asia/arts/259717.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/418450.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.1d3jeg.asia/arts/125690.Doc

?
