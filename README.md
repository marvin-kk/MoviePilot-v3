自定义规则组

```
[{"id":"filterGlobal","name":"全局过滤","include":"","exclude":"(?i)日语无字|先行|MiniBD|DIY原盘|原盘|iPad|UPSCALE|AV1|BDMV|RMVB|CAMRip|DVD|vcd|480p|OPUS"},{"id":"Complete","name":"完结","include":"(全|共)\\d+(集|期)|完结|合集|Complete","exclude":""},{"id":"filerGroup","name":"组过滤","include":"","exclude":"(?i)SubsPlease|Up to 21°C|VARYG|TELESYNC|NTb|sGnb|BHYS|HDSWEB|DBD|HDH|COLLECTiVE|SRVFI|YTS.MX|HDSPad"},{"id":"filterMovie","name":"电影体积过滤","include":"","exclude":"","size_range":"0-1000000"},{"id":"Netflix","name":"NF源","include":"Netflix|NF","exclude":""},{"id":"AMZN","name":"AMZN源","include":"AMZN|Amazon","exclude":""},{"id":"HQ","name":"高码","include":"HQ|高码|EDR","exclude":""},{"id":"WhiteList","name":"白名单","include":"\\b(Oldboys|GTR|RO|Telesto|CatEDU|PbK|Rainbaby|Ao|BMDru|c0kE|cfandora|jsum|RNML|FraMeSToR|ADE|CHD|CMCT|Sunny|WiKi|PTer|MTeam|FRDS|UBits|FROGE|beAst|Dream|BeiTai|RLeaves|R²|PTH|HDChina|LHD|ZONE|btshd|ADWeb|HHWEB|CHDWEB|CMCTV|TJUPT|OurTV|PTerWEB|MWeb|UBWEB|FROGWeb|QHstudIo|DBTV|RLWeb|LeagueWEB|HDCTV|ZWEX|ZmWeb|Kitsune|NTb|playWEB|BYNDR|FLUX|ETHEL|EDITH|VARYG|HONE|YingWEB|OPS|AilMWeb|ARiC|喵萌奶茶屋|豌豆字幕组|爱恋字幕社|漫猫字幕社|北宇治字幕组|云光字幕组|织梦字幕组|千夏字幕组|极影字幕社|风之圣殿字幕组|风车字幕组|银色子弹字幕组|熔岩动画|MingYSub|枫叶字幕组|诸神字幕组|AKito|秋人|霜庭云花Sub|轻之国度字幕组|星空字幕组|离谱Sub|雪飘工作室|拨雪寻春|新Sub|MCE汉化组|極彩字幕组|氢气烤肉架|悠哈璃羽字幕社|桜都字幕组|SweetSub|LoliHouse|&VCB-Studio|VCB-Studio&|7³ACG|幻之字幕组|魔穗字幕组|澄空学园|LittleBakas!|白恋字幕组|动漫国字幕组|FSD字幕组|FSD粉羽社|一只出格君|猫恋汉化组|OPFans枫雪动漫|GM-Team|康复重症监护室字幕组|SilverBullet|APTX4869|幻樱字幕组|永恒译制|咪梦字幕组|NEO·QSW)\\b"},{"id":"PreferenceGroup","name":"剧集优先组","include":"ADWeb｜HHWEB｜CHDWEB｜OurTV｜HDSWEB｜UBWEB"},{"id":"RULE11","name":"杜比","include":"DV|DoVi"},{"id":"filterSeries","name":"剧集体积过滤","size_range":"3000-15000"}]
```

优先级规则组

```
[{"name":"国漫","rule_string":" 4K & WEBDL &PreferenceGroup> 4K & WEBDL > 1080P & WEBDL &PreferenceGroup> 1080P & WEBDL ","media_type":"电视剧","category":"国漫"},{"name":"国产剧","rule_string":" 4K & WEBDL &PreferenceGroup&RULE11&filterSeries> 4K & WEBDL & HDR &PreferenceGroup&filterSeries> 4K & WEBDL &HQ&PreferenceGroup&filterSeries> 4K & WEBDL & 60FPS &PreferenceGroup&filterSeries> 4K & WEBDL & SDR &PreferenceGroup&filterSeries> 4K & WEBDL &PreferenceGroup&filterSeries> 4K & WEBDL &PreferenceGroup","media_type":"电视剧","category":"国产剧"},{"name":"日韩剧","rule_string":" SPECSUB & 1080P & BLURAY &filterSeries> CNSUB & 1080P &filterSeries& BLURAY > 1080P & CNSUB &filterSeries> CNSUB &filterSeries","media_type":"电视剧","category":"日韩剧"},{"name":"欧美剧","rule_string":" CNSUB & 4K & WEBDL & DOLBY &PreferenceGroup> CNSUB & 4K & WEBDL & HDR &PreferenceGroup> CNSUB & 4K & WEBDL &PreferenceGroup> CNSUB & 1080P & WEBDL & DOLBY &PreferenceGroup> CNSUB & 1080P & WEBDL & HDR &PreferenceGroup> CNSUB & 1080P & WEBDL &PreferenceGroup","media_type":"电视剧","category":"欧美剧"},{"name":"纪录片","rule_string":" 4K & BLURAY > 1080P & BLURAY > 4K > 1080P ","media_type":"电视剧","category":"纪录片"},{"name":"日番","rule_string":" BLURAY & H265 &PreferenceGroup& 1080P > BLURAY & H265 & CNSUB & 1080P > BLURAY & CNSUB & 1080P > WEBDL &PreferenceGroup& 1080P &Crunchyroll> WEBDL &PreferenceGroup& 1080P &AMZN>PreferenceGroup&Netflix& 1080P & WEBDL > WEBDL &PreferenceGroup& 1080P > 1080P & CNSUB > CNSUB ","media_type":"电视剧","category":"日番"},{"name":"欧美漫","rule_string":" BLURAY & H265 & CNSUB > BLURAY & CNSUB > WEBDL & CNSUB > CNSUB ","media_type":"电视剧","category":"欧美漫"},{"name":"综艺","rule_string":" 4K &PreferenceGroup&Complete> 4K &PreferenceGroup> 1080P &PreferenceGroup> 1080P ","media_type":"电视剧","category":"综艺"},{"name":"现场","rule_string":" CNSUB & 4K > CNSUB & 1080P > 4K > 1080P > !720P ","media_type":"电影","category":"现场"},{"name":"华语电影","media_type":"电影","category":"华语电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY > 4K & WEBDL & DOLBY > 4K & WEBDL & HDR > 4K & WEBDL &HQ> 4K & WEBDL > 1080P & BLURAY > 1080P & WEBDL "},{"name":"外语电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY & CNSUB > 4K & WEBDL & DOLBY & SPECSUB > 4K & WEBDL & HDR & SPECSUB > 4K & WEBDL & SPECSUB > 4K & WEBDL & DOLBY & CNSUB > 4K & WEBDL & HDR & CNSUB > 4K & WEBDL & CNSUB > 1080P & BLURAY & SPECSUB > 1080P & BLURAY & CNSUB > 1080P & WEBDL & CNSUB ","media_type":"电影","category":"外语电影"},{"name":"动画电影","rule_string":" 4K & BLURAY & DOLBY & SPECSUB > 4K & BLURAY & HDR & SPECSUB > 4K & BLURAY & DOLBY & CNSUB > 4K & BLURAY & HDR & CNSUB > 4K & UHD & BLURAY & SPECSUB > 4K & BLURAY & REMUX & DOLBY & SPECSUB > 4K & BLURAY & REMUX & HDR & SPECSUB > 4K & BLURAY & REMUX & SPECSUB > 4K & BLURAY & REMUX & DOLBY & CNSUB > 4K & BLURAY & REMUX & HDR & CNSUB > 4K & BLURAY & SPECSUB > 4K & BLURAY & CNSUB > 4K & WEBDL & DOLBY & SPECSUB > 4K & WEBDL & HDR & SPECSUB > 4K & WEBDL & SPECSUB > 4K & WEBDL & DOLBY & CNSUB > 4K & WEBDL & HDR & CNSUB > 4K & WEBDL & CNSUB > 1080P & BLURAY & SPECSUB > 1080P & BLURAY & CNSUB > 1080P & WEBDL & CNSUB ","media_type":"电影","category":"动画电影"},{"name":"国产高码","rule_string":" 4K & WEBDL &HQ&PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产60fps","rule_string":" 4K & WEBDL & 60FPS &PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产杜比","rule_string":" 4K & WEBDL &PreferenceGroup&RULE11&filterSeries","media_type":"电视剧","category":"国产剧"},{"name":"国产HDR","rule_string":" 4K & WEBDL & HDR &PreferenceGroup&filterSeries","media_type":"电视剧","category":"国产剧"}]
```

资源入库

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

资源下载

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

添加订阅

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

订阅完成

```
{
        'title': '🎞 {{ title_year }} {% if season %}{{season}}{% endif %} 已完成订阅',
        'text': '{% if vote_average %}✨ 评分：{{ vote_average }}/10{% endif %}'
                '{% if username %}\n👾 用户：{{ username }}{% endif %}'
                '{% if overview %}\n\n🍿 简介：\n{{ overview }}{% endif %}'
}
```

电影重命名

```
{{title}} ({{year}}) [tmdbid={{tmdbid}}] /{{original_name}}
```

电视剧重命名

```
{{title}} ({{year}}) [tmdbid={{tmdbid}}] /{{original_name}}
```

API令牌

```
HQfRBuEOcxcbcTZtYdmQQfEiZ
```

Telegram

```
chai ID:866309914
Bot Token:8333940258:AAEBv-cLifls709SU_bo4Dg2GUp0MzCzTmc
```

