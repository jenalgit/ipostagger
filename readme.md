# IPOSTagger

Ini merupakan kode dari [Alfan Farizki Wicaksono, Ayu Purwarianti. HMM Based POS Tagger for Bahasa Indonesia. On Proceedings of 4th International MALINDO (Malay - Indonesian Language) Workshop. 2nd August 2010.](http://www.informatika.org/~ayu/2010postagger.pdf). Untuk cara penggunaan silahkan refer ke peneliti [http://alfan-farizki.blogspot.co.id/2010/03/release-ipostaggerv10-beta-hmm-based.html](http://alfan-farizki.blogspot.co.id/2010/03/release-ipostaggerv10-beta-hmm-based.html).


## Instalasi

Untuk menginstall, tambahkan kode berikut pada berkas `pom.xml`:

```
<repositories>
    <repository>
      <id>NLP_ITB.POSTagger</id>
      <name>HMM</name>
      <url>https://github.com/yusufsyaifudin/ipostagger/raw/1.0.0/</url>
    </repository>
</repositories> 
```

dan kode berikut pada _dependency_ `pom.xml`

```
<dependencies>
    <dependency>
      <groupId>NLP_ITB.POSTagger</groupId>
      <artifactId>HMM</artifactId>
      <version>1.0.0</version>
      <scope>compile</scope>
    </dependency>
</dependencies>
```
