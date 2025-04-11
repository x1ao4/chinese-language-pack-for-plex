# Chinese Language Pack for Plex
Plex 的本地化工作并不是由专业团队完成的，而是通过翻译平台 Transifex 的[公开项目](https://explore.transifex.com/plex-1/)，由各国的志愿者自发参与翻译完成的。参与翻译的人员比较比较多，构成复杂，翻译工作的时间跨度比较大，并且缺乏统一的管理和审核，目前，虽然汉化工作基本上已经完成，但是依然存在大量错误或者不恰当的翻译，整体汉化质量一般。

据我所知，Plex 的简体中文翻译板块已经很多年没有审核人员了，并且似乎也无法再进行申请（可能已经取消审核流程了）。早期的审核人员审核通过了很多错误的翻译，比如 “Studio（制片公司）” 被翻译为了 “演播室”，“Record Label（唱片公司）” 被翻译为了 “录音标签” 等等；目前使用的翻译还存在很多一词多译的情况，比如 “Artist” 同时存在 “艺人、艺术家、作者” 三种翻译，“Collection” 同时存在 “合集、收藏集、选集、收集” 四种翻译等等；此外，目前的翻译还存在很多语义表达上的问题，导致很多功能的描述虽然翻译为了中文，但是中文用户却难以理解其含义。

因为 Plex 是一个跨平台的应用服务，有很多内容需要分平台进行翻译，比如安卓端、苹果端、网页端、服务器等都有单独的翻译项目，对于未审核（未复核）的字符串，我们是可以自由进行翻译和修改的，但是已审核（已复核）的字符串我们就无权修改了，如上所述，有很多已审核的翻译是存在问题的，由于我们无权进行修改，通过官方渠道似乎没有什么办法干预，同时也因为未审核的字符串可以被随意修改，直接在官方项目上修改或提交翻译也可能被其他人再次改动，所以我决定自己建立一个 Plex 的翻译项目，按照我认为规范的方式对 Plex 进行汉化，并将汉化后的语言包共享给大家使用。

## 翻译进度
<img width="100%" alt="进度" src="https://github.com/user-attachments/assets/6f0f5e22-d314-4d9c-9459-4683b2597219">

上图中蓝色的部分代表官方翻译的部分，绿色的部分代表我翻译的部分。其中对 Plex Media Server 的翻译将应用到全平台的 Plex、Plex Web、Plex HTPC、Plexamp 和 Plex Dash 等应用程序上，对 Web Clients 的翻译将应用到桌面端的 Plex 应用程序以及通过 IP 或自定义域名访问的 Plex Web（网页端）上。（翻译将持续更新）


## 效果展示
以下为部分翻译内容对比，左侧为 Plex 官方版本，右侧为我的版本。下图使用的是 Plex for MacOS 客户端。

<img width="100%" alt="1" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/0e093536-2efa-4409-8584-93b0ec4a8f2f">

<img width="100%" alt="2" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/5cf76a03-aba3-45c2-83ba-fbbe22b3fed6">

<img width="100%" alt="3" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/8ccc25b1-56f4-4182-8616-d4a88a74a9ca">

<img width="100%" alt="4" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/500d8854-b4f9-4c75-8002-7a0b8fddb94c">

<img width="100%" alt="5" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/54f07a11-970b-4dd4-b3fd-854877dd2ff3">

<img width="100%" alt="6" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/e6dcc029-372b-4e67-b0a7-198eac310b02">

<img width="100%" alt="7" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/68bd76f2-8682-4e01-9749-10417c7a26b8">

<img width="100%" alt="8" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/f8bda678-b910-437a-8fe2-52dae65e4204">

<img width="100%" alt="9" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/6275a1db-904d-4f1e-bd9a-bfaa799be800">

<img width="100%" alt="10" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/1c80c81a-8864-4906-a53a-6df520edfd9a">

<img width="100%" alt="11" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/93cac18b-8c8a-4bc1-b5c8-9c1544b5e9af">

<img width="100%" alt="12" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/4689780d-9070-49bd-b02b-17583649980c">

<img width="100%" alt="13" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/bc185bea-fd4f-4239-a37e-3e8f35378f21">

<img width="100%" alt="14" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/76637d63-75e3-4071-ab00-4f21b41efb4d">

<img width="100%" alt="15" src="https://github.com/x1ao4/chinese-language-pack-for-plex/assets/112841659/6fddb59f-6679-498d-ae22-80e7b6c55e70">

## 支持平台
### Plex Desktop
- Plex for MacOS
- Plex for Windows
- Plex for Linux

### Plex Web
- 通过 IP 或自定义域名访问的 Plex 网页端

### Plex Media Server
- Plex Media Server for MacOS
- Plex Media Server for Windows
- Plex Media Server for Linux
- Plex Media Server for Docker
- Plex Media Server for NAS（套件）

## 使用方法
### Plex Desktop
请下载 Web Clients 文件夹内的 `zh.json` 文件，然后替换你的 Plex 目录中的 `zh.json` 文件，重启 Plex 客户端后即可生效（请确保文件的权限和模式与原文件一致）。你可以参考以下地址找到你的 `zh.json` 文件。
```
# MacOS
/Applications/Plex.app/Contents/Resources/web-client/translations/zh.json

# Windows
C:\Program Files\Plex\Plex\web-client\translations\zh.json
```

### Plex Web
请下载 Web Clients 文件夹内的 `zh.json` 文件，然后替换你的 Plex Media Server 目录中的 `zh.json` 文件，重启 Plex Media Server 后即可生效（请确保文件的权限和模式与原文件一致）。你可以参考以下地址找到你的 `zh.json` 文件。（`Plug-ins-c0dd5a73e` 会随着 Plex Media Server 的版本发生变化）
```
# MacOS
/Applications/Plex Media Server.app/Contents/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# Windows
C:\Program Files\Plex\Plex Media Server\Resources\Plug-ins-c0dd5a73e\WebClient.bundle\Contents\Resources\translations\zh.json

# Docker（容器内部目录）
/usr/lib/plexmediaserver/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# QNAP
/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# Synology
/volume1/@appstore/PlexMediaServer/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json
```

### Plex Media Server
请下载 Plex Media Server 文件夹内的 `plex.mo` 文件，然后替换你的 Plex Media Server 目录中的 `plex.mo` 文件，重启 Plex Media Server 后即可生效（请确保文件的权限和模式与原文件一致）。你可以参考以下地址找到你的 `plex.mo` 文件。
```
# MacOS
/Applications/Plex Media Server.app/Contents/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# Windows
C:\Program Files\Plex\Plex Media Server\Resources\locale\zh_CN\LC_MESSAGES/plex.mo

# Docker（容器内部目录）
/usr/lib/plexmediaserver/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# QNAP
/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# Synology
/volume1/@appstore/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo
```

## 注意事项
- 提供的文件地址仅供参考，因为安装设置差异，文件地址也许不会完全一致，请在类似的目录结构中查找文件。
- 通过 Docker 安装的 Plex Media Server 请在容器内部目录中查找和替换文件（非宿主机目录）。
- 建议在替换文件前先备份你原有的 `zh.json` 和 `plex.mo` 文件，以便你能够退回官方版本（如果有需要）。
- 语言包会持续更新，你可以关注本项目，及时获取最新版本，根据需要，某些翻译可能会在后续版本中变更。
- 更新 Plex 桌面客户端或 Plex Media Server 版本后会重置语言包，请在更新版本后重新替换语言包。

## 赞赏
如果你觉得这个项目对你有用，可以考虑请我喝杯咖啡或者给我一个⭐️。谢谢你的支持！

<img width="383" alt="赞赏" src="https://github.com/user-attachments/assets/bdd2226b-6282-439d-be92-5311b6e9d29c">
