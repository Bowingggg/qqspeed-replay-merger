# 更新记录

## v0.8.10 — 2026-10-21（最新）

构建：`QQSpeed_Merger_v0.8.10_BidirectionalElastic.exe`

- **皮筋双向回拉修复**：回拉判定不再依赖“原完赛顺序预测”，此前比分接近时会被误判、导致一方始终不回拉；现改为固定时间间隔去抖，领先方均可成为下一次回拉对象（双向可回拉）。
- **回拉次数达上限后保留结果**：达到回拉事件上限时停止继续追加回拉并保留已生成的合并结果，不再抛错拒绝整次合并。
- 窗口标题版本号更新为 v0.8.10。
- 其余既有功能与历史版本全部保留，未做额外功能修改。

## 历史版本（已保留）

| 版本 | 构建名 |
| --- | --- |
| v0.8.9 | IdentityRankFix |
| v0.8.8 | CameraByRank |
| v0.8.7 | ElasticView2Test |
| v0.8.6 | ProfileSlotPreserve |
| v0.8.5 | AkinayamaBase_WindowFix |
| v0.8.4 | NewBase |
| v0.8.3 | FinalUX |
| v0.8.2 | ClockAndNaming |
| v0.8.1 | Release |
| v0.8.0 | CoreNative / MonolithPreview / ConsoleDebug |
