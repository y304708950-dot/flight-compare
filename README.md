# 机票比价工具 (FlightCompare)

手机端自适应的机票比价网页，支持多平台票价对比。

## 功能
- 机场智能搜索（支持中文城市名/机场代码）
- 航班时刻表展示（出发时间、到达时间、飞行时长、直飞/中转）
- 多平台票价对比（携程、去哪儿、飞猪、同程、美团）
- 移动端自适应

## 数据来源
- 航班数据：Aviationstack API
- 票价数据：比价演示数据（后续可接入真实价格API）

## 部署到 GitHub Pages

```bash
# 1. 登录 GitHub CLI
gh auth login

# 2. 创建仓库并推送
gh repo create flight-compare --public --source=. --push

# 3. 开启 GitHub Pages
# Settings → Pages → Source: master branch → Save

# 4. 访问地址
# https://<your-username>.github.io/flight-compare/
```

## 本地测试
直接用浏览器打开 `index.html` 即可。
