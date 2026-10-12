# MoviePilot 现行媒体优先级规则

线上核对时间：2026-10-12 17:20:04+08:00（北京时间）。

范围：资源筛选、自定义规则和媒体类型优先级。本文不包含刷流、换源、空间保护或删种策略；没有修改线上设置。

## 1. 如何理解排序

🛑 前置过滤 → 🚫 排除原盘 / ISO / REMUX → 🈶 中文字幕证据 → 🎞️ 所属媒体类别的基础层级 → 🔤 同层字幕排序。

各类别列表从上到下优先级降低。“＋”表示必须同时满足。规则按首个匹配分支确定优先级，不是把命中条件逐项相加；字幕优先只在同一个基础层级内生效。前置过滤和各类别自身均含中文字幕及原盘排除条件。

**所有类别共同要求：有中文字幕标记，拒绝无中字／无字幕标记；排除BD原盘、ISO和任何REMUX。蓝光压制、BDRip、BRRip仍可被允许。**

前置过滤另外排除3D，以及全局质量排除项和被屏蔽的制作组；DVP8规则排除标记DV却未标记HDR的资源。它依据描述判断兼容性，不能核实真实Dolby Vision Profile。

## 2. 字幕内部排序

### 外语电影、欧美剧、日番、日韩剧、欧美漫

🥇 简体中文＋外语同屏双语 → 🥈 简体中文字幕（未命中同屏双语） → 🥉 其他中文字幕＋外语同屏双语 → ④ 其他中文字幕（未命中同屏双语）。

“其他中文字幕”包含繁体以及未明确简繁的中文资源；“简繁共同提供”可以命中简体优先。同层的简体单语排在繁体双语之前，以保留你要求的简体优先。

双语要求同一条字幕同时显示中文和外语；支持中英、中日、中德、中法、中韩等明确双语描述。仅双语音轨、可分别切换的两条字幕轨、标明非同屏的资源，不获得这项加分。“简日／繁日”单独出现不一定能证明同屏双语。

### 动画电影、华语电影、国漫、纪录片、综艺、国产剧、现场

🥇 简体中文字幕 → 🥈 其他中文字幕；这些类别当前没有独立的同屏双语加分。

**特效字幕层级保留在电影和原有相应类别中。** 双语没有取代特效字幕，也不会跨越画质、来源、特效字幕或制作组的基础层级。

## 3. 各媒体类型的现行优先顺序

每一行均隐含“中文字幕硬条件＋原盘/ISO/REMUX排除”。一行再按第2节展开为2层或4层。

### 🍿 动画电影

15个基础层级，字幕展开后30个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 |
| 2 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR ＋ ✨ 特效字幕 |
| 3 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 |
| 4 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR |
| 5 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 |
| 6 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 7 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 |
| 8 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ ✨ 特效字幕 |
| 9 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ ✨ 特效字幕 |
| 10 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 |
| 11 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR |
| 12 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 13 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 |
| 14 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 15 | 🖥️ 1080p ＋ 🌐 WEB-DL |

### 🇨🇳 华语电影

12个基础层级，字幕展开后24个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 |
| 2 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR ＋ ✨ 特效字幕 |
| 3 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 |
| 4 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR |
| 5 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 |
| 6 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 7 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 |
| 8 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR |
| 9 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ HQ |
| 10 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 11 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 12 | 🖥️ 1080p ＋ 🌐 WEB-DL |

### 🎬 外语电影

15个基础层级，字幕展开后60个分支；同层简体与双语排序。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 |
| 2 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR ＋ ✨ 特效字幕 |
| 3 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 杜比视界 |
| 4 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🌈 HDR |
| 5 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 |
| 6 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 7 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 |
| 8 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ ✨ 特效字幕 |
| 9 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ ✨ 特效字幕 |
| 10 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 |
| 11 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR |
| 12 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 13 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 |
| 14 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 15 | 🖥️ 1080p ＋ 🌐 WEB-DL |

### 🗾 日番

16个基础层级，字幕展开后64个分支；同层简体与双语排序。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 ＋ 🏅 动漫优选制作组 ＋ 🖥️ 4K |
| 2 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 ＋ 🖥️ 4K |
| 3 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🖥️ 4K |
| 4 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 4K ＋ Crunchyroll |
| 5 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 4K ＋ Amazon |
| 6 | 🏅 动漫优选制作组 ＋ Netflix ＋ 🖥️ 4K ＋ 🌐 WEB-DL |
| 7 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 4K |
| 8 | 🖥️ 4K |
| 9 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 ＋ 🏅 动漫优选制作组 ＋ 🖥️ 1080p |
| 10 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 ＋ 🖥️ 1080p |
| 11 | 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🖥️ 1080p |
| 12 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 1080p ＋ Crunchyroll |
| 13 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 1080p ＋ Amazon |
| 14 | 🏅 动漫优选制作组 ＋ Netflix ＋ 🖥️ 1080p ＋ 🌐 WEB-DL |
| 15 | 🌐 WEB-DL ＋ 🏅 动漫优选制作组 ＋ 🖥️ 1080p |
| 16 | 🖥️ 1080p |

### 🌎 欧美漫

8个基础层级，字幕展开后32个分支；同层简体与双语排序。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 |
| 2 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 3 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 4 | 🖥️ 4K |
| 5 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ H.265 |
| 6 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 7 | 🖥️ 1080p ＋ 🌐 WEB-DL |
| 8 | 🖥️ 1080p |

### 🐉 国漫

6个基础层级，字幕展开后12个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 🏅 动漫优选制作组 ＋ 🔊 DDP |
| 2 | 🖥️ 4K ＋ 🏅 动漫优选制作组 |
| 3 | 🖥️ 4K |
| 4 | 🖥️ 1080p ＋ 🏅 动漫优选制作组 |
| 5 | 🖥️ 1080p |
| 6 | 🖥️ 720p |

### 🌿 纪录片

4个基础层级，字幕展开后8个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 2 | 🖥️ 4K |
| 3 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 4 | 🖥️ 1080p |

### 🎤 综艺

5个基础层级，字幕展开后10个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 🏅 优先制作组 ＋ 📚 全集 |
| 2 | 🖥️ 4K ＋ 🏅 优先制作组 |
| 3 | 🖥️ 4K |
| 4 | 🖥️ 1080p ＋ 🏅 优先制作组 |
| 5 | 🖥️ 1080p |

### 📺 国产剧

9个基础层级，字幕展开后18个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ HQ ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 2 | 🖥️ 4K ＋ UHD |
| 3 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ 🏅 优先制作组 |
| 4 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🏅 优先制作组 |
| 5 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 6 | 🖥️ 4K |
| 7 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 8 | 🖥️ 1080p ＋ 🌐 WEB-DL |
| 9 | 🖥️ 1080p |

### 🌍 欧美剧

21个基础层级，字幕展开后84个分支；同层简体与双语排序。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ UHD ＋ H.265 ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 2 | 🖥️ 4K ＋ UHD ＋ H.265 ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 3 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 4 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 5 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 6 | 🖥️ 4K ＋ ✨ 特效字幕 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 7 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 8 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 杜比视界 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 9 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 10 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 11 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 12 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 13 | 🖥️ 4K ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 14 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 15 | 🖥️ 1080p ＋ 🌐 WEB-DL ＋ ✨ 特效字幕 ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 16 | 🖥️ 1080p ＋ ✨ 特效字幕 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 17 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 18 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 19 | 🖥️ 1080p ＋ 🌐 WEB-DL ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 20 | 🖥️ 1080p ＋ 🌐 WEB-DL ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 21 | 🖥️ 1080p ＋ 📏 剧集体积过滤（每集≤10 GiB） |

### 🇯🇵 日韩剧

9个基础层级，字幕展开后36个分支；同层简体与双语排序。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ HQ ＋ 🏅 优先制作组 ＋ 📏 剧集体积过滤（每集≤10 GiB） |
| 2 | 🖥️ 4K ＋ UHD |
| 3 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🌈 HDR ＋ 🏅 优先制作组 |
| 4 | 🖥️ 4K ＋ 🌐 WEB-DL ＋ 🏅 优先制作组 |
| 5 | 🖥️ 4K ＋ 🌐 WEB-DL |
| 6 | 🖥️ 4K |
| 7 | 🖥️ 1080p ＋ 💿 蓝光压制（BluRay / BDRip / BRRip） |
| 8 | 🖥️ 1080p ＋ 🌐 WEB-DL |
| 9 | 🖥️ 1080p |

### 🎵 现场

3个基础层级，字幕展开后6个分支；同层简体优先。

| 顺位 | 同时满足的条件 |
|---|---|
| 1 | 🖥️ 4K |
| 2 | 🖥️ 1080p |
| 3 | 非720p |

## 4. 19条自定义规则

| 标识 | 名称 | 实际用途 |
|---|---|---|
| Complete | 完结 | 识别完结、合集、Complete、全/共若干集或期；用于综艺全集优先。 |
| filterGlobal | 全局过滤 | 排除日语无字、先行、MiniBD、iPad、UPSCALE、BDMV、RMVB、CAMRip、DVD、vcd、480p等标记。 |
| filterGroup | 组过滤 | 排除SubsPlease、Up to 21°C、TELESYNC、sGnb、BHYS、DBD、HDH、COLLECTiVE、SRVFI、YTS.MX、HDSPad。 |
| filterMovie | 电影体积过滤 | 体积范围0–1000000 MiB；当前13个优先级组未引用，不能当作有效的电影体积限制。 |
| filterSeries | 剧集体积过滤 | 按识别出的集数计算每集大小≤10 GiB；未识别集数时按1集计算。所有欧美剧层级使用，国产剧/日韩剧仅首个HQ层级使用。 |
| Crunchyroll | CR源 | 识别CR/Crunchyroll，用于日番WEB来源细分。 |
| Netflix | NF源 | 识别NF/Netflix，用于日番WEB来源细分。 |
| AMZN | AMZN源 | 识别AMZN/Amazon，用于日番WEB来源细分。 |
| HQ | 高码 | 依据HQ、高码、EDR文字判断；不是测量实际视频码率。 |
| DVP8 | 杜比P8 | 排除有DV/dovi/DoVi但无HDR标记的资源；名称虽为杜比P8，实际逻辑不能核实文件的Dolby Vision Profile。 |
| DDP | 杜比音轨 | 识别DDP、DDPlus、EAC3、E-AC-3、DD+音轨，用于国漫优先级。 |
| WhiteList | 白名单 | 较长的发布组/字幕组名单；当前13个优先级组未引用，不作为现行下载白名单。 |
| PreferenceGroup | 优先组 | 优先制作组：QHstudIo、CHDWEB、HDSWEB、CMCTV、ADWeb、HHWEB、FROGWeb、ADE、FROGE。 |
| CNSubStrict | 中文字幕硬条件 | 必须有中文字幕证据；支持中字、简/繁中文、CHS/CHT及明确中外双语字幕等；同时排除无字幕/无中文字样。 |
| CNSimp | 简体中文字幕优先 | 简体中文、简繁共同提供等标记优先；仅在同一基础层级内部比较。 |
| NoDiscISO | 排除原盘、ISO及REMUX | 所有优先级组硬性排除原盘、ISO、BDMV、BD25/50/66/100、MiniBD、REMUX及重封装等；刷流另有相同标题/简介排除。 |
| CNDual | 中外同屏双语字幕优先 | 同屏中文＋外语双语加分，支持中英/中日/中德/中法/中韩等；明确音轨/配音/非同屏/独立切换不加分。 |
| BluRayEncode | 蓝光压制来源（含BDRip/BRRip） | 新增蓝光压制来源规则，匹配BluRay、Blu-Ray、Blu.Ray、Blu Ray、BDRip、BD-Rip、BRRip及大小写变体；不改变原盘/REMUX排除。 |
| AnimePreferenceGroup | 动漫优选制作组 | 仅日番和国漫引用；保留原优选组并加入VCB-Studio、7³ACG/73ACG。 |

## 5. 适用入口和范围

当前搜索、订阅和洗版入口均引用以下13个同名规则组：前置过滤、动画电影、华语电影、外语电影、日番、欧美漫、国漫、纪录片、综艺、国产剧、欧美剧、日韩剧、现场。类别规则按实际媒体类型及分类匹配；单个订阅指定规则组、识别词或额外过滤时，还会受到该订阅设置约束。

这些是搜索或后续下载选择规则，不会重命名、重新下载或删除已入库的电影。洗版只有在对应功能和订阅实际启用时才会执行。

## 6. 当前规则的边界与取舍

- 画质／来源／制作组的基础顺序先于字幕比较，因此低层双语资源不一定胜过高层单语资源。
- 未标注字幕的资源会被拒绝，即使实际文件中可能有中文字幕；相反，标题或简介声称有中文字幕，也不能保证文件内真实存在。规则依据资源文本，不读取每个候选视频验证字幕。
- 特效字幕并非全局最高条件：必须看第3节具体分支的位置。
- 简体优先在同一基础层级内成立，不能解释成所有简体资源都排在所有繁体资源前面。
- 日番、欧美漫最低分辨率分支为1080p；国漫仍有720p兜底；现场末级为非720p，并非严格1080p下限。
- 动漫优选制作组只用于日番、国漫；电影和其他类别的制作组条件保持各自规则。
- `filterSeries`按识别到的集数计算每集体积；识别不到集数时按单集计算。`filterMovie`及`WhiteList`未被现行13组引用，不能当成正在执行的电影体积限制或发布组白名单。

## 附录A：当前优先级表达式原文

用于逐条核对或后续调整。`>`从左到右优先级递减；`&`表示同时满足；`!`表示不匹配该条件。为便于阅读，每个分支单独成行，顺序未改动。

### 前置过滤

```text
!3D & DVP8 & filterGlobal & filterGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
!3D & DVP8 & filterGlobal & filterGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 动画电影

```text
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 华语电影

```text
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & HQ & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HQ & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 外语电影

```text
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & DOLBY & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & DOLBY & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & SPECSUB & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual
```

### 日番

```text
BluRayEncode & H265 & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
BluRayEncode & H265 & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & H265 & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & H265 & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & H265 & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
BluRayEncode & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
AnimePreferenceGroup & Netflix & 4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
AnimePreferenceGroup & Netflix & 4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
AnimePreferenceGroup & Netflix & 4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
AnimePreferenceGroup & Netflix & 4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & H265 & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
BluRayEncode & H265 & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & H265 & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & H265 & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & H265 & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
BluRayEncode & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
BluRayEncode & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
BluRayEncode & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
BluRayEncode & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & Crunchyroll & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & AMZN & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
AnimePreferenceGroup & Netflix & 1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
AnimePreferenceGroup & Netflix & 1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
AnimePreferenceGroup & Netflix & 1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
AnimePreferenceGroup & Netflix & 1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
WEBDL & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
WEBDL & AnimePreferenceGroup & 1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual
```

### 欧美漫

```text
4K & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & H265 & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual
```

### 国漫

```text
4K & AnimePreferenceGroup & DDP & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & AnimePreferenceGroup & DDP & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & AnimePreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & AnimePreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & AnimePreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & AnimePreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
720P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
720P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 纪录片

```text
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 综艺

```text
4K & PreferenceGroup & Complete & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & PreferenceGroup & Complete & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 国产剧

```text
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

### 欧美剧

```text
4K & UHD & H265 & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & UHD & H265 & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & UHD & H265 & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & UHD & H265 & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & UHD & H265 & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & UHD & H265 & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & UHD & H265 & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & UHD & H265 & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & DOLBY & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & DOLBY & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & DOLBY & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & DOLBY & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & DOLBY & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & DOLBY & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & DOLBY & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & DOLBY & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & DOLBY & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & SPECSUB & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & SPECSUB & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual
```

### 日韩剧

```text
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HQ & PreferenceGroup & filterSeries & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & UHD & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & HDR & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & PreferenceGroup & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & BluRayEncode & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & WEBDL & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp & !CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & CNDual >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp & !CNDual
```

### 现场

```text
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
4K & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
1080P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp >
!720P & CNSubStrict & NoDiscISO & !BLU & !REMUX & CNSimp >
!720P & CNSubStrict & NoDiscISO & !BLU & !REMUX & !CNSimp
```

## 附录B：当前自定义匹配条件原文

### Complete — 完结

```json
{
  "id": "Complete",
  "name": "完结",
  "include": "(全|共)\\d+(集|期)|完结|合集|Complete",
  "exclude": ""
}
```

### filterGlobal — 全局过滤

```json
{
  "id": "filterGlobal",
  "name": "全局过滤",
  "include": "",
  "exclude": "(?i)日语无字|先行|MiniBD|iPad|UPSCALE|BDMV|RMVB|CAMRip|DVD|vcd|480p"
}
```

### filterGroup — 组过滤

```json
{
  "id": "filterGroup",
  "name": "组过滤",
  "include": "",
  "exclude": "(?i)SubsPlease|Up to 21°C|TELESYNC|sGnb|BHYS|DBD|HDH|COLLECTiVE|SRVFI|YTS\\.MX|HDSPad"
}
```

### filterMovie — 电影体积过滤

```json
{
  "id": "filterMovie",
  "name": "电影体积过滤",
  "include": "",
  "exclude": "",
  "size_range": "0-1000000"
}
```

### filterSeries — 剧集体积过滤

```json
{
  "id": "filterSeries",
  "name": "剧集体积过滤",
  "include": "",
  "exclude": "",
  "size_range": "0-10240"
}
```

### Crunchyroll — CR源

```json
{
  "id": "Crunchyroll",
  "name": "CR源",
  "include": "(?i)\\b(CR|Crunchyroll)\\b",
  "exclude": ""
}
```

### Netflix — NF源

```json
{
  "id": "Netflix",
  "name": "NF源",
  "include": "(?i)\\b(NF|Netflix)\\b",
  "exclude": ""
}
```

### AMZN — AMZN源

```json
{
  "id": "AMZN",
  "name": "AMZN源",
  "include": "(?i)\\b(AMZN|Amazon)\\b",
  "exclude": ""
}
```

### HQ — 高码

```json
{
  "id": "HQ",
  "name": "高码",
  "include": "(?i)HQ|高码|EDR",
  "exclude": ""
}
```

### DVP8 — 杜比P8

```json
{
  "id": "DVP8",
  "name": "杜比P8",
  "include": "",
  "exclude": "^(?!.*HDR).*(DV|dovi|DoVi)"
}
```

### DDP — 杜比音轨

```json
{
  "id": "DDP",
  "name": "杜比音轨",
  "include": "(?<![A-Za-z0-9])(?:DDP|DDPlus|EAC3|E-AC-3)(?=[0-9 ._+-]|$)|(?<![A-Za-z0-9])DD\\+(?=[0-9 ._-]|$)",
  "exclude": ""
}
```

### WhiteList — 白名单

```json
{
  "id": "WhiteList",
  "name": "白名单",
  "include": "(Oldboys|GTR|RO|Telesto|CatEDU|PbK|Rainbaby|Ao|BMDru|c0kE|cfandora|jsum|RNML|FraMeSToR|ADE|CHD|CMCT|Sunny|WiKi|PTer|MTeam|FRDS|UBits|FROGE|beAst|Dream|BeiTai|RLeaves|R²|PTH|HDChina|LHD|ZONE|btshd|ADWeb|HHWEB|CHDWEB|CMCTV|TJUPT|OurTV|PTerWEB|MWeb|UBWEB|FROGWeb|QHstudIo|DBTV|RLWeb|LeagueWEB|HDCTV|ZWEX|ZmWeb|Kitsune|NTb|playWEB|BYNDR|FLUX|ETHEL|EDITH|VARYG|HONE|YingWEB|OPS|AilMWeb|ARiC|喵萌奶茶屋|豌豆字幕组|爱恋字幕社|漫猫字幕社|北宇治字幕组|云光字幕组|织梦字幕组|千夏字幕组|极影字幕社|风之圣殿字幕组|风车字幕组|银色子弹字幕组|熔岩动画|MingYSub|枫叶字幕组|诸神字幕组|AKito|秋人|霜庭云花Sub|轻之国度字幕组|星空字幕组|离谱Sub|雪飘工作室|拨雪寻春|新Sub|MCE汉化组|極彩字幕组|氢气烤肉架|悠哈璃羽字幕社|桜都字幕组|SweetSub|LoliHouse|&VCB-Studio|VCB-Studio&|7³ACG|幻之字幕组|魔穗字幕组|澄空学园|LittleBakas!|白恋字幕组|动漫国字幕组|FSD字幕组|FSD粉羽社|一只出格君|猫恋汉化组|OPFans枫雪动漫|GM-Team|康复重症监护室字幕组|SilverBullet|APTX4869|幻樱字幕组|永恒译制|咪梦字幕组|NEO·QSW)",
  "exclude": ""
}
```

### PreferenceGroup — 优先组

```json
{
  "id": "PreferenceGroup",
  "name": "优先组",
  "include": "(?i)QHstudIo|CHDWEB|HDSWEB|CMCTV|ADWeb|HHWEB|FROGWeb|ADE|FROGE",
  "exclude": ""
}
```

### CNSubStrict — 中文字幕硬条件

```json
{
  "id": "CNSubStrict",
  "name": "中文字幕硬条件",
  "include": "(?:中文|中英|英中|简体|簡體|繁体|繁體)[ ._-]*字幕|中字|简体|簡體|繁体|繁體|简中|簡中|繁中|中简|中簡|中繁|简英|簡英|繁英|英简|英簡|英繁|简日|簡日|繁日|简繁|簡繁|繁简|繁簡|中英双字|中英雙字|(?<![A-Za-z0-9])(?:CHS|CHT|BIG5|zh[ ._-]?(?:CN|TW|Hans|Hant))(?![A-Za-z0-9])|(?:(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))|(?:简体中文|簡體中文|繁体中文|繁體中文|中文)[ ._/+&＆-]*(?:和|与|與|及)?[ ._/+&＆-]*(?:英语|英語|英文|日语|日語|日文|德语|德語|德文|法语|法語|法文|韩语|韓語|韩文|韓文|西班牙语|西班牙語|意大利语|意大利語|俄语|俄語|葡萄牙语|葡萄牙語|阿拉伯语|阿拉伯語|泰语|泰語|越南语|越南語))[ ._-]*(?:同屏[ ._-]*)?(?:双语|雙語|双字|雙字)(?:[ ._-]*(?:字幕|内封|內封|内嵌|內嵌)|(?=[\\]】)）]|[ \\t]*$))|(?:双语|雙語)[ ._-]*字幕[^\\n]{0,12}(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))",
  "exclude": "(?:中文)?字幕[ ：:＝=（(]*\\s*(?:无|無|none|no\\b)|无中文字幕|無中文字幕|无中字|無中字|无字幕|無字幕|无字版|無字版|日语无字|日語無字|(?<![A-Za-z0-9])(?:NO[ ._-]?SUBS?|UNSUBBED|RAWS?)(?![A-Za-z0-9])"
}
```

### CNSimp — 简体中文字幕优先

```json
{
  "id": "CNSimp",
  "name": "简体中文字幕优先",
  "include": "简体|簡體|简中|簡中|中简|中簡|简英|簡英|英简|英簡|简日|簡日|简繁|簡繁|繁简|繁簡|(?<![A-Za-z0-9])(?:CHS|zh[ ._-]?(?:CN|Hans))(?![A-Za-z0-9])|(?:简|簡)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)[ ._-]*(?:双语|雙語|双字|雙字)(?:[ ._-]*(?:字幕|内封|內封|内嵌|內嵌)|(?=[\\]】)）]|[ \\t]*$))"
}
```

### NoDiscISO — 排除原盘、ISO及REMUX

```json
{
  "id": "NoDiscISO",
  "name": "排除原盘、ISO及REMUX",
  "exclude": "(?<![A-Za-z0-9])(?:ISO|BDISO|BDMV|BD25|BD50|BD66|BD100|MiniBD)(?![A-Za-z0-9])|原盘|原盤|原碟|蓝光完整盘|藍光完整碟|(?<![A-Za-z0-9])(?:COMPLETE|FULL)[ ._-]+(?:UHD[ ._-]+)?Blu[ ._-]?Ray(?![A-Za-z0-9])|RE[ ._-]*MUX|重封装|重封裝"
}
```

### CNDual — 中外同屏双语字幕优先

```json
{
  "id": "CNDual",
  "name": "中外同屏双语字幕优先",
  "include": "(?:(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))|(?:简体中文|簡體中文|繁体中文|繁體中文|中文)[ ._/+&＆-]*(?:和|与|與|及)?[ ._/+&＆-]*(?:英语|英語|英文|日语|日語|日文|德语|德語|德文|法语|法語|法文|韩语|韓語|韩文|韓文|西班牙语|西班牙語|意大利语|意大利語|俄语|俄語|葡萄牙语|葡萄牙語|阿拉伯语|阿拉伯語|泰语|泰語|越南语|越南語))[ ._-]*(?:同屏[ ._-]*)?(?:双语|雙語|双字|雙字)(?:[ ._-]*(?:字幕|内封|內封|内嵌|內嵌)|(?=[\\]】)）]|[ \\t]*$))|(?:双语|雙語)[ ._-]*字幕[^\\n]{0,12}(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))",
  "exclude": "(?:无|無|非|不含|不带|不帶)[ ._-]*(?:(?:(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))|(?:简体中文|簡體中文|繁体中文|繁體中文|中文)[ ._/+&＆-]*(?:和|与|與|及)?[ ._/+&＆-]*(?:英语|英語|英文|日语|日語|日文|德语|德語|德文|法语|法語|法文|韩语|韓語|韩文|韓文|西班牙语|西班牙語|意大利语|意大利語|俄语|俄語|葡萄牙语|葡萄牙語|阿拉伯语|阿拉伯語|泰语|泰語|越南语|越南語)))?[ ._-]*(?:双语|雙語|双字|雙字)|(?:(?:(?:简繁|簡繁|中|简|簡|繁)(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)|(?:印尼|印地|英|日|德|法|西|意|俄|韩|韓|葡|阿|泰|越|土|波)(?:简繁|簡繁|中|简|簡|繁))|(?:简体中文|簡體中文|繁体中文|繁體中文|中文)[ ._/+&＆-]*(?:和|与|與|及)?[ ._/+&＆-]*(?:英语|英語|英文|日语|日語|日文|德语|德語|德文|法语|法語|法文|韩语|韓語|韩文|韓文|西班牙语|西班牙語|意大利语|意大利語|俄语|俄語|葡萄牙语|葡萄牙語|阿拉伯语|阿拉伯語|泰语|泰語|越南语|越南語))[ ._-]*(?:双语|雙語)[ ._-]*(?:音轨|音軌|配音|音频|音頻)|非同屏|不同屏|独立字幕轨|獨立字幕軌|分别切换|分別切換"
}
```

### BluRayEncode — 蓝光压制来源（含BDRip/BRRip）

```json
{
  "id": "BluRayEncode",
  "name": "蓝光压制来源（含BDRip/BRRip）",
  "include": "(?<![A-Za-z0-9])(?:Blu[ ._-]?Ray|BD[ ._-]?Rip|BR[ ._-]?Rip)(?![A-Za-z0-9])"
}
```

### AnimePreferenceGroup — 动漫优选制作组

```json
{
  "id": "AnimePreferenceGroup",
  "name": "动漫优选制作组",
  "include": "(?i)QHstudIo|CHDWEB|HDSWEB|CMCTV|ADWeb|HHWEB|FROGWeb|ADE|FROGE|VCB[ ._-]?Studio|7[3³]ACG"
}
```


===============================================================================================================================================================================================

<h1 style="font-size:32px">自定义规则组</h1>

```
[{"id":"filterGlobal","name":"全局过滤","include":"","exclude":"(?i)日语无字|先行|MiniBD|DIY原盘|原盘|iPad|UPSCALE|AV1|BDMV|RMVB|CAMRip|DVD|vcd|480p|OPUS"},{"id":"Complete","name":"完结","include":"(全|共)\\d+(集|期)|完结|合集|Complete","exclude":""},{"id":"filerGroup","name":"组过滤","include":"","exclude":"(?i)SubsPlease|Up to 21°C|VARYG|TELESYNC|NTb|sGnb|BHYS|HDSWEB|DBD|HDH|COLLECTiVE|SRVFI|YTS.MX|HDSPad"},{"id":"filterMovie","name":"电影体积过滤","include":"","exclude":"","size_range":"0-1000000"},{"id":"Netflix","name":"NF源","include":"Netflix|NF","exclude":""},{"id":"AMZN","name":"AMZN源","include":"AMZN|Amazon","exclude":""},{"id":"HQ","name":"高码","include":"HQ|高码|EDR","exclude":""},{"id":"WhiteList","name":"白名单","include":"\\b(Oldboys|GTR|RO|Telesto|CatEDU|PbK|Rainbaby|Ao|BMDru|c0kE|cfandora|jsum|RNML|FraMeSToR|ADE|CHD|CMCT|Sunny|WiKi|PTer|MTeam|FRDS|UBits|FROGE|beAst|Dream|BeiTai|RLeaves|R²|PTH|HDChina|LHD|ZONE|btshd|ADWeb|HHWEB|CHDWEB|CMCTV|TJUPT|OurTV|PTerWEB|MWeb|UBWEB|FROGWeb|QHstudIo|DBTV|RLWeb|LeagueWEB|HDCTV|ZWEX|ZmWeb|Kitsune|NTb|playWEB|BYNDR|FLUX|ETHEL|EDITH|VARYG|HONE|YingWEB|OPS|AilMWeb|ARiC|喵萌奶茶屋|豌豆字幕组|爱恋字幕社|漫猫字幕社|北宇治字幕组|云光字幕组|织梦字幕组|千夏字幕组|极影字幕社|风之圣殿字幕组|风车字幕组|银色子弹字幕组|熔岩动画|MingYSub|枫叶字幕组|诸神字幕组|AKito|秋人|霜庭云花Sub|轻之国度字幕组|星空字幕组|离谱Sub|雪飘工作室|拨雪寻春|新Sub|MCE汉化组|極彩字幕组|氢气烤肉架|悠哈璃羽字幕社|桜都字幕组|SweetSub|LoliHouse|&VCB-Studio|VCB-Studio&|7³ACG|幻之字幕组|魔穗字幕组|澄空学园|LittleBakas!|白恋字幕组|动漫国字幕组|FSD字幕组|FSD粉羽社|一只出格君|猫恋汉化组|OPFans枫雪动漫|GM-Team|康复重症监护室字幕组|SilverBullet|APTX4869|幻樱字幕组|永恒译制|咪梦字幕组|NEO·QSW)\\b"},{"id":"PreferenceGroup","name":"剧集优先组","include":"ADWeb｜HHWEB｜CHDWEB｜OurTV｜HDSWEB｜UBWEB"},{"id":"RULE11","name":"杜比","include":"DV|DoVi"},{"id":"filterSeries","name":"剧集体积过滤","size_range":"3000-15000"}]
```

<h1 style="font-size:32px">优先级规则组</h1>

```
[{"name":"国漫","rule_string":" 4K & WEBDL &PreferenceGroup> 4K & WEBDL > 1080P & WEBDL &PreferenceGroup> 1080P & WEBDL ","media_type":"电视剧","category":"国漫"},{"name":"国产剧","rule_string":" 4K & WEBDL &PreferenceGroup&RULE11&filterSeries> 4K & WEBDL & HDR &PreferenceGroup&filterSeries> 4K & WEBDL &HQ&PreferenceGroup&filterSeries> 4K & WEBDL & 60FPS &PreferenceGroup&filterSeries> 4K & WEBDL & SDR &PreferenceGroup&filterSeries> 4K & WEBDL &PreferenceGroup&filterSeries> 4K & WEBDL &PreferenceGroup","media_type":"电视剧","category":"国产剧"},{"name":"日韩剧","rule_string":" SPECSUB & 1080P & BLURAY &filterSeries> CNSUB & 1080P &filterSeries& BLURAY > 1080P & CNSUB &filterSeries> CNSUB &filterSeries","media_type":"电视剧","category":"日韩剧"},{"name":"欧美剧","rule_string":" CNSUB & 4K & WEBDL & DOLBY &PreferenceGroup> CNSUB & 4K & WEBDL & HDR &PreferenceGroup> CNSUB & 4K & WEBDL &PreferenceGroup> CNSUB & 1080P & WEBDL & DOLBY &PreferenceGroup> CNSUB & 1080P & WEBDL & HDR &PreferenceGroup> CNSUB & 1080P & WEBDL &PreferenceGroup","media_type":"电视剧","category":"欧美剧"},{"name":"纪录片","rule_string":" 4K & BLURAY > 1080P & BLURAY > 4K > 1080P ","media_type":"电视剧","category":"纪录片"},{"name":"日番","rule_string":" BLURAY & H265 &PreferenceGroup& 1080P > BLURAY & H265 & CNSUB & 1080P > BLURAY & CNSUB & 1080P > WEBDL &PreferenceGroup& 1080P &Crunchyroll> WEBDL &PreferenceGroup& 1080P &AMZN>PreferenceGroup&Netflix& 1080P & WEBDL > WEBDL &PreferenceGroup& 1080P > 1080P & CNSUB > CNSUB ","media_type":"电视剧","category":"日番"},{"name":"欧美漫","rule_string":" BLURAY & H265 & CNSUB > BLURAY & CNSUB > WEBDL & CNSUB > CNSUB ","media_type":"电视剧","category":"欧美漫"},{"name":"综艺","rule_string":" 4K &PreferenceGroup&Complete> 4K &PreferenceGroup> 1080P &PreferenceGroup> 1080P ","media_type":"电视剧","category":"综艺"},{"name":"现场","rule_string":" CNSUB & 4K > CNSUB & 1080P > 4K > 1080P > !720P ","media_type":"电影","category":"现场"},{"name":"华语电影","media_type":"电影","category":"华语电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY > 4K & WEBDL & DOLBY > 4K & WEBDL & HDR > 4K & WEBDL &HQ> 4K & WEBDL > 1080P & BLURAY > 1080P & WEBDL "},{"name":"外语电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY & CNSUB > 4K & WEBDL & DOLBY & SPECSUB > 4K & WEBDL & HDR & SPECSUB > 4K & WEBDL & SPECSUB > 4K & WEBDL & DOLBY & CNSUB > 4K & WEBDL & HDR & CNSUB > 4K & WEBDL & CNSUB > 1080P & BLURAY & SPECSUB > 1080P & BLURAY & CNSUB > 1080P & WEBDL & CNSUB ","media_type":"电影","category":"外语电影"},{"name":"动画电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY & CNSUB > 4K & WEBDL & DOLBY & SPECSUB > 4K & WEBDL & HDR & SPECSUB > 4K & WEBDL & SPECSUB > 4K & WEBDL & DOLBY & CNSUB > 4K & WEBDL & HDR & CNSUB > 4K & WEBDL & CNSUB > 1080P & BLURAY & SPECSUB > 1080P & BLURAY & CNSUB > 1080P & WEBDL & CNSUB ","media_type":"电影","category":"动画电影"},{"name":"国产高码","rule_string":" 4K & WEBDL &HQ&PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产60fps","rule_string":" 4K & WEBDL & 60FPS &PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产杜比","rule_string":" 4K & WEBDL &PreferenceGroup&RULE11&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产HDR","rule_string":" 4K & WEBDL & HDR &PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"}]
```

<h1 style="font-size:32px">资源入库</h1>

```
{
        'title':'📂 已入库{{ file_count }}个文件\n'
                '{{ title_year }}',
        'text': '{% if season_episode %}\n📺 集数： {{ season_episode }}{% endif %}'
                '{% if category %}\n🎭 类别： {{ category }}{% endif %}'
                '{% if releaseGroup %}\n👥 小组： {{ releaseGroup }}{% endif %}'
                '{% if resource_term %}\n🌟 质量：{{ resource_term }}{% endif %}'
                '{% if audioCodec %} {{ audioCodec }}{% endif %}'
                '\n💾 大小： {{ total_size }}{% endif %}'
                '{% if overview %}🍿 简介：\n{{ overview }}{% endif %}'
                '{% if err_msg %}，以下文件处理失败：{{ err_msg }}{% endif %}'
    }
```

<h1 style="font-size:32px">资源下载</h1>

```
{
    'title': '📥 开始下载\n*[{{ title_year }}]({{ __mediainfo__.detail_link }})*'
            '{% if download_episodes %} ({{ season }} {{ download_episodes }})[https://www.themoviedb.org/tv/{{tmdbid}}/season/{{ season }}/episode/{{ download_episodes }}]{% else %}{{ season_episode }} {% endif %}',
    'text': '{% if pubdate %}\n🕒 时间： {{ pubdate }}{% endif %}'
            '{% if category %}\n🎭 类别： {{ category }}{% endif %}'
            '{% if site_name %}\n🌐 站点： {{ site_name }}{% endif %}'
            '{% if resource_term %}\n🌟 质量：{{ resource_term }}{% endif %}'
            '{% if size %}\n💾 大小： {{ size }}{% endif %}'
            '{% if seeders %}\n🌱 做种： {{ seeders }}{% endif %}'
            '{% if labels %}\n️🏷 标签： {{ labels }}{% endif %}'
            '{% if original_name %}\n📛 名称： \n{{ original_name }}{% endif %}'
            '{% if description %}\n\n📝 描述： {{ description }}{% endif %}'
            
}
```

<h1 style="font-size:32px">添加订阅</h1>

```
{
        'title': '🎞 {{ title_year }} {% if season %}{{season}}{% endif %} 已添加订阅',
        'text': '{% if vote_average %}✨ 评分：{{ vote_average }}/10\n{% endif %}'
                '{% if category %}📽 类型：{{ category }}\n{% endif %}'
                '{% if username %}👾 用户：{{ username }}\n\n{% endif %}'
                '{% if actors %}🤵 参演：{{ actors }}\n\n{% endif %}'
                '{% if overview %}🍿 简介：\n{{ overview }}{% endif %}'
    }
```

<h1 style="font-size:32px">订阅完成</h1>

```
{
  "title": "🎞 {{ title_year }} {% if season %}{{season}}{% endif %} 已完成订阅",
  "text": "{% if vote_average %}✨ 评分：{{ vote_average }}/10{% endif %}"
          "{% if username %}\n👾 用户：{{ username }}{% endif %}"
          "{% if overview %}\n\n🍿 简介：\n{{ overview }}{% endif %}"
}
```

<h1 style="font-size:32px">电影重命名</h1>

```
{{title}} ({{year}}) [tmdbid={{tmdbid}}] /{{original_name}}
```

<h1 style="font-size:32px">电视剧重命名</h1>

```
{{title}} ({{year}}) [tmdbid={{tmdbid}}] /{{original_name}}
```

<h1 style="font-size:32px">API令牌</h1>

```
HQfRBuEOcxcbcTZtYdmQQfEiZ
```

<h1 style="font-size:32px">Telegram</h1>

```
chai ID:866309914
Bot Token:8333940258:AAEBv-cLifls709SU_bo4Dg2GUp0MzCzTmc
```

<h1 style="font-size:32px">docker compose</h1>

```
version: '3'

services:

  moviepilot:
    stdin_open: true
    tty: true
    container_name: moviepilot-v2
    hostname: moviepilot-v2
    privileged: true
    devices:
      - '/dev/fuse:/dev/fuse'
    ports:
     - '3000:3000'
     - '3001:3001'
     - '8091:8091'
    volumes:
      - '/vol1/1000/CloudNAS:/cd2' #媒体
      - '/vol1/1000/mp-strm:/mp-strm'
      - '/vol1/1000/1E1TB:/vol1/1000/1E1TB' #媒体
      - '/vol2/1000/2E14T:/vol2/1000/2E14T' #媒体
      - '/vol3/1000/3E14T:/vol3/1000/3E14T' #媒体
      - './moviepilot-v2/config:/config' #持久化配置
      - './moviepilot-v2/core:/moviepilot/.cache/ms-playwright' #内核浏览器
      - '/var/run/docker.sock:/var/run/docker.sock:ro' #重启MP权限
    environment:
      - 'NGINX_PORT=3000'
      - 'PORT=3001'
      - 'PUID=0'
      - 'PGID=0'
      - 'UMASK=000'
      - 'TZ=Asia/Shanghai'
      - 'SUPERUSER=admin'
      - 'DB_TYPE=postgresql'
      - 'DB_POSTGRESQL_HOST=postgresql'
      - 'DB_POSTGRESQL_PORT=5432'
      - 'DB_POSTGRESQL_DATABASE=moviepilot'
      - 'DB_POSTGRESQL_USERNAME=moviepilot'
      - 'DB_POSTGRESQL_PASSWORD=pg_password'
      - 'CACHE_BACKEND_TYPE=redis'
      - 'CACHE_BACKEND_URL=redis://:redis_password@redis:6379'
      - 'PROXY_HOST=http://10.0.0.100:7890' # 代理地址
      - 'API_TOKEN=HQfRBuEOcxcbcTZtYdmQQfEiZ'
#      - 'GITHUB_TOKEN=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' #修改为自己的GITHUB_TOKEN
#      - 'MOVIEPILOT_AUTO_UPDATE=false' #关闭重启时的自动升级功能 自动升级：MOVIEPILOT_AUTO_UPDATE=release
#      - 'AUTO_UPDATE_RESOURCE=false'   #关闭自动更新资源包功能   关闭自动升级：MOVIEPILOT_AUTO_UPDATE=false
# CookieCloud设置
      - 'COOKIECLOUD_HOST=https://ck.599000.xyz:59999'   #CookieCloud服务器地址 必须添加
      - 'COOKIECLOUD_KEY=hjDyRh4KpcbxpJa9VTB8ZH'  #cc用户KEY
      - 'COOKIECLOUD_PASSWORD=uAm24GGnCcmKXkKqxiFWYb'  #cc端对端加密密码  
# 用户认证
      - 'AUTH_SITE=audiences'  #认证站点
      - 'AUDIENCES_UID=10229' # 观众 ID 
      - 'AUDIENCES_PASSKEY=8d451667e4e1eaa6f61813e6cfb43cdd ' # 观众 passkey
#重命名格式
#      - 'TV_RENAME_FORMAT={{title}}{% if year %} ({{year}}){% endif %} {% if tmdbid %}[tmdbid={{tmdbid}}]{% endif %}{% if season %}/Season {{season}}/{% endif %}{{original_name}}'  # 电视剧
#      - 'MOVIE_RENAME_FORMAT={{title}}{% if year %} ({{year}}){% endif %} {% if tmdbid %}[tmdbid={{tmdbid}}]{% endif %}/{{original_name}}'  # 电影

    restart: always
    depends_on:
      postgresql:
        condition: service_healthy
      redis:
        condition: service_healthy
    image: jxxghp/moviepilot-v2:latest

  redis:
    container_name: moviepilot-redis
    volumes:
        - ./redis/data:/data
    image: redis:7.2.11
    restart: always
    command: redis-server --save 600 1 --requirepass redis_password
    healthcheck:
      test: ["CMD", "redis-cli", "--raw", "incr", "ping"]
      interval: 10s
      timeout: 5s
      retries: 5

  postgresql:
    container_name: moviepilot-postgresql
    image: postgres:17.6
    restart: always
    environment:
      POSTGRES_DB: moviepilot
      POSTGRES_USER: moviepilot
      POSTGRES_PASSWORD: pg_password
    volumes:
      - ./postgresql:/var/lib/postgresql/data
    healthcheck:
      test: ["CMD-SHELL", "pg_isready -U moviepilot -d moviepilot"]
      interval: 10s
      timeout: 5s
      retries: 5
```
