## 简介
1. 提供 androidx 版本的 glide-3.8 项目 jar 包。自己作记录，也为他人行方便。
2. 建立这个小项目缘由是，一个折腾本人一天的问题。有一个主项目使用 glide 3x，新建的模块是基于 glide 4x，因为这个问题尝试主项目升级 glide ,但是使用点颇多，涉及到迁移问题无法解决；也尝试新模块降级，但是新模块是基于 androidx, 而 glide 3x 是基于 supportv4，也是各种不兼容。
3. 使用官方jetifier 工具[https://developer.android.google.cn/studio/command-line/jetifier]，将 glide 3x jar 包的supportv4 升级到 androidx