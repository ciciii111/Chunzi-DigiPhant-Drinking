# Chunzi — DigiPhant Drinking

给 Yuwen 的喝水模块。先读 [中文集成说明](给Yuwen_先读我.txt)。

推荐导入 [Drinking_2026-10-08.unitypackage](Drinking_2026-10-08.unitypackage)，不要勾选 Include dependencies 重新导出。
源码在 `Assets/StudentWork/Drinking/`，所有 `.meta` 一起提供。不要把外层 Chunzi 目录复制到 Unity Assets 中。

默认 P1：双手高于校准休息值 0.10，保持2秒；完整动画6.5秒。
必须由 Yuwen 接入共享动作锁，三人合并时关闭 Solo preview，并禁用旧喝水入口。
不含共享 Controller、Locomotion、Python、场景或 ProjectSettings。

已在本地项目副本完成导入、编译和无摄像头状态验证；尚未进行三人摄像头及摘果/搬木头联调。
本地 Unity 6000.6.4f1，团队目标6000.6.3f1需复测。

完整说明：[INTEGRATION_README.md](INTEGRATION_README.md)。
