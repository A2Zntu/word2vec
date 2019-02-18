# word2vec

## 準備訓練資料

1. 從<a href='https://zh.wikipedia.org/wiki/Wikipedia:%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%8B%E8%BD%BD'>維基百科:資料庫下載</a>，找到<a href='https://dumps.wikimedia.org/zhwiki/'>中文版</a>的下載處

2. 下載最新的語料 （目前下載：<a href='https://dumps.wikimedia.org/zhwiki/20190201/zhwiki-20190201-pages-articles.xml.bz2'>2019/02/01</a>）

3. 將維基資料吃進純文字檔     wiki_to_txt.py程式請參閱<a href='https://github.com/zake7749/word2vec-tutorial/blob/master/wiki_to_txt.py'>zake7749/word2vec-tutorial: wiki_to_txt.py</a>

<pre><code>$ python3 wiki_to_txt.py zhwiki-20190201-pages-articles.xml.bz2 </code></pre>

4. 簡體轉繁體

5. 將純文字檔用<a href='https://github.com/fxsjy/jieba'>JIEBA</a>斷句   斷句程式參閱<a href='https://github.com/zake7749/word2vec-tutorial/blob/master/segment.py'>zake7749/word2vec-tutorial: segment.py</a>

<pre><code>$ python3 segment.py</code></pre>

6. 訓練資料準備完畢

## 準備訓練資料



