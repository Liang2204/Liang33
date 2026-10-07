# 🍉 水果连连看

一个纯 HTML / CSS / JavaScript 实现的经典连连看小游戏，零依赖、零构建，打开即玩。

## 玩法

- 点击两个**相同**的水果，如果它们之间能用**不超过 3 条直线**（最多拐 2 个弯）连起来，就能消除
- 在倒计时（300 秒）结束前清空全部水果即获胜
- 连击有加分，剩余时间越多奖励越高

## 功能

- 🎯 8 × 10 棋盘，20 种水果，共 40 对
- 💡 提示（3 次）：高亮一对可消除的水果
- 🔀 洗牌（3 次）：重新排列剩余水果
- 🤖 死局自动检测并自动洗牌
- ⏸ 暂停 / 继续
- 🏆 历史最高分（localStorage 保存）
- 📱 适配手机屏幕

## 本地运行

直接用浏览器打开 `index.html` 即可，无需任何安装。

## 部署

本项目为纯静态页面，部署到 Vercel 时 Framework Preset 选择 **Other** 即可。

```bash
git init
git add .
git commit -m "连连看游戏"
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
```

然后在 [vercel.com](https://vercel.com) 用 GitHub 登录 → Add New Project → Import 该仓库 → Deploy。
