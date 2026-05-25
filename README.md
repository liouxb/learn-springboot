# learn-springboot
learn spring-boot project
1. 添加readme文件
2.springboot项目结构
```
your-project/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── yourcompany/
│   │   │           └── yourproject/
│   │   │               ├── YourProjectApplication.java  # 启动类（必须放根目录）
│   │   │               ├── config/        # 配置类：跨域、MyBatis、Redis、线程池等
│   │   │               ├── controller/    # 控制层：接口入口，接收请求
│   │   │               ├── service/       # 业务逻辑层
│   │   │               │   └── impl/     # 业务实现类
│   │   │               ├── mapper/       # 数据访问层：DAO，操作数据库
│   │   │               ├── entity/        # 实体类：数据库表映射对象
│   │   │               ├── dto/          # 数据传输对象：接收前端参数
│   │   │               ├── vo/           # 视图对象：返回给前端的数据
│   │   │               ├── common/       # 公共模块
│   │   │               │   ├── result/   # 统一返回结果封装
│   │   │               │   └── exception/# 全局异常处理
│   │   │               └── util/         # 工具类：日期、加密、校验等
│   │   └── resources/
│   │       ├── application.yml           # 主配置文件（核心）
│   │       ├── application-dev.yml       # 开发环境配置
│   │       ├── application-prod.yml      # 生产环境配置
│   │       ├── mapper/                   # MyBatis XML 文件（可选）
│   │       └── static/                   # 静态资源：html、css、js
│   └── test/                             # 单元测试
├── pom.xml                               # 依赖管理
└── README.md                             # 项目说明
```
