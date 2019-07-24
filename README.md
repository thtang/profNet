# ProfNet : Are they friends?

In this project we create a professor relation netword based on the thesis data of NTHU. Each professor is linked to other professors that once being _**the oral commissioner**_ of one's students. The weights of linkages are derived from **the count** of being one's student's oral commissioner.
<img src="https://github.com/thtang/profNet/blob/master/figure/f0.png" width = "600">
### Theses data 

| field             |  Example            |
|-------------------|---------------------|
| 編號               |  1                  |
| **校院名稱**           | 國立清華大學              |
| **系所名稱**        |  電機工程學系  |
| 作者              | 譚OO                  |
| 作者(外文)         | Tam, OOOOO-OOO       |
| 論文名稱        | 用每分鐘心電圖訊號特徵為支持向量機之睡眠呼吸中止症辨識方法 |
| 論文名稱(外文)    | An Obstructive Sleep Apnea Recognition Algorithm...    |
| **指導教授**      | 馬OO        |
| 指導教授(外文)             |  Ma, OOO-OOO |
| **口試委員**       | 黃OO,劉OO           |
| 口試委員(外文)| Huang, OOOO-O    Liu, OO-OOO |
| 口試日期       |  2013.12.3      |
| 學位類別    | 碩士       |
| 畢業學年度      | 102       |
| 出版年   |  103   |
| 語文別   |英文   |
| 中文關鍵詞  |睡眠呼吸中止 支持向量機 心電圖     |
| 外文關鍵詞   | " " |
| **摘要**| 近年來，隨著睡眠時間以及睡眠品質逐漸受到重視，睡眠呼吸中止症逐漸...     |
| 摘要(外文)   |Nowadays, sleep disorders become an important...     |
| 論文目次   |Abstract i\n1 Introduction 1\n1.1 Backgrounds . .      |
| 參考文獻   |[1] L. R. Melinda Smith, M. A. an...     |
| 論文頁數   |  71     |

### See [demo](http://u102034038.22web.org/prof_relation.html) 
(I used free host and the data is quite large, so please wait and press F5 for several times > < )

First, enter professor's name yor are interested in.

<img src="https://github.com/thtang/profNet/blob/master/figure/f1.png" width="500">

Then Find the biggest node. **That's yor PROFESSOR!**

Each node represents a professor. Color denotes different department.

Stay your mouse pointer on the node and see the professor's name.
<img src="https://github.com/thtang/profNet/blob/master/figure/f4.png" width="600">


Double click the node to see further information of the professor!
<img src="https://github.com/thtang/profNet/blob/master/figure/f2.png" width="600">

We also provide word cloud with abstract from different department across three years.
<img src="https://github.com/thtang/profNet/blob/master/figure/f3.png" width="600">

### Want a comfortable one, click the link!
https://public.tableau.com/profile/rosalie.dolor#!/vizhome/TextMining-WordCloud-Small/WordCloud

This is in collaboration with [rdolor.](https://github.com/rdolor/Text-Mining-WordCloud)
