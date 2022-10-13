---
title: Tags
tags:
---
## Tags for Games
 - Game.raw/translated
 --- 用于描述该游戏是否有汉化版。只要有一个Release标注为有中文，即标注为translated。
 --- [raw](./raw)
 --- [translated](./translated)
 - Game.not-playable
 --- 用于描述该游戏整体是否可玩。所有游戏默认不使用此tag。如果游戏没有任何已收集的Release或没有任何标注为complete的Release可玩性为playable及以上，即标注为not-playable。
 --- [not-playable](./not-playable)
 - Game.unofficial
 --- 在VNDB上，unofficial用于描述VN间的关系，而且是双向的——我认为这不太合理。在这里，unofficial这个标签用于描述游戏自身，而非关系。另外，在VNDB上，unofficial还用于描述Release，在这里将改用homebrew描述此类非官方的release。
 --- [unofficial](./unofficial)

## Tags for Releases
 - Release.platform(Windows, PS3, Xbox360, and else)
 --- 用于描述该游戏版本的平台。某些release可能会有多个平台标签，这可能是因为这个游戏使用了跨平台引擎并预留了多个可执行文件，或是官方的移植版本（PSX2PSP，PSX2PS3），但可以用旧平台的模拟器运行。
 --- [Windows](./windows)
 --- [PS1](./ps1)
 - Release.language(Chinese, Japanese, English, and else)
 --- 用于描述该游戏版本所用的语言。可以有多个。此处按VNDB的早期标准，不区分繁体中文和简体中文。有些游戏在购买页面显示多语言，但实际在下载时只能选择其中一个，此时将只标注收集版本的语言，因此将和VNDB的release页面标注有所不同。
 --- [Chinese](./chinese)
 --- [Japanese](./japanese)
 - Release.compatibility(playable, ingame, loadable, crash, not-tested)
 --- 用于描述该游戏版本的运行状态。根据各个模拟器的compatibility分类简化而来。这一描述将综合个人测试结果和其他用户贡献的测试结果。
 --- playable表示游戏几乎完全可玩，只有少量基本不影响游戏体验的问题。ingame表示可以进入游戏，有基本正确的响应内容，但无法体验完整内容。loadable表示游戏可以引导，但没有正确的输出内容，无法进行游戏。crash表示完全无法进入游戏。not-tested表示该游戏未经测试。
 --- 对于主机平台的游戏，这一信息仅代表模拟器上的表现。如果您希望在破解的游戏机上使用这些内容，请自行测试且后果自负。
 --- 对于Windows平台的游戏，可能因为系统版本不匹配、驱动异常、相关API异常、缺少相关运行环境等问题而无法运行或出现各种小错误，此类问题过于杂乱且因设备而异，故不进行描述。只要该游戏版本在Windows7或更高的系统上不经太过复杂的处理成功运行过一次，即标注为playable。如果出现普遍性的问题，才会使用其他描述。
 --- [playable](./playable)
 --- [ingame](./ingame)
 --- [loadable](./loadable)
 --- [crash](./crash)
 --- [not-tested](./not-tested)
 - Release.completeness(complete, partial, trial)
 --- 用于描述游戏版本的完整性。参考VNDB的标注，设置complete, partial, trial三个档次。使用此tag的游戏版本默认为“包含完整游戏文件的、独立的可执行文件”。
 --- [complete](./complete)
 --- [partial](./partial)
 --- [trial](./trial)
 - Release.patch/UPD
 --- 用于描述游戏版本的程序的完整性。使用此tag的游戏版本默认为“不包含完整游戏文件的内容”、“无法独立运行的可执行文件”或“不包含可执行文件”。
 --- [patch](./patch)
 - Release.early-version
 --- 用于描述游戏版本是否为早期版本。
 - Release.all-aged
 --- 使用此tag表示该游戏有着“有年龄限制的”版本，而此游戏版本不包含此类内容。
 --- [all-aged](./all-aged)