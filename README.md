# awesome-fairness-papers
Papers about fairness in NLP/CV/ML

## Background
Fairness, accountability, transparity and ethics become more and more important in machine learning communities. We hope to provide a list of great papers that can work as a reference for researchers interested in such topics. This repo mainly focuses on NLP area but we also point to some resources in the end.

<!-- <p align='center'>
<a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/"><figure><img src="fairness_plot.svg", align="center"></figure></a>
</p>
<p align='center'>credit to <a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/">Stijn Tonk</a></p> -->

**If you have any suggestion, please feel free to edit or pull a request. Your contribution means a lot to us!**


## Contents
- Paper List
- Conference List
- Other resources


### Paper List
- #### Bias Detection
1. Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings. [[pdf]](https://arxiv.org/abs/1607.06520), [[github]](https://github.com/tolga-b/debiaswe)
2. Semantics derived automatically from language corpora contain human-like biases. [[pdf]](https://science.sciencemag.org/content/356/6334/183)
3. Balanced Datasets Are Not Enough: Estimating and Mitigating Gender Bias in Deep Image Representations
4. [Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change](https://cs.stanford.edu/people/jure/pubs/diachronic-acl16.pdf), [[gitub]](https://nlp.stanford.edu/projects/histwords/)
1. [RtGender: A Corpus for Studying Differential Responses to Gender](https://nlp.stanford.edu/robvoigt/rtgender/rtgender.pdf). It provides a dataset to evaluate bias in responses to gender. It could be used in bias detection in dialogue. 
1. [{`}Il {\'e}tait une fois{'} les patterns prosodiques des contes de f{\'e}e ({`}Once upon a time{'} prosodic patterns of fairy tales)](https://www.aclweb.org/anthology/2020.jeptalnrecital-jep.1), Abrougui, Rim  and Bartkova, Katarina, 2020
1. [Unsupervised {WSD} based on Automatically Retrieved Examples: The Importance of Bias](https://www.aclweb.org/anthology/W04-3204), Agirre, Eneko  and Martinez, David, 2004
1. [Identifying and Measuring Annotator Bias Based on Annotators{'} Demographic Characteristics](https://www.aclweb.org/anthology/2020.alw-1.21), Al Kuwatly, Hala  and Wich, Maximilian  and Groh, Georg, 2020
1. [Multilingual sentence-level bias detection in {W}ikipedia](https://www.aclweb.org/anthology/R19-1006), Aleksandrova, Desislava  and Lareau, Fran{\c{c}}ois  and M{\'e}nard, Pierre Andr{\'e}, 2019
1. [Biasing Attention-Based Recurrent Neural Networks Using External Alignment Information](https://www.aclweb.org/anthology/W17-4711), Alkhouli, Tamer  and Ney, Hermann, 2017
1. [Quantitative study of disfluencies in schizophrenics{'} speech: Automatize to limit biases ({\'E}tude quantitative des disfluences dans le discours de schizophr{\`e}nes : automatiser pour limiter les biais) [in {F}rench]](https://www.aclweb.org/anthology/F14-1026), Amblard, Maxime  and Fort, Kar{\"e}n, 2014
1. [Identifying Annotator Bias: A new {IRT}-based method for bias identification](https://www.aclweb.org/anthology/2020.coling-main.421), Amidei, Jacopo  and Piwek, Paul  and Willis, Alistair, 2020
1. [Automated Essay Scoring in the Presence of Biased Ratings](https://www.aclweb.org/anthology/N18-1021), Amorim, Evelin  and Can{\c{c}}ado, Marcia  and Veloso, Adriano, 2018
1. [On-line Language Model Biasing for Statistical Machine Translation](https://www.aclweb.org/anthology/P11-2078), Ananthakrishnan, Sankaranarayanan  and Prasad, Rohit  and Natarajan, Prem, 2011
1. [Inherent Dependency Displacement Bias of Transition-Based Algorithms](https://www.aclweb.org/anthology/2020.lrec-1.633), Anderson, Mark  and G{\'o}mez-Rodr{\'\i}guez, Carlos, 2020
1. [Team Kermit-the-frog at {S}em{E}val-2019 Task 4: Bias Detection Through Sentiment Analysis and Simple Linguistic Features](https://www.aclweb.org/anthology/S19-2177), Anthonio, Talita  and Kloppenburg, Lennart, 2019
1. [Don{'}t Stop Me Now! Using Global Dynamic Oracles to Correct Training Biases of Transition-Based Dependency Parsers](https://www.aclweb.org/anthology/E17-2051), Aufrant, Lauriane  and Wisniewski, Guillaume  and Yvon, Fran{\c{c}}ois, 2017
1. [Measuring the Effects of Bias in Training Data for Literary Classification](https://www.aclweb.org/anthology/2020.latechclfl-1.9), Bagga, Sunyam  and Piper, Andrew, 2020
1. [Predicting Factuality of Reporting and Bias of News Media Sources](https://www.aclweb.org/anthology/D18-1389), Baly, Ramy  and Karadzhov, Georgi  and Alexandrov, Dimitar  and Glass, James  and Nakov, Preslav, 2018
1. [We Can Detect Your Bias: Predicting the Political Ideology of News Articles](https://www.aclweb.org/anthology/2020.emnlp-main.404), Baly, Ramy  and Da San Martino, Giovanni  and Glass, James  and Nakov, Preslav, 2020
1. [How Topic Biases Your Results? A Case Study of Sentiment Analysis and Irony Detection in {I}talian](https://www.aclweb.org/anthology/R15-1006), Barbieri, Francesco  and Ronzano, Francesco  and Saggion, Horacio, 2015
1. [Robust Sentiment Detection on {T}witter from Biased and Noisy Data](https://www.aclweb.org/anthology/C10-2005), Barbosa, Luciano  and Feng, Junlan, 2010
1. [Unmasking Contextual Stereotypes: Measuring and Mitigating {BERT}{'}s Gender Bias](https://www.aclweb.org/anthology/2020.gebnlp-1.1), Bartl, Marion  and Nissim, Malvina  and Gatt, Albert, 2020
1. [Evaluating the Underlying Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/W19-3805), Basta, Christine  and Costa-juss{\`a}, Marta R.  and Casas, Noe, 2019
1. [Towards Mitigating Gender Bias in a decoder-based Neural Machine Translation model by Adding Contextual Information](https://www.aclweb.org/anthology/2020.winlp-1.25), Basta, Christine  and Costa-juss{\`a}, Marta R.  and Fonollosa, Jos{\'e} A. R., 2020
1. [Representation Problems in Linguistic Annotations: Ambiguity, Variation, Uncertainty, Error and Bias](https://www.aclweb.org/anthology/2020.law-1.6), Beck, Christin  and Booth, Hannah  and El-Assady, Mennatallah  and Butt, Miriam, 2020
1. [On Adversarial Removal of Hypothesis-only Bias in Natural Language Inference](https://www.aclweb.org/anthology/S19-1028), Belinkov, Yonatan  and Poliak, Adam  and Shieber, Stuart  and Van Durme, Benjamin  and Rush, Alexander, 2019
1. [Data Statements for Natural Language Processing: Toward Mitigating System Bias and Enabling Better Science](https://www.aclweb.org/anthology/Q18-1041), Bender, Emily M.  and Friedman, Batya, 2018
1. [Bias Analysis and Mitigation in the Evaluation of Authorship Verification](https://www.aclweb.org/anthology/P19-1634), Bevendorff, Janek  and Hagen, Matthias  and Stein, Benno  and Potthast, Martin, 2019
1. [Language (Technology) is Power: A Critical Survey of {``}Bias{''} in {NLP}](https://www.aclweb.org/anthology/2020.acl-main.485), Blodgett, Su Lin  and Barocas, Solon  and Daum{\'e} III, Hal  and Wallach, Hanna, 2020
1. [Identifying and Reducing Gender Bias in Word-Level Language Models](https://www.aclweb.org/anthology/N19-3002), Bordia, Shikha  and Bowman, Samuel R., 2019
1. [How to do Dialogue in a Fairy-tale World](https://www.aclweb.org/anthology/2005.sigdial-1.27), Boye, Johan  and Gustafson, Joakim, 2005
1. [The Multilingual Affective Soccer Corpus ({MASC}): Compiling a biased parallel corpus on soccer reportage in {E}nglish, {G}erman and {D}utch](https://www.aclweb.org/anthology/W16-6612), Braun, Nadine  and Goudbeek, Martijn  and Krahmer, Emiel, 2016
1. [Word-order Biases in Deep-agent Emergent Communication](https://www.aclweb.org/anthology/P19-1509), Chaabouni, Rahma  and Kharitonov, Eugene  and Lazaric, Alessandro  and Dupoux, Emmanuel  and Baroni, Marco, 2019
1. [Importance sampling for unbiased on-demand evaluation of knowledge base population](https://www.aclweb.org/anthology/D17-1109), Chaganty, Arun  and Paranjape, Ashwin  and Liang, Percy  and Manning, Christopher D., 2017
1. [The price of debiasing automatic metrics in natural language evalaution](https://www.aclweb.org/anthology/P18-1060), Chaganty, Arun  and Mussmann, Stephen  and Liang, Percy, 2018
1. [Measuring Gender Bias in Word Embeddings across Domains and Discovering New Gender Bias Word Categories](https://www.aclweb.org/anthology/W19-3804), Chaloner, Kaytlin  and Maldonado, Alfredo, 2019
1. [Countering Position Bias in Instructor Interventions in {MOOC} Discussion Forums](https://www.aclweb.org/anthology/W18-3720), Chandrasekaran, Muthu Kumar  and Kan, Min-Yen, 2018
1. [Bias and Fairness in Natural Language Processing](https://www.aclweb.org/anthology/D19-2004), Chang, Kai-Wei  and Prabhakaran, Vinod  and Ordonez, Vicente, 2019
1. [A Natural Language Processing System for National {COVID-19} Surveillance in the {US Department of Veterans Affairs}](https://www.aclweb.org/anthology/2020.nlpcovid19-acl.10), Chapman, Alec  and Peterson, Kelly  and Turano, Augie  and Box, Tam{\'a}ra  and Wallace, Katherine  and Jones, Makoto, 2020
1. [Evaluating Bias In {D}utch Word Embeddings](https://www.aclweb.org/anthology/2020.gebnlp-1.6), Ch{\'a}vez Mulsa, Rodrigo Alejandro  and Spanakis, Gerasimos, 2020
1. [Collective Event Detection via a Hierarchical and Bias Tagging Networks with Gated Multi-level Attention Mechanisms](https://www.aclweb.org/anthology/D18-1158), Chen, Yubo  and Yang, Hang  and Liu, Kang  and Zhao, Jun  and Jia, Yantao, 2018
1. [Learning to Flip the Bias of News Headlines](https://www.aclweb.org/anthology/W18-6509), Chen, Wei-Fan  and Wachsmuth, Henning  and Al-Khatib, Khalid  and Stein, Benno, 2018
1. [Analyzing Political Bias and Unfairness in News Articles at Different Levels of Granularity](https://www.aclweb.org/anthology/2020.nlpcss-1.16), Chen, Wei-Fan  and Al Khatib, Khalid  and Wachsmuth, Henning  and Stein, Benno, 2020
1. [Detecting Media Bias in News Articles using {G}aussian Bias Distributions](https://www.aclweb.org/anthology/2020.findings-emnlp.383), Chen, Wei-Fan  and Al Khatib, Khalid  and Stein, Benno  and Wachsmuth, Henning, 2020
1. [Exploring Text Specific and Blackbox Fairness Algorithms in Multimodal Clinical {NLP}](https://www.aclweb.org/anthology/2020.clinicalnlp-1.33), Chen, John  and Berlot-Attwell, Ian  and Wang, Xindi  and Hossain, Safwan  and Rudzicz, Frank, 2020
1. [On Measuring Gender Bias in Translation of Gender-neutral Pronouns](https://www.aclweb.org/anthology/W19-3824), Cho, Won Ik  and Kim, Ji Won  and Kim, Seok Min  and Kim, Nam Soo, 2019
1. [Structured Local Training and Biased Potential Functions for Conditional Random Fields with Application to Coreference Resolution](https://www.aclweb.org/anthology/N07-1009), Choi, Yejin  and Cardie, Claire, 2007
1. [Inherent Biases in Reference-based Evaluation for Grammatical Error Correction](https://www.aclweb.org/anthology/P18-1059), Choshen, Leshem  and Abend, Omri, 2018
1. [Symbolic Inductive Bias for Visually Grounded Learning of Spoken Language](https://www.aclweb.org/anthology/P19-1647), Chrupa{\l}a, Grzegorz, 2019
1. [Don{'}t Take the Easy Way Out: Ensemble Based Methods for Avoiding Known Dataset Biases](https://www.aclweb.org/anthology/D19-1418), Clark, Christopher  and Yatskar, Mark  and Zettlemoyer, Luke, 2019
1. [Learning to Model and Ignore Dataset Bias with Mixed Capacity Ensembles](https://www.aclweb.org/anthology/2020.findings-emnlp.272), Clark, Christopher  and Yatskar, Mark  and Zettlemoyer, Luke, 2020
1. [Incorporating Structural Alignment Biases into an Attentional Neural Translation Model](https://www.aclweb.org/anthology/N16-1102), Cohn, Trevor  and Hoang, Cong Duy Vu  and Vymolova, Ekaterina  and Yao, Kaisheng  and Dyer, Chris  and Haffari, Gholamreza, 2016
1. [Modelling Annotator Bias with Multi-task {G}aussian Processes: An Application to Machine Translation Quality Estimation](https://www.aclweb.org/anthology/P13-1004), Cohn, Trevor  and Specia, Lucia, 2013
1. [Regional Bias in the Broad Phonetic Transcriptions of the Spoken {D}utch Corpus](http://www.lrec-conf.org/proceedings/lrec2006/pdf/323_pdf.pdf), Couss{\'e}, Evie  and Gillis, Steven, 2006
1. [Racial Bias in Hate Speech and Abusive Language Detection Datasets](https://www.aclweb.org/anthology/W19-3504), Davidson, Thomas  and Bhattacharya, Debasmita  and Weber, Ingmar, 2019
1. [Masking Actor Information Leads to Fairer Political Claims Detection](https://www.aclweb.org/anthology/2020.acl-main.404), Dayanik, Erenay  and Pad{\'o}, Sebastian, 2020
1. [{CLARIN}: Towards {FAIR} and Responsible Data Science Using Language Resources](https://www.aclweb.org/anthology/L18-1515), de Jong, Franciska  and Maegaard, Bente  and De Smedt, Koenraad  and Fi{\v{s}}er, Darja  and Van Uytvanck, Dieter, 2018
1. [The Role of Algorithm Bias vs Information Source in Learning Algorithms for Morphosyntactic Disambiguation](https://www.aclweb.org/anthology/W00-0704), De Pauw, Guy  and Daelemans, Walter, 2000
1. [Semi-Supervised Topic Modeling for Gender Bias Discovery in {E}nglish and {S}wedish](https://www.aclweb.org/anthology/2020.gebnlp-1.8), Devinney, Hannah  and Bj{\"o}rklund, Jenny  and Bj{\"o}rklund, Henrik, 2020
1. [Corpora Evaluation and System Bias Detection in Multi-document Summarization](https://www.aclweb.org/anthology/2020.findings-emnlp.254), Dey, Alvin  and Chowdhury, Tanya  and Kumar, Yash  and Chakraborty, Tanmoy, 2020
1. [Multi-Dimensional Gender Bias Classification](https://www.aclweb.org/anthology/2020.emnlp-main.23), Dinan, Emily  and Fan, Angela  and Wu, Ledell  and Weston, Jason  and Kiela, Douwe  and Williams, Adina, 2020
1. [Queens are Powerful too: Mitigating Gender Bias in Dialogue Generation](https://www.aclweb.org/anthology/2020.emnlp-main.656), Dinan, Emily  and Fan, Angela  and Williams, Adina  and Urbanek, Jack  and Kiela, Douwe  and Weston, Jason, 2020
1. [Exploring the Functional and Geometric Bias of Spatial Relations Using Neural Language Models](https://www.aclweb.org/anthology/W18-1401), Dobnik, Simon  and Ghanimifard, Mehdi  and Kelleher, John, 2018
1. [Inherent Biases of Recurrent Neural Networks for Phonological Assimilation and Dissimilation](https://www.aclweb.org/anthology/W17-0705), Doucette, Amanda, 2017
1. [Outta Control: Laws of Semantic Change and Inherent Biases in Word Representation Models](https://www.aclweb.org/anthology/D17-1118), Dubossarsky, Haim  and Weinshall, Daphna  and Grossman, Eitan, 2017
1. [{S}yntax{F}est 2019 Invited talk - Inductive biases and language emergence in communicative agents](https://www.aclweb.org/anthology/W19-7701), Dupoux, Emmanuel, 2019
1. [A {F}rench Fairy Tale Corpus syntactically and semantically annotated](http://www.lrec-conf.org/proceedings/lrec2012/pdf/220_Paper.pdf), El Maarouf, Isma{\"\i}l  and Villaneau, Jeanne, 2012
1. [Detecting Word Sense Disambiguation Biases in Machine Translation for Model-Agnostic Adversarial Attacks](https://www.aclweb.org/anthology/2020.emnlp-main.616), Emelin, Denis  and Titov, Ivan  and Sennrich, Rico, 2020
1. [Equalizing Gender Bias in Neural Machine Translation with Word Embeddings Techniques](https://www.aclweb.org/anthology/W19-3821), Escud{\'e} Font, Joel  and Costa-juss{\`a}, Marta R., 2019
1. [Is Your Classifier Actually Biased? Measuring Fairness under Uncertainty with Bernstein Bounds](https://www.aclweb.org/anthology/2020.acl-main.262), Ethayarajh, Kawin, 2020
1. [In Plain Sight: Media Bias Through the Lens of Factual Reporting](https://www.aclweb.org/anthology/D19-1664), Fan, Lisa  and White, Marshall  and Sharma, Eva  and Su, Ruisi  and Choubey, Prafulla Kumar  and Huang, Ruihong  and Wang, Lu, 2019
1. [Team Peter Brinkmann at {S}em{E}val-2019 Task 4: Detecting Biased News Articles Using Convolutional Neural Networks](https://www.aclweb.org/anthology/S19-2180), F{\"a}rber, Michael  and Qurdina, Agon  and Ahmedi, Lule, 2019
1. [The Impact of Topic Bias on Quality Flaw Prediction in {W}ikipedia](https://www.aclweb.org/anthology/P13-1071), Ferschke, Oliver  and Gurevych, Iryna  and Rittberger, Marc, 2013
1. [Unsupervised Discovery of Implicit Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.44), Field, Anjalie  and Tsvetkov, Yulia, 2020
1. [Biases in Predicting the Human Language Model](https://www.aclweb.org/anthology/P14-2002), Fine, Alex B.  and Frank, Austin F.  and Jaeger, T. Florian  and Van Durme, Benjamin, 2014
1. [Debiasing knowledge graph embeddings](https://www.aclweb.org/anthology/2020.emnlp-main.595), Fisher, Joseph  and Mittal, Arpit  and Palfrey, Dave  and Christodoulopoulos, Christos, 2020
1. [Analyzing Biases in Human Perception of User Age and Gender from Text](https://www.aclweb.org/anthology/P16-1080), Flekova, Lucie  and Carpenter, Jordan  and Giorgi, Salvatore  and Ungar, Lyle  and Preo{\c{t}}iuc-Pietro, Daniel, 2016
1. [Reference Bias in Monolingual Machine Translation Evaluation](https://www.aclweb.org/anthology/P16-2013), Fomicheva, Marina  and Specia, Lucia, 2016
1. [{APE} at Scale and Its Implications on {MT} Evaluation Biases](https://www.aclweb.org/anthology/W19-5204), Freitag, Markus  and Caswell, Isaac  and Roy, Scott, 2019
1. [Relating Word Embedding Gender Biases to Gender Gaps: A Cross-Cultural Analysis](https://www.aclweb.org/anthology/W19-3803), Friedman, Scott  and Schmer-Galunder, Sonja  and Chen, Anthony  and Rye, Jeffrey, 2019
1. [Analyzing Gender Bias within Narrative Tropes](https://www.aclweb.org/anthology/2020.nlpcss-1.23), Gala, Dhruvil  and Khursheed, Mohammad Omar  and Lerner, Hannah  and O{'}Connor, Brendan  and Iyyer, Mohit, 2020
1. [Detecting Political Bias in News Articles Using Headline Attention](https://www.aclweb.org/anthology/W19-4809), Gangula, Rama Rohit Reddy  and Duggenpudi, Suma Reddy  and Mamidi, Radhika, 2019
1. [Women{'}s Syntactic Resilience and Men{'}s Grammatical Luck: Gender-Bias in Part-of-Speech Tagging and Dependency Parsing](https://www.aclweb.org/anthology/P19-1339), Garimella, Aparna  and Banea, Carmen  and Hovy, Dirk  and Mihalcea, Rada, 2019
1. [Pratiques d{'}{\'e}valuation en {ASR} et biais de performance (Evaluation methodology in {ASR} and performance bias)](https://www.aclweb.org/anthology/2020.jeptalnrecital-eternal.1), Garnerin, Mahault  and Rossato, Solange  and Besacier, Laurent, 2020
1. [Towards Understanding Gender Bias in Relation Extraction](https://www.aclweb.org/anthology/2020.acl-main.265), Gaut, Andrew  and Sun, Tony  and Tang, Shirlyn  and Huang, Yuxin  and Qian, Jing  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2020
1. [Proceedings of the Second Workshop on Gender Bias in Natural Language Processing](https://www.aclweb.org/anthology/2020.gebnlp-1.0), Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will  and Webster, Kellie, 2020
1. [Posing Fair Generalization Tasks for Natural Language Inference](https://www.aclweb.org/anthology/D19-1456), Geiger, Atticus  and Cases, Ignacio  and Karttunen, Lauri  and Potts, Christopher, 2019
1. [Are We Modeling the Task or the Annotator? An Investigation of Annotator Bias in Natural Language Understanding Datasets](https://www.aclweb.org/anthology/D19-1107), Geva, Mor  and Goldberg, Yoav  and Berant, Jonathan, 2019
1. [Learning Bias and Phonological-Rule Induction](https://www.aclweb.org/anthology/J96-4003), Gildea, Daniel  and Jurafsky, Daniel, 1996
1. [Inspecting the Structural Biases of Dependency Parsing Algorithms](https://www.aclweb.org/anthology/W10-2927), Goldberg, Yoav  and Elhadad, Michael, 2010
1. [Representational Bias in Unsupervised Learning of Syllable Structure](https://www.aclweb.org/anthology/W05-0615), Goldwater, Sharon  and Johnson, Mark, 2005
1. [Lipstick on a Pig: {D}ebiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://www.aclweb.org/anthology/N19-1061), Gonen, Hila  and Goldberg, Yoav, 2019
1. [Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://www.aclweb.org/anthology/W19-3621), Gonen, Hila  and Goldberg, Yoav, 2019
1. [Type {B} Reflexivization as an Unambiguous Testbed for Multilingual Multi-Task Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.209), Gonz{\'a}lez, Ana Valeria  and Barrett, Maria  and Hvingelby, Rasmus  and Webster, Kellie  and S{\o}gaard, Anders, 2020
1. [Countering the Effects of Lead Bias in News Summarization via Multi-Stage Training and Auxiliary Losses](https://www.aclweb.org/anthology/D19-1620), Grenander, Matt  and Dong, Yue  and Cheung, Jackie Chi Kit  and Louis, Annie, 2019
1. [Inflating Topic Relevance with Ideology: A Case Study of Political Ideology Bias in Social Topic Detection Models](https://www.aclweb.org/anthology/2020.coling-main.428), Guo, Meiqi  and Hwa, Rebecca  and Lin, Yu-Ru  and Chung, Wen-Ting, 2020
1. [Viable Threat on News Reading: Generating Biased News Using Natural Language Models](https://www.aclweb.org/anthology/2020.nlpcss-1.7), Gupta, Saurabh  and Nguyen, Hong Huy  and Yamagishi, Junichi  and Echizen, Isao, 2020
1. [The {NICE} Fairy-tale Game System](https://www.aclweb.org/anthology/W04-2304), Gustafson, Joakim  and Bell, Linda  and Boye, Johan  and Lindstr{\"o}m, Anders  and Wir{\'e}n, Mats, 2004
1. [It{'}s All in the Name: Mitigating Gender Bias with Name-Based Counterfactual Data Substitution](https://www.aclweb.org/anthology/D19-1530), Hall Maudslay, Rowan  and Gonen, Hila  and Cotterell, Ryan  and Teufel, Simone, 2019
1. [Media Bias, the Social Sciences, and {NLP}: Automating Frame Analyses to Identify Bias by Word Choice and Labeling](https://www.aclweb.org/anthology/2020.acl-srw.12), Hamborg, Felix, 2020
1. [Investigating representations of verb bias in neural language models](https://www.aclweb.org/anthology/2020.emnlp-main.376), Hawkins, Robert  and Yamakoshi, Takateru  and Griffiths, Thomas  and Goldberg, Adele, 2020
1. [Unlearn Dataset Bias in Natural Language Inference by Fitting the Residual](https://www.aclweb.org/anthology/D19-6115), He, He  and Zha, Sheng  and Wang, Haohan, 2019
1. [An Annotation Scheme for Automated Bias Detection in {W}ikipedia](https://www.aclweb.org/anthology/W11-0406), Herzig, Livnat  and Nunes, Alex  and Snir, Batia, 2011
1. [Debiasing Word Embeddings Improves Multimodal Machine Translation](https://www.aclweb.org/anthology/W19-6604), Hirasawa, Tosho  and Komachi, Mamoru, 2019
1. [Proposed Taxonomy for Gender Bias in Text; A Filtering Methodology for the Gender Generalization Subtype](https://www.aclweb.org/anthology/W19-3802), Hitti, Yasmeen  and Jang, Eunbee  and Moreno, Ines  and Pelletier, Carolyne, 2019
1. [When {POS} data sets don{'}t add up: Combatting sample bias](http://www.lrec-conf.org/proceedings/lrec2014/pdf/476_Paper.pdf), Hovy, Dirk  and Plank, Barbara  and S{\o}gaard, Anders, 2014
1. [{``}You Sound Just Like Your Father{''} Commercial Machine Translation Systems Include Stylistic Biases](https://www.aclweb.org/anthology/2020.acl-main.154), Hovy, Dirk  and Bianchi, Federico  and Fornaciari, Tommaso, 2020
1. [Fertility-based Source-Language-biased Inversion Transduction Grammar for Word Alignment](https://www.aclweb.org/anthology/O09-3001), Huang, Chung-Chi  and Chang, Jason S., 2009
1. [Quality-biased Ranking of Short Texts in Microblogging Services](https://www.aclweb.org/anthology/I11-1042), Huang, Minlie  and Yang, Yi  and Zhu, Xiaoyan, 2011
1. [Multilingual {T}witter Corpus and Baselines for Evaluating Demographic Bias in Hate Speech Recognition](https://www.aclweb.org/anthology/2020.lrec-1.180), Huang, Xiaolei  and Xing, Linzi  and Dernoncourt, Franck  and Paul, Michael J., 2020
1. [Reducing Sentiment Bias in Language Models via Counterfactual Evaluation](https://www.aclweb.org/anthology/2020.findings-emnlp.7), Huang, Po-Sen  and Zhang, Huan  and Jiang, Ray  and Stanforth, Robert  and Welbl, Johannes  and Rae, Jack  and Maini, Vishal  and Yogatama, Dani  and Kohli, Pushmeet, 2020
1. [Biased Representation Learning for Domain Adaptation](https://www.aclweb.org/anthology/D12-1120), Huang, Fei  and Yates, Alexander, 2012
1. [Social Biases in {NLP} Models as Barriers for Persons with Disabilities](https://www.aclweb.org/anthology/2020.acl-main.487), Hutchinson, Ben  and Prabhakaran, Vinodkumar  and Denton, Emily  and Webster, Kellie  and Zhong, Yu  and Denuyl, Stephen, 2020
1. [Mitigating Gender Bias Amplification in Distribution by Posterior Regularization](https://www.aclweb.org/anthology/2020.acl-main.264), Jia, Shengyu  and Meng, Tao  and Zhao, Jieyu  and Chang, Kai-Wei, 2020
1. [Squibs and Discussions: The {DOP} Estimation Method is Biased and Inconsistent](https://www.aclweb.org/anthology/J02-1005), Johnson, Mark, 2002
1. [Earlier Isn{'}t Always Better: Sub-aspect Analysis on Corpus and System Biases in Summarization](https://www.aclweb.org/anthology/D19-1327), Jung, Taehee  and Kang, Dongyeop  and Mentch, Lucas  and Hovy, Eduard, 2019
1. [Enhancing Bias Detection in Political News Using Pragmatic Presupposition](https://www.aclweb.org/anthology/2020.socialnlp-1.1), Kameswari, Lalitha  and Sravani, Dama  and Mamidi, Radhika, 2020
1. [Gender-preserving Debiasing for Pre-trained Word Embeddings](https://www.aclweb.org/anthology/P19-1160), Kaneko, Masahiro  and Bollegala, Danushka, 2019
1. [End-to-End Bias Mitigation by Modelling Biases in Corpora](https://www.aclweb.org/anthology/2020.acl-main.769), Karimi Mahabadi, Rabeeh  and Belinkov, Yonatan  and Henderson, James, 2020
1. [Conceptor Debiasing of Word Representations Evaluated on {WEAT}](https://www.aclweb.org/anthology/W19-3806), Karve, Saket  and Ungar, Lyle  and Sedoc, Jo{\~a}o, 2019
1. [Query-Focused Summaries or Query-Biased Summaries?](https://www.aclweb.org/anthology/P09-2027), Katragadda, Rahul  and Varma, Vasudeva, 2009
1. [Biased {T}ext{R}ank: Unsupervised Graph-Based Content Extraction](https://www.aclweb.org/anthology/2020.coling-main.144), Kazemi, Ashkan  and P{\'e}rez-Rosas, Ver{\'o}nica  and Mihalcea, Rada, 2020
1. [When Transliteration Met Crowdsourcing : An Empirical Study of Transliteration via Crowdsourcing using Efficient, Non-redundant and Fair Quality Control](http://www.lrec-conf.org/proceedings/lrec2014/pdf/94_Paper.pdf), Khapra, Mitesh M.  and Ramanathan, Ananthakrishnan  and Kunchukuttan, Anoop  and Visweswariah, Karthik  and Bhattacharyya, Pushpak, 2014
1. [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://www.aclweb.org/anthology/S18-2005), Kiritchenko, Svetlana  and Mohammad, Saif, 2018
1. [Look at the First Sentence: Position Bias in Question Answering](https://www.aclweb.org/anthology/2020.emnlp-main.84), Ko, Miyoung  and Lee, Jinhyuk  and Kim, Hyunjae  and Kim, Gangwoo  and Kang, Jaewoo, 2020
1. [Gender Coreference and Bias Evaluation at {WMT} 2020](https://www.aclweb.org/anthology/2020.wmt-1.39), Kocmi, Tom  and Limisiewicz, Tomasz  and Stanovsky, Gabriel, 2020
1. [These are not the Stereotypes You are Looking For: Bias and Fairness in Authorial Gender Attribution](https://www.aclweb.org/anthology/W17-1602), Koolen, Corina  and van Cranenburgh, Andreas, 2017
1. [Du bruit, du silence et des ambigu{\"\i}t{\'e}s : que faire du {TAL} pour l{'}apprentissage des langues ?](https://www.aclweb.org/anthology/2007.jeptalnrecital-poster.14), Kraif, Olivier  and Ponton, Claude, 2007
1. [Fair Embedding Engine: A Library for Analyzing and Mitigating Gender Bias in Word Embeddings](https://www.aclweb.org/anthology/2020.nlposs-1.5), Kumar, Vaibhav  and Bhotia, Tenzin  and Kumar, Vaibhav, 2020
1. [Nurse is Closer to Woman than Surgeon? Mitigating Gender-Biased Proximities in Word Embeddings](https://www.aclweb.org/anthology/2020.tacl-1.32), Kumar, Vaibhav  and Bhotia, Tenzin Singhay  and Kumar, Vaibhav  and Chakraborty, Tanmoy, 2020
1. [Measuring Bias in Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3823), Kurita, Keita  and Vyas, Nidhi  and Pareek, Ayush  and Black, Alan W  and Tsvetkov, Yulia, 2019
1. [{A}ra{WEAT}: Multidimensional Analysis of Biases in {A}rabic Word Embeddings](https://www.aclweb.org/anthology/2020.wanlp-1.17), Lauscher, Anne  and Takieddin, Rafik  and Ponzetto, Simone Paolo  and Glava{\v{s}}, Goran, 2020
1. [Are We Consistently Biased? Multidimensional Analysis of Biases in Distributional Word Vectors](https://www.aclweb.org/anthology/S19-1010), Lauscher, Anne  and Glava{\v{s}}, Goran, 2019
1. [Discovering Biased News Articles Leveraging Multiple Human Annotations](https://www.aclweb.org/anthology/2020.lrec-1.159), Lazaridou, Konstantina  and L{\"o}ser, Alexander  and Mestre, Maria  and Naumann, Felix, 2020
1. [Exploring Social Bias in Chatbots using Stereotype Knowledge](https://www.aclweb.org/anthology/W19-3655), Lee, Nayeon  and Madotto, Andrea  and Fung, Pascale, 2019
1. [Integration of Linguistic Markup into Semantic Models of Folk Narratives: The Fairy Tale Use Case](http://www.lrec-conf.org/proceedings/lrec2010/pdf/654_Paper.pdf), Lendvai, Piroska  and Declerck, Thierry  and Dar{\'a}nyi, S{\'a}ndor  and Gerv{\'a}s, Pablo  and Herv{\'a}s, Raquel  and Malec, Scott  and Peinado, Federico, 2010
1. [Unequal Representations: Analyzing Intersectional Biases in Word Embeddings Using Representational Similarity Analysis](https://www.aclweb.org/anthology/2020.coling-main.151), Lepori, Michael, 2020
1. [Pourquoi construire des ressources terminologiques et pourquoi le faire diff{\'e}remment ?](https://www.aclweb.org/anthology/2015.jeptalnrecital-invite.2), L{'}Homme, Marie-Claude, 2015
1. [Active Testing: An Unbiased Evaluation Method for Distantly Supervised Relation Extraction](https://www.aclweb.org/anthology/2020.findings-emnlp.20), Li, Pengshuai  and Zhang, Xinsong  and Jia, Weijia  and Zhao, Wei, 2020
1. [On the Branching Bias of Syntax Extracted from Pre-trained Language Models](https://www.aclweb.org/anthology/2020.findings-emnlp.401), Li, Huayang  and Liu, Lemao  and Huang, Guoping  and Shi, Shuming, 2020
1. [{UNQOVER}ing Stereotyping Biases via Underspecified Questions](https://www.aclweb.org/anthology/2020.findings-emnlp.311), Li, Tao  and Khashabi, Daniel  and Khot, Tushar  and Sabharwal, Ashish  and Srikumar, Vivek, 2020
1. [Monolingual and Multilingual Reduction of Gender Bias in Contextualized Representations](https://www.aclweb.org/anthology/2020.coling-main.446), Liang, Sheng  and Dufter, Philipp  and Sch{\"u}tze, Hinrich, 2020
1. [Towards Debiasing Sentence Representations](https://www.aclweb.org/anthology/2020.acl-main.488), Liang, Paul Pu  and Li, Irene Mengze  and Zheng, Emily  and Lim, Yao Chong  and Salakhutdinov, Ruslan  and Morency, Louis-Philippe, 2020
1. [Annotating and Analyzing Biased Sentences in News Articles using Crowdsourcing](https://www.aclweb.org/anthology/2020.lrec-1.184), Lim, Sora  and Jatowt, Adam  and F{\"a}rber, Michael  and Yoshikawa, Masatoshi, 2020
1. [An Empirical Study on Model-agnostic Debiasing Strategies for Robust Natural Language Inference](https://www.aclweb.org/anthology/2020.conll-1.48), Liu, Tianyu  and Xin, Zheng  and Ding, Xiaoan  and Chang, Baobao  and Sui, Zhifang, 2020
1. [Does Gender Matter? Towards Fairness in Dialogue Systems](https://www.aclweb.org/anthology/2020.coling-main.390), Liu, Haochen  and Dacon, Jamell  and Fan, Wenqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [{H}ypo{NLI}: Exploring the Artificial Patterns of Hypothesis-only Bias in Natural Language Inference](https://www.aclweb.org/anthology/2020.lrec-1.846), Liu, Tianyu  and Xin, Zheng  and Chang, Baobao  and Sui, Zhifang, 2020
1. [Mitigating Gender Bias for Neural Dialogue Generation with Adversarial Learning](https://www.aclweb.org/anthology/2020.emnlp-main.64), Liu, Haochen  and Wang, Wentao  and Wang, Yiqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [Producing Monolingual and Parallel Web Corpora at the Same Time - {S}pider{L}ing and Bitextor{'}s Love Affair](https://www.aclweb.org/anthology/L16-1471), Ljube{\v{s}}i{\'c}, Nikola  and Espl{\`a}-Gomis, Miquel  and Toral, Antonio  and Rojas, Sergio Ortiz  and Klubi{\v{c}}ka, Filip, 2016
1. [Fairy Tale Corpus Organization Using Latent Semantic Mapping and an Item-to-item Top-n Recommendation Algorithm](http://www.lrec-conf.org/proceedings/lrec2010/pdf/786_Paper.pdf), Lobo, Paula Vaz  and de Matos, David Martins, 2010
1. [Dual Memory Network Model for Biased Product Review Classification](https://www.aclweb.org/anthology/W18-6220), Long, Yunfei  and Ma, Mingyu  and Lu, Qin  and Xiang, Rong  and Huang, Chu-Ren, 2018
1. [The many dimensions of algorithmic fairness in educational applications](https://www.aclweb.org/anthology/W19-4401), Loukina, Anastassia  and Madnani, Nitin  and Zechner, Klaus, 2019
1. [Mining human interactions to construct a virtual guide for a virtual fair](https://www.aclweb.org/anthology/W14-0206), Luna, Andr{\'e}s  and Benotti, Luciana, 2014
1. [Differentially Private Representation for {NLP}: Formal Guarantee and An Empirical Study on Privacy and Fairness](https://www.aclweb.org/anthology/2020.findings-emnlp.213), Lyu, Lingjuan  and He, Xuanli  and Li, Yitong, 2020
1. [Further Investigation into Reference Bias in Monolingual Evaluation of Machine Translation](https://www.aclweb.org/anthology/D17-1262), Ma, Qingsong  and Graham, Yvette  and Baldwin, Timothy  and Liu, Qun, 2017
1. [{P}ower{T}ransformer: Unsupervised Controllable Revision for Biased Language Correction](https://www.aclweb.org/anthology/2020.emnlp-main.602), Ma, Xinyao  and Sap, Maarten  and Rashkin, Hannah  and Choi, Yejin, 2020
1. [Building Better Open-Source Tools to Support Fairness in Automated Scoring](https://www.aclweb.org/anthology/W17-1605), Madnani, Nitin  and Loukina, Anastassia  and von Davier, Alina  and Burstein, Jill  and Cahill, Aoife, 2017
1. [Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings](https://www.aclweb.org/anthology/N19-1062), Manzini, Thomas  and Yao Chong, Lim  and Black, Alan W  and Tsvetkov, Yulia, 2019
1. [The Effect of Bias on an Automatically-built Word Sense Corpus](http://www.lrec-conf.org/proceedings/lrec2004/pdf/648.pdf), Mart{\'\i}nez, David  and Agirre, Eneko, 2004
1. [On Measuring Social Biases in Sentence Encoders](https://www.aclweb.org/anthology/N19-1063), May, Chandler  and Wang, Alex  and Bordia, Shikha  and Bowman, Samuel R.  and Rudinger, Rachel, 2019
1. [Equity Beyond Bias in Language Technologies for Education](https://www.aclweb.org/anthology/W19-4446), Mayfield, Elijah  and Madaio, Michael  and Prabhumoye, Shrimai  and Gerritsen, David  and McLaughlin, Brittany  and Dixon-Rom{\'a}n, Ezekiel  and Black, Alan W, 2019
1. [Does Syntax Need to Grow on Trees? Sources of Hierarchical Inductive Bias in Sequence-to-Sequence Networks](https://www.aclweb.org/anthology/2020.tacl-1.9), McCoy, R. Thomas  and Frank, Robert  and Linzen, Tal, 2020
1. [Event-Related Bias Removal for Real-time Disaster Events](https://www.aclweb.org/anthology/2020.findings-emnlp.344), Medina Maza, Salvador  and Spiliopoulou, Evangelia  and Hovy, Eduard  and Hauptmann, Alexander, 2020
1. [Investigating Sports Commentator Bias within a Large Corpus of {A}merican Football Broadcasts](https://www.aclweb.org/anthology/D19-1666), Merullo, Jack  and Yeh, Luke  and Handler, Abram  and Grissom II, Alvin  and O{'}Connor, Brendan  and Iyyer, Mohit, 2019
1. [Artie Bias Corpus: An Open Dataset for Detecting Demographic Bias in Speech Applications](https://www.aclweb.org/anthology/2020.lrec-1.796), Meyer, Josh  and Rauchenstein, Lindy  and Eisenberg, Joshua D.  and Howell, Nicholas, 2020
1. [From Once Upon a Time to Happily Ever After: Tracking Emotions in Novels and Fairy Tales](https://www.aclweb.org/anthology/W11-1514), Mohammad, Saif, 2011
1. [Comparative Experiments on Disambiguating Word Senses: An Illustration of the Role of Bias in Machine Learning](https://www.aclweb.org/anthology/W96-0208), Mooney, Raymond J., 1996
1. [Investigating the Documentation of Electronic Cigarette Use in the Veteran Affairs Electronic Health Record: A Pilot Study](https://www.aclweb.org/anthology/W17-2335), Mowery, Danielle  and South, Brett  and Patterson, Olga  and Zhu, Shu-Hong  and Conway, Mike, 2017
1. [Seventh Message Understanding Conference ({MUC}-7): Proceedings of a Conference Held in Fairfax, Virginia, {A}pril 29 - May 1, 1998](https://www.aclweb.org/anthology/M98-1000), 1998
1. [Detecting Independent Pronoun Bias with Partially-Synthetic Data Generation](https://www.aclweb.org/anthology/2020.emnlp-main.157), Munro, Robert  and Morrison, Alex (Carmen), 2020
1. [Correcting Length Bias in Neural Machine Translation](https://www.aclweb.org/anthology/W18-6322), Murray, Kenton  and Chiang, David, 2018
1. [Lexical and Structural Biases for Function Parsing](https://www.aclweb.org/anthology/W05-1509), Musillo, Gabriele  and Merlo, Paola, 2005
1. [Fact-Checking, Fake News, Propaganda, and Media Bias: Truth Seeking in the Post-Truth Era](https://www.aclweb.org/anthology/2020.emnlp-tutorials.2), Nakov, Preslav  and Da San Martino, Giovanni, 2020
1. [Analyse automatique des noms d{\'e}verbaux compos{\'e}s : pourquoi et comment faire interagir analogie et syst{\`e}me de r{\`e}gles](https://www.aclweb.org/anthology/2009.jeptalnrecital-court.2), Namer, Fiammetta, 2009
1. [{C}row{S}-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.154), Nangia, Nikita  and Vania, Clara  and Bhalerao, Rasika  and Bowman, Samuel R., 2020
1. [{F}acebook {FAIR}{'}s {WMT}19 News Translation Task Submission](https://www.aclweb.org/anthology/W19-5333), Ng, Nathan  and Yee, Kyra  and Baevski, Alexei  and Ott, Myle  and Auli, Michael  and Edunov, Sergey, 2019
1. [Noise Isn{'}t Always Negative: Countering Exposure Bias in Sequence-to-Sequence Inflection Models](https://www.aclweb.org/anthology/2020.coling-main.255), Nicolai, Garrett  and Silfverberg, Miikka, 2020
1. [Fair Is Better than Sensational: Man Is to Doctor as Woman Is to Doctor](https://www.aclweb.org/anthology/2020.cl-2.7), Nissim, Malvina  and van Noord, Rik  and van der Goot, Rob, 2020
1. [Measuring Alignment to Authoritarian State Media as Framing Bias](https://www.aclweb.org/anthology/2020.nlp4if-1.2), Niven, Timothy  and Kao, Hung-Yu, 2020
1. [Bias in {AI}-systems: A multi-step approach](https://www.aclweb.org/anthology/2020.nl4xai-1.2), Ntoutsi, Eirini, 2020
1. [Modeling Personal Biases in Language Use by Inducing Personalized Word Embeddings](https://www.aclweb.org/anthology/N19-1215), Oba, Daisuke  and Yoshinaga, Naoki  and Sato, Shoetsu  and Akasaki, Satoshi  and Toyoda, Masashi, 2019
1. [Remarks on epistemically biased questions](https://www.aclweb.org/anthology/Y17-1025), Oshima, David Yoshikazu, 2017
1. [fairseq: A Fast, Extensible Toolkit for Sequence Modeling](https://www.aclweb.org/anthology/N19-4009), Ott, Myle  and Edunov, Sergey  and Baevski, Alexei  and Fan, Angela  and Gross, Sam  and Ng, Nathan  and Grangier, David  and Auli, Michael, 2019
1. [Comparative Evaluation of Label-Agnostic Selection Bias in Multilingual Hate Speech Datasets](https://www.aclweb.org/anthology/2020.emnlp-main.199), Ousidhoum, Nedjma  and Song, Yangqiu  and Yeung, Dit-Yan, 2020
1. [Reducing Gender Bias in Abusive Language Detection](https://www.aclweb.org/anthology/D18-1302), Park, Ji Ho  and Shin, Jamin  and Fung, Pascale, 2018
1. [Towards the Necessity for Debiasing Natural Language Inference Datasets](https://www.aclweb.org/anthology/2020.lrec-1.850), Paul Panenghat, Mithun  and Suntwal, Sandeep  and Rafique, Faiz  and Sharp, Rebecca  and Surdeanu, Mihai, 2020
1. [Cueing the Virtual Storyteller: Analysis of cue phrase usage in fairy tales](https://www.aclweb.org/anthology/W07-2326), Penning, Manon  and Theune, Mari{\"e}t, 2007
1. [Topic Sensitive Attention on Generic Corpora Corrects Sense Bias in Pretrained Embeddings](https://www.aclweb.org/anthology/P19-1168), Piratla, Vihari  and Sarawagi, Sunita  and Chakrabarti, Soumen, 2019
1. [Addressing the {MFS} Bias in {WSD} systems](https://www.aclweb.org/anthology/L16-1268), Postma, Marten  and Izquierdo, Ruben  and Agirre, Eneko  and Rigau, German  and Vossen, Piek, 2016
1. [Tracking Bias in News Sources Using Social Media: the Russia-{U}kraine Maidan Crisis of 2013{--}2014](https://www.aclweb.org/anthology/W17-4203), Potash, Peter  and Romanov, Alexey  and Gronas, Mikhail  and Rumshisky, Anna  and Gronas, Mikhail, 2017
1. [Perturbation Sensitivity Analysis to Detect Unintended Model Biases](https://www.aclweb.org/anthology/D19-1578), Prabhakaran, Vinodkumar  and Hutchinson, Ben  and Mitchell, Margaret, 2019
1. [Sampling Bias in Deep Active Classification: An Empirical Study](https://www.aclweb.org/anthology/D19-1417), Prabhu, Ameya  and Dognin, Charles  and Singh, Maneesh, 2019
1. [Debiasing Embeddings for Reduced Gender Bias in Text Classification](https://www.aclweb.org/anthology/W19-3810), Prost, Flavien  and Thain, Nithum  and Bolukbasi, Tolga, 2019
1. [A Comparative Study of {E}nglish-{C}hinese Translations of Court Texts by Machine and Human Translators and the {W}ord2{V}ec Based Similarity Measure{'}s Ability To Gauge Human Evaluation Biases](https://www.aclweb.org/anthology/W19-6714), Qian, Ming  and Liu, Jessie  and Li, Chaofeng  and Pals, Liming, 2019
1. [Reducing Gender Bias in Word-Level Language Models with a Gender-Equalizing Loss Function](https://www.aclweb.org/anthology/P19-2031), Qian, Yusu  and Muaz, Urwa  and Zhang, Ben  and Hyun, Jae Won, 2019
1. [{``}A Little Birdie Told Me ... {''} - Inductive Biases for Rumour Stance Detection on Social Media](https://www.aclweb.org/anthology/2020.wnut-1.31), Radhakrishnan, Karthik  and Kanakagiri, Tushar  and Chakravarthy, Sharanya  and Balachandran, Vidhisha, 2020
1. [Crowd Prefers the Middle Path: A New {IAA} Metric for Crowdsourcing Reveals Turker Biases in Query Segmentation](https://www.aclweb.org/anthology/P13-1168), Ramanath, Rohan  and Choudhury, Monojit  and Bali, Kalika  and Saha Roy, Rishiraj, 2013
1. [Studying the Inductive Biases of {RNN}s with Synthetic Variations of Natural Languages](https://www.aclweb.org/anthology/N19-1356), Ravfogel, Shauli  and Goldberg, Yoav  and Linzen, Tal, 2019
1. [Investigating Sampling Bias in Abusive Language Detection](https://www.aclweb.org/anthology/2020.alw-1.9), Razo, Dante  and K{\"u}bler, Sandra, 2020
1. [Linguistic Models for Analyzing and Detecting Biased Language](https://www.aclweb.org/anthology/P13-1162), Recasens, Marta  and Danescu-Niculescu-Mizil, Cristian  and Jurafsky, Dan, 2013
1. [Toward Natural Language Mitigation Strategies for Cognitive Biases in Recommender Systems](https://www.aclweb.org/anthology/2020.nl4xai-1.11), Rieger, Alisa  and Theune, Mari{\"e}t  and Tintarev, Nava, 2020
1. [Quantifying 60 Years of Gender Bias in Biomedical Research with Word Embeddings](https://www.aclweb.org/anthology/2020.bionlp-1.1), Rios, Anthony  and Joshi, Reenam  and Shin, Hejin, 2020
1. [What{'}s in a Name? {R}educing Bias in Bios without Access to Protected Attributes](https://www.aclweb.org/anthology/N19-1424), Romanov, Alexey  and De-Arteaga, Maria  and Wallach, Hanna  and Chayes, Jennifer  and Borgs, Christian  and Chouldechova, Alexandra  and Geyik, Sahin  and Kenthapadi, Krishnaram  and Rumshisky, Anna  and Kalai, Adam, 2019
1. [Social Bias in Elicited Natural Language Inferences](https://www.aclweb.org/anthology/W17-1609), Rudinger, Rachel  and May, Chandler  and Van Durme, Benjamin, 2017
1. [Gender Bias in Coreference Resolution](https://www.aclweb.org/anthology/N18-2002), Rudinger, Rachel  and Naradowsky, Jason  and Leonard, Brian  and Van Durme, Benjamin, 2018
1. [Gender Bias in Pretrained {S}wedish Embeddings](https://www.aclweb.org/anthology/W19-6104), Sahlgren, Magnus  and Olsson, Fredrik, 2019
1. [{GL{\`A}FF}, a Large Versatile {F}rench Lexicon ({GL{\`A}FF}, un Gros Lexique {{\`A}} tout Faire du Fran{\c{c}}ais) [in {F}rench]](https://www.aclweb.org/anthology/F13-1021), Sajous, Franck  and Hathout, Nabil  and Calderone, Basilio, 2013
1. [The Risk of Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/P19-1163), Sap, Maarten  and Card, Dallas  and Gabriel, Saadia  and Choi, Yejin  and Smith, Noah A., 2019
1. [Social Bias Frames: Reasoning about Social and Power Implications of Language](https://www.aclweb.org/anthology/2020.acl-main.486), Sap, Maarten  and Gabriel, Saadia  and Qin, Lianhui  and Jurafsky, Dan  and Smith, Noah A.  and Choi, Yejin, 2020
1. [Question Answering as Question-Biased Term Extraction: A New Approach toward Multilingual {QA}](https://www.aclweb.org/anthology/P05-1027), Sasaki, Yutaka, 2005
1. [Addressing Exposure Bias With Document Minimum Risk Training: {C}ambridge at the {WMT}20 Biomedical Translation Task](https://www.aclweb.org/anthology/2020.wmt-1.94), Saunders, Danielle  and Byrne, Bill, 2020
1. [Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem](https://www.aclweb.org/anthology/2020.acl-main.690), Saunders, Danielle  and Byrne, Bill, 2020
1. [On Bias-free Crawling and Representative Web Corpora](https://www.aclweb.org/anthology/W16-2612), Sch{\"a}fer, Roland, 2016
1. [Is {W}ikipedia succeeding in reducing gender bias? Assessing changes in gender bias in {W}ikipedia using word embeddings](https://www.aclweb.org/anthology/2020.nlpcss-1.11), Schmahl, Katja Geertruida  and Viering, Tom Julian  and Makrodimitris, Stavros  and Naseri Jahfari, Arman  and Tax, David  and Loog, Marco, 2020
1. [Generalization in Generation: A closer look at Exposure Bias](https://www.aclweb.org/anthology/D19-5616), Schmidt, Florian, 2019
1. [{``}This is a Problem, Don{'}t You Agree?{''} Framing and Bias in Human Evaluation for Natural Language Generation](https://www.aclweb.org/anthology/2020.evalnlgeval-1.2), Schoch, Stephanie  and Yang, Diyi  and Ji, Yangfeng, 2020
1. [Towards Debiasing Fact Verification Models](https://www.aclweb.org/anthology/D19-1341), Schuster, Tal  and Shah, Darsh  and Yeo, Yun Jie Serene  and Roberto Filizzola Ortiz, Daniel  and Santus, Enrico  and Barzilay, Regina, 2019
1. [The Role of Protected Class Word Lists in Bias Identification of Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3808), Sedoc, Jo{\~a}o  and Ungar, Lyle, 2019
1. [Predictive Biases in Natural Language Processing Models: A Conceptual Framework and Overview](https://www.aclweb.org/anthology/2020.acl-main.468), Shah, Deven Santosh  and Schwartz, H. Andrew  and Hovy, Dirk, 2020
1. [Detecting and understanding moral biases in news](https://www.aclweb.org/anthology/2020.nuse-1.15), Shahid, Usman  and Di Eugenio, Barbara  and Rojecki, Andrew  and Zheleva, Elena, 2020
1. [Tackling the Story Ending Biases in The Story Cloze Test](https://www.aclweb.org/anthology/P18-2119), Sharma, Rishi  and Allen, James  and Bakhshandeh, Omid  and Mostafazadeh, Nasrin, 2018
1. [A Two-Stage Approach for Generating Unbiased Estimates of Text Complexity](https://www.aclweb.org/anthology/W13-1506), Sheehan, Kathleen M.  and Flor, Michael  and Napolitano, Diane, 2013
1. [The Woman Worked as a Babysitter: On Biases in Language Generation](https://www.aclweb.org/anthology/D19-1339), Sheng, Emily  and Chang, Kai-Wei  and Natarajan, Premkumar  and Peng, Nanyun, 2019
1. [Investigating Societal Biases in a Poetry Composition System](https://www.aclweb.org/anthology/2020.gebnlp-1.9), Sheng, Emily  and Uthus, David, 2020
1. [Neutralizing Gender Bias in Word Embeddings with Latent Disentanglement and Counterfactual Generation](https://www.aclweb.org/anthology/2020.findings-emnlp.280), Shin, Seungjae  and Song, Kyungwoo  and Jang, JoonHo  and Kim, Hyemi  and Joo, Weonyoung  and Moon, Il-Chul, 2020
1. [Do Neural Language Models Overcome Reporting Bias?](https://www.aclweb.org/anthology/2020.coling-main.605), Shwartz, Vered  and Choi, Yejin, 2020
1. [{BERT} is Not an Interlingua and the Bias of Tokenization](https://www.aclweb.org/anthology/D19-6106), Singh, Jasdeep  and McCann, Bryan  and Socher, Richard  and Xiong, Caiming, 2019
1. [Annealing Structural Bias in Multilingual Weighted Grammar Induction](https://www.aclweb.org/anthology/P06-1072), Smith, Noah A.  and Eisner, Jason, 2006
1. [Selection Bias, Label Bias, and Bias in Ground Truth](https://www.aclweb.org/anthology/C14-3005), S{\o}gaard, Anders  and Plank, Barbara  and Hovy, Dirk, 2014
1. [Length bias in Encoder Decoder Models and a Case for Global Conditioning](https://www.aclweb.org/anthology/D16-1158), Sountsov, Pavel  and Sarawagi, Sunita, 2016
1. [Argument from Old Man{'}s View: Assessing Social Bias in Argumentation](https://www.aclweb.org/anthology/2020.argmining-1.9), Splieth{\"o}ver, Maximilian  and Wachsmuth, Henning, 2020
1. [Mitigating Gender Bias in Machine Translation with Target Gender Annotations](https://www.aclweb.org/anthology/2020.wmt-1.73), Stafanovi{\v{c}}s, Art{\=u}rs  and Pinnis, M{\=a}rcis  and Bergmanis, Toms, 2020
1. [Evaluating Gender Bias in Machine Translation](https://www.aclweb.org/anthology/P19-1164), Stanovsky, Gabriel  and Smith, Noah A.  and Zettlemoyer, Luke, 2019
1. [Symbolisme phon{\'e}tique du genre dans les pr{\'e}noms fran{\c{c}}ais (Sex-biased sound symbolism in {F}rench first names)](https://www.aclweb.org/anthology/2020.jeptalnrecital-jep.66), Suire, Alexandre  and Bossoms Mesa, Alba  and Raymond, Michel  and Barkat-Defradas, Melissa, 2020
1. [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159), Sun, Tony  and Gaut, Andrew  and Tang, Shirlyn  and Huang, Yuxin  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2019
1. [A Transparent Framework for Evaluating Unintended Demographic Bias in Word Embeddings](https://www.aclweb.org/anthology/P19-1162), Sweeney, Chris  and Najafian, Maryam, 2019
1. [Can Existing Methods Debias Languages Other than {E}nglish? First Attempt to Analyze and Mitigate {J}apanese Word Embeddings](https://www.aclweb.org/anthology/2020.gebnlp-1.5), Takeshita, Masashi  and Katsumata, Yuki  and Rzepka, Rafal  and Araki, Kenji, 2020
1. [Gender and Dialect Bias in {Y}ou{T}ube{'}s Automatic Captions](https://www.aclweb.org/anthology/W17-1606), Tatman, Rachael, 2017
1. [{``}Oh, {I}{'}ve Heard That Before{''}: Modelling Own-Dialect Bias After Perceptual Learning by Weighting Training Data](https://www.aclweb.org/anthology/W17-0704), Tatman, Rachael, 2017
1. [Not All Reviews Are Equal: Towards Addressing Reviewer Biases for Opinion Summarization](https://www.aclweb.org/anthology/P19-2005), Tay, Wenyi, 2019
1. [Analyzing Gender Bias in Student Evaluations](https://www.aclweb.org/anthology/C16-1083), Terkik, Andamlak  and Prud{'}hommeaux, Emily  and Ovesdotter Alm, Cecilia  and Homan, Christopher  and Franklin, Scott, 2016
1. [Authorless Topic Models: Biasing Models Away from Known Structure](https://www.aclweb.org/anthology/C18-1329), Thompson, Laure  and Mimno, David, 2018
1. [Named Entity Recognition with Stack Residual {LSTM} and Trainable Bias Decoding](https://www.aclweb.org/anthology/I17-1057), Tran, Quan  and MacKinlay, Andrew  and Jimeno Yepes, Antonio, 2017
1. [Performance Impact Caused by Hidden Bias of Training Data for Recognizing Textual Entailment](https://www.aclweb.org/anthology/L18-1239), Tsuchiya, Masatoshi, 2018
1. [Combining the Sparsity and Unambiguity Biases for Grammar Induction](https://www.aclweb.org/anthology/W12-1915), Tu, Kewei, 2012
1. [Fair Evaluation in Concept Normalization: a Large-scale Comparative Analysis for {BERT}-based Models](https://www.aclweb.org/anthology/2020.coling-main.588), Tutubalina, Elena  and Kadurin, Artur  and Miftahutdinov, Zulfat, 2020
1. [Mind the Trade-off: Debiasing {NLU} Models without Degrading the In-distribution Performance](https://www.aclweb.org/anthology/2020.acl-main.770), Utama, Prasetya Ajie  and Moosavi, Nafise Sadat  and Gurevych, Iryna, 2020
1. [Towards Debiasing {NLU} Models from Unknown Biases](https://www.aclweb.org/anthology/2020.emnlp-main.613), Utama, Prasetya Ajie  and Moosavi, Nafise Sadat  and Gurevych, Iryna, 2020
1. [Context in Informational Bias Detection](https://www.aclweb.org/anthology/2020.coling-main.556), van den Berg, Esther  and Markert, Katja, 2020
1. [{SLR} Validation: Present State of Affairs and Prospects](http://www.lrec-conf.org/proceedings/lrec2000/pdf/39.pdf), van den Heuvel, Henk  and Boves, Lou  and Choukri, Khalid  and Goddijn, Simo  and Sanders, Eric, 2000
1. [Lower Bias, Higher Density Abusive Language Datasets: A Recipe](https://www.aclweb.org/anthology/2020.restup-1.4), van Rosendaal, Juliet  and Caselli, Tommaso  and Nissim, Malvina, 2020
1. [Exploring the Linear Subspace Hypothesis in Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.emnlp-main.232), Vargas, Francisco  and Cotterell, Ryan, 2020
1. [Emotional Perception of Fairy Tales: Achieving Agreement in Emotion Annotation of Text](https://www.aclweb.org/anthology/W10-0212), Volkova, Ekaterina P.  and Mohler, Betty  and Meurers, Detmar  and Gerdemann, Dale  and B{\"u}lthoff, Heinrich H., 2010
1. [Multimodal Review Generation with Privacy and Fairness Awareness](https://www.aclweb.org/anthology/2020.coling-main.37), Vu, Xuan-Son  and Nguyen, Thanh-Son  and Le, Duc-Trong  and Jiang, Lili, 2020
1. [In-Browser Summarisation: Generating Elaborative Summaries Biased Towards the Reading Context](https://www.aclweb.org/anthology/P08-2033), Wan, Stephen  and Paris, C{\'e}cile, 2008
1. [Group Linguistic Bias Aware Neural Response Generation](https://www.aclweb.org/anthology/W17-6001), Wang, Jianan  and Wang, Xin  and Li, Fang  and Xu, Zhen  and Wang, Zhuoran  and Wang, Baoxun, 2017
1. [Double-Hard Debias: Tailoring Word Embeddings for Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.acl-main.484), Wang, Tianlu  and Lin, Xi Victoria  and Rajani, Nazneen Fatema  and McCann, Bryan  and Ordonez, Vicente  and Xiong, Caiming, 2020
1. [Fairseq {S}2{T}: Fast Speech-to-Text Modeling with Fairseq](https://www.aclweb.org/anthology/2020.aacl-demo.6), Wang, Changhan  and Tang, Yun  and Ma, Xutai  and Wu, Anne  and Okhonko, Dmytro  and Pino, Juan, 2020
1. [On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation](https://www.aclweb.org/anthology/2020.acl-main.326), Wang, Chaojun  and Sennrich, Rico, 2020
1. [On Lexically Biased Discourse Organization in Text Generation](https://www.aclweb.org/anthology/C94-1060), Wanner, Leo, 1994
1. [Gendered Ambiguous Pronoun ({GAP}) Shared Task at the Gender Bias in {NLP} Workshop 2019](https://www.aclweb.org/anthology/W19-3801), Webster, Kellie  and Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will, 2019
1. [Using Word Embeddings to Examine Gender Bias in {D}utch Newspapers, 1950-1990](https://www.aclweb.org/anthology/W19-4712), Wevers, Melvin, 2019
1. [Impact of Politically Biased Data on Hate Speech Classification](https://www.aclweb.org/anthology/2020.alw-1.7), Wich, Maximilian  and Bauer, Jan  and Groh, Georg, 2020
1. [Investigating Annotator Bias with a Graph-Based Approach](https://www.aclweb.org/anthology/2020.alw-1.22), Wich, Maximilian  and Al Kuwatly, Hala  and Groh, Georg, 2020
1. [Finding Good Enough: A Task-Based Evaluation of Query Biased Summarization for Cross-Language Information Retrieval](https://www.aclweb.org/anthology/D14-1073), Williams, Jennifer  and Tam, Sharon  and Shen, Wade, 2014
1. [Proceedings of the First Workshop on Gender Bias in Natural Language Processing](https://www.aclweb.org/anthology/W19-3800), Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will  and Webster, Kellie, 2019
1. [An Evaluation on Query-biased Summarisation for the Question Answering Task](https://www.aclweb.org/anthology/U04-1005), Wu, Mingfang  and Wilkinson, Ross  and Paris, Cecile, 2004
1. [De-Biased Court{'}s View Generation with Causality](https://www.aclweb.org/anthology/2020.emnlp-main.56), Wu, Yiquan  and Kuang, Kun  and Zhang, Yating  and Liu, Xiaozhong  and Sun, Changlong  and Xiao, Jun  and Zhuang, Yueting  and Si, Luo  and Wu, Fei, 2020
1. [Improving {QA} Generalization by Concurrent Modeling of Multiple Biases](https://www.aclweb.org/anthology/2020.findings-emnlp.74), Wu, Mingzhu  and Moosavi, Nafise Sadat  and R{\"u}ckl{\'e}, Andreas  and Gurevych, Iryna, 2020
1. [Demoting Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/2020.socialnlp-1.2), Xia, Mengzhou  and Field, Anjalie  and Tsvetkov, Yulia, 2020
1. [Imposing Label-Relational Inductive Bias for Extremely Fine-Grained Entity Typing](https://www.aclweb.org/anthology/N19-1084), Xiong, Wenhan  and Wu, Jiawei  and Lei, Deren  and Yu, Mo  and Chang, Shiyu  and Guo, Xiaoxiao  and Wang, William Yang, 2019
1. [Unbiasing Review Ratings with Tendency Based Collaborative Filtering](https://www.aclweb.org/anthology/2020.aacl-srw.8), Yadav, Pranshi  and Yadav, Priya  and Nokhiz, Pegah  and Gupta, Vivek, 2020
1. [Shedding (a Thousand Points of) Light on Biased Language](https://www.aclweb.org/anthology/W10-0723), Yano, Tae  and Resnik, Philip  and Smith, Noah A., 2010
1. [Defining and Evaluating Fair Natural Language Generation](https://www.aclweb.org/anthology/2020.winlp-1.27), Yeo, Catherine  and Chen, Alyssa, 2020
1. [Selection Bias Explorations and Debias Methods for Natural Language Sentence Matching Datasets](https://www.aclweb.org/anthology/P19-1435), Zhang, Guanhua  and Bai, Bing  and Liang, Jian  and Bai, Kun  and Chang, Shiyu  and Yu, Mo  and Zhu, Conghui  and Zhao, Tiejun, 2019
1. [Minimize Exposure Bias of {S}eq2{S}eq Models in Joint Entity and Relation Extraction](https://www.aclweb.org/anthology/2020.findings-emnlp.23), Zhang, Ranran Haoran  and Liu, Qianying  and Fan, Aysa Xuemo  and Ji, Heng  and Zeng, Daojian  and Cheng, Fei  and Kawahara, Daisuke  and Kurohashi, Sadao, 2020
1. [Robustness and Reliability of Gender Bias Assessment in Word Embeddings: The Role of Base Pairs](https://www.aclweb.org/anthology/2020.aacl-main.76), Zhang, Haiyang  and Sneyd, Alison  and Stevenson, Mark, 2020
1. [{LOGAN}: Local Group Bias Detection by Clustering](https://www.aclweb.org/anthology/2020.emnlp-main.155), Zhao, Jieyu  and Chang, Kai-Wei, 2020
1. [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://www.aclweb.org/anthology/D17-1323), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2017
1. [Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://www.aclweb.org/anthology/N18-2003), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2018
1. [Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/N19-1064), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Cotterell, Ryan  and Ordonez, Vicente  and Chang, Kai-Wei, 2019
1. [Gender Bias in Multilingual Embeddings and Cross-Lingual Transfer](https://www.aclweb.org/anthology/2020.acl-main.260), Zhao, Jieyu  and Mukherjee, Subhabrata  and Hosseini, Saghar  and Chang, Kai-Wei  and Hassan Awadallah, Ahmed, 2020
1. [A Closer Look at Data Bias in Neural Extractive Summarization Models](https://www.aclweb.org/anthology/D19-5410), Zhong, Ming  and Wang, Danqing  and Liu, Pengfei  and Qiu, Xipeng  and Huang, Xuanjing, 2019
1. [Detecting and Reducing Bias in a High Stakes Domain](https://www.aclweb.org/anthology/D19-1483), Zhong, Ruiqi  and Chen, Yanda  and Patton, Desmond  and Selous, Charlotte  and McKeown, Kathy, 2019
1. [Towards Robustifying {NLI} Models Against Lexical Dataset Biases](https://www.aclweb.org/anthology/2020.acl-main.773), Zhou, Xiang  and Bansal, Mohit, 2020
1. [Examining Gender Bias in Languages with Grammatical Gender](https://www.aclweb.org/anthology/D19-1531), Zhou, Pei  and Shi, Weijia  and Zhao, Jieyu  and Huang, Kuan-Hao  and Chen, Muhao  and Cotterell, Ryan  and Chang, Kai-Wei, 2019
1. [Reducing Unintended Identity Bias in {R}ussian Hate Speech Detection](https://www.aclweb.org/anthology/2020.alw-1.8), Zueva, Nadezhda  and Kabirova, Madina  and Kalaidin, Pavel, 2020


- #### Bias Mitigation
1.  Learning Gender-Neutral Word Embeddings


### Conference List
- [ACM FAT conference](https://fatconference.org/)
- 
### Others
- [Ethics in NLP](https://aclweb.org/aclwiki/Ethics_in_NLP), ACL Wiki
- [Interpretability and Explainability in Machine Learning](https://interpretable-ml-class.github.io/)

