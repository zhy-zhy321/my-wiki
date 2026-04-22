# 🔧 Git 基础命令

> 💡 这是我在 GitHub 30天挑战中整理的 Git 笔记

---

## 初始化

```bash
# 初始化一个新仓库
git init

# 克隆已有的仓库
git clone https://github.com/用户名/项目名.git


再新建 `programming/git/branch.md`：

```markdown
# 🌿 Git 分支管理

> 分支 = 平行宇宙，让你安全地尝试新功能

---

## 基本操作

```bash
git branch                  # 查看所有分支（* 是当前分支）
git switch -c 新分支名       # 创建并切换（推荐！）
git switch 分支名            # 切换分支
git merge 分支名             # 合并分支（先切到目标分支）
git branch -d 分支名         # 删除分支