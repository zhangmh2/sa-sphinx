sa-sphinx
=========
中文的全文检索和英文等latin系列不一样,后者是根据空格等特殊字符来断词,而中文是根据语义来分词.目前大多数数据库尚未支持中文全文检索,如Mysql
故国内出现了一些Mysql的中文全文检索的插件,做的比较好如下:

1：hightman的中文分词scws
参考: http://www.xunsearch.com/scws/

2:sfc(sphinx-for-chinese)
是由网友happy兄提供的一个中文分词插件
其中文词典采用的是xdict. happy兄还在分词方面还有另外一个贡献--php-mmseg,这是php对中文分词的一个扩展库.
详见:
(1):https://code.google.com/p/sphinx-for-chinese/
(2):http://www.sphinx-search.com/

3:Coreseek
Coreseek是现在用的最多的sphinx中文全文检索，它提供了为Sphinx设计的中文分词包LibMMSeg 
Coreseek支持GBK编码的数据源支持
采用Chih-Hao Tsai MMSEG算法的中文分词器

