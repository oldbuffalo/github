#GitHub 漫游指南

在线阅读: [GitHub 漫游指南](http://github.phodal.com/)， 下载: [pdf](https://github.com/phodal/github-roam/raw/gh-pages/github-roam.pdf)、[mobi](https://github.com/phodal/github-roam/raw/gh-pages/github-roam.mobi)、[epub](https://github.com/phodal/github-roam/raw/gh-pages/github-roam.epub)

2014年，写了《[一步步搭建物联网系统](https://github.com/phodal/designiot)》（电子书）。

2015.3.9号，想着写个《[GitHub漫游指南](http://github.phodal.com/)》，于是在最开始的地方写着：

> 我的GitHub主页上写着加入的时间——``Joined on Nov 8, 2010``，那时才大一，在那之后的那长日子里我都没有过到。也许是因为我学的不是计算机，到了今天——``2015.3.9``，我也发现这其实是程序员的社交网站。

但是过了很久都没有动静，今天是2015.10.24，我想是时候完成这个目标了。

##目录

-   [前言](http://github.phodal.com/#前言)
    -   [我与GitHub的故事](http://github.phodal.com/#我与github的故事)
        -   [GitHub与收获](http://github.phodal.com/#github与收获)
        -   [GitHub与成长](http://github.phodal.com/#github与成长)
    -   [为什么你应该深入GitHub](http://github.phodal.com/#为什么你应该深入github)
        -   [方便工作](http://github.phodal.com/#方便工作)
        -   [获得一份工作](http://github.phodal.com/#获得一份工作)
        -   [扩大交际](http://github.phodal.com/#扩大交际)
-   [Git基本知识与GitHub使用](http://github.phodal.com/#git基本知识与github使用)
    -   [Git](http://github.phodal.com/#git)
        -   [Git初入](http://github.phodal.com/#git初入)
    -   [GitHub](http://github.phodal.com/#github)
        -   [版本管理与软件部署](http://github.phodal.com/#版本管理与软件部署)
        -   [GitHub与Git](http://github.phodal.com/#github与git)
        -   [在GitHub创建项目](http://github.phodal.com/#在github创建项目)
    -   [GitHub流行项目分析](http://github.phodal.com/#github流行项目分析)
    -   [Pull Request](http://github.phodal.com/#pull-request)
        -   [我的第一个PR](http://github.phodal.com/#我的第一个pr)
        -   [CLA](http://github.phodal.com/#cla)
-   [构建GitHub项目](http://github.phodal.com/#构建github项目)
    -   [如何用好GitHub](http://github.phodal.com/#如何用好github)
        -   [敏捷软件开发](http://github.phodal.com/#敏捷软件开发)
        -   [测试](http://github.phodal.com/#测试)
        -   [CI](http://github.phodal.com/#ci)
        -   [代码质量](http://github.phodal.com/#代码质量)
    -   [模块分离与测试](http://github.phodal.com/#模块分离与测试)
        -   [代码模块化](http://github.phodal.com/#代码模块化)
        -   [自动化测试](http://github.phodal.com/#自动化测试)
        -   [Jshint](http://github.phodal.com/#jshint)
        -   [Mocha](http://github.phodal.com/#mocha)
        -   [测试示例](http://github.phodal.com/#测试示例)
    -   [代码质量与重构](http://github.phodal.com/#代码质量与重构)
        -   [Code Climate](http://github.phodal.com/#code-climate)
        -   [代码的坏味道](http://github.phodal.com/#代码的坏味道)
-   [创建项目文档](http://github.phodal.com/#创建项目文档)
    -   [README](http://github.phodal.com/#readme)
    -   [在线文档](http://github.phodal.com/#在线文档)
    -   [可用示例](http://github.phodal.com/#可用示例)
-   [测试](http://github.phodal.com/#测试-1)
    -   [TDD](http://github.phodal.com/#tdd)
        -   [一次测试驱动开发](http://github.phodal.com/#一次测试驱动开发)
        -   [说说TDD](http://github.phodal.com/#说说tdd)
        -   [TDD思考](http://github.phodal.com/#tdd思考)
    -   [功能测试](http://github.phodal.com/#功能测试)
        -   [轻量级网站测试TWill](http://github.phodal.com/#轻量级网站测试twill)
        -   [Twill 登陆测试](http://github.phodal.com/#twill-登陆测试)
        -   [Twill 测试脚本](http://github.phodal.com/#twill-测试脚本)
    -   [Fake Server](http://github.phodal.com/#fake-server)
-   [重构](http://github.phodal.com/#重构)
    -   [为什么重构?](http://github.phodal.com/#为什么重构)
    -   [重构uMarkdown](http://github.phodal.com/#重构umarkdown)
        -   [代码说明](http://github.phodal.com/#代码说明)
    -   [Intellij
        Idea重构](http://github.phodal.com/#interllij-idea重构)
        -   [Rename](http://github.phodal.com/#rename)
        -   [Extract Method](http://github.phodal.com/#extract-method)
        -   [Inline Method](http://github.phodal.com/#inline-method)
        -   [Pull Members Up](http://github.phodal.com/#pull-members-up)
        -   [重构之以查询取代临时变量](http://github.phodal.com/#重构之以查询取代临时变量)
-   [如何在GitHub“寻找灵感(fork)”](http://github.phodal.com/#如何在github寻找灵感fork)
    -   [](http://github.phodal.com/#lettuce构建过程)[Lettuce](https://github.com/phodal/lettuce)构建过程
        -   [需求](http://github.phodal.com/#需求)
        -   [计划](http://github.phodal.com/#计划)
        -   [实现第一个需求](http://github.phodal.com/#实现第一个需求)
        -   [实现第二个需求](http://github.phodal.com/#实现第二个需求)
-   [GitHub用户分析](http://github.phodal.com/#github用户分析)
    -   [生成图表](http://github.phodal.com/#生成图表)
        -   [数据解析](http://github.phodal.com/#数据解析)
        -   [Matplotlib](http://github.phodal.com/#matplotlib)
    -   [每周分析](http://github.phodal.com/#每周分析)
        -   [python github
            每周情况分析](http://github.phodal.com/#python-github-每周情况分析)
        -   [Python 数据分析](http://github.phodal.com/#python-数据分析)
        -   [Python
            Matplotlib图表](http://github.phodal.com/#python-matplotlib图表)
    -   [存储到数据库中](http://github.phodal.com/#存储到数据库中)
        -   [SQLite3](http://github.phodal.com/#sqlite3)
        -   [数据导入](http://github.phodal.com/#数据导入)
        -   [Redis](http://github.phodal.com/#redis)
    -   [邻近算法与相似用户](http://github.phodal.com/#邻近算法与相似用户)
-   [GitHub连击](http://github.phodal.com/#github连击)
    -   [100天](http://github.phodal.com/#天)
        -   [40天的提升](http://github.phodal.com/#天的提升)
        -   [100天的挑战](http://github.phodal.com/#天的挑战)
        -   [140天的希冀](http://github.phodal.com/#天的希冀)
    -   [200天的Showcase](http://github.phodal.com/#天的showcase)
        -   [一些项目简述](http://github.phodal.com/#一些项目简述)
        -   [google map solr polygon
            搜索](http://github.phodal.com/#google-map-solr-polygon-搜索)
        -   [技能树](http://github.phodal.com/#技能树)
    -   [365天](http://github.phodal.com/#天-1)
        -   [编程的基础能力](http://github.phodal.com/#编程的基础能力)
        -   [技术与框架设计](http://github.phodal.com/#技术与框架设计)
        -   [领域与练习](http://github.phodal.com/#领域与练习)
        -   [其他](http://github.phodal.com/#其他-1)

## License

![cc](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)

本作品采用[知识共享署名-非商业性使用 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc/4.0/)进行许可。

[![Phodal's Articles](http://brand.phodal.com/shields/article-small.svg)](http://articles.phodal.com/)

[待我代码编成，娶你为妻可好](http://www.xuntayizhan.com/person/ji-ke-ai-qing-zhi-er-shi-dai-wo-dai-ma-bian-cheng-qu-ni-wei-qi-ke-hao-wan/)。

