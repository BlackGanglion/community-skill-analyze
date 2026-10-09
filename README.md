# community-skill-analyze

## 项目状态

保存每条社区 Skill 的元信息，以及对应源码仓库的全部文件内容，建立可追溯、可持续更新的本地资料库，为后续分析提供数据。同一仓库同一 commit 只保存一份完整快照，各 Skill 通过仓库与目录路径关联。

当前已完成基础初始化与采集方案，尚未实现采集程序或启动批量下载。

## 采集方案

见 [社区 Skill 采集与持续更新方案](docs/collection-plan.md)。首期以 LobeHub 为发现入口，方案确认后先验证认证、分页和小样本下载，再开展首次全量采集与定时更新。

## 本地开发

```sh
git clone https://github.com/BlackGanglion/community-skill-analyze.git
cd community-skill-analyze
```

当前没有依赖安装、启动或测试命令；采集模块实现后补充。
