# Grand Luxury Christmas Tree · 离线加强版

基于 [Hwescon/christmas-tree-v17.6](https://github.com/Hwescon/christmas-tree-v17.6)（Grand Luxury Tree v17.6.5，MIT 未声明，原作者保留权利）。

改造点：
- three.js 0.160 / mediapipe tasks-vision / hand_landmarker 模型 全部本地化，不再依赖 jsdelivr、Google Fonts、storage.googleapis.com
- 去掉 Google Fonts，改用系统字体（国内不再卡白屏）
- 竖屏相机距离自适应（手机上树不会被切掉）
- 底部加访客计数（busuanzi，按 IP 去重）

部署：GitHub Pages，支持 https 摄像头/手势。
