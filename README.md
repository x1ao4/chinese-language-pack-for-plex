# plex-locale-zhcn
Plex 的本地化工作并不是由专业团队完成的，而是通过翻译平台 Transifex 的[公开项目](https://explore.transifex.com/plex-1/)，由各国的志愿者自发参与翻译完成的。参与翻译的人员比较比较多，构成复杂，翻译工作的时间跨度比较大，并且缺乏统一的管理和审核，目前，虽然汉化工作基本上已经完成，但是依然存在大量错误或者不恰当的翻译，整体汉化质量一般。

据我所知，Plex 的简体中文翻译板块已经很多年没有审核人员了，并且似乎也无法再进行申请（可能已经取消审核流程了）。早期的审核人员审核通过了很多错误的翻译，比如 “Studio（制片公司）” 被翻译为了 “演播室”，“Record Label（唱片公司）” 被翻译为了 “录音标签” 等等；目前使用的翻译还存在很多一词多译的情况，比如 “Artist” 同时存在 “艺人、艺术家、作者” 三种翻译，“Collection” 同时存在 “合集、收藏集、选集、收集” 四种翻译等等；此外，目前的翻译还存在很多语义表达上的问题，导致很多功能的描述虽然翻译为了中文，但是中文用户却难以理解其含义。

因为 Plex 是一个跨平台的应用服务，有很多内容需要分平台进行翻译，比如安卓端、苹果端、网页端、服务器等都有单独的翻译项目，对于未审核（未复核）的字符串，我们是可以自由进行翻译和修改的，但是已审核（已复核）的字符串我们就无权修改了，如上所述，有很多已审核的翻译是存在问题的，由于我们无权进行修改，通过官方渠道似乎没有什么办法干预，同时也因为未审核的字符串可以被随意修改，直接在官方项目上修改或提交翻译也可能被其他人再次改动，所以我决定自己建立一个 Plex 的翻译项目，按照我认为规范的方式对 Plex 进行汉化，并将汉化后的语言包共享给大家使用。

## 效果展示
以下为部分翻译内容对比，左侧为 Plex 官方翻译，右侧为 plex-locale-zhcn 非官方翻译。plex-locale-zhcn 的翻译覆盖范围主要是桌面端和服务器，对服务器进行的翻译会对所有 Plex 客户端内调用服务器数据的部分生效，下图使用的是 Plex for Mac 客户端。

<img width="100%" alt="1" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2f794399-31e9-4a3f-875c-32a81abad90e">

<img width="100%" alt="2" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ad5d6fb0-b7a0-4b26-8ae2-46da94d785cf">

<img width="100%" alt="3" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/18a11cf2-f1c1-41e6-8d77-fbe6c52d85ab">

<img width="100%" alt="4" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/94344a3e-78b4-498f-867c-96b305e22cce">

<img width="100%" alt="5" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/7ee12fa6-2671-4df6-b5ee-d373c3f86c86">

<img width="100%" alt="6" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/ba017732-e67a-4d48-bafb-ca7e3ab18f49">

<img width="100%" alt="7" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/1b4f0ef3-0cec-454d-80e7-406ddbfa5277">

<img width="100%" alt="8" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/030c1e6c-a4cf-47b8-8206-0fdb9e07f715">

<img width="100%" alt="9" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/873649a0-1ec1-445a-85d5-4a3f669b27ab">

<img width="100%" alt="10" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/3cb96d7e-6f79-4449-9d50-8bb2a107266a">

<img width="100%" alt="11" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/68ca7f6a-987a-4e1d-a8c7-4d42a532cdc0">

<img width="100%" alt="12" src="https://github.com/x1ao4/plex-locale-zhcn/assets/112841659/2be900ea-bf89-424c-bfdd-2ba601768130">
