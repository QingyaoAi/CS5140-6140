# *DS4140/CS5140/CS6140 Data Mining*

Class Hours: Monday/Wednesday 3:00pm-4:20pm, WEB L101

## Instructor

<a href="http://aiqingyao.org">Qingyao Ai</a> (aiqy[at]cs[dot]utah[dot]edu)

Office Hours: Wednesday 10:30am-11:30am, MEB 2172 (hallway)

## TA/TM

* Assignments and Grading
	* Zhichao Xu
		* zhichao[dot]xu[at]utah[dot]edu
		* Office Hours: To be assigned
	* Anh Tran 
		* abtran[at]cs[dot]utah[dot]edu
		* Office Hours: To be assigned
* Project Management
	* Zhenduo Wang
	* zhenduow[at]cs[dot]utah[dot]edu
	* Office Hours: appointments only

## Prerequisites

* Basic Probability, Linear Algebra, Big-O Analysis
* Basic Programming and Data Structures

## Text Books:
* [M4D] <a href="https://mathfordata.github.io">*Mathematical Foundations for Data Analysis*</a>. Jeff M. Phillips.
* [MMDS] <a href="http://www.mmds.org/">*Mining of Massive Datasets*</a>. Anand Rajaraman, Jure Leskovec, and Jeff Ullman. (optional) 
* [FoDS] <a href="http://www.cs.cornell.edu/jeh/book.pdf">*Foundations of Data Science*</a>. Avrim Blum, John Hopcroft and Ravindran Kannan. (optional)


## Resources

* <a href="https://www.cs.utah.edu/~jeffp/teaching/cs5140-S20/cs5140.html">*Previous Class Website*</a>. Jeff M. Phillips.
* <a href="https://www.cs.utah.edu/~jeffp/teaching/cs5140-S20/cs5140/Syllabus.pdf">*Previous Class Syllabus*</a>. Jeff M. Phillips.
* <a href="https://www.cs.utah.edu/~jeffp/teaching/cs5140-S20/cs5140/project.pdf">*Previous Class Project Description*</a>. Jeff M. Phillips.


## Grading

The grade will count the assessments using the following proportions (tentative and subject to change):
* __40%__ of your grade will be determined by homework:
  * We will have 8 short homework assignments roughly covering each main topic in the class 
  * Each assignment take __5%__ of the final grade.
* __25%__ of your grade will be determined by the class project.
  * __5%__ of your grade will be determined by the project proposal.
  * __5%__ of your grade will be determined by the intermediate report.
  * __5%__ of your grade will be determined by the project poster presentation.
  * __10%__ of your grade will be determined by the project final report.
* __10%__ of your grade will be determined by the paper presentation. 
* __10%__ of your grade will be determined by Mid-term Exam.
* __10%__ of your grade will be determined by Final Exam.
* __5%__ of your grade will be determined by your participation. Students who finish the class project, peer reviews, and all assignments/exams will receive the full credits of participation. 
 

## Tentative Class Schedule


Week, Date | Topic | Textbook and Resources | Reminder
------------ | ------------- | ------------- | -------------
Week 01, 01/10 | Class Overview |
Week 02, 01/12 | Statistics Principles | M4D 2.2-2.3, MMDS 1.2, FoDS 12.4
Week 02, 01/17 | Martin Luther King Day | 
Week 02, 01/19 | Similarity : Jaccard + k-Grams | M4D 4.3-4.4, MMDS 3.1+3.2, FoDS 7.3
Week 03, 01/24 | Similarity : Min Hashing | M4D 4.6.6, MMDS 3.3 | Assignment 1 Due
Week 03, 01/26 | Similarity : LSH | M4D 4.6, MMDS 3.4 | Class Project Group Due
Week 04, 01/31 | Similarity : Distances | M4D 4-4.3, MMDS 3.5+7.1, FoDS 8.1 | Assignment 2 Due
Week 04, 02/02 | Similarity : Word Embed + ANN vs. LSH | M4D 4.4, MMDS 3.7+7.1.3
Week 05, 02/07 | Clustering : Hierarchical | M4D 8.5+8.2, MMDS 7.2, FoDS 7.7 | Assignment 3 Due
Week 06, 02/09 | Clustering : K-Means | M4D 8-8.3, MMDS 7.3, FoDS 7.2-3	| Project Proposal Due
Week 05, 02/14 | Clustering : Spectral | M4D 10.3, MMDS 10.4, FoDS 7.5
Week 06, 02/16 | Streaming : Model and Misra-Greis | M4D 11.1-11.2.2, FoDS 6.2.3, MMDS 6
Week 07, 02/21 | Presidents Day | | Assignment 4 Due
Week 07, 02/23 | Streaming : Count-Min Sketch, Count Sketch, and Apriori | 	M4D 11.2.3-4, FoDS 6.2.3, MMDS 4.3 
Week 08, 02/28 | Regression : Basics, and Ridge Regression | M4D 5-5.3 | Assignment 5 Due
Week 08, 03/02 | Regression : Lasso + MP + Comp. Sensing | 	M4D 5.5, FoDS 10.2
Week 09, 03/07 | Spring Break
Week 09, 03/09 | Spring Break
Week 09, 03/14 | Regression : Cross-Validation and p-values | M4D 5.5 
Week 09, 03/16 | Mid-term Exam | |  Intermediate Report Due (03/20)
Week 10, 03/21 | Dim Reduce : SVD + PCA | M4D 7-7.3+7.5, FoDS 4 | Assignment 6 Due
Week 10, 03/23 | Dim Reduce : Matrix Sketching | 	M4D 11.3, MMDS 9.4, FoDS 2.7+7.2.2
Week 11, 03/28 | Dim Reduce : Metric Learning | 	M4D 7.6-7.8 
Week 11, 03/30 | Dim Reduce : Matrix Completion | 	M4D 7.9 
Week 12, 04/04 | Noise : Random Projections and Noise in Data | 	M4D 7.10+8.6, MMDS 9.1, FoDS 2.9 | Assignment 7 Due
Week 12, 04/06 | Noise : Calibration and Counterfactual Learning | Cascade Model <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.112.1288&rep=rep1&type=pdf" target="\blank">Craswell et al. (WSDM 2008)</a> <br /> DBN <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.215.7270&rep=rep1&type=pdf" target="\blank">Chapelle and Zhang (WWW 2009)</a> <br /> UBM <a href="https://www.researchgate.net/profile/Georges_Dupret/publication/200110492_A_user_browsing_model_to_predict_search_engine_click_data_from_past_observations/links/54e4c5ea0cf29865c3351048.pdf" target="\blank">Dupret and Piwowarski (SIGIR 2008)</a> <br /> IPW <a href="https://www.cs.cornell.edu/people/tj/publications/joachims_etal_17a.pdf" target="\blank">Joachims et al. (WSDM 2017)</a> <br /> Regression EM <a href="https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/3bace79f9bcead0b20dec31e2a0878346ad2fb0d.pdf" target="\blank">Wang et al. (WSDM 2018)</a> <br /> DLA <a href="https://arxiv.org/abs/1804.05938" target="\blank"> Ai et al. (SIGIR 2018)</a>
Week 13, 04/11 | Graph Analysis : Markov Chains | M4D 10.1, MMDS 10.1+5.1, FoDS 5
Week 13, 04/13 | Graph Analysis : PageRank | M4D 10.2, MMDS 5.1+5.4
Week 14, 04/18 | Graph Analysis : MapReduce or Communities | M4D 10.4, MMDS 2+10.2+5.5, FoDS 8.8+3.4 | Project Poster Due
Week 14, 04/20 | Class Project Presentation
Week 15, 04/25 | Final Exam | | Assignment 8 Due
Week 15, 04/30 | | | Final Report Due
## Acknowledgements
Special thanks to Prof. Jeff M. Phillips from University of Utah.
Teaching materials are borrowed from his courses on CS5140/6140: Data Mining.
