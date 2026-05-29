# AFOIer 项目状态 & 下一步计划

> 更新日期: 2026-05-29

## 已完成

### P0 补齐框架 ✅
- [x] admission-outline.md — 综合评价招生总述
- [x] admission-provinces.md — 省份单独招生机制

### P1 核心升学 ✅ (缺1)
- [x] postgraduate.md — 保研与考研
- [x] overseas.md — 出国留学
- [x] oh-cs.md — 泛CS专业详情扩充
- [x] about.md — 修链接
- [ ] **oh.md — 强基计划页面还非常单薄**，只有破格入围部分，缺：强基概述、完整流程时间线、适合OIer的择校策略。这些公开信息可以独立写，不需要社区数据。

### P2 社区框架 ✅
- [x] stories/index.md — 退役心路（投稿指南+话题）
- [x] experience/index.md — 就读体验（投稿模板）
- [x] careers/index.md — 职业发展投稿入口
- [x] careers/roadmap.md — 职业路径概览

### P3 知识扩展 ✅
- [x] glossary.md — OI圈竞赛词典
- [x] resources/index.md — 退役后学习资源
- [ ] 删了 projects.md，无需恢复

## 明天可以做的

### 1. 扩充 oh.md（强基计划总述）— 推荐先做
当前只有破格入围部分，可以补充：
- 什么是强基计划（简短概述，面向完全不了解的新人）
- 招生流程与时间线（简章发布→报名→高考→校测→录取）
- OIer 择校策略（金银牌怎么选、省一怎么选、不同层次学校的策略差异）
- 校测形式概述（笔试/面试/体测，各校差异）
- 与综合评价的对比（已有 admission-outline 可互链）
- 参考资料链接

这些内容都是公开可查的，不需要社区数据。

### 2. 可以考虑但不急
- notes/index.md — 技术札记板块框架（退役后对算法的新理解等）
- 各板块写一篇示例投稿做种子内容

### 3. 依赖社区投稿的（只能等）
- oh-exam.md — 强基校测备考经验
- stories/ 下的真实退役故事
- experience/ 下的高校就读体验
- careers/ 下的职业分享

## 站点当前状态

- 16 个内容页面
- 5 个一级导航：首页 / 高校信息 / 社区 / 资源 / 关于
- mkdocs build 通过
- GitHub: AFOIer/AFOIer master 分支
- 本地路径: C:\BaiduNetdiskDownload\claude\afoier\AFOIer-master
- 本地构建: `mkdocs serve` 访问 http://127.0.0.1:8000

## 本地操作备忘

```bash
cd /c/BaiduNetdiskDownload/claude/afoier/AFOIer-master
mkdocs serve          # 预览
mkdocs build --strict # 构建检查
git push origin master # 推送（直推 AFOIer/AFOIer，不加 Claude 署名）
```
