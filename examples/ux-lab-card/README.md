# UX 实验室 · 应用四项原则

交互卡片「UX 实验室：应用四项原则」的视觉重设计。原练习来自 Claude Academy 课程
[用户体验的判断力](https://academy.claude.com/zh-CN/courses/ai-fluency-for-builders/discernment-for-user-experience)。
这个目录把同一道练习做成了一个独立、可直接打开的网页。

用浏览器打开 [`index.html`](index.html) 即可，无需构建，也没有外部依赖。

## 交互

- 四个原则标签：清晰度、层级结构、无障碍性、反馈。
- 每项 3 处问题。悬停、点按或 Tab 聚焦带编号的元素，右侧「实验笔记」显示问题与原因。
- 点击「显示修复」，同一界面切换到修复版本，笔记同步解释每一处改动。
- 方向键切换标签，触屏可用，尊重 `prefers-reduced-motion`，320px 起无横向滚动。
- 「已发现」记录每项原则中查看过的问题。

## 视觉

暖纸色底、陶土色强调、衬线标题、等宽小标签与细线框，参考 Claude Design 的视觉语言。
外卖结算界面作为同一个「实验样本」，用四项原则反复检查；问题以编号定位，解释放在侧边笔记，
不再用浮在界面上的深红提示框。

## 截图

原始卡片（仅用于设计对照，截取自公开课程页）：

- [默认状态（清晰度）](screenshots/before-default.png)
- [悬停「提交」](screenshots/before-hover.png)
- [显示修复](screenshots/before-fixed.png)

重设计（1440px 视口；`after-mobile.jpg` 为 390px）：

- [默认状态](screenshots/after-default.jpg)
- [悬停「合计」](screenshots/after-hover.jpg)
- [显示修复](screenshots/after-fixed.jpg)
- [层级结构 · 修复后](screenshots/after-hierarchy.jpg)
- [反馈 · 修复后](screenshots/after-feedback.jpg)
- [移动端](screenshots/after-mobile.jpg)

## 说明

这是一个独立的设计原型，尚未接入 DSH 面板或课程页面。
