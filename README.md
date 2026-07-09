---

## 🗄 数据库设计

### user_tb（用户表）

| 字段     | 类型      | 说明     |
|--------|-----------|----------|
| id     | bigint    | 主键     |
| username | varchar | 用户名   |
| password | varchar | 密码     |
| role   | varchar   | 角色     |

### score_tb（成绩表）

| 字段        | 类型      | 说明       |
|-----------|-----------|------------|
| id        | bigint    | 主键       |
| student_name | varchar | 学生姓名   |
| subject   | varchar   | 科目       |
| score     | int       | 成绩       |
| exam_time | date      | 考试时间   |

---

## 🔮 可扩展方向

- ✅ JWT 登录鉴权
- ✅ 文件上传（Excel 导入成绩）
- ✅ RBAC 权限控制
- ✅ ECharts 成绩统计图表
- ✅ Redis 缓存优化
- ✅ Swagger 接口文档
- ✅ Docker 容器化部署
- ✅ 单元测试（JUnit）

---

## 📚 实训知识点

- Spring Boot 项目搭建
- RESTful API 设计规范
- MyBatis‑Plus CRUD
- Vue 组件化开发
- Axios 前后端通信
- 跨域问题解决
- 统一返回结果封装
- 全局异常处理
- 分页查询实现
- 前后端联调流程

---

## 👨‍💻 开发信息

- 作者：[Your Name]
- 时间：2026 年
- 用途：课程设计 / 实训项目

---

## 📄 License

This project is licensed under the MIT License.
