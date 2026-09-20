# CM Hook

网易云音乐（`com.netease.cloudmusic`，实测 **9.5.96 / 9005096**）的本机 LSPosed 模块。

**源码 · 构建说明 · 完整免责声明 → https://github.com/justsoso17/cmhook**

<img src="https://raw.githubusercontent.com/justsoso17/cmhook/main/res/mipmap-xxxhdpi/ic_launcher.png" width="96" alt="icon">

## 功能

- **消息防撤回台账**：私信聊天页右下角「撤回 N」胶囊（可拖动、位置持久），点开只列**本会话**被撤原文
- **首页内容清理**：`推荐` 只保留白名单块（默认 每日推荐 / 猜你喜欢 / 根据你喜爱推荐），配套清本地块缓存
- **播客「为你推荐」清理** · **关注页「乐迷团」隐藏** · **去开屏广告** · **长按顶栏搜索区进听歌识曲**
- **独白 HUD**：把接口调用翻译成人话的悬浮窗（可拖/折叠/✕关闭）· **频道精细控制** · **App 探测清单** · **DexKit 锚点自检**
- 设置入口：目标 App 设置页右下角「⚙ CM Hook」胶囊

## 兼容性

- LSPosed（`xposedminversion 82`）· scope：`com.netease.cloudmusic` · minSdk 24 / targetSdk 33
- 目标版本 9.5.96；其它版本个别混淆锚点可能漂移（模块内置 DexKit 兜底与自检日志）

## 免责声明

仅供**自有设备 / 已明确授权的测试环境**使用。与网易云音乐**无隶属或背书关系**；模块只在**本机进程内**读写目标 App 自身的网络请求与本地缓存：不提供服务端能力、不绕过付费或版权内容、不上传任何账号或内容。按“现状”提供，**无任何担保**。详见[源码仓](https://github.com/justsoso17/cmhook)。
