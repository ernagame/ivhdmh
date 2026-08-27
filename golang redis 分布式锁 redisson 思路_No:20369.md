最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang redis 分布式锁 redisson 思路
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.dnkiaeh.asia/blog/0650754.sHtMl

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.dnkiaeh.asia/blog/9029139.sHtMl

原标题：golang consul 健康检查服务注册
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.dnkiaeh.asia/blog/8951904.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.dnkiaeh.asia/blog/0585891.sHtMl

原标题：vite 插件开发自定义构建逻辑
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.dnkiaeh.asia/blog/0549566.sHtMl

原标题：死信队列处理消息阻塞业务
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.dnkiaeh.asia/blog/6001654.sHtMl

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.dnkiaeh.asia/blog/1084265.sHtMl

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.dnkiaeh.asia/blog/5172912.sHtMl

原标题：golang redis 计数器防超卖示例
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.dnkiaeh.asia/blog/6366203.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.dnkiaeh.asia/blog/7978944.sHtMl

原标题：方案设计：分布式锁失效风险架构层面规避
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.dnkiaeh.asia/blog/1586975.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.dnkiaeh.asia/blog/5260611.sHtMl

原标题：前端打包分包加载提速方案
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.dnkiaeh.asia/blog/2576326.sHtMl

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/7576246.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.dnkiaeh.asia/blog/9861133.sHtMl

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.dnkiaeh.asia/blog/6980245.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.dnkiaeh.asia/blog/4194869.sHtMl

原标题：主干开发团队代码合并策略
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.dnkiaeh.asia/blog/0110894.sHtMl

原标题：Shell 运维脚本服务器效率提升
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.dnkiaeh.asia/blog/2386080.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.dnkiaeh.asia/blog/7489204.sHtMl

原标题：Spring 事务传播机制配置生效
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.dnkiaeh.asia/blog/3624949.sHtMl

原标题：golang 信号量控制并发数量
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.dnkiaeh.asia/blog/5753805.sHtMl

原标题：Nginx 请求头大小上限调整
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.dnkiaeh.asia/blog/5941243.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.dnkiaeh.asia/blog/1388685.sHtMl

原标题：golang 系统设计版本号语义化规范讲解
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/2730807.sHtMl

原标题：安全实践：请求输入校验防御恶意参数
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.dnkiaeh.asia/blog/8881693.sHtMl

原标题：golang mysql exists in 性能对比
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.dnkiaeh.asia/blog/1135532.sHtMl

原标题：编译打包产物依赖分析解读
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.dnkiaeh.asia/blog/6832661.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.dnkiaeh.asia/blog/4219577.sHtMl

原标题：数据库分表存储大表优化方案
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.dnkiaeh.asia/blog/7577428.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.dnkiaeh.asia/blog/4833102.sHtMl

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.dnkiaeh.asia/blog/5964733.sHtMl

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.dnkiaeh.asia/blog/5870753.sHtMl

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.dnkiaeh.asia/blog/9097682.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/9952213.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.dnkiaeh.asia/blog/0841455.sHtMl

原标题：golang toml 配置文件解析教程
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.dnkiaeh.asia/blog/8679530.sHtMl

原标题：HTTPS 证书过期更新操作
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.dnkiaeh.asia/blog/9068173.sHtMl

原标题：golang docker 基础命令实操汇总
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/2765389.sHtMl

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.dnkiaeh.asia/blog/7245529.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang pprof 线上采集性能数据
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.dnkiaeh.asia/blog/3128647.sHtMl

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.dnkiaeh.asia/blog/2205162.sHtMl

原标题：golang github actions 缓存依赖提速
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.dnkiaeh.asia/blog/7069066.sHtMl

原标题：golang 集成测试启动测试数据库
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.dnkiaeh.asia/blog/6726427.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.dnkiaeh.asia/blog/3221946.sHtMl

原标题：WebSocket 聊天室实时通讯开发
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.dnkiaeh.asia/blog/1245978.sHtMl

原标题：架构思考：单体应用向微服务拆分演进路径
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.dnkiaeh.asia/blog/1242225.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.dnkiaeh.asia/blog/3156756.sHtMl

原标题：安全实践：接口速率限制防止暴力破解
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.dnkiaeh.asia/blog/6358249.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.dnkiaeh.asia/blog/0601210.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.dnkiaeh.asia/blog/2590958.sHtMl

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.dnkiaeh.asia/blog/9995344.sHtMl

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.dnkiaeh.asia/blog/8023095.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.dnkiaeh.asia/blog/2387568.sHtMl

原标题：golang redis 锁超时业务处理
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.dnkiaeh.asia/blog/4140253.sHtMl

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.dnkiaeh.asia/blog/8106278.sHtMl

原标题：golang 配置文件多环境加载
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.dnkiaeh.asia/blog/8167340.sHtMl

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.dnkiaeh.asia/blog/6347773.sHtMl

原标题：css 变量主题切换方案实现
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.dnkiaeh.asia/blog/4801601.sHtMl

原标题：手写简易 ORM 理解对象映射
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.dnkiaeh.asia/blog/9314807.sHtMl

原标题：golang mysql exists in 性能对比
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.dnkiaeh.asia/blog/1623812.sHtMl

原标题：golang 项目 go mod 依赖管理
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.dnkiaeh.asia/blog/3353278.sHtMl

原标题：CDN 缓存刷新获取最新静态资源
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.dnkiaeh.asia/blog/8904388.sHtMl

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.dnkiaeh.asia/blog/2367755.sHtMl

原标题：golang 系统设计接口参数防篡改校验
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/4492564.sHtMl

原标题：ORM 框架数据库增删改查实操
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.dnkiaeh.asia/blog/2636327.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.dnkiaeh.asia/blog/3355699.sHtMl

原标题：golang http 代理客户端配置
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.dnkiaeh.asia/blog/7174015.sHtMl

原标题：Performance：数据库索引优化常见错误案例
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.dnkiaeh.asia/blog/7580792.sHtMl

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.dnkiaeh.asia/blog/5512415.sHtMl

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.dnkiaeh.asia/blog/9327139.sHtMl

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.dnkiaeh.asia/blog/1912753.sHtMl

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/7532121.sHtMl

原标题：golang 系统设计开源项目协作流程梳理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.dnkiaeh.asia/blog/1558450.sHtMl

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.dnkiaeh.asia/blog/1275276.sHtMl

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.dnkiaeh.asia/blog/8875188.sHtMl

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.dnkiaeh.asia/blog/8645787.sHtMl

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.dnkiaeh.asia/blog/2280107.sHtMl

原标题：复盘总结：系统压测报告模板与分析思路
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/5989425.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.dnkiaeh.asia/blog/7412193.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.dnkiaeh.asia/blog/5023264.sHtMl

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.dnkiaeh.asia/blog/3097347.sHtMl

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.dnkiaeh.asia/blog/7151793.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.dnkiaeh.asia/blog/8876513.sHtMl

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.dnkiaeh.asia/blog/0956272.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.dnkiaeh.asia/blog/3820384.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.dnkiaeh.asia/blog/8995084.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.dnkiaeh.asia/blog/8800560.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.dnkiaeh.asia/blog/6551411.sHtMl

原标题：golang redis zset 排行榜业务实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.dnkiaeh.asia/blog/2903410.sHtMl

原标题：Shell 脚本自动化命令编写
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.dnkiaeh.asia/blog/6895013.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.dnkiaeh.asia/blog/3597504.sHtMl

原标题：方案设计：统一错误处理架构全链路方案
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.dnkiaeh.asia/blog/8686083.sHtMl

原标题：golang gin 中间件执行顺序讲解
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.dnkiaeh.asia/blog/5693492.sHtMl

原标题：限流规则误拦截正常请求修复
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.dnkiaeh.asia/blog/5526944.sHtMl

原标题：golang redis set 集合去重业务
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.dnkiaeh.asia/blog/5503532.sHtMl

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.dnkiaeh.asia/blog/3361347.sHtMl

原标题：Cookie Session 会话状态管理
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.dnkiaeh.asia/blog/6325634.sHtMl

原标题：新手指南：本地多版本环境共存配置
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/4216729.sHtMl

原标题：缓存过期策略优化防业务故障
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.dnkiaeh.asia/blog/7959974.sHtMl

原标题：golang redis 计数器防超卖示例
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.dnkiaeh.asia/blog/8420067.sHtMl

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.dnkiaeh.asia/blog/9676896.sHtMl

原标题：CPU 亲和性配置负载均衡调度
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.dnkiaeh.asia/blog/1384196.sHtMl

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.dnkiaeh.asia/blog/5665722.sHtMl

原标题：golang grafana 监控面板简单配置
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.dnkiaeh.asia/blog/9799191.sHtMl

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.dnkiaeh.asia/blog/5912429.sHtMl

原标题：golang redis 缓存雪崩完整处理
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.dnkiaeh.asia/blog/6937632.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.dnkiaeh.asia/blog/6553929.sHtMl

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.dnkiaeh.asia/blog/7581406.sHtMl

原标题：快速上手简易网关转发逻辑模拟
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.dnkiaeh.asia/blog/4970204.sHtMl

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.dnkiaeh.asia/blog/9584989.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.dnkiaeh.asia/blog/0892270.sHtMl

原标题：多规则数据脱敏组件开发
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.dnkiaeh.asia/blog/6035487.sHtMl

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.dnkiaeh.asia/blog/9973126.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/2932349.sHtMl

原标题：项目脚手架模板生成工具
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/8380575.sHtMl

原标题：nodejs 进程间通信 IPC 实操
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.dnkiaeh.asia/blog/4788919.sHtMl

原标题：golang docker 部署 mongodb 开发环境
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.dnkiaeh.asia/blog/3631927.sHtMl

原标题：大文件导出内存溢出防护
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.dnkiaeh.asia/blog/9686431.sHtMl

原标题：golang mysql exists in 性能对比
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.dnkiaeh.asia/blog/2396077.sHtMl

四、架构设计｜Architecture
原标题：golang 项目目录分层规范设计
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.dnkiaeh.asia/blog/1503102.sHtMl

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.dnkiaeh.asia/blog/2711281.sHtMl

原标题：开发测试生产多环境配置区分
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.dnkiaeh.asia/blog/0198463.sHtMl

原标题：静态资源 404 路径打包修复
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/4869230.sHtMl

原标题：零基础理解读写分离基础思想
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.dnkiaeh.asia/blog/5866806.sHtMl

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.dnkiaeh.asia/blog/3166450.sHtMl

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.dnkiaeh.asia/blog/3472680.sHtMl

原标题：前端骨架屏提升页面体验
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.dnkiaeh.asia/blog/8519381.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.dnkiaeh.asia/blog/5331963.sHtMl

原标题：安全实践：最小权限原则数据库账号管控
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.dnkiaeh.asia/blog/1215939.sHtMl

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.dnkiaeh.asia/blog/0442040.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.dnkiaeh.asia/blog/3787658.sHtMl

原标题：Nginx 静态代理负载均衡全套配置
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.dnkiaeh.asia/blog/3146662.sHtMl

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.dnkiaeh.asia/blog/1017641.sHtMl

原标题：golang 协程泄露问题排查方法
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.dnkiaeh.asia/blog/3132946.sHtMl

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.dnkiaeh.asia/blog/0416868.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.dnkiaeh.asia/blog/2769571.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.dnkiaeh.asia/blog/8451273.sHtMl

?
