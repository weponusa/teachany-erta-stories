# TeachAny 课件存储规范（全局记忆）

## ⚠️ 铁律
1. 所有课件存放在 `teachany-opensource/examples/{course-id}/` 目录下
2. 禁止为单课件创建独立 GitHub 仓库
3. 禁止在课件目录中创建 gallery.html、knowledge-map.html
4. registry.json 使用 `path: "examples/{course-id}"`，不使用外部 URL
5. git push 后同步 gitee: `git push origin main && git push gitee main`
6. deploy-pages.yml 自动部署，最终地址: `https://weponusa.github.io/teachany/examples/{course-id}/`

## 本仓库状态
- teachany-erta-stories 独立仓库已废弃
- 朝花夕拾课件已迁移至 teachany-opensource/examples/chinese-erta-stories/
- 本仓库仅保留 index.html 作为备份，不再用于新课件开发
