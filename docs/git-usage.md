\# Git 使用说明



\## 1. 查看当前状态



git status



\## 2. 创建功能分支111



git switch develop

git switch -c feature/功能名



\## 3. 提交代码



git add 文件名

git commit -m "feat: add xxx"



\## 4. 合并功能分支



git switch develop

git merge feature/功能名



\## 5. 分支命名规范



\- feature/xxx：新功能

\- fix/xxx：问题修复

\- release/v1.2.0：预发布版本

\- hotfix/xxx：线上紧急修复



\## 6. 提交信息规范



\- feat: 新功能

\- fix: 修复 bug

\- docs: 文档变动

\- perf: 性能优化

\- chore: 工程调整

