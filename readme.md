### 热搜榜接口文档
#### 含义
```
热搜榜（Hot Search Ranking）是指一个显示当前热门搜索关键词或话题的列表，这些搜索内容通常是由搜索引擎、社交媒体、新闻网站等渠道收集和统计得来，而且会根据搜索频率、点击率、热度等因素进行排名和显示，以便用户能够快速了解当前热点话题和大众关注的趋势。热搜榜通常用于各种网站的首页、搜索界面、新闻资讯页等。
```
#### 接口列表
```
host: www.yuanxingkang.cn
```
##### 微博
```
/api/hotsearch/weibo
```
###### 接口返回值
<details>

```json
{
    "weibos": [
        {
            "_id": {
                "$oid": "642eca627caeda4bf24e32bd"
            },
            "createTime": "2023-04-06 21:34:26",
            "datas": [
                {
                    "title": "夯实思想之基汲取奋进力量",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%A4%AF%E5%AE%9E%E6%80%9D%E6%83%B3%E4%B9%8B%E5%9F%BA%E6%B1%B2%E5%8F%96%E5%A5%8B%E8%BF%9B%E5%8A%9B%E9%87%8F",
                    "pubDate": null
                },
                {
                    "title": "曝颖儿代言某家居品牌爆雷",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E6%9B%9D%E9%A2%96%E5%84%BF%E4%BB%A3%E8%A8%80%E6%9F%90%E5%AE%B6%E5%B1%85%E5%93%81%E7%89%8C%E7%88%86%E9%9B%B7",
                    "pubDate": null
                },
                {
                    "title": "中电科确认不存在临时工情况",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%B8%AD%E7%94%B5%E7%A7%91%E7%A1%AE%E8%AE%A4%E4%B8%8D%E5%AD%98%E5%9C%A8%E4%B8%B4%E6%97%B6%E5%B7%A5%E6%83%85%E5%86%B5",
                    "pubDate": null
                },
                {
                    "title": "卫星视角下的祖国大地春意盎然",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%8D%AB%E6%98%9F%E8%A7%86%E8%A7%92%E4%B8%8B%E7%9A%84%E7%A5%96%E5%9B%BD%E5%A4%A7%E5%9C%B0%E6%98%A5%E6%84%8F%E7%9B%8E%E7%84%B6",
                    "pubDate": null
                },
                {
                    "title": "任嘉伦好气色秘诀",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%BB%BB%E5%98%89%E4%BC%A6%E5%A5%BD%E6%B0%94%E8%89%B2%E7%A7%98%E8%AF%80",
                    "pubDate": null
                },
                {
                    "title": "润玉时期多好看",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E6%B6%A6%E7%8E%89%E6%97%B6%E6%9C%9F%E5%A4%9A%E5%A5%BD%E7%9C%8B",
                    "pubDate": null
                },
                {
                    "title": "工作4年就诊了50次",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%B7%A5%E4%BD%9C4%E5%B9%B4%E5%B0%B1%E8%AF%8A%E4%BA%8650%E6%AC%A1",
                    "pubDate": null
                },
                {
                    "title": "声生不息把李玟怒斥好声音剪进正片",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%A3%B0%E7%94%9F%E4%B8%8D%E6%81%AF%E6%8A%8A%E6%9D%8E%E7%8E%9F%E6%80%92%E6%96%A5%E5%A5%BD%E5%A3%B0%E9%9F%B3%E5%89%AA%E8%BF%9B%E6%AD%A3%E7%89%87",
                    "pubDate": null
                },
                {
                    "title": "长月烬明配音对不上口型",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%95%BF%E6%9C%88%E7%83%AC%E6%98%8E%E9%85%8D%E9%9F%B3%E5%AF%B9%E4%B8%8D%E4%B8%8A%E5%8F%A3%E5%9E%8B",
                    "pubDate": null
                },
                {
                    "title": "五月天北京演唱会",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%BA%94%E6%9C%88%E5%A4%A9%E5%8C%97%E4%BA%AC%E6%BC%94%E5%94%B1%E4%BC%9A",
                    "pubDate": null
                },
                {
                    "title": "美国男子承认掰断并偷走兵马俑手指",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%BE%8E%E5%9B%BD%E7%94%B7%E5%AD%90%E6%89%BF%E8%AE%A4%E6%8E%B0%E6%96%AD%E5%B9%B6%E5%81%B7%E8%B5%B0%E5%85%B5%E9%A9%AC%E4%BF%91%E6%89%8B%E6%8C%87",
                    "pubDate": null
                },
                {
                    "title": "in了",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3Din%E4%BA%86",
                    "pubDate": null
                },
                {
                    "title": "徐州烧烤",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%BE%90%E5%B7%9E%E7%83%A7%E7%83%A4",
                    "pubDate": null
                },
                {
                    "title": "女子实名举报父亲受贿1900万元",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%A5%B3%E5%AD%90%E5%AE%9E%E5%90%8D%E4%B8%BE%E6%8A%A5%E7%88%B6%E4%BA%B2%E5%8F%97%E8%B4%BF1900%E4%B8%87%E5%85%83",
                    "pubDate": null
                },
                {
                    "title": "白鹿演技",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%99%BD%E9%B9%BF%E6%BC%94%E6%8A%80",
                    "pubDate": null
                },
                {
                    "title": "国内新恋综游戏尺度",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%9B%BD%E5%86%85%E6%96%B0%E6%81%8B%E7%BB%BC%E6%B8%B8%E6%88%8F%E5%B0%BA%E5%BA%A6",
                    "pubDate": null
                },
                {
                    "title": "张杰华晨宇互唱对方代表作",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%BC%A0%E6%9D%B0%E5%8D%8E%E6%99%A8%E5%AE%87%E4%BA%92%E5%94%B1%E5%AF%B9%E6%96%B9%E4%BB%A3%E8%A1%A8%E4%BD%9C",
                    "pubDate": null
                },
                {
                    "title": "为i做e",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%B8%BAi%E5%81%9Ae",
                    "pubDate": null
                },
                {
                    "title": "密室逃脱拼到周笔畅",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%AF%86%E5%AE%A4%E9%80%83%E8%84%B1%E6%8B%BC%E5%88%B0%E5%91%A8%E7%AC%94%E7%95%85",
                    "pubDate": null
                },
                {
                    "title": "EDG晋级胜者组决赛",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3DEDG%E6%99%8B%E7%BA%A7%E8%83%9C%E8%80%85%E7%BB%84%E5%86%B3%E8%B5%9B",
                    "pubDate": null
                },
                {
                    "title": "长月烬明开播观后感",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%95%BF%E6%9C%88%E7%83%AC%E6%98%8E%E5%BC%80%E6%92%AD%E8%A7%82%E5%90%8E%E6%84%9F",
                    "pubDate": null
                },
                {
                    "title": "嘴大 冯晓桐",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%98%B4%E5%A4%A7%20%E5%86%AF%E6%99%93%E6%A1%90",
                    "pubDate": null
                },
                {
                    "title": "痛经的人有福了",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%97%9B%E7%BB%8F%E7%9A%84%E4%BA%BA%E6%9C%89%E7%A6%8F%E4%BA%86",
                    "pubDate": null
                },
                {
                    "title": "古偶魔尊天花板",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%8F%A4%E5%81%B6%E9%AD%94%E5%B0%8A%E5%A4%A9%E8%8A%B1%E6%9D%BF",
                    "pubDate": null
                },
                {
                    "title": "穗禾成了润玉的手下",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%A9%97%E7%A6%BE%E6%88%90%E4%BA%86%E6%B6%A6%E7%8E%89%E7%9A%84%E6%89%8B%E4%B8%8B",
                    "pubDate": null
                },
                {
                    "title": "高加林刘巧珍爱情变亲情",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%AB%98%E5%8A%A0%E6%9E%97%E5%88%98%E5%B7%A7%E7%8F%8D%E7%88%B1%E6%83%85%E5%8F%98%E4%BA%B2%E6%83%85",
                    "pubDate": null
                },
                {
                    "title": "下班该不该回领导信息",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%B8%8B%E7%8F%AD%E8%AF%A5%E4%B8%8D%E8%AF%A5%E5%9B%9E%E9%A2%86%E5%AF%BC%E4%BF%A1%E6%81%AF",
                    "pubDate": null
                },
                {
                    "title": "鹿晗 广海",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%B9%BF%E6%99%97%20%E5%B9%BF%E6%B5%B7",
                    "pubDate": null
                },
                {
                    "title": "接下来4个月都有10天假期",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E6%8E%A5%E4%B8%8B%E6%9D%A54%E4%B8%AA%E6%9C%88%E9%83%BD%E6%9C%8910%E5%A4%A9%E5%81%87%E6%9C%9F",
                    "pubDate": null
                },
                {
                    "title": "EDG战胜OMG",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3DEDG%E6%88%98%E8%83%9COMG",
                    "pubDate": null
                },
                {
                    "title": "固定工位未来会不会消失",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%9B%BA%E5%AE%9A%E5%B7%A5%E4%BD%8D%E6%9C%AA%E6%9D%A5%E4%BC%9A%E4%B8%8D%E4%BC%9A%E6%B6%88%E5%A4%B1",
                    "pubDate": null
                },
                {
                    "title": "马克龙访华",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%A9%AC%E5%85%8B%E9%BE%99%E8%AE%BF%E5%8D%8E",
                    "pubDate": null
                },
                {
                    "title": "朱一龙易烊千玺 合作",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E6%9C%B1%E4%B8%80%E9%BE%99%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%20%E5%90%88%E4%BD%9C",
                    "pubDate": null
                },
                {
                    "title": "目前本人的财务状况",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%9B%AE%E5%89%8D%E6%9C%AC%E4%BA%BA%E7%9A%84%E8%B4%A2%E5%8A%A1%E7%8A%B6%E5%86%B5",
                    "pubDate": null
                },
                {
                    "title": "刘亦菲托腮自拍",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%88%98%E4%BA%A6%E8%8F%B2%E6%89%98%E8%85%AE%E8%87%AA%E6%8B%8D",
                    "pubDate": null
                },
                {
                    "title": "内娱天选神女",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%86%85%E5%A8%B1%E5%A4%A9%E9%80%89%E7%A5%9E%E5%A5%B3",
                    "pubDate": null
                },
                {
                    "title": "爱情而已第28集预告",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%88%B1%E6%83%85%E8%80%8C%E5%B7%B2%E7%AC%AC28%E9%9B%86%E9%A2%84%E5%91%8A",
                    "pubDate": null
                },
                {
                    "title": "大家去长沙不会都是为了吃吧",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%A4%A7%E5%AE%B6%E5%8E%BB%E9%95%BF%E6%B2%99%E4%B8%8D%E4%BC%9A%E9%83%BD%E6%98%AF%E4%B8%BA%E4%BA%86%E5%90%83%E5%90%A7",
                    "pubDate": null
                },
                {
                    "title": "孙策胸肌",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%AD%99%E7%AD%96%E8%83%B8%E8%82%8C",
                    "pubDate": null
                },
                {
                    "title": "于文文曹操吉他solo",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E4%BA%8E%E6%96%87%E6%96%87%E6%9B%B9%E6%93%8D%E5%90%89%E4%BB%96solo",
                    "pubDate": null
                },
                {
                    "title": "张译曾说刘浩存像他的一只猫",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%BC%A0%E8%AF%91%E6%9B%BE%E8%AF%B4%E5%88%98%E6%B5%A9%E5%AD%98%E5%83%8F%E4%BB%96%E7%9A%84%E4%B8%80%E5%8F%AA%E7%8C%AB",
                    "pubDate": null
                },
                {
                    "title": "研究称高脂饮食自由或将实现",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%A0%94%E7%A9%B6%E7%A7%B0%E9%AB%98%E8%84%82%E9%A5%AE%E9%A3%9F%E8%87%AA%E7%94%B1%E6%88%96%E5%B0%86%E5%AE%9E%E7%8E%B0",
                    "pubDate": null
                },
                {
                    "title": "张杰曹操舞台打鼓",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%BC%A0%E6%9D%B0%E6%9B%B9%E6%93%8D%E8%88%9E%E5%8F%B0%E6%89%93%E9%BC%93",
                    "pubDate": null
                },
                {
                    "title": "郭晓婷说去看看陈秀礼的家乡",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E9%83%AD%E6%99%93%E5%A9%B7%E8%AF%B4%E5%8E%BB%E7%9C%8B%E7%9C%8B%E9%99%88%E7%A7%80%E7%A4%BC%E7%9A%84%E5%AE%B6%E4%B9%A1",
                    "pubDate": null
                },
                {
                    "title": "早期甜妹的杀伤力有多强",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E6%97%A9%E6%9C%9F%E7%94%9C%E5%A6%B9%E7%9A%84%E6%9D%80%E4%BC%A4%E5%8A%9B%E6%9C%89%E5%A4%9A%E5%BC%BA",
                    "pubDate": null
                },
                {
                    "title": "EDG对战OMG",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3DEDG%E5%AF%B9%E6%88%98OMG",
                    "pubDate": null
                },
                {
                    "title": "贺峻霖户外四宫格",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E8%B4%BA%E5%B3%BB%E9%9C%96%E6%88%B7%E5%A4%96%E5%9B%9B%E5%AE%AB%E6%A0%BC",
                    "pubDate": null
                },
                {
                    "title": "aespa吐槽ae成员",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3Daespa%E5%90%90%E6%A7%BDae%E6%88%90%E5%91%98",
                    "pubDate": null
                },
                {
                    "title": "辽宁大连3.2级地震",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E8%BE%BD%E5%AE%81%E5%A4%A7%E8%BF%9E3.2%E7%BA%A7%E5%9C%B0%E9%9C%87",
                    "pubDate": null
                },
                {
                    "title": "第四届动漫奖",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E7%AC%AC%E5%9B%9B%E5%B1%8A%E5%8A%A8%E6%BC%AB%E5%A5%96",
                    "pubDate": null
                },
                {
                    "title": "张信哲唱孙燕姿的雨天",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%BC%A0%E4%BF%A1%E5%93%B2%E5%94%B1%E5%AD%99%E7%87%95%E5%A7%BF%E7%9A%84%E9%9B%A8%E5%A4%A9",
                    "pubDate": null
                },
                {
                    "title": "咸蛋黄月亮",
                    "link": "https://m.weibo.cn/search?containerid=100103type%3D1%26q%3D%E5%92%B8%E8%9B%8B%E9%BB%84%E6%9C%88%E4%BA%AE",
                    "pubDate": null
                }
            ]
        }
    ]
}

```
</details>
