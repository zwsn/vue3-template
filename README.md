# Vue3-template

🌟 基于 Vue 3、Vite 5、VueRouter 4、Tailwind CSS、Eslint 9 和 Prettier 创建的 Vue 项目最小模板，开箱即用。

## 功能

* **自动导入**：使用 `unplugin-auto-import`​ 和 `unplugin-vue-components`​ 实现组件和库的自动导入。
* **Axios 集成**：在 `/src/utils/request.js`​ 中配置了网络请求库 Axios，简化 HTTP 请求。
* **Vue Router 4**：在 `/src/router/index.js`​ 中配置了路由管理。
* **Tailwind CSS**：预配置的 Tailwind CSS 用于实用优先的 CSS 样式。
* **代码质量**：使用 Eslint 9 和 Prettier 强制执行代码规范。

## 快速开始

1. **克隆仓库**：

    ```sh
    https://github.com/zwsn/vue3-template.git
    ```
2. **安装依赖**：

    ```sh
    cd vue3-template
    npm install
    ```
3. **运行开发服务器**：

    ```sh
    npm run dev
    ```

## 项目结构

```arduino
vue3-template/
├── src
│   ├── router
│   │   └── index.js       // 路由配置
│   ├── utils
│   │   └── request.js     // Axios配置
│   └── views
│       └── Index
│           └── index.vue // 首页
├── tailwind.config.js    // Tailwind CSS 配置
└── vite.config.js        // Vite配置
```

## 配置详情

### 自动导入

* **unplugin-auto-import**：自动导入常用 API。
* **unplugin-vue-components**：自动导入 Vue 组件。

### 网络请求

* **Axios**：在 `/src/utils/request.js`​ 中预配置了 Axios 实例，用于发送 HTTP 请求。

### 路由管理

* **Vue Router 4**：在 `/src/router/index.js`​ 中设置了路由管理，包含示例路由，帮助你快速上手。

### 样式

* **Tailwind CSS**：预配置的 Tailwind CSS，提供实用优先的 CSS 样式。

### 代码质量

* **Eslint 9**：确保代码质量和一致性。
* **Prettier**：自动格式化代码，保持代码风格统一。

## 脚本命令

* ​**​`npm run dev`​**​：启动开发服务器。
* ​**​`npm run build`​**​：构建生产环境项目。
* ​**​`npm run lint`​**​：运行 Eslint 检查代码质量。
* ​**​`npm run format`​**​：运行 Prettier 格式化代码。

## 贡献

欢迎贡献！请 fork 仓库并提交 pull request。
