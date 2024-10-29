## 项目简介

这是基于Django框架开发的知识图谱展示系统，主要用于展示测试节点的图片属性。系统底层使用neo4j作为知识图谱数据库，关系型数据库使用sqlite，也可以换成mysql，主要用于图谱展示与问答。

## 主要功能

- 用户登录、注册和退出功能
- 图谱展示：支持三元组方式查询
- 图谱查询：通过开始节点、关系和结束节点进行查询
- 展示结果：展示节点名称、ID和图片


## 技术架构

- 前端：HTML、CSS、JS
- 后端：Django
- 数据库：Neo4j（图谱）、SQLite（关系型）
- 图谱展示：ECharts


## 使用说明

1. 克隆项目：`git clone https://github.com/username/project.git`
2. 安装依赖项：`python manage.py dependencies`
3. 运行项目：`python manage.py runserver`

## 联系方式

微信号：zt745324325