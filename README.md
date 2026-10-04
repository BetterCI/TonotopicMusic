# Tonotopic Music

**一起探索人工耳蜗的音乐体验。** 连接音乐、听觉科学与软件设计，以单侧音高和短旋律为起点，研究电极位置、脉冲速率、幅度调制及其组合。

🌿 **[Welcome 网页](https://betterci.github.io/TonotopicMusic/)** · [合作兴趣](https://github.com/BetterCI/TonotopicMusic/issues/new?template=collaboration.yml) · [研究想法](https://github.com/BetterCI/TonotopicMusic/issues/new?template=research-idea.yml)

## 发起人与条件

华南理工大学 **孟庆林副教授** 与深圳市龙岗区耳鼻咽喉医院 **魏朝刚主任** 共同发起，依托两家单位共建的 **数字听力健康联合实验室**。

团队具备 NIC4 和 CCiMobile 的研究条件，已有离线音乐编码、交互展示和客观分析原型。本仓库首次公开的是 Welcome 页面、原创示意图与协作入口；完整原型、设备适配和人体实验数据尚未发布。

**NIC4 由科利耳公司提供。相关实验前必须严格进行科利耳公司报批和医院伦理审查，并获得相应批准。平台提供不代表具体实验已经获批。**

CCiMobile 官方源码与说明：[UT Dallas / CILabUTD / CCi-MOBILE](https://github.com/CILabUTD/CCi-MOBILE)。

孟庆林联系邮箱：[mengqinglin@scut.edu.cn](mailto:mengqinglin@scut.edu.cn)。

## 音乐感知背景

Welcome 新增[简要文献回顾](https://betterci.github.io/TonotopicMusic/#music-review)：节奏相对保留，音高、旋律与音色仍有挑战，且个体差异明显。结合 2004、2014 与 2024 年综述，区分音乐辨认、欣赏与参与，并以原创图展示文献研究重点及本项目双重评价目标。图中的文献数量不是受试者数量或效果数据。

## 相关研究基础

已加入两位发起人参与的十篇人工耳蜗与听觉评估论文，优先推荐《人工耳蜗中的声信号处理》和《人工耳蜗的音高感知编码机制和限制》两篇中文综述；另涵盖平台、TLE 音高编码、Applied Acoustics 的 GET 声学模型、2026 年反相生肖噪声测试与辅音知觉组织，以及魏朝刚参与的声调与临床研究。每篇提供来源、研究内容及与本项目的关系，见 [研究精选](PUBLICATIONS.md) 或 [Welcome 研究基础](https://betterci.github.io/TonotopicMusic/#publications)。这些既往成果不是本项目音乐体验效果的验证。

## 我们想探索什么

- 固定节奏下，通过位置、速率或 AM 单独表达短旋律的上行、下行与转折。
- 比较一致或冲突的组合线索，建立时长、节奏和响度匹配的对照。
- 将通过验证的设计发展为成年植入者可以主动探索的音乐体验。

数学电极重心不等于神经激励中心，脉冲速率不等于声学音高，声学演示不代表植入者听感。CCiMobile 动态速率切换仍需设备验证，不假设任意逐脉冲时间控制。已有 ACE 模式是代理，不是真实 ACE。

客观检查用于发现时序、量化、采样及幅度混杂；效果仍需获批后的设备验证、个体校准与主观实验。尚未证明本方案带来听觉或临床改善。

## 一起参与

欢迎音乐创作、教育、音乐科技，以及听觉科学、临床、信号处理、交互和软件伙伴。尤其欢迎广州、深圳的朋友，也欢迎远程讨论。需求尚在形成，可以从一个问题、一段旋律或一项分析开始。

这是研究与公益音乐体验合作，**不是招聘，也不是受试者报名入口**。参见 [参与指南](CONTRIBUTING.md)，用 Issue 介绍兴趣或提出建议。

## 页面运行

直接打开 `index.html`，或在本目录运行 `python -m http.server 8000`。没有外部脚本、字体、分析跟踪或设备接口。三个滑块仅绘制数学示意，不输出刺激。

GitHub Pages 通过 `.github/workflows/pages.yml` 发布。原创 SVG 在 `assets/`。参考文献与科学边界见 Welcome 页面。

## 公开范围与许可

当前没有授予统一的开源许可；原创内容版权归相应作者，贡献者保留其作品权利。欢迎通过 Issue/PR 提出改进，拟定发布许可是后续协作事项。未公开厂商手册、SDK、设备控制代码、个体 MAP 或临床资料。文献原图未转载；所有本仓库插图均为团队原创示意。
