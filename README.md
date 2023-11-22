# awesome-fairness-papers
Papers about fairness in NLP and Multi-Modal Models

[Christina Chance](https://www.linkedin.com/in/christina-chance-147666166), [Yixin Wan](https://www.linkedin.com/in/elaine-yixin-wan-8032b8136/), [Jieyu Zhao](https://jyzhao.net/), [Emily Sheng](https://ewsheng.github.io/), [Sunipa Dev](https://sunipa.github.io/), [Yu (Hope) Hou](https://github.com/houyu0930), [Nanyun (Violet) Peng](https://vnpeng.net/),
and [Kai-Wei Chang](http://web.cs.ucla.edu/~kwchang/)

## Background
Fairness, accountability, transparency, and ethics are becoming more and more important in Natural Language Processing (NLP) and Multi-Modal Settings. We provide a list of papers that serve as references for researchers interested in these topics. This repo mainly focuses on papers published in the NLP venues, but we also point to some other resources at the end.

For relevant courses and other resources, please refer to [ACL Wiki](https://aclweb.org/aclwiki/Ethics_in_NLP)
<!-- <p align='center'>
<a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/"><figure><img src="fairness_plot.svg", align="center"></figure></a>
</p>
<p align='center'>credit to <a href="https://godatadriven.com/blog/towards-fairness-in-ml-with-adversarial-networks/">Stijn Tonk</a></p> -->

**Disclaimer: We may miss some relevant papers in the list. If you have any suggestions or would like to add some papers, please submit a pull request or email us. Your contribution is much appreciated!**

## Contents
- [awesome-fairness-papers](#awesome-fairness-papers)
  - [Background](#background)
  - [Contents](#contents)
    - [Paper List](#paper-list)
      - [Surveys](#surveys)
      - [Social Impact of Biases](#social-impact-of-biases)
      - [Data, Models, & Metrics](#data-models--metrics)
      - [Word/Sentence Representations](#wordsentence-representations)
      - [Natural Language Understanding](#natural-language-understanding)
        - [Bias Amplification Issue](#bias-amplification-issue)
        - [Bias Detection](#bias-detection)
        - [Bias Mitigation](#bias-mitigation)
      - [Natural Language Generation](#natural-language-generation)
        - [Machine Translation](#machine-translation)
        - [Dialogue Generation](#dialogue-generation)
        - [Other Generation](#other-generation)
      - [Multi-Modal Setting](#multi-modal-setting)
        - [Bias Detection in Multi-Modal Setting](#bias-detection-in-multi-modal-setting)
        - [Bias Mitigation in Multi-Modal Setting](#bias-mitigation-in-multi-modal-setting)
      - [Bias Visualization](#bias-visualization)
      - [Others](#others)
    - [Tutorial List](#tutorial-list)
      - [Jupyter/Colab Tutorial](#jupytercolab-tutorial)
    - [Conference/Workshop List](#conferenceworkshop-list)


### Paper List

#### Surveys
1. [Language (Technology) is Power: A Critical Survey of "Bias" in NLP](https://www.aclweb.org/anthology/2020.acl-main.485), Blodgett, Su Lin  and Barocas, Solon  and Daumé III, Hal  and Wallach, Hanna, 2020
1. [Predictive Biases in Natural Language Processing Models: A Conceptual Framework and Overview](https://www.aclweb.org/anthology/2020.acl-main.468), Shah, Deven Santosh  and Schwartz, H. Andrew  and Hovy, Dirk, 2020
1. [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159), Sun, Tony  and Gaut, Andrew  and Tang, Shirlyn  and Huang, Yuxin  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2019
1. [A survey on bias and fairness in machine learning](https://arxiv.org/abs/1908.09635), Mehrabi, Ninareh and Morstatter, Fred and Saxena, Nripsuta and Lerman, Kristina and Galstyan, Aram, 2019
1. [50 years of test (Un)fairness: Lessons for machine learning](https://dl.acm.org/doi/abs/10.1145/3287560.3287600), Hutchinson, Ben and Mitchell, Margaret, 2019
1. [Societal Biases in Language Generation: Progress and Challenges](https://arxiv.org/abs/2105.04054), Sheng, Emily and Chang, Kai-Wei and Natarajan, Prem and Peng, Nanyun, 2021
1. [Gender Bias in Machine Translation](https://arxiv.org/abs/2104.06001), Savoldi, Beatrice and Gaido, Marco and Bentivogli, Luisa and Negri, Matteo and Turchi, Marco, 2021
1. [Quantifying Social Biases in NLP: A Generalization and Empirical Comparison of Extrinsic Fairness Metrics](https://arxiv.org/abs/2106.14574), Czarnowska, Paula and Vyas, Yogarshi and Shah Kashif, 2021
1. [Confronting Abusive Language Online: A Survey from the Ethical and Human Rights Perspective](https://arxiv.org/abs/2012.12305), Kiritchenko, Svetlana and Nejadgholi, Isar and Fraser, Kathleen C, 2020
1. [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922), Bender, Emily M., Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell. 2021.
2. [An Empirical Survey of the Effectiveness of Debiasing Techniques for Pre-trained Language Models ](https://arxiv.org/abs/2110.08527). Nicholas Meade, Elinor Poole-Dayan, Siva Reddy. ACL 2022
12. [Square One Bias in NLP: Towards a Multi-Dimensional Exploration of the Research Manifold](https://aclanthology.org/2022.findings-acl.184/). Sebastian Ruder, Ivan Vulić, Anders Søgaard. ACL 2022 Findings.
13. [Measuring Fairness with Biased Rulers: A Comparative Study on Bias Metrics for Pre-trained](https://aclanthology.org/2022.naacl-main.122.pdf). Language Models Pieter Delobelle, Ewoenam Kwaku Tokpo, Toon Calders, Bettina Berendt. NAACL 2022
14. [Benchmarking Intersectional Biases in NLP](https://aclanthology.org/2022.naacl-main.263.pdf). John Lalor, Yi Yang, Kendall Smith, Nicole Forsgren, Ahmed Abbasi. NAACL 2022.
15. [Measure and Improve Robustness in NLP Models: A Survey](https://aclanthology.org/2022.naacl-main.339.pdf). Xuezhi Wang, Haohan Wang, Diyi Yang. NAACL 2022.
16. [Bias and Fairness in Large Language Models: A Survey](https://arxiv.org/abs/2309.00770). Isabel O. Gallegos, Ryan A. Rossi, Joe Barrow, Md Mehrab Tanjim, Sungchul Kim, Franck Dernoncourt, Tong Yu, Ruiyi Zhang, and Nesreen K. Ahmed, 2023

#### Social Impact of Biases
1. [The Social Impact of Natural Language Processing](https://www.aclweb.org/anthology/P16-2096), Hovy, Dirk and Spruit, Shannon L., 2016
1. [Give Me Convenience and Give Her Death: Who Should Decide What Uses of NLP are Appropriate, and on What Basis?](https://www.aclweb.org/anthology/2020.acl-main.261), Leins, Kobi and Lau, Jey Han and Baldwin, Timothy, 2020
1. [Situated Data, Situated Systems: A Methodology to Engage with Power Relations in Natural Language Processing Research](https://www.aclweb.org/anthology/2020.gebnlp-1.10), Havens, Lucy and Terras, Melissa and Bach, Benjamin and Alex, Beatrice, 2020
1. [Re-imagining Algorithmic Fairness in India and Beyond](https://arxiv.org/abs/2101.09995), Sambasivan, Nithya and Arnesen, Erin and Hutchinson, Ben and Doshi, Tulsee and Prabhakaran, Vinodkumar, 2021
1. [Improving fairness in machine learning systems: What do industry practitioners need?](https://dl.acm.org/doi/10.1145/3290605.3300830), Holstein, Kenneth and Wortman Vaughan, Jennifer and Daumé III, Hal and Dudik, Miro and Wallach, Hanna, 2019
1. The problem with bias: Allocative versus representational harms in machine learning, Barocas, Solon and Crawford, Kate and Shapiro, Aaron and Wallach, Hanna, 2017
2. [The many dimensions of algorithmic fairness in educational applications](https://www.aclweb.org/anthology/W19-4401), Loukina, Anastassia  and Madnani, Nitin  and Zechner, Klaus, 2019
3. [NLPositionality: Characterizing Design Biases of Datasets and Models](https://aclanthology.org/2023.acl-long.505/). Sebastin Santy, Jenny Liang, Ronan Le Bras, Katharina Reinecke, Maarten Sap. ACL 2023
4. [What social attitudes about gender does BERT encode? Leveraging insights from psycholinguistics](https://aclanthology.org/2023.acl-long.375/). Julia Watson, Barend Beekhuizen, Suzanne Stevenson. ACL 2023
5. [Examining risks of racial biases in NLP tools for child protective services](https://dl.acm.org/doi/10.1145/3593013.3594094). Anjalie Field, Amanda Coston, Nupoor Gandhi, Alexandra Chouldechova, Emily Putnam-Hornstein, David Steier, Yulia Tsvetkov. ACM FAccT 2023
6. ["I wouldn’t say offensive but...": Disability-Centered Perspectives on Large Language Models](https://dl.acm.org/doi/10.1145/3593013.3593989). Vinitha Gadiraju, Shaun Kane, Sunipa Dev, Alex Taylor, Ding Wang, Emily Denton, Robin Brewer. ACM FAccT 2023
7. [Contrastive Language-Vision AI Models Pretrained on Web-Scraped Multimodal Data Exhibit Sexual Objectification Bias](https://dl.acm.org/doi/10.1145/3593013.3594072). Robert Wolfe, Yiwei Yang, Bill Howe, Aylin Caliskan. ACM FAccT 2023

#### Data, Models, & Metrics
1. [Data Statements for Natural Language Processing: Toward Mitigating System Bias and Enabling Better Science](https://www.aclweb.org/anthology/Q18-1041), Bender, Emily M. and Friedman, Batya, 2018
1. [Data and its (dis)contents: A survey of dataset development and use in machine learning research](https://arxiv.org/abs/2012.05345), Paullada, Amandalynne and Raji, Inioluwa Deborah and Bender, Emily M and Denton, Emily and Hanna, Alex, 2020
1. [Datasheets for datasets](https://arxiv.org/abs/1803.09010), Gebru, Timnit and Morgenstern, Jamie and Vecchione, Briana and Vaughan, Jennifer Wortman and Wallach, Hanna and Daumé III, Hal and Crawford, Kate, 2018
1. [Discovering and categorising language biases in reddit](https://arxiv.org/abs/2008.02754), Ferrer, Xavier and van Nuenen, Tom and Such, Jose M. and Criado, Natalia, 2021
1. [Model cards for model reporting](https://dl.acm.org/doi/10.1145/3287560.3287596), Mitchell, Margaret and Wu, Simone and Zaldivar, Andrew and Barnes, Parker and Vasserman, Lucy and Hutchinson, Ben and Spitzer, Elena and Raji, Inioluwa Deborah and Gebru, Timnit, 2019
1. [Counterfactual fairness](https://papers.nips.cc/paper/2017/hash/a486cd07e4ac3d270571622f4f316ec5-Abstract.html), Kusner, Matt J and Loftus, Joshua and Russell, Chris and Silva, Ricardo, 2017
1. [Fairness through awareness](https://dl.acm.org/doi/10.1145/2090236.2090255), Dwork, Cynthia and Hardt, Moritz and Pitassi, Toniann and Reingold, Omer and Zemel, Richard, 2012
1. [Equality of opportunity in supervised learning](https://dl.acm.org/doi/10.5555/3157382.3157469), Hardt, Moritz and Price, Eric and Srebro, Nati, 2016
1. [The price of debiasing automatic metrics in natural language evalaution](https://www.aclweb.org/anthology/P18-1060), Chaganty, Arun  and Mussmann, Stephen  and Liang, Percy, 2018
1. [Are We Modeling the Task or the Annotator? An Investigation of Annotator Bias in Natural Language Understanding Datasets](https://www.aclweb.org/anthology/D19-1107), Geva, Mor  and Goldberg, Yoav  and Berant, Jonathan, 2019
1. [Proposed Taxonomy for Gender Bias in Text; A Filtering Methodology for the Gender Generalization Subtype](https://www.aclweb.org/anthology/W19-3802), Hitti, Yasmeen  and Jang, Eunbee  and Moreno, Ines  and Pelletier, Carolyne, 2019
1. [These are not the Stereotypes You are Looking For: Bias and Fairness in Authorial Gender Attribution](https://www.aclweb.org/anthology/W17-1602), Koolen, Corina  and van Cranenburgh, Andreas, 2017
2. [Discovering Biased News Articles Leveraging Multiple Human Annotations](https://www.aclweb.org/anthology/2020.lrec-1.159), Lazaridou, Konstantina  and L{\"o}ser, Alexander  and Mestre, Maria  and Naumann, Felix, 2020
1. [Annotating and Analyzing Biased Sentences in News Articles using Crowdsourcing](https://www.aclweb.org/anthology/2020.lrec-1.184), Lim, Sora  and Jatowt, Adam  and F{\"a}rber, Michael  and Yoshikawa, Masatoshi, 2020
1.  [Differentially Private Representation for NLP: Formal Guarantee and An Empirical Study on Privacy and Fairness](https://www.aclweb.org/anthology/2020.findings-emnlp.213), Lyu, Lingjuan  and He, Xuanli  and Li, Yitong, 2020
1. [Building Better Open-Source Tools to Support Fairness in Automated Scoring](https://www.aclweb.org/anthology/W17-1605), Madnani, Nitin  and Loukina, Anastassia  and von Davier, Alina  and Burstein, Jill  and Cahill, Aoife, 2017
1. [StereoSet: Measuring stereotypical bias in pretrained language models](https://arxiv.org/abs/2004.09456), Nadeem, Moin and Bethke, Anna and Reddy, Siva, 2020
2. [Investigating Sports Commentator Bias within a Large Corpus of American Football Broadcasts](https://www.aclweb.org/anthology/D19-1666), Merullo, Jack  and Yeh, Luke  and Handler, Abram  and Grissom II, Alvin  and O{'}Connor, Brendan  and Iyyer, Mohit, 2019
3. [Artie Bias Corpus: An Open Dataset for Detecting Demographic Bias in Speech Applications](https://www.aclweb.org/anthology/2020.lrec-1.796), Meyer, Josh  and Rauchenstein, Lindy  and Eisenberg, Joshua D.  and Howell, Nicholas, 2020
4. [RtGender: A Corpus for Studying Differential Responses to Gender](https://nlp.stanford.edu/robvoigt/rtgender/rtgender.pdf), Voigt, Rob and Jurgens, David and Prabhakaran, Vinodkumar and Jurafsky, Dan and Tsvetkov, Yulia, 2018
5. [Multi-Dimensional Gender Bias Classification](https://www.aclweb.org/anthology/2020.emnlp-main.23), Dinan, Emily  and Fan, Angela  and Wu, Ledell  and Weston, Jason  and Kiela, Douwe  and Williams, Adina, 2020
6. [UNQOVERing Stereotyping Biases via Underspecified Questions](https://www.aclweb.org/anthology/2020.findings-emnlp.311), Li, Tao  and Khashabi, Daniel  and Khot, Tushar  and Sabharwal, Ashish  and Srikumar, Vivek, 2020
1. [CrowS-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.154), Nangia, Nikita  and Vania, Clara  and Bhalerao, Rasika  and Bowman, Samuel R., 2020
1. [Gender Bias in Coreference Resolution](https://www.aclweb.org/anthology/N18-2002), Rudinger, Rachel  and Naradowsky, Jason  and Leonard, Brian  and Van Durme, Benjamin, 2018
1. [Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://www.aclweb.org/anthology/N18-2003), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2018
1. [Unmasking the Mask -- Evaluating Social Biases in Masked Language Models](https://arxiv.org/abs/2104.07496), Kaneko, Masahiro  and Bollegala, Danushka, 2021
1. [WIKIBIAS: Detecting Multi-Span Subjective Biases in Language](https://www.cc.gatech.edu/~dyang888/docs/emnlp21_wikibias.pdf), Zhong, Yang and Yang, Jingfeng and Xu, Wei and Yang, Diyi, EMNLP, 2021
2. [Constructing a Psychometric Testbed for Fair Natural Language Processing](https://aclanthology.org/2021.emnlp-main.304), Ahmed Abbasi, David Dobolyi, John P. Lalor, Richard G. Netemeyer, Kendall Smith, and Yi Yang, EMNLP 2021
3. [Benchmarking Bias Mitigation Algorithms in Representation Learning through Fairness Metrics](https://openreview.net/forum?id=OTnqQUEwPKu), Charan Reddy, Deepak Sharma, Soroush Mehri, Adriana Romero, Samira Shabanian, Sina Honari. NeurIPS, 2021.
29. [FairLex: A Multilingual Benchmark for Evaluating
Fairness in Legal Text Processing](https://arxiv.org/pdf/2203.07228.pdf). Ilias Chalkidis, Tommaso Pasini, Sheng Zhang, Letizia Tomada, Sebastian Felix Schwemer, Anders Søgaard. ACL 2022.
30. [French CrowS-Pairs: Extending a challenge dataset for measuring social bias in masked language models to a language other than English](https://aclanthology.org/2022.acl-long.583/). Aurélie Névéol, Yoann Dupont, Julien Bezançon, Karën Fort. ACL 2022
31. [Measuring Fairness of Text Classifiers via Prediction Sensitivity](https://arxiv.org/abs/2203.08670). Satyapriya Krishna, Rahul Gupta, Apurv Verma, Jwala Dhamala, Yada Pruksachatkun, Kai-Wei Chang. ACL 2022.
32. [Optimising Equal Opportunity Fairness in Model Training](https://aclanthology.org/2022.naacl-main.299.pdf). Aili Shen, Xudong Han, Trevor Cohn, Timothy Baldwin, Lea Frermann. NAACL 2022.
33. [Benchmarking Intersectional Biases in NLP](https://aclanthology.org/2022.naacl-main.263/), John P. Lalor, Yi Yang, Kendall Smith, Nicole Forsgren, Ahmed Abbasi. NAACL 2022.
35. [Collecting a Large-Scale Gender Bias Dataset for Coreference Resolution and Machine Translation](https://aclanthology.org/2021.findings-emnlp.211/). Shahar Levy, Koren Lazar, Gabriel Stanovsky. EMNLP 2021
36. [Recognition of They/Them as Singular Personal Pronouns in Coreference Resolution](https://aclanthology.org/2022.naacl-main.250.pdf). Connor Baumler and Rachel Rudinger. NAACL 2022.
37. [Theory-Grounded Measurement of U.S. Social Stereotypes in English Language Models](https://aclanthology.org/2022.naacl-main.92.pdf). Yang Trista Cao, Anna Sotnikova, Hal Daumé III, Rachel Rudinger, Linda Zou. NAACL 2022.
38. [WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models](https://aclanthology.org/2023.acl-long.507/). Virginia Felkner, Ho-Chun Herbert Chang, Eugene Jang, Jonathan May. ACL 2023
39. [The Tail Wagging the Dog: Dataset Construction Biases of Social Bias Benchmarks](https://aclanthology.org/2023.acl-short.118/). Nikil Selvam, Sunipa Dev, Daniel Khashabi, Tushar Khot, Kai-Wei Chang. ACL 2023
40. [Fighting Bias With Bias: Promoting Model Robustness by Amplifying Dataset Biases](https://aclanthology.org/2023.findings-acl.833/). Yuval Reif, Roy Schwartz. ACL 2023 Findings
41. [FORK: A Bite-Sized Test Set for Probing Culinary Cultural Biases in Commonsense Reasoning Models](https://aclanthology.org/2023.findings-acl.631/). Shramay Palta, Rachel Rudinger. ACL 2023 Findings
42. [KoSBI: A Dataset for Mitigating Social Bias Risks Towards Safer Large Language Model Applications](https://aclanthology.org/2023.acl-industry.21/). Hwaran Lee, Seokhee Hong, Joonsuk Park, Takyoung Kim, Gunhee Kim, Jung-woo Ha. ACL 2023
43. [Riveter: Measuring Power and Social Dynamics Between Entities](https://aclanthology.org/2023.acl-demo.36/). Maria Antoniak, Anjalie Field, Jimin Mun, Melanie Walsh, Lauren Klein, Maarten Sap. ACL 2023
44. [BERTScore is Unfair: On Social Bias in Language Model-Based Metrics for Text Generation](https://aclanthology.org/2022.emnlp-main.245/). Tianxiang Sun, Junliang He, Xipeng Qiu, Xuanjing Huang. EMNLP 2022
45. [FairLib: A Unified Framework for Assessing and Improving Fairness](https://aclanthology.org/2022.emnlp-demos.7/). Xudong Han, Aili Shen, Yitong Li, Lea Frermann, Timothy Baldwin, Trevor Cohn. EMNLP 2022
46. [Towards Identifying Social Bias in Dialog Systems: Framework, Dataset, and Benchmark](https://aclanthology.org/2022.findings-emnlp.262/). Jingyan Zhou, Jiawen Deng, Fei Mi, Yitong Li, Yasheng Wang, Minlie Huang, Xin Jiang, Qun Liu, Helen Meng. EMNLP 2022
47. [Detecting Unintended Social Bias in Toxic Language Datasets](https://aclanthology.org/2022.conll-1.10/). Nihar Sahoo, Himanshu Gupta, Pushpak Bhattacharyya. EMNLP 2022
48. [Toward Gender-Inclusive Coreference Resolution](https://aclanthology.org/2020.acl-main.418/). Yang Trista Cao, Hal Daumé III. ACL 2020.

#### Word/Sentence Representations
1. [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/abs/1607.06520), Bolukbasi, Tolga and Chang, Kai-Wei and Zou, James and Saligrama, Venkatesh and Kalai, Adam, 2016 [[github]](https://github.com/tolga-b/debiaswe)
1. [Semantics derived automatically from language corpora contain human-like biases](https://science.sciencemag.org/content/356/6334/183), Caliskan, Aylin and Bryson, Joanna J. and Narayanan, Arvind, 2017
1. [Attenuating Biases in Word Vectors](http://proceedings.mlr.press/v89/dev19a.html), Dev, Sunipa and Phillips, Jeff M, 2019
1. [Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/N19-1064), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Cotterell, Ryan  and Ordonez, Vicente  and Chang, Kai-Wei, 2019
1. [Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings](https://www.aclweb.org/anthology/N19-1062), Manzini, Thomas  and Yao Chong, Lim  and Black, Alan W  and Tsvetkov, Yulia, 2019
1. [Towards Understanding Linear Word Analogies](https://www.aclweb.org/anthology/P19-1315), Ethayarajh, Kawin and Duvenaud, David and Hirst, Graeme, 2019
1. [Understanding Undesirable Word Embedding Associations](https://www.aclweb.org/anthology/P19-1166), Ethayarajh, Kawin and Duvenaud, David and Hirst, Graeme, 2019
2. [Gender Bias in Multilingual Embeddings and Cross-Lingual Transfer](https://www.aclweb.org/anthology/2020.acl-main.260), Zhao, Jieyu  and Mukherjee, Subhabrata  and Hosseini, Saghar  and Chang, Kai-Wei  and Hassan Awadallah, Ahmed, 2020
1. [Nurse is Closer to Woman than Surgeon? Mitigating Gender-Biased Proximities in Word Embeddings](https://www.aclweb.org/anthology/2020.tacl-1.32), Kumar, Vaibhav  and Bhotia, Tenzin Singhay  and Kumar, Vaibhav  and Chakraborty, Tanmoy, 2020
1. [Measuring Bias in Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3823), Kurita, Keita  and Vyas, Nidhi  and Pareek, Ayush  and Black, Alan W and Tsvetkov, Yulia, 2019
1. [Unmasking Contextual Stereotypes: Measuring and Mitigating BERT's Gender Bias](https://www.aclweb.org/anthology/2020.gebnlp-1.1), Bartl, Marion  and Nissim, Malvina  and Gatt, Albert, 2020
1. [Evaluating the Underlying Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/W19-3805), Basta, Christine  and Costa-jussà, Marta R.  and Casas, Noe, 2019
1. [Evaluating Bias In Dutch Word Embeddings](https://www.aclweb.org/anthology/2020.gebnlp-1.6), Chávez Mulsa, Rodrigo Alejandro  and Spanakis, Gerasimos, 2020
1. [Learning Gender-Neutral Word Embeddings](https://arxiv.org/abs/1809.01496), Zhao, Jieyu and Zhou, Yichao and Li, Zeyu and Wang, Wei and Chang, Kai-Wei
1. [Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://www.aclweb.org/anthology/N19-1061), Gonen, Hila  and Goldberg, Yoav, 2019
1. [It{'}s All in the Name: Mitigating Gender Bias with Name-Based Counterfactual Data Substitution](https://www.aclweb.org/anthology/D19-1530), Hall Maudslay, Rowan  and Gonen, Hila  and Cotterell, Ryan  and Teufel, Simone, 2019
1. [Gender-preserving Debiasing for Pre-trained Word Embeddings](https://www.aclweb.org/anthology/P19-1160), Kaneko, Masahiro  and Bollegala, Danushka, 2019
1. [Debiasing Pre-trained Contextualised Embeddings](https://www.aclweb.org/anthology/2021.eacl-main.107), Kaneko, Masahiro  and Bollegala, Danushka, 2021
1. [Dictionary-based Debiasing of Pre-trained Word Embeddings](https://www.aclweb.org/anthology/2021.eacl-main.16), Kaneko, Masahiro  and Bollegala, Danushka, 2021
1. [Conceptor Debiasing of Word Representations Evaluated on WEAT](https://www.aclweb.org/anthology/W19-3806), Karve, Saket  and Ungar, Lyle  and Sedoc, Jo{\~a}o, 2019
2. [Are We Consistently Biased? Multidimensional Analysis of Biases in Distributional Word Vectors](https://www.aclweb.org/anthology/S19-1010), Lauscher, Anne  and Glava{\v{s}}, Goran, 2019
1. [AraWEAT: Multidimensional Analysis of Biases in Arabic Word Embeddings](https://www.aclweb.org/anthology/2020.wanlp-1.17), Lauscher, Anne  and Takieddin, Rafik  and Ponzetto, Simone Paolo  and Glava{\v{s}}, Goran, 2020
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
3. [Modeling Personal Biases in Language Use by Inducing Personalized Word Embeddings](https://www.aclweb.org/anthology/N19-1215), Oba, Daisuke  and Yoshinaga, Naoki  and Sato, Shoetsu  and Akasaki, Satoshi  and Toyoda, Masashi, 2019
4. [Quantifying 60 Years of Gender Bias in Biomedical Research with Word Embeddings](https://www.aclweb.org/anthology/2020.bionlp-1.1), Rios, Anthony  and Joshi, Reenam  and Shin, Hejin, 2020
1. [Debiasing knowledge graph embeddings](https://www.aclweb.org/anthology/2020.emnlp-main.595), Fisher, Joseph  and Mittal, Arpit  and Palfrey, Dave  and Christodoulopoulos, Christos, 2020
1. [Assessing the Reliability of Word Embedding Gender Bias Measures](https://arxiv.org/abs/2109.04732), Du, Yupei and Fang, Qixiang and Nguyen, Dong, EMNLP, 2021
1. [Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies](https://arxiv.org/abs/2108.12084), Dev, Sunipa and Monajatipoor, Masoud and Ovalle, Anaelia and Subramonian, Arjun and Phillips, Jeff M and Chang, Kai-Wei, EMNLP, 2021
45. [Sense Embeddings are also Biased -- Evaluating Social Biases in Static and Contextualised Sense Embeddings](https://aclanthology.org/2022.acl-long.135/). Yi Zhou, Masahiro Kaneko, Danushka Bollegala. ACL 2022
46. [Understanding Gender Bias in Knowledge Base Embeddings](https://aclanthology.org/2022.acl-long.98/). Yupei Du, Qi Zheng, Yuanbin Wu, Man Lan, Yan Yang, Meirong Ma. ACL 2022
47. [On the Intrinsic and Extrinsic Fairness Evaluation Metrics for Contextualized Language Representations ](https://arxiv.org/abs/2203.13928). Yang Trista Cao, Yada Pruksachatkun, Kai-Wei Chang, Rahul Gupta, Varun Kumar, Jwala Dhamala, Aram Galstyan. ACL 2022
48. [Learning Bias-reduced Word Embeddings Using Dictionary Definitions](https://aclanthology.org/2022.findings-acl.90/). Haozhe An, Xiaojiang Liu, Donald Zhang. ACL 2022 Findings.
49. [Socially Aware Bias Measurements for Hindi Language Representations](https://arxiv.org/abs/2110.07871). Vijit Malik, Sunipa Dev, Akihiro Nishi, Nanyun Peng, Kai-Wei Chang. NAACL 2022
50. [No Word Embedding Model Is Perfect: Evaluating the Representation Accuracy for Social Bias in the Media](https://aclanthology.org/2022.findings-emnlp.152/). Maximilian Spliethöver, Maximilian Keiff, Henning Wachsmuth. EMNLP 2022
51. [Gender Bias in Meta-Embeddings](https://aclanthology.org/2022.findings-emnlp.227/). Masahiro Kaneko, Danushka Bollegala, Naoaki Okazaki. EMNLP 2022
52. [The Undesirable Dependence on Frequency of Gender Bias Metrics Based on Word Embeddings](https://aclanthology.org/2022.findings-emnlp.373/). Francisco Valentini, Germán Rosati, Diego Fernandez Slezak, Edgar Altszyler. EMNLP 2022



#### Natural Language Understanding
##### Bias Amplification Issue
1. [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://www.aclweb.org/anthology/D17-1323), Zhao, Jieyu  and Wang, Tianlu  and Yatskar, Mark  and Ordonez, Vicente  and Chang, Kai-Wei, 2017
2. [Feature-Wise Bias Amplification](https://arxiv.org/abs/1812.08999), Klas Leino, Emily Black, Matt Fredrikson, Shayak Sen, Anupam Datta. ICLR, 2019.
1. [Mitigating Gender Bias Amplification in Distribution by Posterior Regularization](https://www.aclweb.org/anthology/2020.acl-main.264), Jia, Shengyu  and Meng, Tao  and Zhao, Jieyu  and Chang, Kai-Wei, 2020
2. [Fairness Without Demographics in Repeated Loss Minimization](https://arxiv.org/abs/1806.08010), Tatsunori B. Hashimoto, Megha Srivastava, Hongseok Namkoong, Percy Liang, ICLM, 2018

##### Bias Detection
1. [LOGAN: Local Group Bias Detection by Clustering](https://www.aclweb.org/anthology/2020.emnlp-main.155), Zhao, Jieyu  and Chang, Kai-Wei, 2020
1. [Examining Gender Bias in Languages with Grammatical Gender](https://www.aclweb.org/anthology/D19-1531), Zhou, Pei  and Shi, Weijia  and Zhao, Jieyu  and Huang, Kuan-Hao  and Chen, Muhao  and Cotterell, Ryan  and Chang, Kai-Wei, 2019
1. [Racial Bias in Hate Speech and Abusive Language Detection Datasets](https://www.aclweb.org/anthology/W19-3504), Davidson, Thomas  and Bhattacharya, Debasmita  and Weber, Ingmar, 2019
1. [Social Biases in NLP Models as Barriers for Persons with Disabilities](https://www.aclweb.org/anthology/2020.acl-main.487), Hutchinson, Ben  and Prabhakaran, Vinodkumar  and Denton, Emily  and Webster, Kellie  and Zhong, Yu  and Denuyl, Stephen, 2020
1. [Perturbation Sensitivity Analysis to Detect Unintended Model Biases](https://www.aclweb.org/anthology/D19-1578), Prabhakaran, Vinodkumar  and Hutchinson, Ben  and Mitchell, Margaret, 2019
1. [OSCaR: Orthogonal Subspace Correction and Rectification of Biases in Word Embeddings](https://arxiv.org/abs/2007.00049), Dev, Sunipa and Li, Tao  and Phillips, Jeff M  and Srikumar, Vivek, 2020
1. [Women's Syntactic Resilience and Men's Grammatical Luck: Gender-Bias in Part-of-Speech Tagging and Dependency Parsing](https://www.aclweb.org/anthology/P19-1339), Garimella, Aparna  and Banea, Carmen  and Hovy, Dirk  and Mihalcea, Rada, 2019
1. [Towards Understanding Gender Bias in Relation Extraction](https://www.aclweb.org/anthology/2020.acl-main.265), Gaut, Andrew  and Sun, Tony  and Tang, Shirlyn  and Huang, Yuxin  and Qian, Jing  and ElSherief, Mai  and Zhao, Jieyu  and Mirza, Diba  and Belding, Elizabeth  and Chang, Kai-Wei  and Wang, William Yang, 2020
1. [Type B Reflexivization as an Unambiguous Testbed for Multilingual Multi-Task Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.209), Gonz{\'a}lez, Ana Valeria  and Barrett, Maria  and Hvingelby, Rasmus  and Webster, Kellie  and S{\o}gaard, Anders, 2020
1. [Inflating Topic Relevance with Ideology: A Case Study of Political Ideology Bias in Social Topic Detection Models](https://www.aclweb.org/anthology/2020.coling-main.428), Guo, Meiqi  and Hwa, Rebecca  and Lin, Yu-Ru  and Chung, Wen-Ting, 2020
1. [Media Bias, the Social Sciences, and NLP: Automating Frame Analyses to Identify Bias by Word Choice and Labeling](https://www.aclweb.org/anthology/2020.acl-srw.12), Hamborg, Felix, 2020
1. [An Annotation Scheme for Automated Bias Detection in Wikipedia](https://www.aclweb.org/anthology/W11-0406), Herzig, Livnat  and Nunes, Alex  and Snir, Batia, 2011
1. [Multilingual Twitter Corpus and Baselines for Evaluating Demographic Bias in Hate Speech Recognition](https://www.aclweb.org/anthology/2020.lrec-1.180), Huang, Xiaolei  and Xing, Linzi  and Dernoncourt, Franck  and Paul, Michael J., 2020
1. [Enhancing Bias Detection in Political News Using Pragmatic Presupposition](https://www.aclweb.org/anthology/2020.socialnlp-1.1), Kameswari, Lalitha  and Sravani, Dama  and Mamidi, Radhika, 2020
1. [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://www.aclweb.org/anthology/S18-2005), Kiritchenko, Svetlana  and Mohammad, Saif, 2018
6. [Social Bias in Elicited Natural Language Inferences](https://www.aclweb.org/anthology/W17-1609), Rudinger, Rachel  and May, Chandler  and Van Durme, Benjamin, 2017
7. [The Risk of Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/P19-1163), Sap, Maarten  and Card, Dallas  and Gabriel, Saadia  and Choi, Yejin  and Smith, Noah A., 2019
8. [Social Bias Frames: Reasoning about Social and Power Implications of Language](https://www.aclweb.org/anthology/2020.acl-main.486), Sap, Maarten  and Gabriel, Saadia  and Qin, Lianhui  and Jurafsky, Dan  and Smith, Noah A.  and Choi, Yejin, 2020
9. [Do Neural Language Models Overcome Reporting Bias?](https://www.aclweb.org/anthology/2020.coling-main.605), Shwartz, Vered  and Choi, Yejin, 2020
10. [Context in Informational Bias Detection](https://www.aclweb.org/anthology/2020.coling-main.556), van den Berg, Esther  and Markert, Katja, 2020
11. [Comparative Evaluation of Label-Agnostic Selection Bias in Multilingual Hate Speech Datasets](https://www.aclweb.org/anthology/2020.emnlp-main.199), Ousidhoum, Nedjma  and Song, Yangqiu  and Yeung, Dit-Yan, 2020
12. [Detecting and Reducing Bias in a High Stakes Domain](https://www.aclweb.org/anthology/D19-1483), Zhong, Ruiqi  and Chen, Yanda  and Patton, Desmond  and Selous, Charlotte  and McKeown, Kathy, 2019
15. [Measuring the Effects of Bias in Training Data for Literary Classification](https://www.aclweb.org/anthology/2020.latechclfl-1.9), Bagga, Sunyam  and Piper, Andrew, 2020
16. [Unsupervised Discovery of Implicit Gender Bias](https://www.aclweb.org/anthology/2020.emnlp-main.44), Field, Anjalie  and Tsvetkov, Yulia, 2020
17. [Evaluating Debiasing Techniques for Intersectional Biases](https://arxiv.org/abs/2109.10441), Subramanian, Shivashankar and Han, Xudong and Baldwin, Timothy and Cohn, Trevor and Frermann, Lea , EMNLP 2021
18. [Towards Automatic Bias Detection in Knowledge Graphs](https://arxiv.org/abs/2109.10697), Keidar, Daphna and Zhong, Mian and Zhang, Ce and Shrestha, Yash Raj and Paudel, Bibek, EMNLP, 2021
19. [Uncovering Implicit Gender Bias in Narratives through Commonsense Inference](https://arxiv.org/abs/2109.06437), Huang, Tenghao and Brahman, Faeze and Shwartz, Vered and Chaturvedi, Snigdha, EMNLP 2021
17. [Is Your Classifier Actually Biased? Measuring Fairness under Uncertainty with Bernstein Bounds](https://www.aclweb.org/anthology/2020.acl-main.262/), Ethayarajh, Kawin, 2020
29. [Suum Cuique: Studying Bias in Taboo Detection with a Community Perspective](https://arxiv.org/abs/2203.11401). Osama Khalid, Jonathan Rusert, Padmini Srinivasan. ACL 2022 Findings
30. [Your fairness may vary: Pretrained language model fairness in toxic text classification](https://arxiv.org/abs/2108.01250). Ioana Baldini, Dennis Wei, Karthikeyan Natesan Ramamurthy, Mikhail Yurochkin, Moninder Singh. ACL 2022 Findings
31. [Features or Spurious Artifacts? Data-centric Baselines for Fair and Robust Hate Speech Detection](https://aclanthology.org/2022.naacl-main.221.pdf). Alan Ramponi, Sara Tonelli. NAACL 2022
32. [Gender Bias in Masked Language Models for Multiple Languages](https://aclanthology.org/2022.naacl-main.197.pdf). Masahiro Kaneko, Aizhan Imankulova, Danushka Bollegala, Naoaki Okazaki. NAACL 2022
33. [Using Natural Sentence Prompts for Understanding Biases in Language Models](https://arxiv.org/abs/2205.06303). Sarah Alnegheimish, Alicia Guo, Yi Sun. NAACL 2022
34. [Easy Adaptation to Mitigate Gender Bias in Multilingual Text Classification](https://arxiv.org/abs/2204.05459). Xiaolei Huang. NAACL 2022
35. [On Measuring Social Biases in Prompt-Based Multi-Task Learning](https://aclanthology.org/2022.findings-naacl.42.pdf). Afra Feyza Akyürek, Sejin Paik, Muhammed Yusuf Kocyigit, Seda Akbiyik, Şerife Leman Runyun, Derry Wijaya. NAACL 2022 Findings
36. [Unpacking the Interdependent Systems of Discrimination: Ableist Bias in NLP Systems through an Intersectional Lens](https://aclanthology.org/2021.findings-emnlp.267/). Saad Hassan, Matt Huenerfauth, Cecilia Ovesdotter Alm. EMNLP 2021
37. [From Pretraining Data to Language Models to Downstream Tasks: Tracking the Trails of Political Biases Leading to Unfair NLP Models](https://aclanthology.org/2023.acl-long.656/). Shangbin Feng, Chan Young Park, Yuhan Liu, Yulia Tsvetkov. ACL 2023
38. [FairPrism: Evaluating Fairness-Related Harms in Text Generation](https://aclanthology.org/2023.acl-long.343/). Eve Fleisig, Aubrie Amstutz, Chad Atalla, Su Lin Blodgett, Hal Daumé III, Alexandra Olteanu, Emily Sheng, Dan Vann, Hanna Wallach. ACL 2023
39. [MISGENDERED: Limits of Large Language Models in Understanding Pronouns](https://aclanthology.org/2023.acl-long.293/). Tamanna Hossain, Sunipa Dev, Sameer Singh. ACL 2023
40. [Are Fairy Tales Fair? Analyzing Gender Bias in Temporal Narrative Event Chains of Children’s Fairy Tales](https://aclanthology.org/2023.acl-long.359/). Paulina Toro Isaza, Guangxuan Xu, Toye Oloko, Yufang Hou, Nanyun Peng, Dakuo Wang. ACL 2023
41. [Measuring Intersectional Biases in Historical Documents](https://aclanthology.org/2023.findings-acl.170/). Nadav Borenstein, Karolina Stanczak, Thea Rolskov, Natacha Klein Käfer, Natália da Silva Perez, Isabelle Augenstein. ACl 2023 Findings.
42. [This prompt is measuring <mask>: evaluating bias evaluation in language models](https://aclanthology.org/2023.findings-acl.139/). Seraphina Goldfarb-Tarrant, Eddie Ungless, Esma Balkir, Su Lin Blodgett. ACL 2023 Findings
43. [Speaking Multiple Languages Affects the Moral Bias of Language Models](https://aclanthology.org/2023.findings-acl.134/). Katharina Haemmerl, Bjoern Deiseroth, Patrick Schramowski, Jindřich Libovický, Constantin Rothkopf, Alexander Fraser, Kristian Kersting. ACL 2023 Findings
44. [With Prejudice to None: A Few-Shot, Multilingual Transfer Learning Approach to Detect Social Bias in Low Resource Languages](https://aclanthology.org/2023.findings-acl.842/). Nihar Sahoo, Niteesh Mallela, Pushpak Bhattacharyya. ACL 2023 Findings
45. [Run Like a Girl! Sport-Related Gender Bias in Language and Vision](https://aclanthology.org/2023.findings-acl.886/). Sophia Harrison, Eleonora Gualdoni, Gemma Boleda. ACL 2023 Findings
46. [Race, Gender, and Age Biases in Biomedical Masked Language Models](https://aclanthology.org/2023.findings-acl.749/). Michelle Kim, Junghwan Kim, Kristen Johnson. ACL 2023 Findings
47. [Stereotypes and Smut: The (Mis)representation of Non-cisgender Identities by Text-to-Image Models](https://aclanthology.org/2023.findings-acl.502/). Eddie Ungless, Bjorn Ross, Anne Lauscher. ACL 2023 Findings
48. [Towards Procedural Fairness: Uncovering Biases in How a Toxic Language Classifier Uses Sentiment Information](https://aclanthology.org/2022.blackboxnlp-1.18/). Isar Nejadgholi, Esma Balkir, Kathleen Fraser, Svetlana Kiritchenko. EMNLP 2022
49. [“I’m sorry to hear that”: Finding New Biases in Language Models with a Holistic Descriptor Dataset](https://aclanthology.org/2022.emnlp-main.625/). Eric Michael Smith, Melissa Hall, Melanie Kambadur, Eleonora Presani, Adina Williams. EMNLP 2022
50. [Mind Your Bias: A Critical Review of Bias Detection Methods for Contextual Language Models](https://aclanthology.org/2022.findings-emnlp.311/). Silke Husse, Andreas Spitz. EMNLP 2022
51. [Bias Against 93 Stigmatized Groups in Masked Language Models and Downstream Sentiment Classification Tasks](https://dl.acm.org/doi/10.1145/3593013.3594109). Katelyn X. Mei, Sonia Fereidooni, Aylin Caliskan. ACM FAccT 2023
52. [On the Independence of Association Bias and Empirical Fairness in Language Models](https://dl.acm.org/doi/10.1145/3593013.3594004). Laura Cabello, Anna Katrine Jørgensen, Anders Søgaard. ACM FAccT 2023

##### Bias Mitigation
1. [Reducing Gender Bias in Abusive Language Detection](https://www.aclweb.org/anthology/D18-1302), Park, Ji Ho  and Shin, Jamin  and Fung, Pascale, 2018
1. [On Measuring and Mitigating Biased Inferences of Word Embeddings](https://arxiv.org/abs/1908.09369), Dev, Sunipa and Li, Tao  and Phillips, Jeff M  and Srikumar, Vivek, 2019
2. [Debiasing Embeddings for Reduced Gender Bias in Text Classification](https://www.aclweb.org/anthology/W19-3810), Prost, Flavien  and Thain, Nithum  and Bolukbasi, Tolga, 2019
3. [Reducing Gender Bias in Word-Level Language Models with a Gender-Equalizing Loss Function](https://www.aclweb.org/anthology/P19-2031), Qian, Yusu  and Muaz, Urwa  and Zhang, Ben  and Hyun, Jae Won, 2019
4. [Linguistic Models for Analyzing and Detecting Biased Language](https://www.aclweb.org/anthology/P13-1162), Recasens, Marta  and Danescu-Niculescu-Mizil, Cristian  and Jurafsky, Dan, 2013
5. [What's in a Name? Reducing Bias in Bios without Access to Protected Attributes](https://www.aclweb.org/anthology/N19-1424), Romanov, Alexey  and De-Arteaga, Maria  and Wallach, Hanna  and Chayes, Jennifer  and Borgs, Christian  and Chouldechova, Alexandra  and Geyik, Sahin  and Kenthapadi, Krishnaram  and Rumshisky, Anna  and Kalai, Adam, 2019
13. [Demoting Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/2020.socialnlp-1.2), Xia, Mengzhou  and Field, Anjalie  and Tsvetkov, Yulia, 2020
14.  [Balanced Datasets Are Not Enough: Estimating and Mitigating Gender Bias in Deep Image Representations](https://arxiv.org/abs/1811.08489), Wang, Tianlu and Zhao, Jieyu and Yatskar, Mark and Chang, Kai-Wei and Ordonez, Vicente, 2019
15. [Fairness without Demographics through Adversarially Reweighted Learning
](https://arxiv.org/abs/2006.13114), Preethi Lahoti, Alex Beutel, Jilin Chen, Kang Lee, Flavien Prost, Nithum Thain, Xuezhi Wang, Ed H. Chi, 2020.
16. [On Dyadic Fairness: Exploring and Mitigating Bias in Graph Connections](https://openreview.net/pdf?id=xgGS6PmzNq6), Peizhao Li, Yifei Wang, Han Zhao, Pengyu Hong, Hongfu Liu, 2021
17. [Challenges in Automated Debiasing for Toxic Language Detection](https://arxiv.org/abs/2102.00086), Zhou, Xuhui and Sap, Maarten and Swayamdipta, Swabha and Choi, Yejin and Smith, Noah A, 2021
18. [Mitigating Language-Dependent Ethnic Bias in BERT](https://arxiv.org/abs/2109.05704), Ahn, Jaimeen and Oh, Alice, EMNLP, 2021
19. [Sustainable Modular Debiasing of Language Models](https://arxiv.org/abs/2109.03646), Lauscher, Anne and Lüken, Tobias and Glavaš, Goran, EMNLP, 2021
20. [An Empirical Survey of the Effectiveness of Debiasing Techniques for Pre-trained Language Models](https://aclanthology.org/2022.acl-long.132/). Nicholas Meade, Elinor Poole-Dayan, Siva Reddy. ACL 2022
15. [Fair and Argumentative Language Modeling for Computational Argumentation](https://arxiv.org/abs/2204.04026). Carolin Holtermann, Anne Lauscher, Simone Paolo Ponzetto. ACL 2022.
16. [Upstream Mitigation Is Not All You Need: Testing the Bias Transfer Hypothesis in Pre-Trained Language Models](https://aclanthology.org/2022.acl-long.247/). Ryan Steed, Swetasudha Panda, Ari Kobren, Michael Wick. ACL 2022
17. [Mitigating Gender Bias in Distilled Language Models via Counterfactual Role Reversal](https://arxiv.org/abs/2203.12574). Umang Gupta, Jwala Dhamala, Varun Kumar, Apurv Verma, Yada Pruksachatkun, Satyapriya Krishna, Rahul Gupta, Kai-Wei Chang, Greg Ver Steeg, Aram Galstyan. ACL 2022 Findings.
18. [How Gender Debiasing Affects Internal Model Representations, and Why It Matters](https://arxiv.org/abs/2204.06827). Hadas Orgad, Seraphina Goldfarb-Tarrant, Yonatan Belinkov. NAACL 2022
19. [Are Gender-Neutral Queries Really Gender-Neutral? Mitigating Gender Bias in Image Search](https://aclanthology.org/2021.emnlp-main.151/). Jialu Wang, Yang Liu, Xin Wang. EMNLP 2021
20. [Prompt Tuning Pushes Farther, Contrastive Learning Pulls Closer: A Two-Stage Approach to Mitigate Social Biases](https://aclanthology.org/2023.acl-long.797/). Yingji Li, Mengnan Du, Xin Wang, Ying Wang. ACL 2023
21. [Social-Group-Agnostic Bias Mitigation via the Stereotype Content Model](https://aclanthology.org/2023.acl-long.227/). Ali Omrani, Alireza Salkhordeh Ziabari, Charles Yu, Preni Golazizian, Brendan Kennedy, Mohammad Atari, Heng Ji, Morteza Dehghani. ACL 2023
22. [BLIND: Bias Removal With No Demographics](https://aclanthology.org/2023.acl-long.490/). Hadas Orgad, Yonatan Belinkov. ACL 2023
23. [CHBias: Bias Evaluation and Mitigation of Chinese Conversational Language Models](https://aclanthology.org/2023.acl-long.757/). Jiaxu Zhao, Meng Fang, Zijing Shi, Yitong Li, Ling Chen, Mykola Pechenizkiy. ACL 2023
24. [D-CALM: A Dynamic Clustering-based Active Learning Approach for Mitigating Bias](https://aclanthology.org/2023.findings-acl.342/). Sabit Hassan, Malihe Alikhani. ACL 2023 Findings
25. [Debiasing should be Good and Bad: Measuring the Consistency of Debiasing Techniques in Language Models](https://aclanthology.org/2023.findings-acl.280/). Robert Morabito, Jad Kabbara, Ali Emami. ACL 2023 Findings
26. [Gender-tuning: Empowering Fine-tuning for Debiasing Pre-trained Language Models](https://aclanthology.org/2023.findings-acl.336/). Somayeh Ghanbarzadeh, Yan Huang, Hamid Palangi, Radames Cruz Moreno, Hamed Khanpour. ACL 2023 Findings
27. [Bias Beyond English: Counterfactual Tests for Bias in Sentiment Analysis in Four Languages](https://aclanthology.org/2023.findings-acl.272/). Seraphina Goldfarb-Tarrant, Adam Lopez, Roi Blanco, Diego Marcheggiani. ACL 2023 Findings
28. [On Evaluating and Mitigating Gender Biases in Multilingual Settings](https://aclanthology.org/2023.findings-acl.21/). Aniket Vashishtha, Kabir Ahuja, Sunayana Sitaram. ACL 2023 Findings
29. [Perturbation Augmentation for Fairer NLP](https://aclanthology.org/2022.emnlp-main.646/). Rebecca Qian, Candace Ross, Jude Fernandes, Eric Michael Smith, Douwe Kiela, Adina Williams. EMNLP 2022
30. [MABEL: Attenuating Gender Bias using Textual Entailment Data](https://aclanthology.org/2022.emnlp-main.657/). Jacqueline He, Mengzhou Xia, Christiane Fellbaum, Danqi Chen. EMNLP 2022
31. [Balancing out Bias: Achieving Fairness Through Balanced Training](https://aclanthology.org/2022.emnlp-main.779/). Xudong Han, Timothy Baldwin, Trevor Cohn. EMNLP 2022
32. [Debiasing Masks: A New Framework for Shortcut Mitigation in NLU](https://aclanthology.org/2022.emnlp-main.517/). Johannes Mario Meissner, Saku Sugawara, Akiko Aizawa. EMNLP 2022
33. [Don’t Just Clean It, Proxy Clean It: Mitigating Bias by Proxy in Pre-Trained Models](https://aclanthology.org/2022.findings-emnlp.372/). Swetasudha Panda, Ari Kobren, Michael Wick, Qinlan Shen. EMNLP 2022
34. [To Prefer or to Choose? Generating Agency and Power Counterfactuals Jointly for Gender Bias Mitigation](https://aclanthology.org/2022.nlpcss-1.6/). Maja Stahl, Maximilian Spliethöver, Henning Wachsmuth. EMNLP 2022
35. [A Robust Bias Mitigation Procedure Based on the Stereotype Content Model](https://aclanthology.org/2022.nlpcss-1.23/). Eddie Ungless, Amy Rafferty, Hrichika Nag, Björn Ross. EMNLP 2022



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
19. [Measuring and Mitigating Name Biases in Neural Machine Translation](https://aclanthology.org/2022.acl-long.184.pdf). Jun Wang, Benjamin Rubinstein, Trevor Cohn. ACL 2022
20. [GFST: Gender-Filtered Self-Training for More Accurate Gender in Translation](https://aclanthology.org/2021.emnlp-main.123/). Prafulla Kumar Choubey, Anna Currey, Prashant Mathur, Georgiana Dinu. EMNLP 2021
21. [What about “em”? How Commercial Machine Translation Fails to Handle (Neo-)Pronouns](https://aclanthology.org/2023.acl-long.23/). Anne Lauscher, Debora Nozza, Ehm Miltersen, Archie Crowley, Dirk Hovy. ACL 2023
22. [How sensitive are translation systems to extra contexts? Mitigating gender bias in Neural Machine Translation models through relevant contexts.](https://aclanthology.org/2022.findings-emnlp.143/). Shanya Sharma, Manan Dey, Koustuv Sinha. EMNLP 2022

##### Dialogue Generation
1. [Conversational Assistants and Gender Stereotypes: Public Perceptions and Desiderata for Voice Personas](https://www.aclweb.org/anthology/2020.gebnlp-1.7), Cercas Curry, Amanda and Robertson, Judy and Rieser, Verena 2020
1. [Does Gender Matter? Towards Fairness in Dialogue Systems](https://www.aclweb.org/anthology/2020.coling-main.390), Liu, Haochen  and Dacon, Jamell  and Fan, Wenqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [Mitigating Gender Bias for Neural Dialogue Generation with Adversarial Learning](https://www.aclweb.org/anthology/2020.emnlp-main.64), Liu, Haochen  and Wang, Wentao  and Wang, Yiqi  and Liu, Hui  and Liu, Zitao  and Tang, Jiliang, 2020
1. [Queens are Powerful too: Mitigating Gender Bias in Dialogue Generation](https://www.aclweb.org/anthology/2020.emnlp-main.656), Dinan, Emily  and Fan, Angela and Williams, Adina and Urbanek, Jack and Kiela, Douwe and Weston, Jason, 2020
1. [Ethical challenges in data-driven dialogue systems](https://arxiv.org/abs/1711.09050), Henderson, Peter and Sinha, Koustuv and Angelard-Gontier, Nicolas and Ke, Nan Rosemary and Fried, Genevieve and Lowe, Ryan and Pineau, Joelle, 2018
1. ["Nice Try, Kiddo": Ad Hominems in Dialogue Systems](https://arxiv.org/abs/2010.12820), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2020
7. [The Moral Integrity Corpus: A Benchmark for Ethical Dialogue Systems](https://arxiv.org/abs/2204.03021). Caleb Ziems, Jane A. Yu, Yi-Chia Wang, Alon Halevy, Diyi Yang. ACL 2022.
8. [First the Worst: Finding Better Gender Translations During Beam Search](https://aclanthology.org/2022.findings-acl.301/). Danielle Saunders, Rosie Sallis, Bill Byrne. ACL 2022 Findings
9. [Hate Speech and Counter Speech Detection: Conversational Context Does Matter](https://aclanthology.org/2022.naacl-main.433.pdf). Xinchen Yu, Eduardo Blanco, Lingzi Hong. NAACL 2022.

##### Other Generation
1. [Gender-Aware Reinflection using Linguistically Enhanced Neural Models](https://www.aclweb.org/anthology/2020.gebnlp-1.12), Alhafni, Bashar and Habash, Nizar and Bouamor, Houda, 2020
1. [Identifying and Reducing Gender Bias in Word-Level Language Models](https://www.aclweb.org/anthology/N19-3002), Bordia, Shikha  and Bowman, Samuel R., 2019
1. [Investigating African-American Vernacular English in Transformer-Based Text Generation](https://www.aclweb.org/anthology/2020.emnlp-main.473), Groenwold, Sophie and Ou, Lily and Parekh, Aesha and Honnavalli, Samhita and Levy, Sharon and Mirza, Diba and Wang, William Yang, 2020
1. [Automatic Gender Identification and Reinflection in Arabic](https://www.aclweb.org/anthology/W19-3822), Habash, Nizar and Bouamor, Houda and Chung, Christine, 2019
1. [Reducing Sentiment Bias in Language Models via Counterfactual Evaluation](https://www.aclweb.org/anthology/2020.findings-emnlp.7), Huang, Po-Sen  and Zhang, Huan  and Jiang, Ray  and Stanforth, Robert  and Welbl, Johannes  and Rae, Jack  and Maini, Vishal  and Yogatama, Dani  and Kohli, Pushmeet, 2020
2. [PowerTransformer: Unsupervised Controllable Revision for Biased Language Correction](https://www.aclweb.org/anthology/2020.emnlp-main.602), Ma, Xinyao  and Sap, Maarten  and Rashkin, Hannah and Choi, Yejin, 2020
1. [Reducing Non-Normative Text Generation from Language Models](https://www.aclweb.org/anthology/2020.inlg-1.43), Peng, Xiangyu and Li, Siyan and Frazier, Spencer  and Riedl, Mark, 2020
1. [The Woman Worked as a Babysitter: On Biases in Language Generation](https://www.aclweb.org/anthology/D19-1339), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2019
1. [Towards Controllable Biases in Language Generation](https://www.aclweb.org/anthology/2020.findings-emnlp.291), Sheng, Emily and Chang, Kai-Wei and Natarajan, Premkumar and Peng, Nanyun, 2020
2. [RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models](https://www.aclweb.org/anthology/2020.findings-emnlp.301/), Gehman, Sam and Gururangan, Suchin and Sap, Maarten and Choi, Yejin and Smith, Noah A, 2020
3. ["You are grounded!": Latent Name Artifacts in Pre-trained Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.556), Shwartz, Vered and Rudinger, Rachel and Tafjord, Oyvind, 2020
4. [Defining and Evaluating Fair Natural Language Generation](https://www.aclweb.org/anthology/2020.winlp-1.27), Yeo, Catherine  and Chen, Alyssa, 2020
5. [Counterfactual Data Augmentation for Mitigating Gender Stereotypes in Languages with Rich Morphology](https://www.aclweb.org/anthology/P19-1161), Zmigrod, Ran and Mielke, Sabrina J. and Wallach, Hanna and Cotterell, Ryan, 2019
6. [Investigating Gender Bias in Language Models Using Causal Mediation Analysis](https://papers.nips.cc/paper/2020/hash/92650b2e92217715fe312e6fa7b90d82-Abstract.html), Vig, Jesse and Gehrmann, Sebastian and Belinkov, Yonatan and Qian, Sharon and Nevo, Daniel and Singer, Yaron and Shieber, Stuart, 2020
7. [Release strategies and the social impacts of language models](https://arxiv.org/abs/1908.09203), Solaiman, Irene and Brundage, Miles and Clark, Jack and Askell, Amanda and Herbert-Voss, Ariel and Wu, Jeff and Radford, Alec and Krueger, Gretchen and Kim, Jong Wook and Kreps, Sarah and others, 2019
8. [Automatically neutralizing subjective bias in text](https://ojs.aaai.org//index.php/AAAI/article/view/5385), Pryzant, Reid and Martinez, Richard Diehl and Dass, Nathan and Kurohashi, Sadao and Jurafsky, Dan and Yang, Diyi, 2020
9. [Language models are few-shot learners](https://arxiv.org/abs/2005.14165), Brown, Tom B and Mann, Benjamin and Ryder, Nick and Subbiah, Melanie and Kaplan, Jared and Dhariwal, Prafulla and Neelakantan, Arvind and Shyam, Pranav and Sastry, Girish and Askell, Amanda and others, 2020
10. [BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation](https://arxiv.org/abs/2101.11718), Dhamala, Jwala and Sun, Tony and Kumar, Varun and Krishna, Satyapriya and Pruksachatkun, Yada and Chang, Kai-Wei and Gupta, Rahul, 2021
11. [Viable Threat on News Reading: Generating Biased News Using Natural Language Models](https://www.aclweb.org/anthology/2020.nlpcss-1.7), Gupta, Saurabh  and Nguyen, Hong Huy  and Yamagishi, Junichi  and Echizen, Isao, 2020
12. [Investigating Societal Biases in a Poetry Composition System](https://www.aclweb.org/anthology/2020.gebnlp-1.9), Sheng, Emily  and Uthus, David, 2020
13. [De-Biased Court's View Generation with Causality](https://www.aclweb.org/anthology/2020.emnlp-main.56), Wu, Yiquan  and Kuang, Kun  and Zhang, Yating  and Liu, Xiaozhong  and Sun, Changlong  and Xiao, Jun  and Zhuang, Yueting  and Si, Luo  and Wu, Fei, 2020
14. [Detoxifying Language Models Risks Marginalizing Minority Voices](https://arxiv.org/abs/2104.06390), Xu, Albert and Pathak, Eshaan and Wallace, Eric and Gururangan, Suchin, and Sap, Maarten and Klein, Dan, 2021
15. [Detect and Perturb: Neutral Rewriting of Biased and Sensitive Text via Gradient-based Decoding](https://arxiv.org/abs/2109.11708), He, Zexue and Majumder, Bodhisattwa Prasad and McAuley, Julian, EMNLP, 2021
24. [Auto-Debias: Debiasing Masked Language Models with Automated Biased Prompts](https://aclanthology.org/2022.acl-long.72.pdf). Yue Guo, Yi Yang, Ahmed Abbasi. ACL 2022.
25. [A Few Thousand Translations Go a Long Way! Leveraging Pre-trained Models for African News Translation](https://aclanthology.org/2022.naacl-main.223.pdf). David Adelani et. al. NAACL 2022.
26. [Exploiting Biased Models to De-bias Text: A Gender-Fair Rewriting Model](https://aclanthology.org/2023.acl-long.246/). Chantal Amrhein, Florian Schottmann, Rico Sennrich, Samuel Läubli. ACL 2023
27. [Towards Robust NLG Bias Evaluation with Syntactically-diverse Prompts](https://aclanthology.org/2022.findings-emnlp.445/). Arshiya Aggarwal, Jiao Sun, Nanyun Peng. EMNLP 2022
28. [“I’m fully who I am”: Towards Centering Transgender and Non-Binary Voices to Measure Biases in Open Language Generation](https://dl.acm.org/doi/10.1145/3593013.3594078). Anaelia Ovalle, Palash Goyal, Jwala Dhamala, Zachary Jaggers, Kai-Wei Chang, Aram Galstyan, Richard Zemel, Rahul Gupta. ACM FAccT 2023

#### Multi-Modal Setting
##### Bias Detection in Multi-Modal Setting
1. [Studying Bias in GANs through the Lens of Race](https://arxiv.org/abs/2209.02836), Maluleke, Vongani H. and Thakkar, Neerja and Brooks, Tim and Weber, Ethan and Darrell, Trevor and Efros, Alexei A. and Kanazawa, Angjoo and Guillory, Devin, 2022
2. [Imperfect ImaGANation: Implications of GANs Exacerbating Biases on Facial Data Augmentation and Snapchat Selfie Lenses](https://www.semanticscholar.org/paper/Imperfect-ImaGANation%3A-Implications-of-GANs-Biases-Jain-Hernandez/2b15d1a1b354573b3ce23b18991d15c850a8546b), Jain, Niharika and Hernandez, Alberto Olmo and Sengupta, Sailik and Manikonda, Lydia and Kambhampati, S., 2020
3. [DALL-Eval: Probing the Reasoning Skills and Social Biases of Text-to-Image Generation Models](https://arxiv.org/abs/2202.04053), Cho, Jaemin and Zala, Abhay and Bansal, Mohit, 2022
4. [Easily Accessible Text-to-Image Generation Amplifies Demographic Stereotypes at Large Scale](https://arxiv.org/abs/2211.03759), Bianchi, Federico and Kalluri, Pratyusha and Durmus, Esin and Ladhak, Faisal and Cheng, Myra and Nozza, Debora and Hashimoto, Tatsunori and Jurafsky, Dan and Zou, James and Caliskan, Aylin, 2022
5. [Social Biases through the Text-to-Image Generation Lens](https://arxiv.org/abs/2304.06034), Naik, Ranjita and Nushi, Besmira, 2023
6. [T2IAT: Measuring Valence and Stereotypical Biases in Text-to-Image Generation](https://aclanthology.org/2023.findings-acl.160/), Wang, Jialu and Liu, Xinyue and Di, Zonglin and Liu, Yang and Wang, Xin, ACL 2023
7. [The Bias Amplification Paradox in Text-to-Image Generation](https://arxiv.org/abs/2308.00755), Seshadri, Preethi and Singh, Sameer and Elazar, Yanai, 2023
8. [Fair Diffusion: Instructing Text-to-Image Generation Models on Fairness](https://arxiv.org/abs/2302.10893), Friedrich, Felix and Brack, Manuel and Struppek, Lukas and Hintersdorf, Dominik and Schramowski, Patrick and Luccioni, Sasha and Kersting, Kristian, 2023
9. [Uncurated image-text datasets: Shedding light on demographic bias.](https://openaccess.thecvf.com/content/CVPR2023/papers/Garcia_Uncurated_Image-Text_Datasets_Shedding_Light_on_Demographic_Bias_CVPR_2023_paper.pdf), Garcia, Noa and Hirota, Yusuke and Wu, Yankun and Nakashima, Yuta, CVPR 2023
10. [Word-Level Explanations for Analyzing Bias in Text-to-Image Models](https://arxiv.org/abs/2306.05500), Lin, Alexander and Paes, Lucas Monteiro and Tanneru, Sree Harsha and Srinivas, Suraj and Lakkaraju, Himabindu, 2023

##### Bias Mitigation in Multi-Modal Setting
1. [Improving the Fairness of Deep Generative Models without Retraining](https://arxiv.org/abs/2012.04842), Tan, Shuhan and Shen, Yujun and Zhou, Bolei, 2020
2. [RepFair-GAN: Mitigating Representation Bias in GANs Using Gradient Clipping](https://arxiv.org/abs/2207.10653), Kenfack, Patrik Joslin and Sabbagh, Kamil and Rivera, Adín Ramírez and Khan, Adil, 2022
3. [The Bias Amplification Paradox in Text-to-Image Generation](https://arxiv.org/abs/2308.00755), Seshadri, Preethi and Singh, Sameer and Elazar, Yanai, 2023
4. [Fair Diffusion: Instructing Text-to-Image Generation Models on Fairness](https://arxiv.org/abs/2302.10893), Friedrich, Felix and Brack, Manuel and Struppek, Lukas and Hintersdorf, Dominik and Schramowski, Patrick and Luccioni, Sasha and Kersting, Kristian, 2023

#### Bias Visualization
1. [Fairsight: Visual analytics for fairness in decision making](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8805420), Ahn, Yongsu and Lin, Yuru, 2019
1. [FairVis: Visual Analytics for Discovering Intersectional Bias in Machine Learning](https://arxiv.org/pdf/1904.05419.pdf), Cabrera, Ángel Alexander and Epperson, Will and Hohman, Fred and Kahng, Minsuk and Morgenstern, Jamie and Chau, Duen Horng, 2021
2. [VERB: Visualizing and Interpreting Bias Mitigation Techniques for Word Representations](https://arxiv.org/pdf/2104.02797.pdf), Archit Rathore, Archit and Dev, Sunipa and Phillips, Jeff M. and Srikumar, Vivek and Zheng, Yan and Yeh, Chin-Chia Michael and Wang, Junpeng and Zhang, Wei and Wang, Bei, 2021
3. [DebIE: A Platform for Implicit and Explicit Debiasing of Word Embedding Spaces](https://arxiv.org/abs/2103.06598), Friedrich, Niklas and Lauscher, Anne and Ponzetto, Simone Paolo and  Glavaš, Goran, 2021


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
1. [Analyzing Biases in Human Perception of User Age and Gender from Text](https://www.aclweb.org/anthology/P16-1080), Flekova, Lucie  and Carpenter, Jordan  and Giorgi, Salvatore  and Ungar, Lyle  and Preoţiuc-Pietro, Daniel, 2016
1. [Reference Bias in Monolingual Machine Translation Evaluation](https://www.aclweb.org/anthology/P16-2013), Fomicheva, Marina  and Specia, Lucia, 2016
1. [Analyzing Gender Bias within Narrative Tropes](https://www.aclweb.org/anthology/2020.nlpcss-1.23), Gala, Dhruvil  and Khursheed, Mohammad Omar  and Lerner, Hannah  and O'Connor, Brendan  and Iyyer, Mohit, 2020
1. [Detecting Political Bias in News Articles Using Headline Attention](https://www.aclweb.org/anthology/W19-4809), Gangula, Rama Rohit Reddy  and Duggenpudi, Suma Reddy  and Mamidi, Radhika, 2019
2. [Detecting Independent Pronoun Bias with Partially-Synthetic Data Generation](https://www.aclweb.org/anthology/2020.emnlp-main.157), Munro, Robert  and Morrison, Alex (Carmen), 2020
5. [Analyzing Gender Bias in Student Evaluations](https://www.aclweb.org/anthology/C16-1083), Terkik, Andamlak  and Prud{'}hommeaux, Emily  and Ovesdotter Alm, Cecilia  and Homan, Christopher  and Franklin, Scott, 2016
30. [Ethics Sheets for AI Tasks](https://arxiv.org/pdf/2107.01183.pdf). Saif M. Mohammad. ACL 2022
31. [VALUE: Understanding Dialect Disparity in NLU](https://arxiv.org/abs/2204.03031).Caleb Ziems, Jiaao Chen, Camille Harris, Jessica Anderson, Diyi Yang. ACL 2022.
32. [Annotators with Attitudes: How Annotator Beliefs And Identities Bias Toxic Language Detection](https://www.semanticscholar.org/paper/Annotators-with-Attitudes%3A-How-Annotator-Beliefs-Sap-Swayamdipta/cf3cfb90a6d8c431dc8a7f115b011d5ffbb439ee). Maarten Sap, Swabha Swayamdipta, Laura Vianna, Xuhui Zhou, Yejin Choi, Noah Smith. NAACL 2022
33. [Multi-VALUE: A Framework for Cross-Dialectal English NLP](https://aclanthology.org/2023.acl-long.44/). Caleb Ziems, William Held, Jingfeng Yang, Jwala Dhamala, Rahul Gupta, Diyi Yang. ACL 2023
34. [Trade-Offs Between Fairness and Privacy in Language Modeling](https://aclanthology.org/2023.findings-acl.434/). Cleo Matzken, Steffen Eger, Ivan Habernal. ACL 2023 Findings
35. [Bridging Fairness and Environmental Sustainability in Natural Language Processing](https://aclanthology.org/2022.emnlp-main.533/). Marius Hessenthaler, Emma Strubell, Dirk Hovy, Anne Lauscher. EMNLP 2022
36. [Fair NLP Models with Differentially Private Text Encoders](https://aclanthology.org/2022.findings-emnlp.514/). Gaurav Maheshwari, Pascal Denis, Mikaela Keller, Aurélien Bellet. EMNLP 2022
37. [Should We Ban English NLP for a Year?](https://aclanthology.org/2022.emnlp-main.351/). Anders Søgaard. EMNLP 2022
38. [Controlling Bias Exposure for Fair Interpretable Predictions](https://aclanthology.org/2022.findings-emnlp.431/). Zexue He, Yu Wang, Julian McAuley, Bodhisattwa Prasad Majumder. EMNLP 2022 


### Tutorial List
- [Fairness in Machine Learning](https://nips.cc/Conferences/2017/Schedule?showEvent=8734), NeurIPS 2017
- [The Trouble with Bias](https://www.youtube.com/watch?v=fMym_BKWQzk), NeurIPS 2017
- [Socially Responsible NLP](https://www.aclweb.org/anthology/N18-6005/), NAACL 2018
- [Tutorial: Bias and Fairness in Natural Language Processing](http://web.cs.ucla.edu/~kwchang/talks/emnlp19-fairnlp/), EMNLP 2019
- [Fairness-Aware Machine Learning: Practical Challenges and Lessons Learned](https://sites.google.com/view/kdd19-fairness-tutorial), KDD 2019
- [Dealing with Bias and Fairness in Building Data Science/ML/AI Systems](https://dssg.github.io/fairness_tutorial/), KDD 2020
- [A Visual Tour of Bias Mitigation Techniques for Word Representations](http://www.sci.utah.edu/~beiwang/aaaibias2021/index.html), AAAI 2021
- [How to test the fairness of ML models? The 80% rule to measure the disparate impact](https://www.giskard.ai/knowledge/how-to-test-ml-models-5-the-80-rule-to-measure-disparity), Giskard 2023

#### Jupyter/Colab Tutorial
- [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://github.com/uclanlp/reducingbias/blob/master/src/fairCRF_gender_ratio.ipynb)
- [Mitigating Gender Bias Ampliﬁcation in Distribution by Posterior Regularization](https://colab.research.google.com/drive/1jBhnzxaaHMY1jbPPa1OqT8-6QxZA_T7p?authuser=2#scrollTo=YpNJrP3uBMd3)

### Conference/Workshop List
- [Ethics in NLP](https://aclweb.org/aclwiki/Ethics_in_NLP), ACL Wiki
- [ACM FAccT conference](https://fatconference.org/)
- [Gendered Ambiguous Pronoun (GAP) Shared Task at the Gender Bias in NLP Workshop 2019](https://www.aclweb.org/anthology/W19-3801), Webster, Kellie  and Costa-jussa, Marta R.  and Hardmeier, Christian  and Radford, Will, 2019
- [Proceedings of the First Workshop on Gender Bias in Natural Language Processing](https://www.aclweb.org/anthology/W19-3800), Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will  and Webster, Kellie, 2019
- [Proceedings of the Second Workshop on Gender Bias in Natural Language Proceedings](https://www.aclweb.org/anthology/2020.gebnlp-1.0/), Costa-juss{\`a}, Marta R.  and Hardmeier, Christian  and Radford, Will  and Webster, Kellie, 2020
- [Team Kermit-the-frog at SemEval-2019 Task 4: Bias Detection Through Sentiment Analysis and Simple Linguistic Features](https://www.aclweb.org/anthology/S19-2177), Anthonio, Talita  and Kloppenburg, Lennart, 2019
- [Fairness and machine learning](https://fairmlbook.org/index.html)
