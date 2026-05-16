# test-ai

计划任务网站第一版（登录 + 任务增删改查）模板。

## 快速开始

```bash
npm install
npm start
```

启动后访问：`http://localhost:3000`

## 已实现功能

- 用户注册 / 登录（JWT）
- 任务新增、列表查询、编辑、删除
- 任务状态切换（todo / done）
- 简单前端页面（纯 HTML + JS）

## 接口列表

- `POST /api/auth/register`
- `POST /api/auth/login`
- `GET /api/tasks`
- `POST /api/tasks`
- `PUT /api/tasks/:id`
- `PATCH /api/tasks/:id/status`
- `DELETE /api/tasks/:id`
