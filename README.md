# Ultra-AcadHomepage

> 🧠 A deeply customized academic homepage template — developed by [Zhenliang Gan](https://github.com/GanZhenliang).

**Ultra-AcadHomepage** 是一个基于 [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io) 模板的深度定制版本，专为学术个人主页设计，具备模块化配置、美观简洁、双语支持等特性，适合研究者、开发者和学生展示自己的学术背景与成果。

超级学术主页模板[Demo](http://www.zlgan.top/Ultra-AcadHomepage/)

---

## 🌟 Features 特性

- 🎓 极简美观的学术主页风格
- 🌐 中英文双语支持，自动切换
- 📱 响应式布局，兼容桌面与移动端
- ⚙️ GitHub Pages 一键部署，支持自定义域名
- 🧩 模块化内容配置，基于 `_data` 和 `_pages` 文件夹
- 💡 支持时间轴、项目展示卡片、荣誉奖项等自定义组件

---

## 🚀 Quick Start 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/GanZhenliang/Ultra-AcadHomepage.git
cd Ultra-AcadHomepage
````

### 2. 安装依赖（确保你安装了 Ruby 和 Bundler）

```bash
bundle install
```

### 3. 本地运行

```bash
bundle exec jekyll serve
```

打开浏览器访问 [http://localhost:4000](http://localhost:4000)

---

## 🧭 目录结构说明

| 目录 / 文件       | 说明                   |
| ------------- | -------------------- |
| `_config.yml` | 全局配置，包括名称、导航、语言等     |
| `_data/`      | 菜单导航、社交链接等结构化数据配置    |
| `_pages/`     | 首页、项目、简历、文章等页面文件     |
| `_includes/`  | 页面片段模板（页头、页脚、导航栏等）   |
| `assets/`     | 样式文件、JavaScript、图像资源 |
| `Gemfile`     | Jekyll 所需的依赖项声明      |

---

## 🌐 自定义部署

你可以将本项目部署在：

* GitHub Pages（推荐）
* Vercel / Netlify 等静态托管平台
* 自定义服务器 + Nginx

### 自定义域名绑定（GitHub Pages）

将你绑定的域名写入 `CNAME` 文件并推送即可，GitHub Pages 会自动识别。

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

> Forked from [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io)
> Developed and maintained by [Zhenliang Gan](https://github.com/GanZhenliang)

---

Feel free to star ⭐ this repo if it helps you!
