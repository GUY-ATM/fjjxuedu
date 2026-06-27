# 福建财经政法大学课表
一款专为**福建财经政法大学**学生设计的课表查询应用，提供简洁高效的课程管理体验，仅适配安卓设备。
<img width="270" height="600" alt="微信图片_20260627162812_353_13" src="https://github.com/user-attachments/assets/e639f789-339c-4e42-9892-64c807a29096" />
<img width="270" height="600" alt="微信图片_20260627162001_350_13" src="https://github.com/user-attachments/assets/65e7e047-1994-4792-bde6-d1b4849d9ed7" />
<img width="270" height="600" alt="微信图片_20260627163410_354_13" src="https://github.com/user-attachments/assets/2e7c7bc0-a8b3-4f93-bf2f-1d4a34f470a1" />


## ✨ 功能特点

### 📅 课程展示
- **周视图课表**：直观展示每周课程安排，支持滑动切换周次
- **课程详情**：点击课程查看详细信息（教室、教师、课程代码）
- **日期滑轨**：顶部日期导航，快速切换查看不同日期课程

### 🎨 个性化定制
- **自定义配色**：支持5种课程颜色方案，打造专属课表风格
- **沉浸式界面**：全屏沉浸式设计，状态栏自动适配
- **壁纸设置**：支持自定义背景壁纸，美化课表界面

### 🔐 安全特性
- **数据加密**：使用 CryptoJS 和 JSEncrypt 对敏感数据进行加密存储
- **本地存储**：课程数据保存在本地，保护个人隐私

### 📱 便捷功能
- **离线使用**：无需网络即可查看课表
- **安卓专属适配**：针对性优化安卓系统显示与交互逻辑
- **响应式设计**：适配不同安卓屏幕尺寸设备

## 🛠️ 技术栈

| 分类 | 技术 |
| :--- | :--- |
| **框架** | uni-app (H5+ App) |
| **UI框架** | Tailwind CSS 3 |
| **图标库** | Font Awesome 5 |
| **加密库** | CryptoJS, JSEncrypt |
| **构建工具** | HBuilderX |
| **开发语言** | HTML5 + CSS3 + JavaScript |

## 📦 安装使用

### 📥 直接安装（推荐）
1. 访问 [Releases](https://github.com/GUY-ATM/福建财经政法大学课表/releases) 页面
2. 下载最新版本的 APK 文件
3. 在 Android 设备上安装并打开应用
4. 首次使用请导入课程表

### 🔧 从源码构建
#### 环境要求
- **HBuilderX**：版本 3.0+
- **Node.js**：版本 14.0+（可选，用于扩展开发）

#### 构建步骤
```
# 1. 克隆仓库
git clone https://github.com/GUY-ATM/福建财经政法大学课表.git

# 2. 使用 HBuilderX 打开项目
# 打开 HBuilderX → 文件 → 打开目录 → 选择项目文件夹

# 3. 运行项目
# 方法一：运行到浏览器
# 工具栏 → 运行 → 运行到浏览器 → 选择浏览器

# 方法二：运行到安卓手机（需要 USB 连接）
# 工具栏 → 运行 → 运行到手机或模拟器 → 选择安卓设备

# 方法三：云打包（生成安卓 APK 安装包）
# 工具栏 → 发行 → 原生App-云打包 → Android → 填写配置 → 打包
```
📁 项目结构
```
plaintext
福建财经政法大学课表/
├── kebiao.html           # 主页面（课表展示）
├── kebiao1.html          # 课程详情页面
├── colors.html           # 配色方案设置页面
├── wallpaper.html        # 壁纸设置页面
├── manifest.json         # 应用配置文件（关键配置）
├── androidPrivacy.json   # Android 隐私政策配置
├── encrypt.js            # 加密工具函数
├── swipe-control.css     # 滑动控制样式
├── .gitignore            # Git 忽略配置
├── README.md             # 项目说明文档
├── LICENSE               # 许可证文件
├── css/                  # 样式文件目录
│   └── all.main.css.js   # 主样式文件
├── img/                  # 图片资源目录
│   ├── 1.png, 2.png, 3.png   # 应用图标和启动图
│   └── view/             # 视图相关图片
├── libs/                 # 第三方库目录
│   ├── css/              # Font Awesome 样式
│   ├── webfonts/         # Font Awesome 字体文件
│   ├── tailwindcss.js    # Tailwind CSS 库
│   ├── crypto-js.min.js  # CryptoJS 加密库
│   ├── jsencrypt.min.js  # JSEncrypt 加密库
│   ├── chart.umd.min.js  # 图表库
│   └── forge.min.js      # 加密工具
├── static/               # 静态资源目录
│   ├── fwxy.html         # 服务协议页面
│   ├── fwxy.txt          # 服务协议文本
│   ├── xszc.txt          # 学生守则
│   └── yszc.html         # 用户协议页面
└── unpackage/            # 构建产物目录
    ├── release/apk/      # APK 安装包（发布用）
    ├── cache/            # 缓存文件（已忽略）
    └── resources/        # 资源文件（已忽略）
```
🤝 贡献指南
欢迎提交 Issue 和 Pull Request！

📜 许可证
本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情
注意：本应用仅供福建财经政法大学学生学习交流使用，请勿用于商业用途。
