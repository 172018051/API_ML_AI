
# 项目名： 一封有声音的信   
一分钟语音留言，记录当下，以文，以乐。 
> PRD 价值主张设计（目标：多层次多长度版本）
> 1. 一句话版本<br>有声信运用百度AI（讯飞）的人工智能语音识别技术，用户需输入1分钟的语音，有声信可以将语音转换为文字并排版为信的格式，最后将语音与文字相结合输出一封有声音的信，支持图文编辑，同时辅以交互的UI设计，最大程度的保留故事与模拟时间给书信带来的痕迹(发黄、变旧)。  
> 2. 一分钟60s版本 (图文线上可阅读含可查连结)<br>
> 3. 400 秒版本 Pecha Kucha 20x20 版本 (线上投影片含可查连结)<br>
 
|发布日期|2019/12/xx|   
|  ----  |  ----  | 
|产品名称|有声信APP|     
|文件状态|编辑中|   
|产品经理|陈咏琴|   

## 文档目录

- [产品介绍](#产品介绍)
- [项目背景](#项目背景)
- [价值主张设计](#价值主张设计)
  - [加值宣言](#PRD1.加值宣言)
  - [核心价值宣言](#PRD2.核心价值宣言)
  - [核心价值与用户痛点](#PRD3.核心价值与用户痛点)
  - [人工智能概率性与用户痛点](#PRD4.人工智能概率性与用户痛点)
  - [需求列表与人工智能API加值](#PRD5.需求列表与人工智能API加值)
- [原型](#原型)
  - [交互及界面设计](#原型1.交互及界面设计)
  - [信息设计](#原型2.信息设计)
  - [原型文档](#原型3.原型文档])
  - [口头操作说明](#原型4.口头操作说明)
- [API 产品使用关键AI或机器学习之API的输出入展示](#API-产品使用关键AI或机器学习之API的输出入展示)
  - [使用水平](#API1.使用水平)
  - [使用比较分析](#API2.使用比较分析)
  - [使用后风险报告](#API3.使用后风险报告)
  - [加分项](#API4.加分项)      

---   
# 有声信APP产品需求文档       
### 产品介绍：  
有声信运用百度AI（讯飞）的人工智能语音识别技术，用户需输入1分钟的语音，有声信可以将语音转换为文字并排版为信的格式，最后将语音与文字相结合输出一封有声音的信，支持图文编辑，同时辅以交互的UI设计，最大程度的保留故事与模拟时间给书信带来的痕迹(发黄、变旧)。

### 项目背景：     
传统的书信已经越来越少人写了，虽然书信的价值相较于手机短信而言依然更加受到人们重视与认可，但是所有事物都不得不随时代的发展而变化，因为短信比信件的效率快的多得多，所以很快就取代了书信，毕竟书信最重要作用就是用来传递信息的，而不是用来留作纪念。    
**手写的信件让大家认为更有价值的原因是：**     
* 信件因为时间的流逝而产生的痕迹，发黄、变皱、变旧。   
* 因为故事，一看到这封信就能瞬间回到过去，万千思绪涌，因为这张纸在从前当下被人认真对待，一笔一字的写下文字。   

### 产品亮点（优势）：    
有声信可以以别的方式来弥补用户对于书信的期待，运用人工智能**语音识别**技术，将语音与文字相结合做出一封有声音的书信，同时辅以**交互的UI设计**，最大程度的**保留故事**与**模拟时间给书信带来的痕迹**。这是有声书可以给用户带来的价值。

#### 市面上相类似的产品/功能是怎么样的，他们是怎么做的     
语音识别：讯飞、等等等     
自然语言处理：抽取关键词，词法分析   
日记、记事本：编辑，添加图片，可手写/绘等    
    
## PRD 价值主张设计   
  
### PRD1.加值宣言     
- 通过人工智能的语音识别技术，将说话者的语音转为文字，同时保留音频，将文字自动排版为信的格式。添加纠错机制，可编辑，可添加图片。   
- 通过自然语言处理API的词法分析，将文字内容进行分词、词性标注、命名实体识别。将返回的结果用pyecharts绘制出文字云。可分享，可做表，统计可交互。     
- 可保存为文档，可打印，旁边附上二维码，使用APP内附扫码工具，扫描二维码即可跳转到语音输入后生成的页面，可以边听边看的信    
可以将信送给别人，也可以邀请别人做这封信   
不需要传统的书写，只需语音输入。
相较于传统书信，情感更加丰富。 
不需要如书写信一样非常正式   
- 界面的交互，随着时间流逝，查看信的界面会发生变化，变黄、变旧。
### PRD2.核心价值      

最小可行性产品MVP：   
  1. 通过语音识别，做出一封有声音的信❤（留念）创作你的有声信    
  2.界面的交互，随着时间流逝，查看信的界面会发生变化，变黄、变旧。   

次重要：
  1. 自然语言处理，把词变成图，可分享（社交）   
  2. 可转为文档文件，可打印实体化（附语音二维码）   

### PRD3.核心价值与用户痛点        
**用户痛点**        
- 如何记录当下，留念。    
- 有意义的纪念品（手写信的取代品，便捷但有价值的。除纪念品之外，可选择的一个象征物，对方的声音）      
- 可分享的，社交。     
- 对于更喜欢单纯用文字表达的用户，可自由选择语音输入或者文字输入，可添加背景音乐。      
   
用户画像：      
	
**有声书如何弥补用户对于书信的期待：**           
* 信件因为时间的流逝而产生痕迹，发黄、变皱、变旧。（对应交互的UI设计）       
* 因为故事，一看到这封信就能瞬间回到过去，万千思绪涌上。因为这张纸在从前当下被人认真对待，一笔一字的写下文字。（创造价值，留下你的故事。音频输入，认真的编辑，添加图片、信封样式选择等）    

用有声的信件取代手写字迹给信带来的故事（声音就像时光机一样，播放按钮就是开启时光机的按钮，当时当下，你或者他，语气、语调、情感，这都是故事，可替换手写的意义），交互的样式设计取代信件信件的时间痕迹，发黄变旧。 随着时间的流逝，查看信件的界面样式也像书信一样变得发黄、老旧。   

**应用场景：**   
记录当下，以文，以乐。快捷方便。   
大学毕业季，小红发送了一个链接，邀请朋友、老师、家长留下对自己的毕业赠言，一分钟祝福。   

生日聚会上，寿星小红和小绿在聚会上放声歌唱，谈天说地，席间小绿使用有声信APP记录了朋友们对小红的生日留言。    
   


### PRD4.人工智能概率性与用户痛点    

AI概率性考量：使用人工智能的加值的表述是否纳入判断有错的（如假阳False Positive假阴False Negative）的精确概率考量，以确保判错对用户体验的负面影响不会压过正面影响的机率。概率性参见 吴雪. [人工智能产品经理]    

产品是否会出现判断错误的情况？例如人脸识别错误，医疗检测错误，面对这种情况，结合产品的价值主张与MVP，谈谈如何保证或者降低判错对用户体验的负面影响不会压过正面影响的机率，或者降低判错对用户体验的负面影响。   

### PRD5.需求列表与人工智能API加值    

需求列表：使用人工智能的加值是否反映到需求列表（核心功能的排序上）且PRD列出明显有可行及可用的API   
功能与需求对应，价值主张与需求列表重要程度对应    

用户需求列表（重要程度降序）：     
|用户需求|功能（核心价值 ）|进度|     
|----|----|-----|   
|记录当下，留念|语音识别（输入语言转文字）|做|   
|有意义的纪念品|音频播放、交互的界面（留言者的声音）|做|  
|社交|邀请留言、存为文档|做|    
|社交，游戏|自然语言处理词法分析、pyecharts文字云|暂时不做|   

---   
## 原型 

### 原型1.交互及界面设计 

交互及界面设计：在PRD文件中是否有说明且原型是否有做到：交互及界面设计的某个核心交互环节使用了人工智能的加值

### 原型2.信息设计 
![产品逻辑.png](https://upload-images.jianshu.io/upload_images/11043770-1864ad0da0d9072c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

信息设计：在PRD文件中是否有说明且原型是否有做到：信息设计的某个核心信息或设计使用了人工智能的加值

### 原型3.原型文档 

原型文档：多少程度上有提供MVP可交互的原型文档，供它人在Github上下载使用

可交互的，AXURE

### 原型4.口头操作说明 

口头操作说明：多少程度上在2-3分钟时间限制内，对听众留下了「的确这是个可行丶可用的人工智能加值产品」的印象

---   
## API 产品使用关键AI或[机器学习](http://e.nfu.edu.cn/mod/page/view.php?id=1135 "机器学习")之API的输出入展示   

### API1.使用水平   
因为语音识别有一定的音频格式范围，因此必须有音频格式转换的工具，这里推荐[ffmpeg](http://ffmpeg.org/download.html)，可参考百度的开发工具[音频文件转码](https://ai.baidu.com/ai-doc/SPEECH/7k38lxpwf#%E7%AE%80%E4%BB%8B-1)查看相关介绍。


使用水平：在PRD文件中是否有说明且展示，核心功能所应用的API之输入及输出
[百度AI语音识别]([https://ai.baidu.com/tech/speech](https://ai.baidu.com/tech/speech)
)：   

输入：   
```
from aip import AipSpeech

""" 你的 APPID AK SK """
APP_ID = '18090119'
API_KEY = 'YtE6uqVodwVwr9zCW0sPjqrH'
SECRET_KEY = 'RGzlYQaeApOcXKmyjRfeKLEV02lKDlvn'

client = AipSpeech(APP_ID, API_KEY, SECRET_KEY)

# 读取文件
def get_file_content(filePath):
    with open(filePath, 'rb') as fp:
        return fp.read()

# 识别本地文件
client.asr(get_file_content('16k.pcm'), 'pcm', 16000, {
    'dev_pid': 1536,
})
```
输出：
```
{'corpus_no': '6773611276171315400',
 'err_msg': 'success.',
 'err_no': 0,
 'result': ['北京科技馆'],
 'sn': '726787071901577104272'}
```
讯飞AI语音识别：
输入：
```
```
输出：
```
```
游戏化设计：
功能需求：可将通过语音识别将用户语音转换为的文字内容进行分类、取关键词，运用pyecharts做出文字云。
我查看了百度AI所有的自然语言处理API，其中最适合与能达到功能需求的是词法分析。

自然语言处理
语音识别将1min的语音转换为文字，再通过自然语言处理的词法分析将文字内容进行分词、词性标注、命名实体识别。将返回的结果用pyecharts绘制出文字云。（形容词、）

### API2.使用比较分析    
百度AI语音识别输入要求格式的音频文件：
pcm（不压缩），也称为raw格式。音频输入最原始的格式，不用再解码。
wav（不压缩，pcm编码）：在pcm文件的开头出上加上一个描述采样率，编码等信息的字节。
amr（有损压缩格式），对音频数据进行有损压缩，类似mp3文件。
m4a（有损压缩格式，AAC编码），对音频数据进行有损压缩，通常仅供微信小程序使用的格式。自行转换比较复杂。
**由于底层识别使用的是pcm，因此推荐直接上传pcm文件。如果上传其它格式，会在服务器端转码成pcm，调用接口的耗时会增加。**

|百度AI语音识别支持的格式|百度AI语音识别支持的格式|
|----|-----|
|pcm（不压缩）||
|wav（不压缩，pcm编码）||
|amr（有损压缩格式）||
|m4a（有损压缩格式，AAC编码）||   

语音识别目前有语音识别标准版（包含输入法、搜索、英语、粤语、四川话、远场）及语音识别极速版接口。

**语音识别计费简介**   
使用短语音识别。
*   语音识别标准版：可按天/月/年购买提升QPS。
*   语音识别极速版：按调用量计费，前5万次调用免费。默认为限额为5QPS，开通付费后限额提升至50QPS（[可申请提升](https://cloud.baidu.com/survey/AICooperativeConsultingApply.html) ）。根据实际调用的次数，系统每小时会对您的百度云账户进行扣费。用多少付多少。根据月累计调用量，可自动享受阶梯折扣。同时，可购买预付次数包。购买后一年内有效，价格更优惠。

使用比较分析：在PRD文件中是否有说明且提供连结证据，所使用的API是查找过最适用的（主要竞争者无或比较次），如考量其成熟度丶性价比丶等等

可支持的格式：
讯飞与百度AI的成熟度：
性价比：价格
### API3.使用后风险报告   

使用后风险报告：在PRD文件中是否有说明且提供连结证据，所使用的API类别的现在及未来发展性，如API市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用API）等等

### API4.加分项   

使用复杂度：用了2个以上[机器学习](http://e.nfu.edu.cn/mod/page/view.php?id=1135 "机器学习")与人工智能的API之输入及输出
语音识别、词法分析

