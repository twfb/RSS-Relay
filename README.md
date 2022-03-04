# RSS中继

### 如何添加RSS源

1. 创建Issue打上Apply标签
2. 审核后生成
3. 审核通过后可通过 https://twfb.org/rss/[Issue Number].xml 访问


申请模板(包括,不包括,替换 均支持正则, 参考Python正则)

    {
        "url": "https://36kr.com/feed",
        "title": {
            "include": ["氪"],
            "exclude": ["\d"],
            "replace": {["氪", "KR"]},
            "from_lang": "zh",
            "to_lang": "en",
        },
        "content": {
            "include": [],
            "exclude": [],
            "replace": {},
            "from_lang": "en",
            "to_lang": "zh",
        }
    }

RSS链接: https://twfb.org/rss/1.xml
