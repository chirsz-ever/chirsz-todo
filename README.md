# 待办清单

我觉得需要一个公开展示的东西来督促我自己……

另外，记得及时玩库存游戏，观看阅读清单上的番剧、电影和书籍。

## 写作

遥记曾立下一个月写两篇文章的壮志……

- [ ] 写作：考证猫里奥的相关历史
- [ ] 写作：量子计算科普，软件模拟

## 学习

- [ ] 《算法概论》（*Algorithms*）
- [ ] PLFA 第二三分册 [link](https://agda-zh.github.io/PLFA-zh/)
- [ ] [TwinklebearDev Tutorials](https://github.com/Twinklebear/TwinklebearDev-Lessons)
- [ ] 学会织围巾
- [ ] 小篆和篆刻
- [ ] The Tex Book 及中西文排版技术
- [ ] 糖画制作
- [ ] 实现软光栅
- [ ] 实现软光线追踪
- [ ] 编译 Gentoo
- [ ] 编译 LFS
- [ ] 学习藤本修三的折纸技术，并将其著作翻译、电子排版
- [ ] 自定义一套用字标准 (基于 [傳承字形標準化文件](https://github.com/ichitenfont/inheritedglyphs))

## 其它

按某种微妙的顺序排序。

- [ ] 研究体验 [thunk-rs](https://github.com/sdleffler/thunk-rs) 和 [OldWin](https://github.com/honsunrise/oldwin)，写英语文章推广它们
- [ ] 用纯 JS 实现兼容 NodeJS 逻辑的 CommonJS
- [ ] 用 deno FFI 实现纯 JavaScript 的 GUI 库
- [ ] 给 fcitx5 写一个 TUI 前端
- [ ] 为 EGE 写一个安装程序
- [ ] 复刻 BGI Demo
- [ ] 实现 EGL 在 MacOS 上的浅封装，支持 OpenGL 2.1/OpenGL 4.1 core/OpenGL 2.0 es (GL_ARB_ES2_compatibility)
- [ ] 实现 wayland 在 MacOS 运行 foot 和输入法
- [ ] 给电工学实验的板子加上按键防抖
- [ ] 完善 pie-rs 并发布
- [ ] 实现 GLSS，复刻 GLUT 中生成的 Mesh
- [ ] 探索 base system (LFS, KISS Linux ...) + linuxbrew 的可行性
- [ ] 基于 deno 实现一个类似 [LÖVE](https://love2d.org/) 或者 [LÖVR](https://lovr.org/) 的框架
- [ ] 完善 [opengl-bunny-demo](https://github.com/chirsz-ever/opengl-bunny-demo)
- [ ] 完善 MagicCube 程序，实现 3D 可视化，移植到 WebGL
- [ ] 为 Ubisurfer 9 装上 Linux 系统
- [ ] 实现 `CanvasRenderingContext2D` over WebGPU
  - [测试套件](https://github.com/web-platform-tests/wpt/tree/5b450a27820a2e8aac21be2a9255659ef578cd5a/html/canvas)
- [ ] 实现 WebGL over WebGPU
- [ ] 排版《新刻全像三寶太監西洋記通俗演義》[link](https://www.shidianguji.com/zh/book/HY1542/)
- [ ] 修复 AList 的 bug，或者自己写一套新的 [link1](https://github.com/AlistGo/alist/issues/7011) [link2](https://github.com/AlistGo/alist/issues/7012)
- [ ] 让 ZeroTier 能更快通过 Moon 节点连接，实现更方便的 ZeroTier 客户端，或者改用 TailScale 等组网方式
- 关注和研究使用玻璃通过光学手段超长期存储数据的方法，主要是 Project Silica

## 进行中

其实意思是“由于某些原因搁置中”。

- [ ] 使 cage 支持输入法 [PR link](https://github.com/cage-kiosk/cage/pull/417)
- [ ] 翻译 Vulkan tutorial [link](https://github.com/Overv/VulkanTutorial/issues/336)
- [ ] 跟进 deno 上的 WebGPU 实现 [link](https://github.com/denoland/deno/issues/23563)
- [ ] 使 esbuild 支持转换正则字面量为纯 ASCII [link](https://github.com/evanw/esbuild/pull/4205)

## 已完成

- 从底层开始实现 NDJSON 协议，在其上实现 JSON-RPC 服务器和客户端 [link](https://github.com/chirsz-ever/jsonrpc-demo-rs)
- 实现 kmscon 的替代品: wlroots-nogpu + cage + foot [文章](https://zhuanlan.zhihu.com/p/21276024278)
- 写作：[证明 Ackermann 函数是非原始递归函数](https://zhuanlan.zhihu.com/p/21484585633)
- 写作：浮点数序列化算法的综述，关于 dragon4，grisu，ryu 等算法 [文章](https://zhuanlan.zhihu.com/p/413271089)
- 为 [nlohmann/json](https://github.com/nlohmann/json) 加上允许尾随逗号的特性支持, 以支持 [JWCC](https://nigeltao.github.io/blog/2021/json-with-commas-comments.html). [PR link](https://github.com/nlohmann/json/pull/4609)

## 已废弃

- 解决 minicom 中文本地化的对齐混乱
- 在 [History of OpenGL](https://www.khronos.org/opengl/wiki/History_of_OpenGL) 页面增加 OpenGL ES 的历史和版本变化
- 改进 clipp
- 设计并开源 Micro-B 3.0 转 Type-C 的转换电路，含芯片
- 实现用录音磁带记录二进制数据
- 使用 NodeAPI 将 dawn 接入 Node.js
  - 直接用 [node-webgpu](https://www.npmjs.com/package/webgpu)
- 用 Python 改一版 [jinliming2/qbittorrent-ban-xunlei](https://github.com/jinliming2/qbittorrent-ban-xunlei)
  - 直接用 [Simple-Tracker/qBittorrent-ClientBlocker](https://github.com/Simple-Tracker/qBittorrent-ClientBlocker)
- 实现纯 Lua 的 bit32 polyfill
  - 直接用 [davidm/lua-bit-numberlua](https://github.com/davidm/lua-bit-numberlua)
- 在 C++ 中用模板实现简化版的事件模型 <!-- f**k C++! -->
- Rust 中 `static_assert` 相关 [link](https://github.com/rust-lang/libs-team/issues/325), 将相关内容加入 TRPL 和 Rust By Example
