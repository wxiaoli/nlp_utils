# NLP资源
***Continuously updated.***  
```
注：以下资源均来自网上公开资源（均已标明出处并在此向发布者致以崇高的敬意），  
整理的目的主要是方便自己备查，如果能方便到其他人纯属意外。
```

____
- [NLP工具](#NLP工具)  
- [预训练模型](#预训练模型)  
- [语料](#语料)  
____

## NLP工具
### 标准集/词库
- [计算所汉语词性标记集ictclas](http://ictclas.nlpir.org/nlpir/html/readme.htm) （[json文件](./)）
- [THUOCL: THU Open Chinese Lexicon](https://github.com/thunlp/THUOCL)

### 工具包
- [结巴](https://github.com/fxsjy/jieba)
- [Natural Language Toolkit,NLTK](https://www.nltk.org/) 
  > Resources backup download [address](https://pan.baidu.com/s/18olLCaXSnbKAghdVhGdW7A) (code: ejlw).
- [Stanza: A Python NLP Library for Many Human Languages](https://github.com/stanfordnlp/stanza) 
  > The Stanford NLP Group's official Python NLP library. <br/>
  > It contains support for running various accurate natural language processing tools on 60+ languages. <br/>
  > Resources backup download [address](https://pan.baidu.com/s/1jm_xiCaTdNari8P7zFSouQ) (code: m90v).[gratitude to...](https://blog.csdn.net/GodDavide/article/details/105539730)
  ```python  
    # 加载本地资源示例
    import stanza    
    config = {
        'dir':'./stanza_resources/', # 本地资源路径
        'lang': 'zh' #'en', # Language code
    #     'processors': 'tokenize,mwt,pos,ner', # Comma-separated list of processors to use        
    #     'tokenize_model_path': './fr_gsd_models/fr_gsd_tokenizer.pt', # Processor-specific arguments are set with keys "{processor_name}_{argument_name}"
    #     'mwt_model_path': './fr_gsd_models/fr_gsd_mwt_expander.pt',
    #     'pos_model_path': './fr_gsd_models/fr_gsd_tagger.pt',
    #     'pos_pretrain_path': './fr_gsd_models/fr_gsd.pretrain.pt',
    #     'tokenize_pretokenized': True # Use pretokenized text as input and disable tokenization
    }
    nlp = stanza.Pipeline(**config)
  ```
- [spacy](https://spacy.io/usage/spacy-101)
- [清华大学THULAC(THU Lexical Analyzer for Chinese)](http://thulac.thunlp.org/)  
- [腾讯texsmart](https://ai.tencent.com/ailab/nlp/texsmart/zh/index.htmll)       
- [百度lac(Lexical Analysis of Chinese)](https://github.com/baidu/lac) 

## 预训练模型/词向量
- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)
- [Tencent AI Lab Embedding Corpus for Chinese Words and Phrases](https://ai.tencent.com/ailab/nlp/zh/index.html)  
- [pretrained Bert from google](https://github.com/google-research/bert/blob/master/multilingual.md)
- [many types chinese word embeddings](https://github.com/Embedding/Chinese-Word-Vectors)
- [pretrained BERT for Chinese](https://github.com/ymcui/Chinese-BERT-wwm)

## 语料
- [TWEETQA: A Social Media Focused Question Answering Dataset](https://tweetqa.github.io/)
  > For question answering based on tweet reading comprehension.<br/>
  > Backup download [address](https://pan.baidu.com/s/1CDNHmfiryxWIOxj8FGqnRw) (code: 8le1).<br/>
  > Normalized data version [address](https://pan.baidu.com/s/12OdWBRQOO1nCBkAPTsMqKQ) (code: 3hhv). [gratitude to...](https://github.com/WhaleFallzz/NUT_RC)

- [Movie Review Data](https://www.cs.cornell.edu/people/pabo/movie-review-data/)
  > This page is a distribution site for movie-review data for use in sentiment-analysis experiments.
   Available are collections of movie-review documents labeled with respect to their overall sentiment polarity (positive or negative) or subjective rating (e.g., "two and a half stars") and sentences labeled with respect to their subjectivity status (subjective or objective) or polarity.

____
  
### 收藏
- [ChineseDiachronicCorpus](https://github.com/liuhuanyong/ChineseDiachronicCorpus)   
    > ChineseDiachronicCorpus，中文历时语料库，横跨六十余年，包括腾讯历时新闻2009-2016，人民日报历时语料1946-2003，参考消息历时语料1957-2002。<br/>
    > 基于历时流通语料库，可用于历时语言变化计算、语言监测、社会文化变迁研究提供基础性的语料支持。该项目由公开渠道收集而成，不可商用，若有侵权，可联系删除。    
- [任务分类语料](https://github.com/SimmerChan/corpus)
- [中文医学NLP公开资源](https://github.com/GanjinZero/awesome_Chinese_medical_NLP)
- [中文](https://github.com/brightmart/nlp_chinese_corpus)
- [manythings](http://www.manythings.org/anki/)
- [心理咨询问答语料库](https://github.com/chatopera/efaqa-corpus-zh)
- [chatterbot](https://github.com/gunthercox/chatterbot-corpus)
- [豆瓣多轮](https://github.com/MarkWuNLP/MultiTurnResponseSelection) (已分词) [Sequential Matching Network: A New Archtechture for Multi-turn Response Selection in Retrieval-based Chatbots](https://www.aclweb.org/anthology/P17-1046/)
