# 📚 My Wiki - 个人知识库

<div align="center">

![GitHub last commit](https://img.shields.io/github/last-commit/你的用户名/my-wiki?style=flat-square&color=6366f1)
![GitHub repo size](https://img.shields.io/github/repo-size/你的用户名/my-wiki?style=flat-square&color=6366f1)
![License](https://img.shields.io/github/license/你的用户名/my-wiki?style=flat-square&color=6366f1)

> 📖 记录我学到的一切，持续更新中...

</div>

---

## 📂 目录结构

---

## 📖 笔记目录

### 💻 编程
| 文件 | 内容 | 更新时间 |
|------|------|---------|
| [Git 基础命令](programming/git/basics.md) | add/commit/push 等基础操作 | 更新中 |
| [Git 分支管理](programming/git/branch.md) | 分支创建、合并、冲突处理 | 更新中 |
| [Git 进阶技巧](programming/git/advanced.md) | stash/rebase/tag 等 | 更新中 |

### 🛠️ 工具
| 文件 | 内容 |
|------|------|
| [VS Code 配置](tools/vscode.md) | 插件推荐、快捷键 |
| [工具推荐](tools/recommendations.md) | 常用工具合集 |

### ❌ 踩坑记录
| 文件 | 内容 |
|------|------|
| [Git 常见报错](errors/git-errors.md) | 报错信息和解决方法 |

---

## 🚀 快速开始

```bash
# 克隆到本地
git clone https://github.com/你的用户名/my-wiki.git

# 进入目录
cd my-wiki


> 记得替换所有 **你的用户名** 和 **你的名字**！

---

## 第四部分：创建 .gitignore

### Step 5：新建 .gitignore 文件

在 VS Code 里新建文件 `.gitignore`：

```bash
# macOS 系统文件
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes

# 编辑器文件
.vscode/settings.json
.idea/
*.swp
*.swo
*~

# 临时文件
*.tmp
*.log
draft/
temp/

# 不上传的私人内容
private/
