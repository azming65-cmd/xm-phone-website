# 杭州境树网络科技有限公司 - 专业手机销售平台

这是一个专业的手机销售平台前端项目，提供完整的电商购物体验。

## 功能特性

- 🛍️ 产品展示和搜索
- 📱 产品详情页面
- 🛒 购物车功能
- 💳 订单确认页面
- 📱 响应式设计
- 🎨 现代化UI界面

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- 响应式设计

## 部署到Railway

### 1. 准备项目
```bash
# 确保所有文件都在项目根目录
# 包括: index.html, checkout.html, product-detail.html, images/ 等
```

### 2. 推送到GitHub
```bash
git init
git add .
git commit -m "Initial commit: Frontend deployment"
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
```

### 3. 在Railway部署
1. 访问 [railway.app](https://railway.app)
2. 连接GitHub仓库
3. 选择项目根目录
4. 配置环境变量（如需要）
5. 部署

## 项目结构

```
├── index.html              # 首页
├── checkout.html           # 订单确认页
├── product-detail.html     # 产品详情页
├── images/                 # 图片资源
├── package.json            # 项目配置
├── railway.json            # Railway部署配置
└── README.md              # 项目说明
```

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 或直接使用serve
npx serve -s . -l 3000
```

## 环境变量

当前版本无需环境变量，所有配置都在代码中。

## 注意事项

- 这是一个纯前端项目
- 所有数据都是静态的
- 支付功能需要后端支持
- 图片资源需要确保路径正确

## 更新日志

### v1.0.0
- 初始版本发布
- 包含完整的电商前端功能
- 支持Railway部署