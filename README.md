# d4d-predicting-poverty

**Slack Channel:** [#p-predicting_poverty](https://datafordemocracy.slack.com/messages/p-predicting_poverty/)

**Project Description:** Poverty prediction based on [research](http://nealjean.com/papers/science_main.pdf) out of Stanford University. The key idea is to predict poverty at a fine grained level using machhine learning techniques(deep learning) and more specifically [Transfer Learning](https://en.wikipedia.org/wiki/Transfer_learning).
The current focus is on replicating results from the paper. I have begun work on predicting poverty in the country of Rwanda and the extremely general steps for doing so are as follows:

1. Downloading the survey data from the [Demographic and Health Surveys](https://dhsprogram.com/data/dataset_admin/login_main.cfm;jsessionid=57B252B2AECF34A9251427957CFDD048.cfusion?CFID=7550754&CFTOKEN=720e64caa1dfcfe0-ABC31E34-B134-C572-3E56D51A580251FD) website. (There is an element of requesting the data from the source, and as a result you will have to sign up to the website and then request demographic data for Rwanda.
2. Downloading night light satellite imagery from NOAA.
3. Downloading satellite imagery via google maps static API.
4. Moving downloaded satellite imagery to corresponding night light values folders.
5. Extracting features of day time satellite imagery to predict night time light intensity using deep learning.
6. Replicating the results of the Stanford research (Performing ridge regression to estimate wealth).
8. Constructing high resolution maps of predicted data.

The immediate aim of the project is to replicate the results and create a scalable pipeline that can be applied to various other coutries, because extracting image features in different countries will likely yield a very different feature spaces which may not be applicable globally.

-[@chrikeli](https://datafordemocracy.slack.com/messages/@chrikeli/)

** Maintainers **
- [chrikeli](https://datafordemocracy.slack.com/messages/@chrikeli/)
- [YOU]

## Taking volunteers for creating a data ingestion pipeline

Deep Learning Stuff:
- [chrikeli](https://datafordemocracy.slack.com/messages/@chrikeli/)
- [YOU]

## Getting Started:

1. Join the [Slack Channel]((https://datafordemocracy.slack.com/messages/p-predicting_poverty/)) 
2. Read the [paper](http://nealjean.com/papers/science_main.pdf) to get a proper understanding of the problem.
3. Go through the [Refined-Solution.ipynb] file to get a better understanding of the approach.
4. If you have ideas, or suggestions feel free to send [@chrikeli](https://datafordemocracy.slack.com/messages/@chrikeli/) a message on Slack.
5. If you are new to GitHub, here are some baby steps to get comfortable with [contributing to a D4D project](https://github.com/Data4Democracy/github-playground).
6. Work on your code and submit a pull request to add it to the project! Reach out for help anytime!

### Things that are nice to know:
* **Beginners are welcome!** To do a lot of the analysis bits, you don't need prior data science or deep learning experience and the code for it is fairly well documented.
* **Deep Learning** You will need to have access to a GPU for a lot of the image processing we will be doing, you may get away with doing it on your CPU, but it may take a few days (compared to a couple of hours via GPU).

## This README is still a work in progress, and I will keep updating it frequently.
