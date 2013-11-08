Solr-zh-config
==============

## Usage
* 將簡體中文轉成繁體中文
```
<charFilter class="solr.MappingCharFilterFactory" mapping="Solr-zh-config/mapping-zh-s2t.txt"/>
```

* 增加一些可能會打錯字的中文
```
<filter class="solr.SynonymFilterFactory" synonyms="Solr-zh-config/zh-synonyms.txt" ignoreCase="true" expand="true"/>
```

