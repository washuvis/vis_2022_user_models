# A Unified Comparison of User Modeling Techniques for Data Interaction Prediction and Exploration Bias
<b>Sunwoo Ha, Shayan Monadjemi, Roman Garnett, and Alvitta Ottley</b>

This repository contains the standardized implementations of all 7 user modeling algorithms, along with the ensemble method, the user study data sets and corresponding interaction logs, and analysis scripts for "A Unified Comparison of User Modeling Techniques for Next Interaction Predicition and Exploration Bias."

## Abstract
The visual analytics community has proposed several user modeling algorithms to capture and analyze users' interaction behavior in order to assist users in data exploration and insight generation. For example, some can detect exploration biases while others can predict data points that the user will interact with before that interaction occurs. Researchers believe this collection of algorithms can help create more intelligent visual analytics tools. However, the community lacks a rigorous evaluation and comparison of the existing techniques. As a result, there is limited guidance on which method to use and when. Our paper seeks to fill in this missing gap by comparing and ranking eight (seven previously proposed, and one ensemble) user modeling algorithms based on their performance on a diverse set of four user study datasets. We analyze exploration bias detection, data interaction prediction, and algorithmic complexity, among other measures. Based on our findings, we highlight open challenges and new directions for analyzing user interactions and visualization provenance.

## Selected User Modeling Techniques 
- [Gotz, D., Sun, S., Cao, N., Kundu, R., & Meyer, A. (2017). Adaptive Contextualization Methods for Combating Selection Bias During High-Dimensional Visualization. ACM TiiS (Vol. 7, Issue 4, No. 17, pp. 1-23.](https://vaclab.unc.edu/publication/tiis_2017_gotz/tiis_2017_gotz.pdf)
- [Healey, C. G. & Dennis, B. M. (2012). Interest Driven Navigation in Visualization. IEEE Transactions on Visualization and Computer Graphics (Vol. 18, No. 10, pp.1744–1756).](https://www.csc2.ncsu.edu/faculty/healey/download/tvcg.12b.pdf)
- [Monadjemi, S., Garnett, R., & Ottley, A. (2020). Competing Models: Inferring Exploration Patterns and Information Relevance via Bayesian Model Selection. IEEE Transactions on Visualization and Computer Graphics, 27(2), 412-421.](http://visualdata.wustl.edu/files/CompetingModels.pdf)
- [Monadjemi, S., Nguyen, Q., Chai H., Garnett, R., & Ottley, A. (2020) Active Visual Analytics: Assisted Data Discovery in Interactive Visualizations via Active Search. arXiv preprint arXiv:2010.08155.](https://arxiv.org/pdf/2010.08155.pdf)
- [Ottley, A., Garnett, R., & Wan, R. (2019). Follow the clicks: Learning and anticipating mouse interactions during exploratory data analysis. In Computer Graphics Forum (Vol. 38, No. 3, pp. 41-52).](http://visualdata.wustl.edu/files/predicting-clicks.pdf)
- [Wall, E., Blaha, L. M., Franklin, L., & Endert, A. (2017). Warning, bias may occur: A proposed approach to detecting cognitive bias in interactive visual analytics. In 2017 IEEE Conference on Visual Analytics Science and Technology (VAST) (pp. 104-115).](https://emilywall.github.io/media/papers/BiasVAST17.pdf)
- [Zhou, Z., Wen, X., Wang, Y., & Gotz, D. (2021). Modeling and Leveraging Analytic Focus During Exploratory Visual Analysis. In Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems (pp. 1-15).](https://vaclab.unc.edu/publication/chi_2021_zhou/chi_2021_zhou.pdf)

## Directory Overview
The following provides an overview of the directories in this repository.

### data
- Contains the full user study datasets along with the corresponding user interaction logs.
### implementation 
- Contains all implementations of selected user modeling techniques as well as the script for the ensemble method.
### notebooks
- Contains Jupyter Notebook files for setting up the analyses and evaluating the techniques.
### output
- Contains the outputs from evaluations as well as the figures included in the paper.
### related_work_coding.pdf
- PDF containing all manuscripts reviewed for this paper.
