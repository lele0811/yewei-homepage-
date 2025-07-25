# 部署说明 - Dr. Ye Wei 学术主页

## 快速部署选项

### 1. GitHub Pages (推荐 - 免费)

**步骤：**
1. 在GitHub上创建一个新仓库，命名为 `yewei-homepage` 或类似名称
2. 将所有文件上传到仓库
3. 在仓库设置中启用GitHub Pages
4. 选择从main分支部署
5. 几分钟后就能通过 `https://[你的用户名].github.io/yewei-homepage` 访问

**优点：**
- 完全免费
- 自动HTTPS
- 易于更新
- 可绑定自定义域名

### 2. Netlify (推荐 - 免费)

**步骤：**
1. 访问 netlify.com 并注册账户
2. 拖拽整个项目文件夹到Netlify部署区域
3. 自动获得类似 `https://amazing-site-123456.netlify.app` 的链接
4. 可以自定义子域名

**优点：**
- 部署极其简单
- 自动HTTPS
- 全球CDN加速
- 可绑定自定义域名

### 3. Vercel (免费)

**步骤：**
1. 访问 vercel.com 并注册
2. 上传项目文件
3. 自动部署并获得链接

### 4. Firebase Hosting (免费)

**步骤：**
1. 创建Firebase项目
2. 使用Firebase CLI部署
3. 获得 `https://项目名.web.app` 链接

## 建议的部署流程

### 最简单方式 - Netlify拖拽部署：

1. **准备文件**：
   - 确保 `weiye.jpg` 照片已放在 `assets` 文件夹中
   - 所有文件都在 `test-project` 文件夹内

2. **部署**：
   - 访问 [netlify.com](https://netlify.com)
   - 注册账户（可使用GitHub账户登录）
   - 将整个 `test-project` 文件夹拖拽到部署区域
   - 等待几分钟完成部署

3. **获得链接**：
   - 部署完成后会自动生成一个链接
   - 类似：`https://wonderful-curie-123456.netlify.app`
   - 可以在设置中自定义域名前缀

4. **更新网站**：
   - 修改文件后，重新拖拽文件夹即可更新

## 需要的文件清单

确保以下文件都在项目文件夹中：
- ✅ `index.html` - 主页面
- ✅ `styles.css` - 样式文件  
- ✅ `script.js` - 交互脚本
- ✅ `assets/weiye.jpg` - 您的照片
- ⚠️ `assets/member2.jpg` - Bo Peng照片 (需要添加)
- ⚠️ `assets/member3.jpg` - Wenjun Gao照片 (需要添加)  
- ⚠️ `assets/member4.jpg` - Liu Yang照片 (需要添加)

## 自定义域名 (可选)

如果您有自己的域名（如 `yewei.com`），可以：
1. 在域名提供商处设置CNAME记录
2. 在部署平台添加自定义域名
3. 自动获得SSL证书

## 联系方式

部署完成后，您就可以将链接分享给任何人：
- 🔗 直接访问链接即可查看您的学术主页
- 📱 完全响应式设计，手机电脑都适配
- ⚡ 快速加载，专业外观

## 推荐操作

**立即可做：**
1. 使用Netlify拖拽部署（5分钟内完成）
2. 获得可分享的链接
3. 后续添加团队成员照片即可

您希望我帮您选择哪种部署方式？Netlify是最简单快捷的选择。