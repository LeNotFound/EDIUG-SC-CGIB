# 贡献指南（Contributing Guide）

感谢你对 EDIUG-SC-CGIB 的关注！🥳  
为了让项目协作更顺畅，请遵循以下规范：

## 📦 提交代码

- **每次提交前，请确保代码能够正常渲染**
- **适当分小提交，避免一次提交修改太多内容**

## 📝 Commit Message 格式

统一使用 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0/) 风格，格式如下：

```
<type>: <简要描述>
```

常见的 `type` 有：

| type | 含义 |
|:----|:----|
| feat | 新功能或页面 |
| fix | 修复问题 |
| docs | 文档更新 |
| style | 格式修改（不涉及逻辑变更） |
| refactor | 重构（即不新增功能也不修复 bug） |
| chore | 杂项（比如脚本、依赖升级等） |

示例：

```
feat: 添加面包房免费冰淇淋说明
fix: 修复康庄食堂二楼链接错误
docs: 更新贡献指南
```

## 🛠️ 文件结构约定

- 页面内容统一放在 `docs/` 下，按学期、课程分类，或按校区、食堂、楼层分类等。
- 静态资源（图片、附件）放在对应页面的 `assets/` 文件夹内，

!!! note
    本仓库目前未启用 Git LFS，还在建设中，所以请尽量避免上传大文件（如视频、音频等），如果有必要，请使用外部链接或云存储服务。

例子：

```
docs/
  校园生活/
    食堂/
      康庄食堂/
        二楼民族餐厅/
          index.md
          assets/
            某窗口菜单.jpg
```

## 📚 Markdown 规范

- 标题请使用规范的层级（# 一级标题，## 二级标题，### 三级标题）
- 推荐使用 Markdown 扩展块（!!! note / !!! info 等）
- 相对路径引用图片或文件，例如：
  
  ```markdown
  ![菜单预览](assets/窗口菜单.jpg)
  ```

---

💬 如果有任何疑问，欢迎提 issue 交流！

一起让 EDIUG-SC-CGIB 更加完善吧！🌟