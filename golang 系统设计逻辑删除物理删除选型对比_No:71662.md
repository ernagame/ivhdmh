最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计逻辑删除物理删除选型对比
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.cnd9jg.asia/arts/188473.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.cnd9jg.asia/arts/909676.Doc

原标题：超大数据集分页性能优化方案
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.cnd9jg.asia/arts/318814.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.cnd9jg.asia/arts/760414.Doc

原标题：从零搭建简单CLI命令行工具
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.cnd9jg.asia/arts/152586.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.cnd9jg.asia/arts/820587.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/378033.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.cnd9jg.asia/arts/652433.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/119778.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.cnd9jg.asia/arts/320576.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.cnd9jg.asia/arts/111156.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/014285.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.cnd9jg.asia/arts/270039.Doc

原标题：静态站点自动部署发布方案
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.cnd9jg.asia/arts/564990.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/034440.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.cnd9jg.asia/arts/562502.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.cnd9jg.asia/arts/783769.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.cnd9jg.asia/arts/756577.Doc

原标题：golang 雪花 id 重复问题排查
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.cnd9jg.asia/arts/729295.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/590924.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.cnd9jg.asia/arts/753915.Doc

原标题：特殊输入字符过滤解析防护
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/345117.Doc

原标题：golang 系统设计 README 开源文档模板
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.cnd9jg.asia/arts/829355.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.cnd9jg.asia/arts/458376.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.cnd9jg.asia/arts/296228.Doc

原标题：语义化版本依赖管理防错乱
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/686581.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.cnd9jg.asia/arts/378668.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.cnd9jg.asia/arts/829184.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.cnd9jg.asia/arts/007227.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.cnd9jg.asia/arts/606209.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.cnd9jg.asia/arts/459443.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.cnd9jg.asia/arts/428731.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/619516.Doc

原标题：前端静态缓存更新生效处理
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.cnd9jg.asia/arts/371463.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.cnd9jg.asia/arts/937986.Doc

原标题：从零搭建本地开发环境完整教程
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.cnd9jg.asia/arts/448666.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/146960.Doc

原标题：golang goroutine 池任务调度
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.cnd9jg.asia/arts/015507.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.cnd9jg.asia/arts/893958.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.cnd9jg.asia/arts/996922.Doc


二、踩坑排错｜Troubleshooting
原标题：架构思考：单体应用向微服务拆分演进路径
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.cnd9jg.asia/arts/075999.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.cnd9jg.asia/arts/859879.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.cnd9jg.asia/arts/663039.Doc

原标题：文件锁正确使用避免死锁
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/940093.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.cnd9jg.asia/arts/995643.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/160024.Doc

原标题：Cookie Session 会话状态管理
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/604411.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.cnd9jg.asia/arts/180639.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.cnd9jg.asia/arts/312584.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.cnd9jg.asia/arts/325071.Doc

原标题：接口限流逻辑简单模拟实现
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/401014.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/755307.Doc

原标题：golang 灰度权重流量分发简单实现
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/089362.Doc

原标题：golang docker 基础命令实操汇总
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.cnd9jg.asia/arts/145554.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.cnd9jg.asia/arts/210805.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/591700.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.cnd9jg.asia/arts/976952.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.cnd9jg.asia/arts/012210.Doc

原标题：服务健康检查告警监控体系
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.cnd9jg.asia/arts/489566.Doc

原标题：golang mysql 防止 sql 注入实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/296762.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.cnd9jg.asia/arts/578732.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.cnd9jg.asia/arts/271215.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/597606.Doc

原标题：站内邮件消息通知功能开发
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.cnd9jg.asia/arts/430306.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.cnd9jg.asia/arts/809565.Doc

原标题：包管理器依赖冲突解决方案
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.cnd9jg.asia/arts/828828.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/188244.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/722804.Doc

原标题：webpack chunk 分包策略详解
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.cnd9jg.asia/arts/799900.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/100063.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/529940.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.cnd9jg.asia/arts/939214.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.cnd9jg.asia/arts/694689.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/426383.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.cnd9jg.asia/arts/745265.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.cnd9jg.asia/arts/112647.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.cnd9jg.asia/arts/420098.Doc

原标题：golang ci 流水线环境变量管理方案
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.cnd9jg.asia/arts/125768.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.cnd9jg.asia/arts/504439.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.cnd9jg.asia/arts/618445.Doc

三、实战开发｜Practice
原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.cnd9jg.asia/arts/612242.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.cnd9jg.asia/arts/672499.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.cnd9jg.asia/arts/530987.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.cnd9jg.asia/arts/719632.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.cnd9jg.asia/arts/074749.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.cnd9jg.asia/arts/157042.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.cnd9jg.asia/arts/482246.Doc

原标题：golang github actions 多平台构建
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.cnd9jg.asia/arts/267302.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.cnd9jg.asia/arts/293047.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.cnd9jg.asia/arts/561543.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/493991.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.cnd9jg.asia/arts/145529.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.cnd9jg.asia/arts/176208.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/137399.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.cnd9jg.asia/arts/426445.Doc

原标题：网关超时时间调优后端等待
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.cnd9jg.asia/arts/324057.Doc

原标题：golang http 请求重试封装工具
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/472697.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.cnd9jg.asia/arts/616224.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.cnd9jg.asia/arts/578915.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.cnd9jg.asia/arts/642225.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/601841.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.cnd9jg.asia/arts/961118.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/969217.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.cnd9jg.asia/arts/120745.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.cnd9jg.asia/arts/789225.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.cnd9jg.asia/arts/243379.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.cnd9jg.asia/arts/974910.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.cnd9jg.asia/arts/504040.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.cnd9jg.asia/arts/848919.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.cnd9jg.asia/arts/505629.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.cnd9jg.asia/arts/204759.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.cnd9jg.asia/arts/019617.Doc

原标题：golang 项目 makefile 脚本编写
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.cnd9jg.asia/arts/355877.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.cnd9jg.asia/arts/405469.Doc

原标题：前端静态缓存更新生效处理
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.cnd9jg.asia/arts/864401.Doc

原标题：环境变量不生效问题修复
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.cnd9jg.asia/arts/267200.Doc

原标题：golang go test 覆盖率统计实操
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.cnd9jg.asia/arts/089148.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.cnd9jg.asia/arts/276577.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.cnd9jg.asia/arts/269212.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/901515.Doc

四、架构设计｜Architecture
原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.cnd9jg.asia/arts/609247.Doc

原标题：golang github actions 多平台构建
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.cnd9jg.asia/arts/185926.Doc

原标题：系统字符集统一乱码修复
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.cnd9jg.asia/arts/238074.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.cnd9jg.asia/arts/961547.Doc

原标题：service‑worker 离线缓存实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.cnd9jg.asia/arts/578370.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.cnd9jg.asia/arts/156834.Doc

原标题：golang 简易埋点日志上报实现
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.cnd9jg.asia/arts/415706.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.cnd9jg.asia/arts/224547.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/842244.Doc

原标题：golang 时间时区处理避坑指南
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.cnd9jg.asia/arts/931582.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.cnd9jg.asia/arts/600704.Doc

原标题：golang docker compose 本地开发最佳实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.cnd9jg.asia/arts/815777.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/169766.Doc

原标题：golang prometheus counter gauge 使用
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.cnd9jg.asia/arts/720540.Doc

原标题：前端工程化 webpack 打包优化
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.cnd9jg.asia/arts/164884.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.cnd9jg.asia/arts/858467.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.cnd9jg.asia/arts/275855.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.cnd9jg.asia/arts/081030.Doc

?
