# StudyFlow

个人学习任务编排系统：课表导入、任务管理与学习计划。

## 当前进度

V0 开发中。后端已完成基础项目初始化，并提供健康检查接口。

## 技术基线

- Java 21 LTS
- Spring Boot 4.1.1
- Maven Wrapper

## 启动后端

请先安装 Java 21，并在终端中执行：

```bash
cd backend
./mvnw spring-boot:run
```

后端默认运行在 `http://localhost:8080`。

## 健康检查

服务启动后，访问：

```text
http://localhost:8080/api/v1/health
```

预期返回的 JSON 包含 `status: "UP"` 与当前时间。

## 运行测试

```bash
cd backend
./mvnw test
```
