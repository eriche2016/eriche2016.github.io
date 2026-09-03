# 机器学习导引网站

这是一个单页响应式课程网站，参考 Stanford CS329A 的信息架构制作，适配手机与桌面端。

## 文件结构

```text
ML_course/
├── index.html
├── README.md
└── assets/
    ├── css/style.css
    └── js/main.js
```

## 需要更新的内容

打开 `index.html`，搜索以下关键词即可快速定位并修改：

- `2026–2027 学年秋季学期`：学期信息
- `何新卫` / `xwhe@mail.hzau.edu.cn`：教师与联系方式
- `课程助教`：助教信息
- `第 1 周` 到 `第 13 周`：课程安排表
- `20%`、`30%` 等百分比：考核比例
- `推荐方向`：课程项目方向

## 本地预览

如果你的电脑已安装 Node.js，可在仓库根目录运行：

```bash
npx http-server ML_course
```

然后访问终端显示的本地地址。若已配置 GitHub Pages，将仓库推送到 `main` 分支后，可直接访问：

```text
https://eriche2016.github.io/ML_course/
```
