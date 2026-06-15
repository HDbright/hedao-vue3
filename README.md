

## 平台简介

* 本仓库为前端技术栈 [Vue3](https://v3.cn.vuejs.org) + [Element Plus](https://element-plus.org/zh-CN) + [Vite](https://cn.vitejs.dev) 版本。
* 配套后端代码仓库地址[hedao-vue](https://gitee.com/hdbright/hedao-vue) 或 [hedao-vue-fast](https://gitcode.com/hdbright/hdedao-vue-fast) 版本。


# 版本对比

hedao-vue 前端项目的三个主要演进版本，方便你直观对比其技术栈差异（并行开发维护）。

| 项目名称      | **hedao-vue** | **hedao-vue3** | **hedao-vue3-TypeScript**   |
| :---          | :---          | :---           | :---                        |
| **前端框架**  | Vue 2        | Vue 3          | Vue 3                       |
| **脚本语言**  | JavaScript   | JavaScript     | TypeScript                  |
| **构建工具**  | Vue CLI      | Vite           | Vite                        |
| **UI 组件库** | Element UI   | Element Plus   | Element Plus                |
| **状态管理**  | Vuex         | Pinia          | Pinia                       |
| **路由管理**  | Vue Router 3 | Vue Router 4   | Vue Router 4                |
| **核心特点**  | 1. 技术栈经典稳定<br>2. 社区资料丰富<br>3. 当前维护重心已转移 | 1. 现代前端技术栈<br>2. 开发体验与性能更优<br>3. 官方主推的活跃版本 | 1. 类型加持，减少沟通成本<br>2. 开发时有提示，效率更高<br>3. 多人协作企业级开发项目 |
| **仓库地址**  | [hedao-vue](https://gitee.com/hdbright/hedao-vue) | [hedao-vue3](https://gitcode.com/hdbright/hedao-vue3) | [hedao-vue3-TypeScript](https://gitcode.com/hdbright/hedao-vue3/tree/typescript) |

## 前端运行

```bash
# 克隆项目
git clone https://github.com/hdbright/hedao-vue3.git

# 进入项目目录
cd hedao-vue3

# 安装依赖
yarn --registry=https://registry.npmmirror.com

# 启动服务
yarn dev

# 构建测试环境 yarn build:stage
# 构建生产环境 yarn build:prod
# 前端访问地址 http://localhost:80
```

## 内置功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16. 缓存监控：对系统的缓存信息查询，命令统计等。
17. 在线构建器：拖动表单元素生成相应的HTML代码。
18. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。

## 在线体验

- admin/admin123  
- 陆陆续续收到一些打赏，为了更好的体验已用于演示服务器升级。谢谢各位小伙伴。

演示地址：http://vue.ruoyi.vip  
文档地址：http://doc.ruoyi.vip



