# SG2. Multilayers/ML & methods list

A curated list of awesome places to learn and practice machine learning and graph-based methods presented at the SG2 meetings

Please refer to the [contribution guidelines](https://github.com/orgs/bsc-life/teams/sg2-multilayers-ml-methods/discussions/1) when preparing your presentation.

## Meetings calendar

*Scheduled presentations. In case of changes, please update and notify valenciaslab@bsc.es*

| Date  | Presenter |
| ------------- | ------------- |
|18.11.2020 | Davide Cirillo |
|02.12.2020 | Iker Núñez |
|16.12.2020 | Núria Olvera |
|29.01.2021 | open discussion |
|24.02.2021 | Hugo Bronchalo |
|10.03.2021 | François Serra |
|24.03.2021 | Carlos Madariaga |
|07.04.2021 | Alejandro Tejada |
|21.04.2021 | Davide Cirillo |

## Methods

*Implementations and presentations of machine learning and graph-based methods*

* **GenOtype PHenotype ExplOrer (GOPHER)** - Statistical inference of associations between HPO and GO terms
    * paper: [Josep-Fabregó et al. 2020](https://link.springer.com/chapter/10.1007%2F978-3-030-59851-8_13)
    * repository: [GitLab](https://pm.bsc.es/gitlab/applications/gopher)
    * presentation: [18.11.2020](https://docs.google.com/presentation/d/1lE_FVOevaqxiKE5vQut1t2mMn7JIEF5Eox3JBpijbqw/edit?usp=sharing)
    * example: [Running GOPHER on MareNostrum](https://github.com/cirillodavide/gopher_usecase/blob/master/example_run.md)

* **Network Enrichment Analysis Test (NEAT)** - Apply enrichment analysis with a network of reference
    * paper: [Signorelli et al. 2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1203-6)
    * repository: [CRAN](https://cran.r-project.org/web/packages/neat/index.html)
    * presentation: [02.12.2020](https://docs.google.com/presentation/d/14CN7aguiQFr8ac26FwVpLY43_uQFWt9fiMIGxOfc3c0/edit?usp=sharing)
    * example: [Running NEAT](https://github.com/ikernunezca/neat_use_case)
    
 * **Extreme Model Exploration With Swift (EMEWS)** - Model exploration framework for HPC facilities
    * paper: [Ozik et al. 2017](https://pubmed.ncbi.nlm.nih.gov/30577742/)
    * repository: [GIT](https://emews.github.io/)
    * presentation: [14.12.2020](https://docs.google.com/presentation/d/1yk4PQNwwn5f8I3z-FnKmWgSWW46aTufCv3NdLzI01sQ/edit?usp=sharing)
    * example: [Improving Hit-and-Run on a tumour simulation](https://github.com/JaninaSchreiber/TNF)
    
* **Similarity Network Fusion (SNF)** - Integrate multiple data types on the basis of similarity between biological samples
    * paper: [B Wang et al. 2014](https://www.nature.com/articles/nmeth.2810)
    * repository: [CRAN](https://cran.r-project.org/web/packages/SNFtool/index.html)
    * presentation: [16.12.2020](https://docs.google.com/presentation/d/1SFAcIR80CjCzDCMnfUXeAMDKXCCdevSqDtsB3JZX03s/edit?usp=sharing)
    * example: [Running SNF](https://github.com/nuria17/COPDHeterogeneity/tree/master/SNF)

* **SUPPA2** - Fast, accurate, and uncertainty-aware differential splicing analysis across multiple conditions
    * paper: [Trincado et al. 2018](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1417-1)
    * repository: [GIT SUPPA2](https://github.com/comprna/SUPPA) [GIT Salmon](https://github.com/COMBINE-lab/salmon/blob/master/doc/source/salmon.rst)
    * presentation: [24.02.2021](https://docs.google.com/presentation/d/1Xqm46Mj0CMc07TPTViqN3RhSHa9zJsNWYayK2P9nkSU/edit#slide=id.gc093395255_0_0)
    * example: [Running SUPPA2](https://github.com/vollutto/Scripts-SUPPA)
  
## Suggestions

*Methods that would be nice to be presented during our meetings*

* [Similarity Network Fusion (SNF)](http://compbio.cs.toronto.edu/SNF/SNF/Software.html)
* [Random Walk with Restart (RWR) in multilayer networks](https://academic.oup.com/bioinformatics/article/35/3/497/5055408)
* Matrix factorization methods (Singular Value decomposition (SVD), Non-Negative Matrix Factorization (NNMF), etc.)
* [COSIFER](https://sysbio.uk-south.containers.mybluemix.net/cosifer/) - network inference
* [Graphlets in multilayer networks](https://www.nature.com/articles/s41598-020-57609-3)
* [Drugs2ways](https://journals.plos.org/ploscompbiol/article?id=10.1371%2Fjournal.pcbi.1008464)
* [Persistence Homology](https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0179-3) - recommended tool: [Ripser](https://pypi.org/project/ripser/)
* [ROMA](https://pubmed.ncbi.nlm.nih.gov/26925094/) - gene activity quantification
* [Datashader](https://datashader.org/) - big data visualization
* [MCL](https://micans.org/mcl/) - Markov cluster algorithm

## External resources

### General and didactic platforms

* [Stateoftheart AI](https://www.stateoftheart.ai/)

### Deep learning frameworks tutorials
* [Keras](https://keras.io/guides/)
* [Pytorch](https://pytorch.org/tutorials/)

### Books
* [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) - Mohri, Rostamizadeh, Talwalkar. 2018 (Free)
* [Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) - Shalev-Shwartz, Ben-David. 2014 (Free)
* [Deep learning](https://www.deeplearningbook.org/) - Goodfellow, Bangio, Courville. 2016 (Free)
* [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.es/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646) - Géron. 2019 (Amazon)
* [Deep Learning for Coders with fastai and PyTorch](https://www.amazon.es/Deep-Learning-Coders-Fastai-Pytorch/dp/1492045527) - Howard, Gugger. 2020 (Amazon)

### Awesome YT videos
* [Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) - 3Blue1Brown
* [Graph Theory](https://www.youtube.com/playlist?list=PLt5AfwLFPxWIO0rkWl44MhS_PLLqu3Kvr) - Numberphile

### Online courses
 * [Machine learning in Python](https://www.coursera.org/learn/python-machine-learning) - Coursera (very complete including regression, clustering and evaluation, predictive models... All in python using scipy and scikit-learn)
