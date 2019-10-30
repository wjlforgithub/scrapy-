# scrapy-
爬文字是迁木网，图片电影链接是电影天堂，音乐是网易云
2个文件夹，qianmu2019里面是爬的迁木网和电影天堂，music163是爬的网易云音乐


安装方法 pip install requirement.txt
爬迁木和电影天堂可以持久化mysql，进对应pipelines修改自己本机配置
进入每个project scrapy list查看有哪些爬虫，
scrapy crawl dianyingspider  qianmu2019
或者进到spider目录scrapy runspider 爬虫名称
