# WebNav Hub 🇺🇦

一个融入乌克兰国旗色彩元素的现代化网址导航站点，采用圆形卡片设计和响应式布局。

## ✨ 项目特色

### 🎨 设计亮点
- **乌克兰色彩主题**: 深度融入乌克兰国旗的蓝色(#005BBB)和黄色(#FFD700)
- **圆形卡片设计**: 摒弃传统长方形，采用现代圆形卡片布局
- **动态视觉效果**: 旋转边框动画、渐变背景和光晕效果
- **响应式布局**: 完美适配桌面、平板和手机设备

### 🌟 功能特性
- **6大分类导航**: AI搜索、社交媒体、实用工具、科技资讯、云存储、电子邮箱
- **平滑滚动**: 点击导航自动滚动到对应分类
- **URL哈希支持**: 支持通过URL直接定位到特定分类
- **粘性导航**: 导航栏在滚动时保持顶部固定
- **Font Awesome图标**: 为每个网站配备精美图标

## 🚀 快速开始

### 本地运行

#### 方法一：使用Python
```bash
# 进入项目目录
cd ge

# 启动HTTP服务器
python -m http.server 8000

# 在浏览器访问
http://localhost:8000
```

#### 方法二：使用Node.js
```bash
# 进入项目目录
cd ge

# 启动服务器
npx serve .

# 按提示访问显示的URL
```

#### 方法三：使用VS Code Live Server
1. 安装 Live Server 插件
2. 右键 `index.html` 选择 "Open with Live Server"

### 在线部署

#### GitHub Pages 部署
1. 将项目推送到GitHub仓库
2. 进入仓库设置 → Pages
3. 选择部署分支（通常是main）
4. 等待部署完成

#### Vercel 部署
1. 访问 [Vercel](https://vercel.com)
2. 连接GitHub仓库
3. 一键部署

#### Netlify 部署
1. 访问 [Netlify](https://netlify.com)
2. 拖拽项目文件夹到部署区域
3. 自动部署完成

## 📁 项目结构

```
ge/
│
├── index.html          # 主页面文件（包含HTML、CSS、JS）
├── README.md          # 项目说明文档
└── 其他资源文件...
```

## 🎯 分类内容

### 🤖 AI搜索
包含40+个AI工具和搜索平台：
- **主流AI**: ChatGPT、Claude、Gemini、Kimi等
- **国产AI**: 通义千问、文心一言、豆包、腾讯元宝等
- **开发工具**: OpenRouter、Websim、v0等

### 📱 社交媒体  
社交平台和相关工具：
- **社交平台**: Facebook、Twitter、Instagram、Reddit等
- **视频下载**: Y2mate、Cobalt、Savefrom等
- **部署平台**: Vercel、Netlify、Railway等

### 🛠️ 实用工具
50+个在线工具：
- **域名服务**: Cloudflare、dynv6、免费域名等
- **开发工具**: Cursor、PicGo、图片处理等
- **网络工具**: 代理服务、IP查询、DNS工具等

### 📰 科技资讯
权威科技新闻源：
- TechCrunch、Wired、The Verge等

### ☁️ 云存储
主流云存储服务：
- Google Drive、Dropbox、OneDrive、MEGA等

### 📧 电子邮箱
邮箱服务提供商：
- Gmail、Outlook、ProtonMail、临时邮箱等

## 🎨 定制化

### 修改颜色主题
在CSS中修改以下变量：
```css
:root {
  --ukraine-blue: #005BBB;        /* 主蓝色 */
  --ukraine-yellow: #FFD700;      /* 主黄色 */
  --ukraine-light-blue: #0066cc;  /* 浅蓝色 */
  --ukraine-dark-blue: #003d82;   /* 深蓝色 */
}
```

### 添加新的网站链接
在HTML中复制现有的卡片结构：
```html
<div class="link-card">
  <a href="网站URL" target="_blank"></a>
  <i class="fa-solid fa-图标名称"></i>
  <h3>网站名称</h3>
</div>
```

### 修改分类
1. 更新导航栏中的链接
2. 添加对应的分类标题
3. 创建新的link-grid区域

## 🔧 技术栈

- **HTML5**: 页面结构
- **CSS3**: 样式设计（包含响应式布局）
- **Vanilla JavaScript**: 交互功能
- **Font Awesome**: 图标库
- **无框架依赖**: 纯静态页面，易于部署

## 📱 响应式设计

### 断点设置
- **桌面端**: > 1200px
- **平板端**: 768px - 1200px  
- **手机端**: 480px - 768px
- **小屏手机**: < 480px

### 卡片尺寸适配
- **桌面**: 7.5rem × 7.5rem
- **平板**: 6.5rem × 6.5rem
- **手机**: 5.5rem × 5.5rem
- **小屏**: 5rem × 5rem

## 🚀 性能优化

- **纯静态**: 无服务器依赖，加载速度快
- **CDN图标**: 使用Font Awesome CDN
- **CSS优化**: 合理使用渐变和动画
- **响应式图片**: 适配不同屏幕密度

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🌟 致谢

- 感谢 [Font Awesome](https://fontawesome.com/) 提供精美图标
- 感谢所有收录网站的优质服务
- 特别致敬乌克兰的坚韧与勇气 🇺🇦

## 📞 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 提交 Issue
- 发起 Pull Request
- 邮箱联系（如有提供）

---

**WebNav Hub** - 让网址导航更美好 ✨