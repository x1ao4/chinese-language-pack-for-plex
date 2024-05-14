# plex-locale-zhcn
Plex 的本地化工作并不是由专业团队完成的，而是通过翻译平台 Transifex 的[公开项目](https://explore.transifex.com/plex-1/)，由各国的志愿者自发参与翻译完成的。参与翻译的人员比较比较多，构成复杂，翻译工作的时间跨度比较大，并且缺乏统一的管理和审核，目前，虽然汉化工作基本上已经完成，但是依然存在大量错误或者不恰当的翻译，整体汉化质量一般。

据我所知，Plex 的简体中文翻译板块已经很多年没有审核人员了，并且似乎也无法再进行申请（可能已经取消审核流程了）。早期的审核人员审核通过了很多错误的翻译，比如 “Studio（制片公司）” 被翻译为了 “演播室”，“Record Label（唱片公司）” 被翻译为了 “录音标签” 等等；目前使用的翻译还存在很多一词多译的情况，比如 “Artist” 同时存在 “艺人、艺术家、作者” 三种翻译，“Collection” 同时存在 “合集、收藏集、选集、收集” 四种翻译等等；此外，目前的翻译还存在很多语义表达上的问题，导致很多功能的描述虽然翻译为了中文，但是中文用户却难以理解其含义。

因为 Plex 是一个跨平台的应用服务，有很多内容需要分平台进行翻译，比如安卓端、苹果端、网页端、服务器等都有单独的翻译项目，对于未审核（未复核）的字符串，我们是可以自由进行翻译和修改的，但是已审核（已复核）的字符串我们就无权修改了，如上所述，有很多已审核的翻译是存在问题的，由于我们无权进行修改，通过官方渠道似乎没有什么办法干预，同时也因为未审核的字符串可以被随意修改，直接在官方项目上修改或提交翻译也可能被其他人再次改动，所以我决定自己建立一个 Plex 的翻译项目，按照我认为规范的方式对 Plex 进行汉化，并将汉化后的语言包共享给大家使用。

## 翻译进度
<img width="100%" alt="进度" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/67d1ad3e-d4fb-4e0a-b3ae-74d786091a50">

上图中蓝色的部分代表官方翻译的部分，绿色的部分代表我翻译的部分。其中对 Plex Media Server 的翻译将应用到全平台的 Plex、Plex Web、Plex HTPC、Plexamp 和 Plex Dash 等应用程序上，对 Web Clients 的翻译将应用到桌面端的 Plex 应用程序以及通过 IP 或自定义域名访问的 Plex Web（网页端）上。（翻译将持续更新）


## 效果展示
以下为部分翻译内容对比，左侧为 Plex 官方版本，右侧为我的版本。下图使用的是 Plex for MacOS 客户端。

<img width="100%" alt="1" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2f794399-31e9-4a3f-875c-32a81abad90e">

<img width="100%" alt="2" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ad5d6fb0-b7a0-4b26-8ae2-46da94d785cf">

<img width="100%" alt="3" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ebad1efa-a2f9-4eeb-bba4-6adf0cc3db03">

<img width="100%" alt="4" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/4fc5e445-08a6-4fd5-a3ab-5cdf01586806">

<img width="100%" alt="5" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/7b755f91-206f-4bd4-ab21-ae5cd877bff0">

<img width="100%" alt="6" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ba017732-e67a-4d48-bafb-ca7e3ab18f49">

<img width="100%" alt="7" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1b4f0ef3-0cec-454d-80e7-406ddbfa5277">

<img width="100%" alt="8" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/030c1e6c-a4cf-47b8-8206-0fdb9e07f715">

<img width="100%" alt="9" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/873649a0-1ec1-445a-85d5-4a3f669b27ab">

<img width="100%" alt="10" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/3cb96d7e-6f79-4449-9d50-8bb2a107266a">

<img width="100%" alt="11" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/68ca7f6a-987a-4e1d-a8c7-4d42a532cdc0">

<img width="100%" alt="12" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2be900ea-bf89-424c-bfdd-2ba601768130">

<img width="100%" alt="13" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1ebe644b-69ca-40da-8947-b0ce701dd958">

<img width="100%" alt="14" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/b4f3d90b-1b0d-4252-a073-2b70bb005b45">

<img width="100%" alt="15" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1d8f8894-bfee-4227-8a25-1ce2cc494351">

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

# Docker
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

# Docker
/usr/lib/plexmediaserver/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# QNAP
/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# Synology
/volume1/@appstore/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo
```

## 注意事项
- 提供的文件地址仅供参考，因为安装设置差异，文件地址也许不会完全一致，请在类似的目录结构中查找文件。
- 通过 Docker 安装的 Plex Media Server 请在容器内部目录中查找和替换文件（不是映射目录）。
- 建议在替换文件前先备份你原有的 `zh.json` 和 `plex.mo` 文件，以便你能够退回官方版本（如果有需要）。
- 语言包会持续更新，你可以关注本项目，及时获取最新版本，根据需要，某些翻译可能会在后续版本中变更。
- 更新 Plex 桌面客户端或 Plex Media Server 版本后会重置语言包，请在更新版本后重新替换语言包。
<br>

# plex-locale-zhcn
The localization work for Plex isn't carried out by a professional team but rather through the [public project](https://explore.transifex.com/plex-1/) on the translation platform Transifex, where volunteers from various countries contribute to translating. The translation process involves many participants, making it complex, and the timeline for translation work spans over a considerable period. Moreover, there's a lack of centralized management and review. Currently, although the localization work for Simplified Chinese is mostly complete, there are still numerous errors or inappropriate translations, resulting in overall mediocre localization quality.

To my knowledge, the Simplified Chinese translation section for Plex has been without reviewers for many years, and it seems that it's no longer possible to apply for reviewer status (The review process might have been discontinued). Early reviewers approved many erroneous translations, such as translating "Studio (制片公司)" as "演播室" and "Record Label (唱片公司)" as "录音标签". Additionally, there are many cases of one term being translated into multiple equivalents, like "Artist" being translated as "艺人", "艺术家", and "作者", and "Collection" being translated as "合集", "收藏集", "选集", and "收集". Furthermore, there are semantic expression issues in the current translations, making it difficult for Chinese users to understand the meaning of certain features despite being translated into Chinese.

As Plex is a cross-platform application service, there are many contents that need to be translated per platform, such as Android, Apple, web, and server. For untranslated (unreviewed) strings, we are free to translate and modify them. However, for reviewed (approved) strings, we don't have the authority to make changes. As mentioned earlier, many approved translations have issues, and since we don't have the right to modify them, there seems to be no way to intervene through official channels. Additionally, since untranslated strings can be freely modified, directly modifying or submitting translations on the official project might be subject to further changes by others. Therefore, I have decided to create my own Plex translation project, adhering to what I consider standard practices for Plex localization, and share the translated language pack with everyone.

## Translation Progress
<img width="100%" alt="进度" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/67d1ad3e-d4fb-4e0a-b3ae-74d786091a50">

The blue part in the figure below represents the official translation, while the green part represents my translation. The translation for Plex Media Server will be applied to all-platform applications like Plex, Plex Web, Plex HTPC, Plexamp, and Plex Dash, while the translation for Web Clients will be applied to the Plex desktop application as well as Plex Web accessed via IP or custom domain. (Translation will continue to be updated)


## Demo
Below are partial comparisons of translated content. The left side shows the Plex official version, while the right side shows my version. The screenshots are from Plex for MacOS client.

<img width="100%" alt="1" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2f794399-31e9-4a3f-875c-32a81abad90e">

<img width="100%" alt="2" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ad5d6fb0-b7a0-4b26-8ae2-46da94d785cf">

<img width="100%" alt="3" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ebad1efa-a2f9-4eeb-bba4-6adf0cc3db03">

<img width="100%" alt="4" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/4fc5e445-08a6-4fd5-a3ab-5cdf01586806">

<img width="100%" alt="5" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/7b755f91-206f-4bd4-ab21-ae5cd877bff0">

<img width="100%" alt="6" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ba017732-e67a-4d48-bafb-ca7e3ab18f49">

<img width="100%" alt="7" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1b4f0ef3-0cec-454d-80e7-406ddbfa5277">

<img width="100%" alt="8" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/030c1e6c-a4cf-47b8-8206-0fdb9e07f715">

<img width="100%" alt="9" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/873649a0-1ec1-445a-85d5-4a3f669b27ab">

<img width="100%" alt="10" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/3cb96d7e-6f79-4449-9d50-8bb2a107266a">

<img width="100%" alt="11" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/68ca7f6a-987a-4e1d-a8c7-4d42a532cdc0">

<img width="100%" alt="12" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2be900ea-bf89-424c-bfdd-2ba601768130">

<img width="100%" alt="13" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1ebe644b-69ca-40da-8947-b0ce701dd958">

<img width="100%" alt="14" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/b4f3d90b-1b0d-4252-a073-2b70bb005b45">

<img width="100%" alt="15" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1d8f8894-bfee-4227-8a25-1ce2cc494351">

## Supported Platforms
### Plex Desktop
- Plex for MacOS
- Plex for Windows
- Plex for Linux

### Plex Web
- Plex Web access via IP or custom domain

### Plex Media Server
- Plex Media Server for MacOS
- Plex Media Server for Windows
- Plex Media Server for Linux
- Plex Media Server for Docker
- Plex Media Server for NAS (packages)

## Usage
### Plex Desktop
Please download the `zh.json` file from the Web Clients folder and replace the `zh.json` file in your Plex directory. Restart the Plex client for the changes to take effect (Ensure file permissions and modes match the original). You can find your `zh.json` file in a directory similar to the following:
```
# MacOS
/Applications/Plex.app/Contents/Resources/web-client/translations/zh.json

# Windows
C:\Program Files\Plex\Plex\web-client\translations\zh.json
```

### Plex Web
Please download the `zh.json` file from the Web Clients folder and replace the `zh.json` file in your Plex Media Server directory. Restart the Plex Media Server for the changes to take effect (Ensure file permissions and modes match the original). You can find your `zh.json` file in a directory similar to the following (The `Plug-ins-c0dd5a73e` will change with the version of Plex Media Server):
```
# MacOS
/Applications/Plex Media Server.app/Contents/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# Windows
C:\Program Files\Plex\Plex Media Server\Resources\Plug-ins-c0dd5a73e\WebClient.bundle\Contents\Resources\translations\zh.json

# Docker
/usr/lib/plexmediaserver/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# QNAP
/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json

# Synology
/volume1/@appstore/PlexMediaServer/Resources/Plug-ins-c0dd5a73e/WebClient.bundle/Contents/Resources/translations/zh.json
```

### Plex Media Server
Please download the `plex.mo` file from the Plex Media Server folder and replace the `plex.mo` file in your Plex Media Server directory. Restart the Plex Media Server for the changes to take effect (Ensure file permissions and modes match the original). You can find your `plex.mo` file in a directory similar to the following:
```
# MacOS
/Applications/Plex Media Server.app/Contents/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# Windows
C:\Program Files\Plex\Plex Media Server\Resources\locale\zh_CN\LC_MESSAGES/plex.mo

# Docker
/usr/lib/plexmediaserver/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# QNAP
/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo

# Synology
/volume1/@appstore/PlexMediaServer/Resources/locale/zh_CN/LC_MESSAGES/plex.mo
```

## Notes
- The provided file paths are for reference only. Due to differences in installation settings, the file paths may not be exactly the same. Please look for the files in a similar directory structure.
- For Plex Media Server installed via Docker, please locate and replace files within the container directory (Not the mapped directory).
- It is recommended to back up your original `zh.json` and `plex.mo` files before replacing them so that you can revert to the official version if needed.
- The language pack will be continuously updated. You can star this repository to get the latest version promptly. Certain translations may change in subsequent versions as needed.
- After updating the Plex desktop client or Plex Media Server version, the language pack will be reset. Please replace the language pack again after updating the version.
