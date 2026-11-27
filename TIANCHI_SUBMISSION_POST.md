# 【2026 Qoder 高校创造力大赛】AI CREATOR：苹果极简风 AI 创作者社区与透明分账交易平台

## 一、项目访问地址
- **公网体验地址（Qoder Sites 部署，公开访问）**：https://ai-creator-scmxivlay9g.qoder.website/
- **备用镜像（GitHub Pages，内容一致）**：https://lfg-stacky.github.io/ai-creator-qoder/
- **演示短视频直链（可直接播放/下载）**：https://lfg-stacky.github.io/ai-creator-qoder/promo/ai_creator_promo_hype.mp4
- **开源代码仓库**：https://github.com/LFG-stacky/ai-creator-qoder
- **演示短视频外链（可选）**：如需发布至抖音/小红书，可在标题中包含「2026 Qoder 高校创造力大赛」后填入此链接

## 二、创意背景与解决的痛点
随着生成式 AI 爆发，高校同学与独立创作者产出了大量 AI 游戏、短片、App、3D 模型与开源智能硬件原型，但这些作品往往零散沉睡在网盘或代码仓库里，缺乏一个既具备高质量展示美学、又能清晰标明开源/闭源授权并实现透明收益变现的垂直平台。

因此我们打造了 **AI CREATOR**——不堆砌臃肿功能，专注为 AI 创作者提供「高清展示、多维筛选比选、80% 高分成透明交易、实时经营看板与社区私信协作」的一站式桌面端体验。

## 三、核心功能与交互亮点（评委 30 秒体验路径）
进入首页后，可直接点击顶部的 **「30 秒亮点导览」**，或按以下路径体验完整业务闭环：
1. **双栏交易市场 & 横向对比台**：进入「市场」（快捷键 `2`），左侧常驻多维筛选器（12 大分类、数字/现实形态、免费/付费、开源筛选），悬停作品卡片勾选「对比」即可并排对比最多 3 件作品的授权与价格。
2. **购物袋 80%/20% 透明分账 & 经营大屏实时联动**：将任意作品加入购物袋（快捷键 `B`），即可查看创作者实得 80% 与平台 20% 明细；点击「模拟结算」生成电子授权订单后，系统会自动跳转「经营中心」（快捷键 `6`），11 月营收柱状图与累计成交额实时增长。
3. **详情页评分评价 & 私信协作抽屉**：点击任意作品可体验实时提交星级评价；在作品页、社区或榜单点击「私信」可滑出创作者对话抽屉，模拟发起合作咨询。
4. **桌面宽屏美学与全键盘效率**：全站采用统一 1.8px 线性矢量 SVG 图标，支持浅色/深色 Apple 外观无缝切换（快捷键 `D`）、Spotlight 全站搜索（`⌘K` 或 `/`）与快捷键面板（`?`）。

## 四、使用 Qoder 开发与部署过程
- **需求拆解与界面迭代**：依托 Qoder 进行组件结构梳理、Apple Design System 视觉重构、宽屏双栏适配与矢量图标系统替换。
- **全链路状态联动与验证**：实现前端本地状态持久化、购物车分账计算、经营图表动态联动与无依赖静态打包。
- **公网部署**：作品为**零依赖单文件静态打包**（图片/图标全部内联，无后端依赖），用 Qoder CLI 的 `qoder sites` 打包上传并发布为 **Qoder Sites** 公开站点：https://ai-creator-scmxivlay9g.qoder.website/ （同时保留 GitHub Pages 镜像）。

## 五、界面截图展示（可直接引用线上图片链接发帖）

> 以下 6 张均为线上环境的真实运行截图，点击链接可直接在发帖编辑器中插入。

1. **首页浅色主视觉**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/01-hero-light.png
2. **首页深色主视觉（快捷键 `D`）**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/02-hero-dark.png
3. **市场双栏筛选 + 对比台（已选 2/3）**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/03-market-compare.png
4. **作品参数横向对比弹窗**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/04-compare-table.png
5. **购物袋 80%/20% 透明分账抽屉**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/05-bag-split.png
6. **经营中心实时营收大屏**：https://lfg-stacky.github.io/ai-creator-qoder/screenshots/06-business-dashboard.png

![首页浅色主视觉](https://lfg-stacky.github.io/ai-creator-qoder/screenshots/01-hero-light.png)
![市场双栏筛选与对比台](https://lfg-stacky.github.io/ai-creator-qoder/screenshots/03-market-compare.png)
![购物袋 80%/20% 分账](https://lfg-stacky.github.io/ai-creator-qoder/screenshots/05-bag-split.png)
![经营中心营收大屏](https://lfg-stacky.github.io/ai-creator-qoder/screenshots/06-business-dashboard.png)
