# SQL 10 Minutes Playground

《SQL 必知必会》配套练习环境 · 单文件 HTML，打开即用。

## 功能
- 内嵌 SQLite（WebAssembly），无需安装、无需服务器
- 支持 SQLite / MySQL / SQL Server / Oracle / PostgreSQL 方言高亮与切换（记忆上次选择）
- 自动补全、查询历史、一键执行（Ctrl+Enter）
- 58 道配套挑战题（已中文化）与答案，可一键加载运行
- 表 / 视图快捷查询、右键删除、查看结构
- 阅读进度、笔记、编辑器内容自动保存在浏览器 localStorage

## 使用
- 直接双击打开 `index.html` 即可使用全部功能
- 阅读功能：点击「📂 导入 PDF」加载你自己的 PDF（本仓库不包含任何书籍正文内容）

## 部署到 GitHub Pages
1. 将本仓库推送至 GitHub
2. 仓库 Settings → Pages → Source 选择 `Deploy from a branch` → 分支 `main`、目录 `/ (root)`
3. 完成后访问 `https://<你的用户名>.github.io/sql-10-minutes-playground/`

## 版权声明
- 本项目代码以 [MIT License](LICENSE.md) 开源
- 挑战题来源于《SQL 必知必会》官方配套页面：https://forta.com/books/0135182794/challenges （题目已中文化改写，版权归原书作者与出版社所有）
- 示例数据库建表 / 填充脚本来自官方配套资源：http://forta.com/books/0135182794/
- 本仓库不包含《SQL 必知必会》正文 PDF，请自行导入你拥有的正版 PDF，仅供个人学习使用
