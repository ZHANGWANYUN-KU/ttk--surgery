# 疼痛科手术排程系统 - 豪华版

**Pain Department Surgery Schedule System Pro**

## 🎯 简介

这是一个功能完整的医院手术排程管理系统，为疼痛科专门设计。通过该系统，您可以轻松管理所有手术计划。

## ✨ 主要功能

- **CRUD操作** - 新增、编辑、删除、查看手术记录
- **多视图模式** - 列表视图、时间线视图、日历视图
- **高级过滤** - 按日期、患者名、医生、手术类型、状态过滤
- **数据导入导出** - 支持 CSV 和 JSON 格式
- **实时统计** - 总手术数、待术、术中、已完成等数据实时显示
- **医生工作量分析** - 展示各医生的手术负荷
- **手术间利用率** - 追踪各手术间的使用情况
- **主题切换** - 支持深色/浅色主题
- **本地存储** - 所有数据用浏览器 localStorage 保存，自动备份

## 🚀 快速开始

### 在线访问
直接在浏览器中打开 `index.html` 文件即可使用，无需后端服务器。

### 本地使用
```bash
# 克隆或下载此仓库
git clone https://github.com/ZHANGWANYUN-KU/surgery-scheduler.git

# 用浏览器打开 index.html
open index.html
```

## 📊 系统包含

- **样本数据** - 预加载 3 个手术案例用于演示
- **响应式设计** - 适配各种屏幕尺寸
- **无依赖部署** - 纯 HTML/CSS/JavaScript，无需后端

## 🛠️ 技术栈

- **React 18** - UI 框架
- **Tailwind CSS** - 样式库
- **Babel** - JSX 转译
- **localStorage** - 数据持久化

## 💾 数据管理

所有手术数据存储在浏览器的 localStorage 中：
- **自动保存** - 任何修改自动保存
- **数据备份** - 支持 JSON 导出备份
- **数据恢复** - 支持 JSON 导入恢复

## 📱 浏览器兼容性

- Chrome/Edge (推荐)
- Firefox
- Safari
- 移动浏览器

## 📄 许可证

MIT License

---

**开发者**: Surgery Scheduler Team  
**最后更新**: 2026-03-29
