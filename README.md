# 个人主页维护说明

Yashuai Cao 个人学术主页（https://yashcao.github.io ）。改内容时按下面表格定位对应文件即可。

## 内容速查表

| 要更新的内容 | 去哪个文件修改 |
|---|---|
| 首页 / 个人简介 | `_pages/about.md` |
| Research（研究方向 / 项目） | `_pages/research.html` |
| Publications（论文 / 专利 / 标准） | `_pages/publications.html` |
| Teaching（学生指导 / 课程教学） | `_pages/teaching.html` |
| Activities（学术活动 / 审稿） | `_pages/activities.html` |
| Experience（教育 / 工作经历） | `_pages/experience.html` |
| 顶部导航菜单（名称 / 顺序） | `_data/navigation.yml` |
| 侧边栏（姓名 / 头像 / 单位 / 邮箱 / 社交链接） | `_config.yml` 的 `author:` 段 |
| 站点标题 | `_config.yml` 的 `title` |
| 页脚版权信息 | `_includes/footer.html` |
| 图片（头像 / 活动照片等） | 上传到 `images/`，页面里写 `/images/文件名` |
| 颜色 / 字体 / 间距等样式 | `_sass/` 下的 `.scss` 文件 |

## 页面编辑说明

各内容页（`_pages/*.html`）是静态 HTML，直接编辑列表项即可：

```html
<h2>小节标题</h2>
<ul>
  <li>列表项</li>
</ul>
<ol>
  <li>编号列表项</li>
</ol>
