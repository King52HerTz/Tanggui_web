# 唐朝诡事录 - 古风探案主题网站

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

这是一个基于热门剧集《唐朝诡事录》设计的古风探案主题网站，融合了现代前端技术与唐代美学元素，打造沉浸式探案体验。

## ✨ 项目亮点

- **古风美学设计**：融合唐代建筑、书画、服饰等元素，打造沉浸式视觉体验
- **响应式布局**：适配桌面端和移动端，提供一致的用户体验
- **交互丰富**：3D轮播图、动画效果、角色卡片、视频播放等交互功能
- **主题特色**：日夜模式切换、水墨背景、卷轴式UI设计
- **内容完整**：涵盖剧情简介、诡案录、角色卷宗、精彩内容等多个模块

## 🏗️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构与内容 |
| CSS3 | 样式设计与布局 |
| JavaScript | 交互逻辑与动态效果 |
| Font Awesome | 图标库 |
| Google Fonts | 字体库 |
| Canvas | 水墨背景与特效 |

## 📁 项目结构

```
唐朝诡事录/
├── index.html          # 首页（剧情简介）
├── guian.html          # 诡案录
├── people.html         # 角色卷宗
├── jingcai.html        # 精彩内容
├── lianxi.html         # 联系我们
├── caidan.html         # 彩蛋页面
├── login.html          # 登录页面
├── register.html       # 注册页面
├── game.html           # 迷宫小游戏
├── css/                # 样式文件夹
│   ├── common.css      # 通用样式
│   ├── index.css       # 首页样式
│   ├── guian.css       # 诡案录样式
│   ├── people.css      # 角色卷宗样式
│   ├── jingcai.css     # 精彩内容样式
│   ├── lianxi.css      # 联系我们样式
│   ├── caidan.css      # 彩蛋页面样式
│   ├── login.css       # 登录页面样式
│   └── register.css    # 注册页面样式
├── JS/                 # JavaScript文件夹
│   ├── index.js        # 首页脚本
│   ├── guian.js        # 诡案录脚本
│   ├── people.js       # 角色卷宗脚本
│   ├── jingcai.js      # 精彩内容脚本
│   ├── lianxi.js       # 联系我们脚本
│   ├── caidan.js       # 彩蛋页面脚本
│   ├── login.js        # 登录页面脚本
│   └── register.js     # 注册页面脚本
├── images/             # 图片资源
├── jingcai-images/     # 精彩内容图片
├── vedio/              # 视频资源
├── music/              # 音乐资源
├── card-html/          # 案件详情页面
└── renwu-html/         # 人物扩展页面
```

## 🚀 功能模块

### 1. 首页（剧情简介）
- 3D立体轮播图展示剧照
- 视频背景播放
- 经典语录展示
- 响应式导航栏

### 2. 诡案录
- 案件卡片式展示
- 案件分类筛选（凶杀疑案、灵异事件、宫廷阴谋）
- 关键词搜索功能
- 案件详情跳转

### 3. 角色卷宗
- 角色卡片交互展示
- 模态框查看角色详情
- 角色属性数据可视化
- 人物关系图展示

### 4. 精彩内容
- 3D轮播图
- 视频片段播放
- 剧照集锦展示
- 鼠标悬停效果

### 5. 联系我们
- 日夜模式切换
- 卷轴式UI设计
- 留言表单
- 设计思路展示

### 6. 彩蛋页面
- Q版人物互动
- 隐藏彩蛋探索
- 音乐播放控制
- 古风特效装饰

### 7. 迷宫小游戏
- 随机迷宫生成
- 键盘操控移动
- 自动寻路算法
- 步数统计显示

## 🎨 设计特色

### 视觉风格
- **色彩搭配**：以朱红、墨黑、素白为主，辅以金、青等传统色
- **字体选择**：使用"Ma Shan Zheng"等书法字体，体现唐代风韵
- **装饰元素**：云纹、卷轴、印章、水墨、灯笼等传统元素

### 交互体验
- **动画效果**：缓动动画、悬浮效果、过渡动画
- **响应式反馈**：按钮点击效果、表单验证提示
- **主题切换**：日夜模式、音乐控制

### 内容组织
- **信息架构清晰**：导航明确，内容分类合理
- **深度与广度平衡**：既有概括性介绍，也有详细内容
- **多媒体融合**：图文并茂，视频音频辅助

## 🔧 快速开始

### 本地运行
1. 克隆项目到本地：
   ```bash
   git clone https://github.com/yourusername/tang-dynasty-mystery.git
   ```

2. 进入项目目录：
   ```bash
   cd tang-dynasty-mystery
   ```

3. 使用本地服务器运行（推荐使用VS Code的Live Server插件）：
   ```bash
   # 如果没有安装http-server，先安装
   npm install -g http-server
   
   # 启动本地服务器
   http-server
   ```

4. 在浏览器中访问：
   ```
   http://localhost:8080
   ```

### 在线访问
将项目部署到GitHub Pages或其他静态网站托管服务。

## 📱 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- 移动端主流浏览器

## 🛠️ 开发说明

### 代码规范
- **HTML**：语义化标签，合理嵌套结构
- **CSS**：BEM命名规范，模块化组织
- **JavaScript**：ES6+语法，函数式编程

### 扩展建议
1. **性能优化**：图片懒加载，代码分割
2. **功能增强**：用户评论系统，案件时间线
3. **交互深化**：案件推理小游戏，角色养成系统
4. **移动端优化**：触摸手势，PWA支持

## 🤝 贡献指南

欢迎提交Issue和Pull Request！

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

## 🙏 致谢

- 感谢《唐朝诡事录》制作团队创作出如此精彩的作品
- 感谢所有开源项目提供的技术支持和灵感
- 感谢所有参与测试和反馈的用户

## 📞 联系我们

如有问题或建议，请通过GitHub Issues提交反馈。

---

**温馨提示**：本项目为学习交流用途，所有影视相关内容版权归原制作方所有。

*创作于大一时期，记录学习前端开发的成长历程*
