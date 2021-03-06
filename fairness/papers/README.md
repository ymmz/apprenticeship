# Awesome Fairness Papers

A curated list of awesome fairness papers.

## Contents

- [Survey](#survey)
- [Statistical Fairness](#statistical-fairness)
    - [Demographic Parity](#demographic-parity)
    - [Equalized Odds](#equalized-odds)
- [Causal Fairness](#causal-fairness)
    - [Counterfactual Fairness](#counterfactual-fairness)
- [Resource Allocation](#resource-allocation)
- [Others](#others)
    - [Stability](#stability)


**Legend**:

| :ledger: | :memo: | :keyboard: | :camera: | :floppy_disk: |
| :-: | :-: |  :-: |  :-: |  :-: | 
| PDF<br>Files | Notes | Code | Slides | Other<br>Supplementaries |

---

## Survey

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | A Survey on Bias and Fairness in Machine Learning | Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, Aram Galstyan | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1908.09635) | | |
| | The Frontiers of Fairness in Machine Learning | Alexandra Chouldechova, Aaron Roth | CoRR | 2018 | [:ledger:](https://arxiv.org/pdf/1810.08810.pdf) | | |

[:top:](#contents)

## Statistical Fairness

#### Demographic Parity

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| CFair | Conditional Learning of Fair Representations | Han Zhao, Amanda Coston, Tameem Adel, Geoffrey J. Gordon | ICLR | 2020 | [:ledger:](https://openreview.net/pdf?id=Hkekl0NFPr) | [:memo:](https://mp.weixin.qq.com/s/ig6jSvcW4_91FehlfN-O7A) | [:memo:](https://openreview.net/forum?id=Hkekl0NFPr) | 
| AdvDebias | Inherent Tradeoffs in Learning Fair Representations | Han Zhao, Geoffrey J. Gordon | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9698-inherent-tradeoffs-in-learning-fair-representations.pdf) | [:memo:](https://mp.weixin.qq.com/s/d1PJNo6ObkUtUfAPr3gSeg) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/9114-metareview.html)[:camera:](https://www.cs.cmu.edu/~hzhao1/papers/NIPS2019/fairness_poster.pdf)[:camera:](https://www.cs.cmu.edu/~hzhao1/papers/NIPS2019/fairness_slides.pdf)[:keyboard:](http://papers.nips.cc/paper/9698-inherent-tradeoffs-in-learning-fair-representations-supplemental.zip) |
| Random Repair | Obtaining Fairness using Optimal Transport Theory | Paula Gordaliza, Eustasio del Barrio, Fabrice Gamboa, Jean-Michel Loubes | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/gordaliza19a/gordaliza19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/gordaliza19a/gordaliza19a-supp.pdf)[:keyboard:](https://github.com/JMLToulouse/FairLearning)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-12-00-4857-obtaining_fairn.pdf) |
| FFVAE | Flexibly Fair Representation Learning by Disentanglement | Elliot Creager, David Madras, Jörn-Henrik Jacobsen, Marissa A. Weis, Kevin Swersky, Toniann Pitassi, Richard S. Zemel | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/creager19a/creager19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/creager19a/creager19a-supp.pdf)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-25-4853-flexibly_fair_r.pdf) |
| Fair Regression | Fair Regression: Quantitative Definitions and Reduction-Based Algorithms | Alekh Agarwal, Miroslav Dudík, Zhiwei Steven Wu | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/agarwal19d/agarwal19d.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/agarwal19d/agarwal19d-supp.pdf)[:keyboard:](https://github.com/steven7woo/fair_regression)[:keyboard:](https://github.com/fairlearn/fairlearn)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-30-4854-fair_regression.pdf) |
| Strong Demographic Parity | Wasserstein Fair Classification | Ray Jiang, Aldo Pacchiano, Tom Stepleton, Heinrich Jiang, Silvia Chiappa | UAI | 2019 | [:ledger:](http://auai.org/uai2019/proceedings/papers/315.pdf) | | [:ledger:](http://auai.org/uai2019/proceedings/supplements/315_supplement.pdf)[:keyboard:](https://github.com/deepmind/wasserstein_fairness) |
| | Exploring Human Gender Stereotypes with Word Association Test | Yupei Du, Yuanbin Wu, Man Lan | EMNLP | 2019 | [:ledger:](https://yupei-du.github.io/papers/graph-bias.pdf) | | [:keyboard:](https://github.com/Yupei-Du/bias-in-wat) |

[:top:](#contents)

#### Equalized Odds

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Pairwise Fairness | Fairness in Recommendation Ranking through Pairwise Comparisons | Alex Beutel, Jilin Chen, Tulsee Doshi, Hai Qian, Li Wei, Yi Wu, Lukasz Heldt, Zhe Zhao, Lichan Hong, Ed H. Chi, Cristos Goodrow | KDD | 2019 | [:ledger:](https://dl.acm.org/citation.cfm?doid=3292500.3330745) | [:memo:](https://mp.weixin.qq.com/s/QJeOBXG6sIGb6ML6v8T8CQ) | [:camera:](https://www.kdd.org/kdd2019/accepted-papers/view/fairness-in-recommendation-ranking-through-pairwise-comparisons) |
| DP-postprocessing<br>DP-oracle-learner | Differentially Private Fair Learning | Matthew Jagielski, Michael J. Kearns, Jieming Mao, Alina Oprea, Aaron Roth, Saeed Sharifi-Malvajerdi, Jonathan Ullman | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/jagielski19a/jagielski19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/jagielski19a/jagielski19a-supp.pdf)[:camera:](https://slideslive.com/38916902/fairness?t=2645) |
| AVD Penalizers<br>SD Penalizers | Penalizing Unfairness in Binary Classification | Yahav Bechavod, Katrina Ligett | CoRR | 2017 | [:ledger:](https://arxiv.org/abs/1707.00044) | | [:keyboard:](https://github.com/jjgold012/lab-project-fairness) |
| Equalized Odds | Equality of Opportunity in Supervised Learning | Moritz Hardt, Eric Price, Nati Srebro | NIPS | 2016 | [:ledger:](http://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning) | | [:ledger:](https://arxiv.org/abs/1610.02413)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips29/reviews/1654.html) |

[:top:](#contents)

## Causal Fairness

#### Counterfactual Fairness

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Counterfactual Privilege | Making Decisions that Reduce Discriminatory Impacts | 	Matt J. Kusner, Chris Russell, Joshua R. Loftus, Ricardo Silva | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/kusner19a/kusner19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/kusner19a/kusner19a-supp.pdf)[:keyboard:](https://github.com/mkusner/reducing_discriminatory_impact)<br>[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-12-15-4860-making_decision.pdf)[:camera:](https://www.dropbox.com/s/p2pnf5uiurd699d/MDRDI_2019.pdf) |
| Fair K<br>Fair Add | Counterfactual Fairness | Matt J. Kusner, Joshua R. Loftus, Chris Russell, Ricardo Silva | NIPS | 2017 | [:ledger:](http://papers.nips.cc/paper/6995-counterfactual-fairness) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/2152.html) | [:ledger:](http://papers.nips.cc/paper/6995-counterfactual-fairness-supplemental.zip)[:keyboard:](https://github.com/mkusner/counterfactual-fairness)[:camera:](http://mkusner.github.io/posters/CF_Poster.pdf)[:camera:](https://www.facebook.com/nipsfoundation/videos/1554741734617060/) |
| Multi-World Fairness | When Worlds Collide: Integrating Different Counterfactual Assumptions in Fairness | Chris Russell, Matt J. Kusner, Joshua R. Loftus, Ricardo Silva | NIPS | 2017 | [:ledger:](http://papers.nips.cc/paper/7220-when-worlds-collide-integrating-different-counterfactual-assumptions-in-fairness) | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/3209.html) | [:camera:](https://drive.google.com/file/d/1YWV5PIzjNyapVvI5gUsKFcUttzEkcVt-/view) |

[:top:](#contents)

## Resource Allocation

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| | Fair decision making using privacy-protected data | David Pujol, Ryan McKenna, Satya Kuppam, Michael Hay, Ashwin Machanavajjhala, Gerome Miklau | FAT* | 2020 | [:ledger:](https://dl.acm.org/doi/abs/10.1145/3351095.3372872) | | [:camera:](https://www.youtube.com/watch?v=ZsG7OA0sG6I&list=PLXA0IWa3BpHkaM6uJauBdtkR3Hp4rePfp&index=53)[:camera:](https://slideslive.com/38923327/invited-talk-fair-decision-making-using-privacyprotected-data) |
| FEN | Learning Fairness in Multi-Agent Systems | Jiechuan Jiang, Zongqing Lu | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9537-learning-fairness-in-multi-agent-systems.pdf) | | [:ledger:](http://papers.nips.cc/paper/9537-learning-fairness-in-multi-agent-systems-supplemental.zip)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/7755-metareview.html)[:keyboard:](https://github.com/PKU-AI-Edge/FEN) |
| | Differential Privacy Has Disparate Impact on Model Accuracy | Eugene Bagdasaryan, Omid Poursaeed, Vitaly Shmatikov | NeurIPS | 2019 | [:ledger:](http://papers.nips.cc/paper/9681-differential-privacy-has-disparate-impact-on-model-accuracy.pdf) | | [:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969.html)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969-AuthorFeedback.pdf)[:memo:](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/8969-metareview.html)[:camera:](https://github.com/ebagdasa/differential-privacy-vs-fairness/blob/master/poster/neurips_diffprivacy_fairness.pdf)[:keyboard:](https://github.com/ebagdasa/differential-privacy-vs-fairness) |
| DC<br>Maximin | Group-Fairness in Influence Maximization | Alan Tsang, Bryan Wilder, Eric Rice, Milind Tambe, Yair Zick | IJCAI | 2019 | [:ledger:](https://www.ijcai.org/Proceedings/2019/831) | | [:memo:](https://arxiv.org/abs/1903.00967)[:keyboard:](https://github.com/bwilder0/fair_influmax_code_release) |
| TREE01 | Fairness without Harm: Decoupled Classifiers with Preference Guarantees | Berk Ustun, Yang Liu, David C. Parkes | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/ustun19a/ustun19a.pdf) | | [:ledger:](http://proceedings.mlr.press/v97/ustun19a/ustun19a-supp.pdf)[:keyboard:](https://github.com/ustunb/dcptree)[:camera:](https://icml.cc/media/Slides/icml/2019/seasideball(13-11-00)-13-11-35-4855-fairness_withou.pdf) |
| Greedy Capture<br>Local Capture | Proportionally Fair Clustering | Xingyu Chen, Brandon Fain, Liang Lyu, Kamesh Munagala | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/chen19d.html) | | [:memo:](https://arxiv.org/abs/1905.03674)[:keyboard:](https://github.com/DukeXY/Proportionally-Fair-Clustering)[:camera:](https://slideslive.com/38917643/fairness) |
| GF1A/B | Group Fairness for the Allocation of Indivisible Goods | Vincent Conitzer, Rupert Freeman, Nisarg Shah, Jennifer Wortman Vaughan | AAAI | 2019 | [:ledger:](https://www.aaai.org/ojs/index.php/AAAI/article/view/4010) | | [:memo:](https://users.cs.duke.edu/~conitzer/group-fairness-full.pdf) |
| FULTR | Fair Learning-to-Rank from Implicit Feedback | Himank Yadav, Zhengxiao Du, Thorsten Joachims | CoRR | 2019 | [:ledger:](https://arxiv.org/abs/1911.08054) | | |

[:top:](#contents)

## Others

#### Stability

| | Title | Authors | Published in | Year | Files | Notes | Supplementaries |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Stable-Fair | Stable and Fair Classification | Lingxiao Huang, Nisheeth K. Vishnoi | ICML | 2019 | [:ledger:](http://proceedings.mlr.press/v97/huang19e.html) | | [:memo:](http://proceedings.mlr.press/v97/huang19e.html) |

[:top:](#contents)
