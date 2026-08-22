# Health Handbook Icons

微信小程序「今天你打卡了没」图标资源库，通过 jsDelivr CDN 加载。

## 目录结构

- `ui/` — UI 图标（39 张）：tabBar、功能入口、设置选项等
- `cat/` — 食物分类图标（8 张）
- `food/` — 食物图标（162 张）
- `method/` — 做法图标（309 张）
- `ex/` — 运动图标（37 张）

## CDN 使用

```javascript
// jsDelivr CDN 地址
const CDN_ROOT = 'https://cdn.jsdelivr.net/gh/{USER}/{REPO}@main/icons';

// 示例
icon.uiImg('weight')     // → {CDN_ROOT}/ui/ui_weight.png
icon.foodImg('almond')   // → {CDN_ROOT}/food/food_almond.png
```

## 文件命名规则

- UI: `ui_{name}.png`
- 分类: `cat_{name}.png`
- 食物: `food_{id}.png`
- 做法: `icon_method_{foodId}_{做法名}.png`（中文 URL 编码）
- 运动: `ex_{id}.png`
