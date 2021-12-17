# Hej hallå!

Welcome to my Github ✨
Currently, I'm pursuing a masters degree in Financial Mathematics at KTH in Stockholm, Sweden. My B.Sc was in Applied Mathematics and Industrial Economics, also at KTH - I was on an exchange to ETH Zürich where I studied risk mathematics among other things, and I was a visiting student at the University of Nairobi during my last semester. 

I mostly operate in private repos, but some are available to the public (_or somewhat available_ 🍳)  Reason for this is that the lion part of my work involve Topological Data Analysis where I use licensed libraries. 

## [Feasability prediction](https://github.com/KodAgge/Feasibility-Prediction)
📊 Working together with a fintech firm and three classmates we looked into the possibility of using Machine Learning to speed up their operations. The team within the firm we were working with had one main task: solving a constrained non-linear optimization problem using an evolutionary optimization algorithm called CMA-ES. However, there was one problem, deciding upon the feasibility of the solutions the algorithm suggested was computationally heavy. Our task was thus to see if Machine Learning could be used to filter out infeasible solutions. We took an explorative approach, testing a wide range of Machine Learning algorithms, supervised as well as unsupervised. Unfortunetaly, not method yielded useful results. We thinks this is mainly due to the evolutionary algorithm advancing towards the optimum in iterational steps through the large feature space (~4000 dimensions), which means that the classifiers needs to extrapolate.

Below follows a gif of how the CMA-ES moves during its first 100 iterations, projected down to 3 dimensions using PCA.
![](https://github.com/KodAgge/Feasibility-Prediction/blob/master/code/plots/3dscatter.gif)

## [Barcoding Nairobi](https://github.com/EricBojs/Barcoding-Nairobi)
⚡ My most interesting work is in the field of **Topological Data Analysis**.
My B.Sc thesis in Applied Mathematics was done at the University of Nairobi and Uber Technologies in Kenya. The code is yet to be published, but you can find the thesis [here](https://www.diva-portal.org/smash/record.jsf?dswid=-6769&faces-redirect=true&language=en&searchType=SIMPLE&query=bojs&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&pid=diva2%3A1450295&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=all) and a my presentation at the African Math Seminar 2020 [here](https://www.youtube.com/watch?v=dwxhMm9wtOY).

![Figures from B.Sc Thesis Project "Barcoding Nairobi"](https://github.com/EricBojs/Barcoding-Nairobi/blob/master/Plots/Figure_5-3.png?raw=true "Barcoding Nairobi")


## [Osäker osäkerhet](https://github.com/EricBojs/Osaker-osakerhet)
📈 You'll also find a project on financial modelling using Python. The project is in the form of a workbook using Colab/Jupyter Notebook teaching the reader how to download financial data, model financial claims and calculating volatilities (implied and historical). Unfortunely (?), it is only available for the Swedish speaker...

<img src="https://github.com/EricBojs/Osaker-osakerhet/blob/master/Plots/Figure.png?raw=true" width="500">
