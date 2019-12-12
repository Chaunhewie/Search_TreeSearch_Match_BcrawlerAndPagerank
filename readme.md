# 计算机应用与编程实践
### 一共四个实践编程作业：
  1. 判断一个模式串pattern是否在一系列模式串中出现过。

        array search暴力字符串搜索；
      
        hashtable search拉链表字符串搜索；
      
        bloomfilter search布隆过滤器字符串搜索。
      
  2. 建立树结构，判断一个模式串pattern是否在一系列模式串中出现过。

        Binary Balanced Search Tree二叉平衡搜索树；
      
        B_Plus Search B+树；
      
        Trie Search 前缀树 ---引出--- Radix Trie 基数树（四叉二进制树）
      
        Patricia Trie 二阶基数树（二叉二进制树）
      
  3. 多模式串字符串匹配，判断一个Pattern字符串在一个超长字符串Book中出现了多少次。

        strstr暴力字符串匹配查找；
      
        kmp半暴力字符串匹配查找；
            
        ac自动机字符串匹配查找。
      
  4. 页面网站分析器，爬取一个网站系统（news.sohu.com），并获取网站的超链接，将整个网站系统爬取下来，建立对应链接关系，最后通过pagerank进行网站排名。

        bcrawler 爬虫
      
        pagerank 网站排名pagerank系统
      
      
### 文件讲解
  .rar 代码是四道题的代码，其中前三道在 windows10 系统下 VS2017IDE 编译运行；第四道题在 Ubuntu 环境下命令行 make 并运行。

  .docx 是对四道题的实验报告

  .pdf 是作业安排的课件

  .pptx 是针对前两道题的自己的做法的讲解



## ```仅供学习交流，切勿抄袭作业！！！```


### 在实验报告中有各个实验运行的结果展示和性能展示，部分图片如下：

#### 题目一

*  array search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/01-array_search_v2.png">

*  hashtable search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/01-hashtable_search_v2.png">

*  bf search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/01-bf_search_v2.png">


#### 题目二

*  btree search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-btree.png">
<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-btree_search.gif">

*  bplustree search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-bplustree.png">
<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-bplus_search.gif">

*  radixtree search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-radixtree.png">
<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-radix4.gif">

*  patriciatree search

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/02-patricia.gif">

#### 题目三

*  strstr match

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/03-strstr.png">

*  multikmp match

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/03-multikmp.png">

*  acauto match

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/03-ac_auto.png">

#### 题目四

*  bcrawler

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/04-bcrawler.png">

*  pagerank

<img width="450" alt="运行结果" align="center" src="https://github.com/Chaunhewie/Search_TreeSearch_Match_BcrawlerAndPagerank/raw/master/images/04-pagerank.png">


