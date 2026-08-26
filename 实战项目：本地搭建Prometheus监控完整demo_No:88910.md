最新前沿技术资讯

一、入门教程｜Getting Started
原标题：实战项目：本地搭建Prometheus监控完整demo
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.5giki2.asia/arts/865976.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.5giki2.asia/arts/480114.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.5giki2.asia/arts/343127.Doc

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.5giki2.asia/arts/630140.Doc

原标题：golang 配置文件多环境加载
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.5giki2.asia/arts/866825.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.5giki2.asia/arts/563255.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.5giki2.asia/arts/936677.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.5giki2.asia/arts/684765.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.5giki2.asia/arts/714581.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.5giki2.asia/arts/380830.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.5giki2.asia/arts/900870.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.5giki2.asia/arts/813030.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.5giki2.asia/arts/539181.Doc

原标题：golang docker 部署 redis 配置要点
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.5giki2.asia/arts/906677.Doc

原标题：重复提交幂等防护再次讲解
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.5giki2.asia/arts/903580.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.5giki2.asia/arts/740358.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.5giki2.asia/arts/996323.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.5giki2.asia/arts/858874.Doc

原标题：golang url 参数编码处理方案
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.5giki2.asia/arts/526574.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.5giki2.asia/arts/462905.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.5giki2.asia/arts/839403.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.5giki2.asia/arts/598284.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.5giki2.asia/arts/444137.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.5giki2.asia/arts/713827.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.5giki2.asia/arts/354449.Doc

原标题：零基础理解模块化与组件化基础思想
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.5giki2.asia/arts/017764.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.5giki2.asia/arts/568979.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.5giki2.asia/arts/177886.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.5giki2.asia/arts/290250.Doc

原标题：安全组端口开放网络访问
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.5giki2.asia/arts/717778.Doc

原标题：golang es 索引生命周期管理思路
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.5giki2.asia/arts/304097.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.5giki2.asia/arts/377935.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.5giki2.asia/arts/897923.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.5giki2.asia/arts/663041.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.5giki2.asia/arts/055277.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.5giki2.asia/arts/930056.Doc

原标题：golang elasticsearch 索引设计思路
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.5giki2.asia/arts/422697.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.5giki2.asia/arts/937187.Doc

原标题：golang 大文件 http 下载服务
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.5giki2.asia/arts/781327.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.5giki2.asia/arts/845278.Doc


二、踩坑排错｜Troubleshooting
原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.5giki2.asia/arts/228579.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.5giki2.asia/arts/041883.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.5giki2.asia/arts/362723.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.5giki2.asia/arts/835308.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.5giki2.asia/arts/352976.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.5giki2.asia/arts/147138.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.5giki2.asia/arts/607540.Doc

原标题：golang makefile 自动化构建脚本
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.5giki2.asia/arts/595594.Doc

原标题：golang redis pipeline 原子性说明
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.5giki2.asia/arts/403179.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.5giki2.asia/arts/174531.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.5giki2.asia/arts/230874.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.5giki2.asia/arts/644290.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.5giki2.asia/arts/713794.Doc

原标题：前后端交互跨域问题完整处理
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.5giki2.asia/arts/220096.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.5giki2.asia/arts/011403.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.5giki2.asia/arts/486320.Doc

原标题：缓存穿透防护保护数据库
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.5giki2.asia/arts/383633.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.5giki2.asia/arts/899381.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.5giki2.asia/arts/595515.Doc

原标题：golang 项目目录分层规范设计
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.5giki2.asia/arts/498545.Doc

原标题：Docker 容器时区错误修复方案
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.5giki2.asia/arts/655314.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.5giki2.asia/arts/593137.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.5giki2.asia/arts/147642.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.5giki2.asia/arts/784552.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.5giki2.asia/arts/415495.Doc

原标题：开发代理服务网络限制解决
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.5giki2.asia/arts/410767.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.5giki2.asia/arts/864135.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.5giki2.asia/arts/374191.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.5giki2.asia/arts/775789.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.5giki2.asia/arts/204023.Doc

原标题：golang kafka offset 提交策略
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.5giki2.asia/arts/891327.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.5giki2.asia/arts/121257.Doc

原标题：MySQL 慢查询索引优化实战
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.5giki2.asia/arts/770127.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.5giki2.asia/arts/903118.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.5giki2.asia/arts/969219.Doc

原标题：主干开发团队代码合并策略
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.5giki2.asia/arts/172951.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.5giki2.asia/arts/820694.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.5giki2.asia/arts/992142.Doc

原标题：golang redis 地理位置 geo 使用
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.5giki2.asia/arts/357885.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.5giki2.asia/arts/852928.Doc

三、实战开发｜Practice
原标题：golang 系统设计容器健康检查设计思路
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.5giki2.asia/arts/292804.Doc

原标题：GraphQL 接口查询优化实操
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.5giki2.asia/arts/232331.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.5giki2.asia/arts/059665.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.5giki2.asia/arts/907686.Doc

原标题：golang 分布式锁 redis 实现
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.5giki2.asia/arts/423300.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.5giki2.asia/arts/668260.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.5giki2.asia/arts/093765.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.5giki2.asia/arts/736551.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.5giki2.asia/arts/421072.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.5giki2.asia/arts/222146.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.5giki2.asia/arts/854219.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.5giki2.asia/arts/943841.Doc

原标题：golang 集成测试启动测试数据库
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.5giki2.asia/arts/546489.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.5giki2.asia/arts/299842.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.5giki2.asia/arts/488957.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.5giki2.asia/arts/536122.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.5giki2.asia/arts/377234.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.5giki2.asia/arts/481108.Doc

原标题：webpack chunk 分包策略详解
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.5giki2.asia/arts/238937.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.5giki2.asia/arts/445381.Doc

原标题：包管理器依赖冲突解决方案
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.5giki2.asia/arts/407271.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.5giki2.asia/arts/764642.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.5giki2.asia/arts/933775.Doc

原标题：golang 系统设计防爬虫简单策略
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.5giki2.asia/arts/305029.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.5giki2.asia/arts/952808.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.5giki2.asia/arts/130101.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.5giki2.asia/arts/664090.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.5giki2.asia/arts/584245.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.5giki2.asia/arts/990131.Doc

原标题：golang base64 编码解码实操
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.5giki2.asia/arts/452460.Doc

原标题：开源项目本地运行排错完整清单
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.5giki2.asia/arts/907956.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.5giki2.asia/arts/937988.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.5giki2.asia/arts/123668.Doc

原标题：golang cron 定时任务防并发执行
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.5giki2.asia/arts/811253.Doc

原标题：版本升级服务启动失败处理
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.5giki2.asia/arts/154845.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.5giki2.asia/arts/340692.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.5giki2.asia/arts/007897.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.5giki2.asia/arts/691326.Doc

原标题：大文件导出内存溢出防护
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.5giki2.asia/arts/169360.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.5giki2.asia/arts/337278.Doc

四、架构设计｜Architecture
原标题：golang 分页查询封装通用工具
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.5giki2.asia/arts/444578.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.5giki2.asia/arts/774801.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.5giki2.asia/arts/899761.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.5giki2.asia/arts/236705.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.5giki2.asia/arts/152050.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.5giki2.asia/arts/256277.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.5giki2.asia/arts/260177.Doc

原标题：序列化版本不一致解析失败
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.5giki2.asia/arts/885353.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.5giki2.asia/arts/412312.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.5giki2.asia/arts/716491.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.5giki2.asia/arts/474678.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.5giki2.asia/arts/058649.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.5giki2.asia/arts/053109.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.5giki2.asia/arts/669984.Doc

原标题：golang 系统设计灰度发布实现思路
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.5giki2.asia/arts/559943.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.5giki2.asia/arts/151352.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.5giki2.asia/arts/637646.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.5giki2.asia/arts/718892.Doc

?
