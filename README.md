# awesome-fairness-papers
Papers about fairness in NLP

## Background
Fairness, accountability, transparency, and ethics are becoming more and more important in machine learning communities. We hope to provide a list of great papers that can serve as a reference for researchers interested in such topics. This repo mainly focuses on papers from ACL anthology, but we also point to some other resources at the end.

<!-- <p align='center'>
<a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/"><figure><img src="fairness_plot.svg", align="center"></figure></a>
</p>
<p align='center'>credit to <a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/">Stijn Tonk</a></p> -->

**We are not able to cover all the papers in the list. But if you have any suggestions or want to add some relevant papers, please feel free to edit or submit a pull request. Your contribution means a lot to us!**


## Contents
- [Paper List](#paper-list)
    - [Surveys](#surveys)
    - [Social Impact of Biases](#social-impact-of-biases)
    - [Data, Models, & Metrics](#data-models--metrics)
    - [Word/Sentence Representations](#word/sentence-representations)
    - [Natural Language Understanding](#natural-language-understanding)
    - [Natural Language Generation](#natural-language-generation)
        - [Machine Translation](#machine-translation)
        - [Dialogue Generation](#dialogue-generation)
        - [Other Generation](#other-generation)
    - [Other](#others)
- [Tutorial List](#tutorial-list)
    - [Jupyter/Colab List](#jupyter/colab-list)
- [Conference/Workshop List](#conference/workshop-list)


### Paper List

#### Surveys
1. [Language (Technology) is Power: A Critical Survey of "Bias" in NLP](https://www.aclweb.org/anthology/2020.acl-main.485), Blodgett, Su Lin  and Barocas, Solon  and Daumé III, Hal  and Wallach, Hanna, 2020
1. [Predictive Biases in Natural Language Processing Models: A Conceptual Framework and Overview](https://www.aclweb.org/anthology/2020.acl-main.468), Shah, Deven Santosh  and Schwartz, H. Andrew  and Hovy, Dirk, 2020
1. [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159), Sun, Tony  and Gaut, Andrew  and Tang, Shirlyn  and Huang, Yuxin  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2019
1. [A survey on bias and fairness in machine learning](https://arxiv.org/abs/1908.09635), Mehrabi, Ninareh and Morstatter, Fred and Saxena, Nripsuta and Lerman, Kristina and Galstyan, Aram, 2019
1. [50 years of test (Un)fairness: Lessons for machine learning](https://dl.acm.org/doi/abs/10.1145/3287560.3287600), Hutchinson, Ben and Mitchell, Margaret, 2019
1. [Confronting Abusive Language Online: A Survey from the Ethical and Human Rights Perspective](https://arxiv.org/abs/2012.12305), Kiritchenko, Svetlana and Nejadgholi, Isar and Fraser, Kathleen C, 2020
2. [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922), Bender, Emily M., Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell. 2021.

#### Social Impact of Biases
1. [The Social Impact of Natural Language Processing](https://www.aclweb.org/anthology/P16-2096), Hovy, Dirk and Spruit, Shannon L., 2016
1. [Give Me Convenience and Give Her Death: Who Should Decide What Uses of NLP are Appropriate, and on What Basis?](https://www.aclweb.org/anthology/2020.acl-main.261), Leins, Kobi and Lau, Jey Han and Baldwin, Timothy, 2020
1. [Situated Data, Situated Systems: A Methodology to Engage with Power Relations in Natural Language Processing Research](https://www.aclweb.org/anthology/2020.gebnlp-1.10), Havens, Lucy and Terras, Melissa and Bach, Benjamin and Alex, Beatrice, 2020
1. [Re-imagining Algorithmic Fairness in India and Beyond](https://arxiv.org/abs/2101.09995), Sambasivan, Nithya and Arnesen, Erin and Hutchinson, Ben and Doshi, Tulsee and Prabhakaran, Vinodkumar, 2021
1. [Improving fairness in machine learning systems: What do industry practitioners need?](https://dl.acm.org/doi/10.1145/3290605.3300830), Holstein, Kenneth and Wortman Vaughan, Jennifer and Daumé III, Hal and Dudik, Miro and Wallach, Hanna, 2019
1. The problem with bias: Allocative versus representational harms in machine learning, Barocas, Solon and Crawford, Kate and Shapiro, Aaron and Wallach, Hanna, 2017
2. [The many dimensions of algorithmic fairness in educational applications](https://www.aclweb.org/anthology/W19-4401), Loukina, Anastassia  and Madnani, Nitin  and Zechner, Klaus, 2019


#### Data, Models, & Metrics
1. [Data Statements for Natural Language Processing: Toward Mitigating System Bias and Enabling Better Science](https://www.aclweb.org/anthology/Q18-1041), Bender, Emily M. and Friedman, Batya, 2018
1. [Data and its (dis)contents: A survey of dataset development and use in machine learning research](https://arxiv.org/abs/2012.05345), Paullada, Amandalynne and Raji, Inioluwa Deborah and Bender, Emily M and Denton, Emily and Hanna, Alex, 2020
1. [Datasheets for datasets](https://arxiv.org/abs/1803.09010), Gebru, Timnit and Morgenstern, Jamie and Vecchione, Briana and Vaughan, Jennifer Wortman and Wallach, Hanna and Daumé III, Hal and Crawford, Kate, 2018
1. [Discovering and categorising language biases in reddit](https://arxiv.org/abs/2008.02754), Ferrer, Xavier and van Nuenen, Tom and Such, Jose M. and Criado, Natalia, 2021
1. [Model cards for model reporting](https://dl.acm.org/doi/10.1145/3287560.3287596), Mitchell, Margaret and Wu, Simone and Zaldivar, Andrew and Barnes, Parker and Vasserman, Lucy and Hutchinson, Ben and Spitzer, Elena and Raji, Inioluwa Deborah and Gebru, Timnit, 2019
1. [On the dangers of stochastic parrots: Can language models be too big](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf), Bender, Emily M and Gebru, Timnit and McMillan-Major, Angelina and Shmitchell, Shmargaret, 2021
1. [Counterfactual fairness](https://papers.nips.cc/paper/2017/hash/a486cd07e4ac3d270571622f4f316ec5-Abstract.html), Kusner, Matt J and Loftus, Joshua and Russell, Chris and Silva, Ricardo, 2017
1. [Fairness through awareness](https://dl.acm.org/doi/10.1145/2090236.2090255), Dwork, Cynthia and Hardt, Moritz and Pitassi, Toniann and Reingold, Omer and Zemel, Richard, 2012
1. [Equality of opportunity in supervised learning](https://dl.acm.org/doi/10.5555/3157382.3157469), Hardt, Moritz and Price, Eric and Srebro, Nati, 2016
1. [Are We Modeling the Task or the Annotator? An Investigation of Annotator Bias in Natural Language Understanding Datasets](https://www.aclweb.org/anthology/D19-1107), Geva, Mor  and Goldberg, Yoav  and Berant, Jonathan, 2019
1. [Proposed Taxonomy for Gender Bias in Text; A Filtering Methodology for the Gender Generalization Subtype](https://www.aclweb.org/anthology/W19-3802), Hitti, Yasmeen  and Jang, Eunbee  and Moreno, Ines  and Pelletier, Carolyne, 2019
1. [These are not the Stereotypes You are Looking For: Bias and Fairness in Authorial Gender Attribution](https://www.aclweb.org/anthology/W17-1602), Koolen, Corina  and van Cranenburgh, Andreas, 2017
2. [Discovering Biased News Articles Leveraging Multiple Human Annotations](https://www.aclweb.org/anthology/2020.lrec-1.159), Lazaridou, Konstantina  and L{\"o}ser, Alexander  and Mestre, Maria  and Naumann, Felix, 2020
1. [Annotating and Analyzing Biased Sentences in News Articles using Crowdsourcing](https://www.aclweb.org/anthology/2020.lrec-1.184), Lim, Sora  and Jatowt, Adam  and F{\"a}rber, Michael  and Yoshikawa, Masatoshi, 2020
1.  [Differentially Private Representation for {NLP}: Formal Guarantee and An Empirical Study on Privacy and Fairness](https://www.aclweb.org/anthology/2020.findings-emnlp.213), Lyu, Lingjuan  and He, Xuanli  and Li, Yitong, 2020
1. [Building Better Open-Source Tools to Support Fairness in Automated Scoring](https://www.aclweb.org/anthology/W17-1605), Madnani, Nitin  and Loukina, Anastassia  and von Davier, Alina  and Burstein, Jill  and Cahill, Aoife, 2017
1. [StereoSet: Measuring stereotypical bias in pretrained language models](https://arxiv.org/abs/2004.09456), Nadeem, Moin and Bethke, Anna and Reddy, Siva, 2020
2. [Investigating Sports Commentator Bias within a Large Corpus of {A}merican Football Broadcasts](https://www.aclweb.org/anthology/D19-1666), Merullo, Jack  and Yeh, Luke  and Handler, Abram  and Grissom II, Alvin  and O{'}Connor, Brendan  and Iyyer, Mohit, 2019
3. [Artie Bias Corpus: An Open Dataset for Detecting Demographic Bias in Speech Applications](https://www.aclweb.org/anthology/2020.lrec-1.796), Meyer, Josh  and Rauchenstein, Lindy  and Eisenberg, Joshua D.  and Howell, Nicholas, 2020
4. [RtGender: A Corpus for Studying Differential Responses to Gender](https://nlp.stanford.edu/robvoigt/rtgender/rtgender.pdf), Voigt, Rob and Jurgens, David and Prabhakaran, Vinodkumar and Jurafsky, Dan and Tsvetkov, Yulia, 2018
5. [Multi-Dimensional Gender Bias Classification](https://www.aclweb.org/anthology/2020.emnlp-main.23), Dinan, Emily  and Fan, Angela  and Wu, Ledell  and Weston, Jason  and Kiela, Douwe  and Williams, Adina, 2020

#### Word/Sentence Representations
1. [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/abs/1607.06520), Bolukbasi, Tolga and Chang, Kai-Wei and Zou, James and Saligrama, Venkatesh and Kalai, Adam, 2016 [[github]](https://github.com/tolga-b/debiaswe)
1. [Semantics derived automatically from language corpora contain human-like biases](https://science.sciencemag.org/content/356/6334/183), Caliskan, Aylin and Bryson, Joanna J. and Narayanan, Arvind, 2017
1. [Attenuating Biases in Word Vectors](http://proceedings.mlr.press/v89/dev19a.html), Dev, Sunipa and Phillips, Jeff M, 2019
1. [Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/N19-1064), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Cotterell, Ryan  and Ordonez, Vicente  and Chang, Kai-Wei, 2019
1. [Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings](https://www.aclweb.org/anthology/N19-1062), Manzini, Thomas  and Yao Chong, Lim  and Black, Alan W  and Tsvetkov, Yulia, 2019
2. [Gender Bias in Multilingual Embeddings and Cross-Lingual Transfer](https://www.aclweb.org/anthology/2020.acl-main.260), Zhao, Jieyu  and Mukherjee, Subhabrata  and Hosseini, Saghar  and Chang, Kai-Wei  and Hassan Awadallah, Ahmed, 2020
1. [Nurse is Closer to Woman than Surgeon? Mitigating Gender-Biased Proximities in Word Embeddings](https://www.aclweb.org/anthology/2020.tacl-1.32), Kumar, Vaibhav  and Bhotia, Tenzin Singhay  and Kumar, Vaibhav  and Chakraborty, Tanmoy, 2020
1. [Measuring Bias in Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3823), Kurita, Keita  and Vyas, Nidhi  and Pareek, Ayush  and Black, Alan W and Tsvetkov, Yulia, 2019
1. [Unmasking Contextual Stereotypes: Measuring and Mitigating BERT's Gender Bias](https://www.aclweb.org/anthology/2020.gebnlp-1.1), Bartl, Marion  and Nissim, Malvina  and Gatt, Albert, 2020
1. [Evaluating the Underlying Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/W19-3805), Basta, Christine  and Costa-jussà, Marta R.  and Casas, Noe, 2019
1. [Evaluating Bias In Dutch Word Embeddings](https://www.aclweb.org/anthology/2020.gebnlp-1.6), Chávez Mulsa, Rodrigo Alejandro  and Spanakis, Gerasimos, 2020
1. [Learning Gender-Neutral Word Embeddings](https://arxiv.org/abs/1809.01496), Zhao, Jieyu and Zhou, Yichao and Li, Zeyu and Wang, Wei and Chang, Kai-Wei
1. [Lipstick on a Pig: {D}ebiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://www.aclweb.org/anthology/N19-1061), Gonen, Hila  and Goldberg, Yoav, 2019
1. [It{'}s All in the Name: Mitigating Gender Bias with Name-Based Counterfactual Data Substitution](https://www.aclweb.org/anthology/D19-1530), Hall Maudslay, Rowan  and Gonen, Hila  and Cotterell, Ryan  and Teufel, Simone, 2019
1. [Gender-preserving Debiasing for Pre-trained Word Embeddings](https://www.aclweb.org/anthology/P19-1160), Kaneko, Masahiro  and Bollegala, Danushka, 2019
1. [Conceptor Debiasing of Word Representations Evaluated on {WEAT}](https://www.aclweb.org/anthology/W19-3806), Karve, Saket  and Ungar, Lyle  and Sedoc, Jo{\~a}o, 2019
2. [Are We Consistently Biased? Multidimensional Analysis of Biases in Distributional Word Vectors](https://www.aclweb.org/anthology/S19-1010), Lauscher, Anne  and Glava{\v{s}}, Goran, 2019
1. [{A}ra{WEAT}: Multidimensional Analysis of Biases in {A}rabic Word Embeddings](https://www.aclweb.org/anthology/2020.wanlp-1.17), Lauscher, Anne  and Takieddin, Rafik  and Ponzetto, Simone Paolo  and Glava{\v{s}}, Goran, 2020
1. [Unequal Representations: Analyzing Intersectional Biases in Word Embeddings Using Representational Similarity Analysis](https://www.aclweb.org/anthology/2020.coling-main.151), Lepori, Michael, 2020
1. [Monolingual and Multilingual Reduction of Gender Bias in Contextualized Representations](https://www.aclweb.org/anthology/2020.coling-main.446), Liang, Sheng  and Dufter, Philipp  and Sch{\"u}tze, Hinrich, 2020
1. [Towards Debiasing Sentence Representations](https://www.aclweb.org/anthology/2020.acl-main.488), Liang, Paul Pu  and Li, Irene Mengze  and Zheng, Emily  and Lim, Yao Chong  and Salakhutdinov, Ruslan  and Morency, Louis-Philippe, 2020
2. [On Measuring Social Biases in Sentence Encoders](https://www.aclweb.org/anthology/N19-1063), May, Chandler  and Wang, Alex  and Bordia, Shikha  and Bowman, Samuel R.  and Rudinger, Rachel, 2019
3. [Fair Is Better than Sensational: Man Is to Doctor as Woman Is to Doctor](https://www.aclweb.org/anthology/2020.cl-2.7), Nissim, Malvina  and van Noord, Rik  and van der Goot, Rob, 2020
4.  [Gender Bias in Pretrained Swedish Embeddings](https://www.aclweb.org/anthology/W19-6104), Sahlgren, Magnus  and Olsson, Fredrik, 2019
5. [Is Wikipedia succeeding in reducing gender bias? Assessing changes in gender bias in Wikipedia using word embeddings](https://www.aclweb.org/anthology/2020.nlpcss-1.11), Schmahl, Katja Geertruida  and Viering, Tom Julian  and Makrodimitris, Stavros  and Naseri Jahfari, Arman  and Tax, David  and Loog, Marco, 2020
4. [The Role of Protected Class Word Lists in Bias Identification of Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3808), Sedoc, Jo{\~a}o  and Ungar, Lyle, 2019
5. [Neutralizing Gender Bias in Word Embeddings with Latent Disentanglement and Counterfactual Generation](https://www.aclweb.org/anthology/2020.findings-emnlp.280), Shin, Seungjae  and Song, Kyungwoo  and Jang, JoonHo  and Kim, Hyemi  and Joo, Weonyoung  and Moon, Il-Chul, 2020
6. [A Transparent Framework for Evaluating Unintended Demographic Bias in Word Embeddings](https://www.aclweb.org/anthology/P19-1162), Sweeney, Chris  and Najafian, Maryam, 2019
7. [Can Existing Methods Debias Languages Other than English? First Attempt to Analyze and Mitigate Japanese Word Embeddings](https://www.aclweb.org/anthology/2020.gebnlp-1.5), Takeshita, Masashi  and Katsumata, Yuki  and Rzepka, Rafal  and Araki, Kenji, 2020
8. [Exploring the Linear Subspace Hypothesis in Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.emnlp-main.232), Vargas, Francisco  and Cotterell, Ryan, 2020
9. [Double-Hard Debias: Tailoring Word Embeddings for Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.acl-main.484), Wang, Tianlu  and Lin, Xi Victoria  and Rajani, Nazneen Fatema  and McCann, Bryan  and Ordonez, Vicente  and Xiong, Caiming, 2020
10. [Robustness and Reliability of Gender Bias Assessment in Word Embeddings: The Role of Base Pairs](https://www.aclweb.org/anthology/2020.aacl-main.76), Zhang, Haiyang  and Sneyd, Alison  and Stevenson, Mark, 2020
11. [Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change](https://cs.stanford.edu/people/jure/pubs/diachronic-acl16.pdf), Hamilton, William L. and Leskovec, Jure and Jurafsky, Dan, 2016 [[github]](https://nlp.stanford.edu/projects/histwords/)
12. [Measuring Gender Bias in Word Embeddings across Domains and Discovering New Gender Bias Word Categories](https://www.aclweb.org/anthology/W19-3804), Chaloner, Kaytlin  and Maldonado, Alfredo, 2019
13. [Relating Word Embedding Gender Biases to Gender Gaps: A Cross-Cultural Analysis](https://www.aclweb.org/anthology/W19-3803), Friedman, Scott  and Schmer-Galunder, Sonja  and Chen, Anthony  and Rye, Jeffrey, 2019



#### Natural Language Understanding
5. [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://www.aclweb.org/anthology/D17-1323), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2017
4. [LOGAN: Local Group Bias Detection by Clustering](https://www.aclweb.org/anthology/2020.emnlp-main.155), Zhao, Jieyu  and Chang, Kai-Wei, 2020
1. [Reducing Gender Bias in Abusive Language Detection](https://www.aclweb.org/anthology/D18-1302), Park, Ji Ho  and Shin, Jamin  and Fung, Pascale, 2018
1. [Gender Bias in Coreference Resolution](https://www.aclweb.org/anthology/N18-2002), Rudinger, Rachel  and Naradowsky, Jason  and Leonard, Brian  and Van Durme, Benjamin, 2018
1. [Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://www.aclweb.org/anthology/N18-2003), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2018
1. [On Measuring and Mitigating Biased Inferences of Word Embeddings](https://arxiv.org/abs/1908.09369), Dev, Sunipa and Li, Tao  and Phillips, Jeff M  and Srikumar, Vivek, 2019
1. [Examining Gender Bias in Languages with Grammatical Gender](https://www.aclweb.org/anthology/D19-1531), Zhou, Pei  and Shi, Weijia  and Zhao, Jieyu  and Huang, Kuan-Hao  and Chen, Muhao  and Cotterell, Ryan  and Chang, Kai-Wei, 2019
1. [Racial Bias in Hate Speech and Abusive Language Detection Datasets](https://www.aclweb.org/anthology/W19-3504), Davidson, Thomas  and Bhattacharya, Debasmita  and Weber, Ingmar, 2019
1. [Social Biases in NLP Models as Barriers for Persons with Disabilities](https://www.aclweb.org/anthology/2020.acl-main.487), Hutchinson, Ben  and Prabhakaran, Vinodkumar  and Denton, Emily  and Webster, Kellie  and Zhong, Yu  and Denuyl, Stephen, 2020
1. [Perturbation Sensitivity Analysis to Detect Unintended Model Biases](https://www.aclweb.org/anthology/D19-1578), Prabhakaran, Vinodkumar  and Hutchinson, Ben  and Mitchell, Margaret, 2019
1. [UNQOVERing Stereotyping Biases via Underspecified Questions](https://www.aclweb.org/anthology/2020.findings-emnlp.311), Li, Tao  and Khashabi, Daniel  and Khot, Tushar  and Sabharwal, Ashish  and Srikumar, Vivek, 2020
1. [OSCaR: Orthogonal Subspace Correction and Rectification of Biases in Word Embeddings](https://arxiv.org/abs/2007.00049), Dev, Sunipa and Li, Tao  and Phillips, Jeff M  and Srikumar, Vivek, 2020
1. [CrowS-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.154), Nangia, Nikita  and Vania, Clara  and Bhalerao, Rasika  and Bowman, Samuel R., 2020
1. [Women's Syntactic Resilience and Men's Grammatical Luck: Gender-Bias in Part-of-Speech Tagging and Dependency Parsing](https://www.aclweb.org/anthology/P19-1339), Garimella, Aparna  and Banea, Carmen  and Hovy, Dirk  and Mihalcea, Rada, 2019
1. [Towards Understanding Gender Bias in Relation Extraction](https://www.aclweb.org/anthology/2020.acl-main.265), Gaut, Andrew  and Sun, Tony  and Tang, Shirlyn  and Huang, Yuxin  and Qian, Jing  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2020
1. [Type {B} Reflexivization as an Unambiguous Testbed for Multilingual Multi-Task Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.209), Gonz{\'a}lez, Ana Valeria  and Barrett, Maria  and Hvingelby, Rasmus  and Webster, Kellie  and S{\o}gaard, Anders, 2020
1. [Inflating Topic Relevance with Ideology: A Case Study of Political Ideology Bias in Social Topic Detection Models](https://www.aclweb.org/anthology/2020.coling-main.428), Guo, Meiqi  and Hwa, Rebecca  and Lin, Yu-Ru  and Chung, Wen-Ting, 2020
1. [Media Bias, the Social Sciences, and {NLP}: Automating Frame Analyses to Identify Bias by Word Choice and Labeling](https://www.aclweb.org/anthology/2020.acl-srw.12), Hamborg, Felix, 2020
1. [An Annotation Scheme for Automated Bias Detection in {W}ikipedia](https://www.aclweb.org/anthology/W11-0406), Herzig, Livnat  and Nunes, Alex  and Snir, Batia, 2011
1. [Multilingual {T}witter Corpus and Baselines for Evaluating Demographic Bias in Hate Speech Recognition](https://www.aclweb.org/anthology/2020.lrec-1.180), Huang, Xiaolei  and Xing, Linzi  and Dernoncourt, Franck  and Paul, Michael J., 2020
1. [Mitigating Gender Bias Amplification in Distribution by Posterior Regularization](https://www.aclweb.org/anthology/2020.acl-main.264), Jia, Shengyu  and Meng, Tao  and Zhao, Jieyu  and Chang, Kai-Wei, 2020
1. [Enhancing Bias Detection in Political News Using Pragmatic Presupposition](https://www.aclweb.org/anthology/2020.socialnlp-1.1), Kameswari, Lalitha  and Sravani, Dama  and Mamidi, Radhika, 2020
1. [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://www.aclweb.org/anthology/S18-2005), Kiritchenko, Svetlana  and Mohammad, Saif, 2018
2. [Debiasing Embeddings for Reduced Gender Bias in Text Classification](https://www.aclweb.org/anthology/W19-3810), Prost, Flavien  and Thain, Nithum  and Bolukbasi, Tolga, 2019
3. [Reducing Gender Bias in Word-Level Language Models with a Gender-Equalizing Loss Function](https://www.aclweb.org/anthology/P19-2031), Qian, Yusu  and Muaz, Urwa  and Zhang, Ben  and Hyun, Jae Won, 2019
4. [Linguistic Models for Analyzing and Detecting Biased Language](https://www.aclweb.org/anthology/P13-1162), Recasens, Marta  and Danescu-Niculescu-Mizil, Cristian  and Jurafsky, Dan, 2013
5. [What's in a Name? {R}educing Bias in Bios without Access to Protected Attributes](https://www.aclweb.org/anthology/N19-1424), Romanov, Alexey  and De-Arteaga, Maria  and Wallach, Hanna  and Chayes, Jennifer  and Borgs, Christian  and Chouldechova, Alexandra  and Geyik, Sahin  and Kenthapadi, Krishnaram  and Rumshisky, Anna  and Kalai, Adam, 2019
6. [Social Bias in Elicited Natural Language Inferences](https://www.aclweb.org/anthology/W17-1609), Rudinger, Rachel  and May, Chandler  and Van Durme, Benjamin, 2017
7. [The Risk of Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/P19-1163), Sap, Maarten  and Card, Dallas  and Gabriel, Saadia  and Choi, Yejin  and Smith, Noah A., 2019
8. [Social Bias Frames: Reasoning about Social and Power Implications of Language](https://www.aclweb.org/anthology/2020.acl-main.486), Sap, Maarten  and Gabriel, Saadia  and Qin, Lianhui  and Jurafsky, Dan  and Smith, Noah A.  and Choi, Yejin, 2020
9. [Do Neural Language Models Overcome Reporting Bias?](https://www.aclweb.org/anthology/2020.coling-main.605), Shwartz, Vered  and Choi, Yejin, 2020
10. [Context in Informational Bias Detection](https://www.aclweb.org/anthology/2020.coling-main.556), van den Berg, Esther  and Markert, Katja, 2020
11. [Comparative Evaluation of Label-Agnostic Selection Bias in Multilingual Hate Speech Datasets](https://www.aclweb.org/anthology/2020.emnlp-main.199), Ousidhoum, Nedjma  and Song, Yangqiu  and Yeung, Dit-Yan, 2020 
12. [Detecting and Reducing Bias in a High Stakes Domain](https://www.aclweb.org/anthology/D19-1483), Zhong, Ruiqi  and Chen, Yanda  and Patton, Desmond  and Selous, Charlotte  and McKeown, Kathy, 2019
13. [Demoting Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/2020.socialnlp-1.2), Xia, Mengzhou  and Field, Anjalie  and Tsvetkov, Yulia, 2020
14.  [Balanced Datasets Are Not Enough: Estimating and Mitigating Gender Bias in Deep Image Representations](https://arxiv.org/abs/1811.08489), Wang, Tianlu and Zhao, Jieyu and Yatskar, Mark and Chang, Kai-Wei and Ordonez, Vicente, 2019
15. [Measuring the Effects of Bias in Training Data for Literary Classification](https://www.aclweb.org/anthology/2020.latechclfl-1.9), Bagga, Sunyam  and Piper, Andrew, 2020
16. [Unsupervised Discovery of Implicit Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.44), Field, Anjalie  and Tsvetkov, Yulia, 2020


#### Natural Language Generation

##### Machine Translation
1. [Towards Mitigating Gender Bias in a decoder-based Neural Machine Translation model by Adding Contextual Information](https://www.aclweb.org/anthology/2020.winlp-1.25), Basta, Christine  and Costa-jussà, Marta R.  and Fonollosa, José A. R., 2020
1. [On Measuring Gender Bias in Translation of Gender-neutral Pronouns](https://www.aclweb.org/anthology/W19-3824), Cho, Won Ik and Kim, Ji Won and Kim, Seok Min and Kim, Nam Soo, 2019
1. [Fine-tuning Neural Machine Translation on Gender-Balanced Datasets](https://www.aclweb.org/anthology/2020.gebnlp-1.3), Costa-jussà, Marta R. and de Jorge, Adrià, 2020
1. [Equalizing Gender Bias in Neural Machine Translation with Word Embeddings Techniques](https://www.aclweb.org/anthology/W19-3821), Escudé Font, Joel  and Costa-jussà, Marta R., 2019
1. [Automatically Identifying Gender Issues in Machine Translation using Perturbations](https://www.aclweb.org/anthology/2020.findings-emnlp.180), Gonen, Hila and  Webster, Kellie, 2020
1. [Gender Coreference and Bias Evaluation at WMT 2020](https://www.aclweb.org/anthology/2020.wmt-1.39), Kocmi, Tom  and Limisiewicz, Tomasz  and Stanovsky, Gabriel, 2020
1. [Filling Gender & Number Gaps in Neural Machine Translation with Black-box Context Injection](https://www.aclweb.org/anthology/W19-3807), Moryossef, Amit  and Aharoni, Roee and Goldberg, Yoav, 2019
1. [Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem](https://www.aclweb.org/anthology/2020.acl-main.690), Saunders, Danielle and Byrne, Bill, 2020
1. [Neural Machine Translation Doesn't Translate Gender Coreference Right Unless You Make It](https://www.aclweb.org/anthology/2020.gebnlp-1.4), Saunders, Danielle and Sallis, Rosie and Byrne, Bill, 2020
1. [Mitigating Gender Bias in Machine Translation with Target Gender Annotations](https://www.aclweb.org/anthology/2020.wmt-1.73), Stafanovičs, Artūrs  and Pinnis, Mārcis  and Bergmanis, Toms, 2020
1. [Evaluating Gender Bias in Machine Translation](https://www.aclweb.org/anthology/P19-1164), Stanovsky, Gabriel  and Smith, Noah A.  and Zettlemoyer, Luke, 2019
1. [Getting Gender Right in Neural Machine Translation](https://www.aclweb.org/anthology/D18-1334), Vanmassenhove, Eva and Hardmeier, Christian and Way, Andy, 2018
1. ["You Sound Just Like Your Father" Commercial Machine Translation Systems Include Stylistic Biases](https://www.aclweb.org/anthology/2020.acl-main.154), Hovy, Dirk  and Bianchi, Federico  and Fornaciari, Tommaso, 2020
1. [Assessing gender bias in machine translation: a case study with google translate](https://arxiv.org/abs/1809.02208), Prates, Marcelo O. R. and Avelar, Pedro H. C. and Lamb, Luis, 2019
1. [Gender Bias in Multilingual Neural Machine Translation: The Architecture Matters](https://arxiv.org/abs/2012.13176), Costa-jussà, Marta R. and Escolano, Carlos and Basta, Christine and Ferrando, Javier and Batlle, Roser and Kharitonova, Ksenia, 2020
1. [How to Measure Gender Bias in Machine Translation: Optimal Translators, Multiple Reference Points](https://arxiv.org/abs/2011.06445), Farkas, Anna and Németh, Renáta, 2020
1. [Gender aware spoken language translation applied to English-Arabic](https://arxiv.org/abs/1802.09287), Elaraby, Mostafa and Tawfik, Ahmed Y and Khaled, Mahmoud and Hassan, Hany and Osama, Aly, 2018
1. [Type {B} Reflexivization as an Unambiguous Testbed for Multilingual Multi-Task Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.209), Gonz{\'a}lez, Ana Valeria  and Barrett, Maria  and Hvingelby, Rasmus  and Webster, Kellie  and S{\o}gaard, Anders, 2020

##### Dialogue Generation
1. [Conversational Assistants and Gender Stereotypes: Public Perceptions and Desiderata for Voice Personas](https://www.aclweb.org/anthology/2020.gebnlp-1.7), Cercas Curry, Amanda and Robertson, Judy and Rieser, Verena 2020
1. [Does Gender Matter? Towards Fairness in Dialogue Systems](https://www.aclweb.org/anthology/2020.coling-main.390), Liu, Haochen  and Dacon, Jamell  and Fan, Wenqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [Mitigating Gender Bias for Neural Dialogue Generation with Adversarial Learning](https://www.aclweb.org/anthology/2020.emnlp-main.64), Liu, Haochen  and Wang, Wentao  and Wang, Yiqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [Queens are Powerful too: Mitigating Gender Bias in Dialogue Generation](https://www.aclweb.org/anthology/2020.emnlp-main.656), Dinan, Emily  and Fan, Angela and Williams, Adina and Urbanek, Jack and Kiela, Douwe and Weston, Jason, 2020
1. [Ethical challenges in data-driven dialogue systems](https://arxiv.org/abs/1711.09050), Henderson, Peter and Sinha, Koustuv and Angelard-Gontier, Nicolas and Ke, Nan Rosemary and Fried, Genevieve and Lowe, Ryan and Pineau, Joelle, 2018
1. ["Nice Try, Kiddo": Ad Hominems in Dialogue Systems](https://arxiv.org/abs/2010.12820), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2020

##### Other Generation
1. [Gender-Aware Reinflection using Linguistically Enhanced Neural Models](https://www.aclweb.org/anthology/2020.gebnlp-1.12), Alhafni, Bashar and Habash, Nizar and Bouamor, Houda, 2020
1. [Identifying and Reducing Gender Bias in Word-Level Language Models](https://www.aclweb.org/anthology/N19-3002), Bordia, Shikha  and Bowman, Samuel R., 2019
1. [Investigating African-American Vernacular English in Transformer-Based Text Generation](https://www.aclweb.org/anthology/2020.emnlp-main.473), Groenwold, Sophie and Ou, Lily and Parekh, Aesha and Honnavalli, Samhita and Levy, Sharon and Mirza, Diba and Wang, William Yang, 2020
1. [Automatic Gender Identification and Reinflection in Arabic](https://www.aclweb.org/anthology/W19-3822), Habash, Nizar and Bouamor, Houda and Chung, Christine, 2019
1. [Reducing Sentiment Bias in Language Models via Counterfactual Evaluation](https://www.aclweb.org/anthology/2020.findings-emnlp.7), Huang, Po-Sen  and Zhang, Huan  and Jiang, Ray  and Stanforth, Robert  and Welbl, Johannes  and Rae, Jack  and Maini, Vishal  and Yogatama, Dani  and Kohli, Pushmeet, 2020
1. [PowerTransformer: Unsupervised Controllable Revision for Biased Language Correction](https://www.aclweb.org/anthology/2020.emnlp-main.602), Ma, Xinyao and Sap, Maarten and Rashkin, Hannah and Choi, Yejin, 2020
1. [Reducing Non-Normative Text Generation from Language Models](https://www.aclweb.org/anthology/2020.inlg-1.43), Peng, Xiangyu and Li, Siyan and Frazier, Spencer  and Riedl, Mark, 2020
1. [The Woman Worked as a Babysitter: On Biases in Language Generation](https://www.aclweb.org/anthology/D19-1339), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2019
1. [Towards Controllable Biases in Language Generation](https://www.aclweb.org/anthology/2020.findings-emnlp.291), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2020
1. ["You are grounded!": Latent Name Artifacts in Pre-trained Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.556), Shwartz, Vered and Rudinger, Rachel and Tafjord, Oyvind, 2020
1. [Defining and Evaluating Fair Natural Language Generation](https://www.aclweb.org/anthology/2020.winlp-1.27), Yeo, Catherine  and Chen, Alyssa, 2020
1. [Counterfactual Data Augmentation for Mitigating Gender Stereotypes in Languages with Rich Morphology](https://www.aclweb.org/anthology/P19-1161), Zmigrod, Ran and Mielke, Sabrina J. and Wallach, Hanna and Cotterell, Ryan, 2019
1. [Investigating Gender Bias in Language Models Using Causal Mediation Analysis](https://papers.nips.cc/paper/2020/hash/92650b2e92217715fe312e6fa7b90d82-Abstract.html), Vig, Jesse and Gehrmann, Sebastian and Belinkov, Yonatan and Qian, Sharon and Nevo, Daniel and Singer, Yaron and Shieber, Stuart, 2020
1. [Release strategies and the social impacts of language models](https://arxiv.org/abs/1908.09203), Solaiman, Irene and Brundage, Miles and Clark, Jack and Askell, Amanda and Herbert-Voss, Ariel and Wu, Jeff and Radford, Alec and Krueger, Gretchen and Kim, Jong Wook and Kreps, Sarah and others, 2019
1. [Automatically neutralizing subjective bias in text](https://ojs.aaai.org//index.php/AAAI/article/view/5385), Pryzant, Reid and Martinez, Richard Diehl and Dass, Nathan and Kurohashi, Sadao and Jurafsky, Dan and Yang, Diyi, 2020
1. [Language models are few-shot learners](https://arxiv.org/abs/2005.14165), Brown, Tom B and Mann, Benjamin and Ryder, Nick and Subbiah, Melanie and Kaplan, Jared and Dhariwal, Prafulla and Neelakantan, Arvind and Shyam, Pranav and Sastry, Girish and Askell, Amanda and others, 2020
1. [BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation](https://arxiv.org/abs/2101.11718), Dhamala, Jwala and Sun, Tony and Kumar, Varun and Krishna, Satyapriya and Pruksachatkun, Yada and Chang, Kai-Wei and Gupta, Rahul, 2021
1. [Viable Threat on News Reading: Generating Biased News Using Natural Language Models](https://www.aclweb.org/anthology/2020.nlpcss-1.7), Gupta, Saurabh  and Nguyen, Hong Huy  and Yamagishi, Junichi  and Echizen, Isao, 2020
1. [Investigating Societal Biases in a Poetry Composition System](https://www.aclweb.org/anthology/2020.gebnlp-1.9), Sheng, Emily  and Uthus, David, 2020
2. [PowerTransformer: Unsupervised Controllable Revision for Biased Language Correction](https://www.aclweb.org/anthology/2020.emnlp-main.602), Ma, Xinyao  and Sap, Maarten  and Rashkin, Hannah  and Choi, Yejin, 2020
3. [De-Biased Court's View Generation with Causality](https://www.aclweb.org/anthology/2020.emnlp-main.56), Wu, Yiquan  and Kuang, Kun  and Zhang, Yating  and Liu, Xiaozhong  and Sun, Changlong  and Xiao, Jun  and Zhuang, Yueting  and Si, Luo  and Wu, Fei, 2020


#### Others
1. [Gender bias in neural natural language processing](https://link.springer.com/chapter/10.1007/978-3-030-62077-6_14), Lu, Kaiji and Mardziel, Piotr and Wu, Fangjing and Amancharla, Preetam and Datta, Anupam, 2020
2. [Equity Beyond Bias in Language Technologies for Education](https://www.aclweb.org/anthology/W19-4446), Mayfield, Elijah  and Madaio, Michael  and Prabhumoye, Shrimai  and Gerritsen, David  and McLaughlin, Brittany  and Dixon-Rom{\'a}n, Ezekiel  and Black, Alan W, 2019
3. [Shedding (a Thousand Points of) Light on Biased Language](https://www.aclweb.org/anthology/W10-0723), Yano, Tae  and Resnik, Philip  and Smith, Noah A., 2010
1. [Dialect Diversity in Text Summarization on Twitter](https://arxiv.org/abs/2007.07860), Celis, L Elisa and Keswani, Vijay, 2020
1. [Identifying and Measuring Annotator Bias Based on Annotators' Demographic Characteristics](https://www.aclweb.org/anthology/2020.alw-1.21), Al Kuwatly, Hala  and Wich, Maximilian  and Groh, Georg, 2020
1. [Multilingual sentence-level bias detection in Wikipedia](https://www.aclweb.org/anthology/R19-1006), Aleksandrova, Desislava  and Lareau, François and Ménard, Pierre André, 2019
1. [Automated Essay Scoring in the Presence of Biased Ratings](https://www.aclweb.org/anthology/N18-1021), Amorim, Evelin  and Cançado, Marcia  and Veloso, Adriano, 2018
1. [Predicting Factuality of Reporting and Bias of News Media Sources](https://www.aclweb.org/anthology/D18-1389), Baly, Ramy  and Karadzhov, Georgi  and Alexandrov, Dimitar  and Glass, James  and Nakov, Preslav, 2018
1. [We Can Detect Your Bias: Predicting the Political Ideology of News Articles](https://www.aclweb.org/anthology/2020.emnlp-main.404), Baly, Ramy  and Da San Martino, Giovanni  and Glass, James  and Nakov, Preslav, 2020
1. [The Multilingual Affective Soccer Corpus (MASC): Compiling a biased parallel corpus on soccer reportage in English, German and Dutch](https://www.aclweb.org/anthology/W16-6612), Braun, Nadine  and Goudbeek, Martijn  and Krahmer, Emiel, 2016
1. [Word-order Biases in Deep-agent Emergent Communication](https://www.aclweb.org/anthology/P19-1509), Chaabouni, Rahma  and Kharitonov, Eugene  and Lazaric, Alessandro  and Dupoux, Emmanuel  and Baroni, Marco, 2019
1. [Importance sampling for unbiased on-demand evaluation of knowledge base population](https://www.aclweb.org/anthology/D17-1109), Chaganty, Arun  and Paranjape, Ashwin  and Liang, Percy  and Manning, Christopher D., 2017
1. [The price of debiasing automatic metrics in natural language evalaution](https://www.aclweb.org/anthology/P18-1060), Chaganty, Arun  and Mussmann, Stephen  and Liang, Percy, 2018
1. [Bias and Fairness in Natural Language Processing](https://www.aclweb.org/anthology/D19-2004), Chang, Kai-Wei  and Prabhakaran, Vinod  and Ordonez, Vicente, 2019
1. [Learning to Flip the Bias of News Headlines](https://www.aclweb.org/anthology/W18-6509), Chen, Wei-Fan  and Wachsmuth, Henning  and Al-Khatib, Khalid  and Stein, Benno, 2018
1. [Analyzing Political Bias and Unfairness in News Articles at Different Levels of Granularity](https://www.aclweb.org/anthology/2020.nlpcss-1.16), Chen, Wei-Fan  and Al Khatib, Khalid  and Wachsmuth, Henning  and Stein, Benno, 2020
1. [Detecting Media Bias in News Articles using Gaussian Bias Distributions](https://www.aclweb.org/anthology/2020.findings-emnlp.383), Chen, Wei-Fan  and Al Khatib, Khalid  and Stein, Benno  and Wachsmuth, Henning, 2020
1. [Modelling Annotator Bias with Multi-task Gaussian Processes: An Application to Machine Translation Quality Estimation](https://www.aclweb.org/anthology/P13-1004), Cohn, Trevor  and Specia, Lucia, 2013
1. [Masking Actor Information Leads to Fairer Political Claims Detection](https://www.aclweb.org/anthology/2020.acl-main.404), Dayanik, Erenay  and Padó, Sebastian, 2020
1. [CLARIN: Towards FAIR and Responsible Data Science Using Language Resources](https://www.aclweb.org/anthology/L18-1515), de Jong, Franciska  and Maegaard, Bente  and De Smedt, Koenraad  and Fišer, Darja  and Van Uytvanck, Dieter, 2018
1. [Semi-Supervised Topic Modeling for Gender Bias Discovery in English and Swedish](https://www.aclweb.org/anthology/2020.gebnlp-1.8), Devinney, Hannah  and Björklund, Jenny  and Björklund, Henrik, 2020
1. [Is Your Classifier Actually Biased? Measuring Fairness under Uncertainty with Bernstein Bounds](https://www.aclweb.org/anthology/2020.acl-main.262), Ethayarajh, Kawin, 2020
1. [Team Peter Brinkmann at SemEval-2019 Task 4: Detecting Biased News Articles Using Convolutional Neural Networks](https://www.aclweb.org/anthology/S19-2180), Färber, Michael  and Qurdina, Agon  and Ahmedi, Lule, 2019
1. [Biases in Predicting the Human Language Model](https://www.aclweb.org/anthology/P14-2002), Fine, Alex B.  and Frank, Austin F.  and Jaeger, T. Florian  and Van Durme, Benjamin, 2014
1. [Debiasing knowledge graph embeddings](https://www.aclweb.org/anthology/2020.emnlp-main.595), Fisher, Joseph  and Mittal, Arpit  and Palfrey, Dave  and Christodoulopoulos, Christos, 2020
1. [Analyzing Biases in Human Perception of User Age and Gender from Text](https://www.aclweb.org/anthology/P16-1080), Flekova, Lucie  and Carpenter, Jordan  and Giorgi, Salvatore  and Ungar, Lyle  and Preoţiuc-Pietro, Daniel, 2016
1. [Reference Bias in Monolingual Machine Translation Evaluation](https://www.aclweb.org/anthology/P16-2013), Fomicheva, Marina  and Specia, Lucia, 2016
1. [Analyzing Gender Bias within Narrative Tropes](https://www.aclweb.org/anthology/2020.nlpcss-1.23), Gala, Dhruvil  and Khursheed, Mohammad Omar  and Lerner, Hannah  and O'Connor, Brendan  and Iyyer, Mohit, 2020
1. [Detecting Political Bias in News Articles Using Headline Attention](https://www.aclweb.org/anthology/W19-4809), Gangula, Rama Rohit Reddy  and Duggenpudi, Suma Reddy  and Mamidi, Radhika, 2019
2. [Detecting Independent Pronoun Bias with Partially-Synthetic Data Generation](https://www.aclweb.org/anthology/2020.emnlp-main.157), Munro, Robert  and Morrison, Alex (Carmen), 2020
3. [Modeling Personal Biases in Language Use by Inducing Personalized Word Embeddings](https://www.aclweb.org/anthology/N19-1215), Oba, Daisuke  and Yoshinaga, Naoki  and Sato, Shoetsu  and Akasaki, Satoshi  and Toyoda, Masashi, 2019
4. [Quantifying 60 Years of Gender Bias in Biomedical Research with Word Embeddings](https://www.aclweb.org/anthology/2020.bionlp-1.1), Rios, Anthony  and Joshi, Reenam  and Shin, Hejin, 2020
5. [Analyzing Gender Bias in Student Evaluations](https://www.aclweb.org/anthology/C16-1083), Terkik, Andamlak  and Prud{'}hommeaux, Emily  and Ovesdotter Alm, Cecilia  and Homan, Christopher  and Franklin, Scott, 2016

#### Tutorial List
- [Fairness in Machine Learning](https://nips.cc/Conferences/2017/Schedule?showEvent=8734), NeurIPS 2017
- [The Trouble with Bias](https://www.youtube.com/watch?v=fMym_BKWQzk), NeurIPS 2017
- [Socially Responsible NLP](https://www.aclweb.org/anthology/N18-6005/), NAACL 2018
- [Tutorial: Bias and Fairness in Natural Language Processing](http://web.cs.ucla.edu/~kwchang/talks/emnlp19-fairnlp/), EMNLP 2019
- [Fairness-Aware Machine Learning: Practical Challenges and Lessons Learned](https://sites.google.com/view/kdd19-fairness-tutorial), KDD 2019
- [Dealing with Bias and Fairness in Building Data Science/ML/AI Systems](https://dssg.github.io/fairness_tutorial/), KDD 2020

#### Jupter/Colab tutorial
- [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://github.com/uclanlp/reducingbias/blob/master/src/fairCRF_gender_ratio.ipynb)
- [Mitigating Gender Bias Ampliﬁcation in Distribution by Posterior Regularization](https://colab.research.google.com/drive/1jBhnzxaaHMY1jbPPa1OqT8-6QxZA_T7p?authuser=2#scrollTo=YpNJrP3uBMd3)

#### Conference/Workshop List
- [Ethics in NLP](https://aclweb.org/aclwiki/Ethics_in_NLP), ACL Wiki
- [ACM FAT conference](https://fatconference.org/)
- [Gendered Ambiguous Pronoun (GAP) Shared Task at the Gender Bias in NLP Workshop 2019](https://www.aclweb.org/anthology/W19-3801), Webster, Kellie  and Costa-jussa, Marta R.  and Hardmeier, Christian  and Radford, Will, 2019
- [Proceedings of the First Workshop on Gender Bias in Natural Language Processing](https://www.aclweb.org/anthology/W19-3800), Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will  and Webster, Kellie, 2019
- [Team Kermit-the-frog at SemEval-2019 Task 4: Bias Detection Through Sentiment Analysis and Simple Linguistic Features](https://www.aclweb.org/anthology/S19-2177), Anthonio, Talita  and Kloppenburg, Lennart, 2019
- [Fairness and machine learning](https://fairmlbook.org/index.html)