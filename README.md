# Machine Learning for Healthcare (CSCI-GA.3033-083 / DS-GA.3001-005)

#### *Course staff:*
| | Name | E-mail |
|----------|---------------|----------------|
| Instructor | [Rajesh Ranganath](https://cims.nyu.edu/~rajeshr/)        | rajeshr@cims.nyu.edu           |
| TA | [Aahlad Puli](https://aahladmanas.github.io/)        | aahlad@nyu.edu        |
| Grader | ?       | ?      |

## Course Description
The course covers machine learning methods important for healthcare including causal inference, k-shot learning, time series models, and fairness. We will learn about important clinical questions and the data (such as from ICU monitors and imaging) that along with machine learning can help answer these questions. We will focus on recent work in machine learning for healthcare.

## Course Structure

* Every lecture will be pre-recorded and the students are expected to watch the lecture prior to the class.  

* Each class will be split up into two parts 1) lecture discussion (30 min) and 2) two student presentations (35 min : 25 min + 10 min for questions)

* A few lectures will be presentations from researchers involved in deploying machine learning models in the real world.

* Students can join the discussion or do their class presentations over zoom.


### Lecture Location
Monday, 2:00-3:40pm, in [HEBU CR1](https://www.nyu.edu/students/student-information-and-resources/registration-records-and-graduation/registration/classroom-locations.html)

### [Recitation/Laboratory](https://github.com/inf16nyu/home/tree/master/labs)
Tuesdays, 1:00-1:50pm in TBD

### Office hours
RR: Fill office hours. Mondays, 10:00-11:00am. Location: 715 Broadway, 12th floor, room 1204.

### Grading
The final project report will be the largest part of the grade. 
The project report is due on 12/15/20. In addition to the research paper, a weekly reading response
is due in class. People will be required to report on their projects once during the
course of the term.

**The grade split up is as follows: ** 

**Reading Responses sets (10%) + lecture scribe (10%) + class presentation (10%) + final project report (70%).**


### Piazza 
We will use [Piazza](http://piazza.com/nyu/fall2016/dsga1005csciga2569/home) (link outdated) to answer questions and post announcements about the course. Please sign up [here](http://piazza.com/nyu/fall2016/dsga1005csciga2569) (link outdated). Students' use of Piazza, particularly for adequately answering other students' questions, will contribute toward their participation grade (how much for this?).

## Lab Section

## Schedule and Reading Assignments
***
* __Introduction and Opportunities and Challenges in Healthcare (9/14/20)__  
* __Risk Scores and Survival (9/21/20)__
	+ [Opportunities in Machine Learning for Healthcare](https://arxiv.org/pdf/1806.00388.pdf)
	+ [Big Data In Health Care: Using Analytics To Identify And Manage High-Risk And High-Cost Patients](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2014.0041)
	+ Deep Survival Analysis ([1](https://arxiv.org/abs/1608.02158)) ([2](https://www.mlforhc.org/s/21.pdf))
* __Missing Data and the Electronic Health Record (9/28/20)__
	+ [Recurrent Neural Networks for Multivariate Time Series with Missing Values](https://arxiv.org/pdf/1606.01865.pdf)
	+ [Inference and missing data] (https://academic.oup.com/biomet/article-abstract/63/3/581/270932)
	+ [Electronic Health Records] (http://discovery.ucl.ac.uk/1598/1/A22.pdf) : A quick skim will suffice
* __Causal Inference from Observational Data (10/5/20)__
	+ [Statistics and Causal Inference] (https://www.jstor.org/stable/2289064)
* __Electrocardiography and Echocardiography (10/12/20)__
	+ [Basic mechanisms of cardiac impulse propagation and associated arrhythmias](https://www.ncbi.nlm.nih.gov/pubmed/15044680)
	+ [12 Lead ECG Explained, Animation](https://www.youtube.com/watch?v=kwLbSx9BNbU)
	+ [Atrial Fibrillation Anatomy, ECG and Stroke, Animation](https://www.youtube.com/watch?v=tPqs4xKPG3A)
	+ [Cardiac Conduction System and Understanding ECG, Animation](https://www.youtube.com/watch?v=RYZ4daFwMa8)
* __Fairness (10/19/20)__
	+ [Sex Bias in Graduate Admissions: Data from Berkeley](http://science.sciencemag.org/content/187/4175/398)
	+ [Equality of Opportunity in Supervised Learning] (https://arxiv.org/pdf/1610.02413.pdf)
	+ [Inherent Trade-Offs in the Fair Determination of Risk Scores] (https://arxiv.org/pdf/1609.05807.pdf)
	+ [Counterfactual Fairness](https://arxiv.org/pdf/1703.06856.pdf)
	+ [Avoiding Discrimination through Causal Reasoning] (https://arxiv.org/pdf/1706.02744.pdf)
	+ [Fair Inference On Outcomes] (https://arxiv.org/pdf/1705.10378.pdf)
* __Medical Imaging (10/26/20)__
	+ [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf)
	+ [Classification and mutation prediction from non small cell lung cancer histopathology images using deep learning] (https://www.nature.com/articles/s41591-018-0177-5)
	+ [High-Resolution Breast Cancer Screening with
Multi-View Deep Convolutional Neural Networks] (https://arxiv.org/pdf/1703.07047.pdf)
* __Clinical NLP (11/2/20)__
 	+ [Challenges in clinical natural language processing for automated disorder normalization] (https://www.sciencedirect.com/science/article/pii/S1532046415001501)
	+ [Medical Language Processing: Applications to Patient Data Representation and Automatic Encoding](https://cs.nyu.edu/cs/projects/lsp/pubs/LSPonSNOMED.pdf)
	+ [Multi-Label Learning from Medical Plain Text with Convolutional
Residual Models] (https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/5b7373cc032be4fab0075363/1534292941994/30.pdf)
* __Physiologic Time Series (11/9/20)__
	+ [Understanding vasopressor intervention and weaning: risk prediction in a public heterogeneous clinical time series database ] (https://academic.oup.com/jamia/article/24/3/488/2907906)
	+ [Clinical Intervention Prediction and Understanding with Deep Neural
Networks] (http://mucmd.org/CameraReadySubmissions/65%5CCameraReadySubmission%5Cclinical-intervention-prediction%20(4).pdf)
	+ [Towards Understanding ECG Rhythm Classification Using
Convolutional Neural Networks and Attention Mappings] (https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/5b73729d562fa79aabf87383/1534292642748/9.pdf)
* __What Makes a Disease a Disease? (11/16/20)__
* __OHDSI (11/23/20)__
* __Reinforcement Learning in Healthcare (11/27/18)__
	+ [A Reinforcement Learning Approach to Weaning of Mechanical Ventilation in
Intensive Care Units] (https://arxiv.org/pdf/1704.06300.pdf)
	+ [Continuous State-Space Models for Optimal Sepsis Treatment - a Deep
Reinforcement Learning Approach](https://arxiv.org/pdf/1705.08422.pdf)
* __The Role of Prior Knowledge? (11/30/20)__
* __Project Presentations I (12/7/20)__
* __Project Presentations II (12/14/20)__

### Bibliography
There is no required book. Assigned readings will come from freely-available online material.

#### Core Materials


#### Background on Probability and Optimization


#### Further Reading

