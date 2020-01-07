.. CSE474574 course webpage documentation master file, created by
   sphinx-quickstart on Fri Mar 17 21:28:07 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Syllabus
====================================================================

`Computer Science and Engineering <http://www.cse.buffalo.edu/>`_, University at Buffalo 

Spring Semester 2020


.. raw:: html

    <style> .red {color:red} </style>
    <style> .blue {color:blue} </style>
    <style> .gr {color:green;font-weight:bold} </style>
    <style> .highlights {background-color:#ef9c7f;padding:1em} </style>

Instructors
------------

* `Varun Chandola <http://www.cse.buffalo.edu/~chandola>`_ (lead instructor; chandola[at]buffalo.edu)

* TBA 

.. note::
   Students are strongly encouraged to use the Piazza's private messaging option to contact the intructors to ensure that the messages are dealt with promptly. 

Class Website
-------------
https://cse.buffalo.edu/~chandola/machinelearning.html

Meeting times and locations
----------------------------
* Mondays, Wednesdays and Fridays, 1.00 PM - 1.50 PM, 20 Knox Hall. 

* Chandola Office Hours: 12.00 PM - 2.00 PM, 213 Capen Hall (Inside Capen 212 Suite) 

Prerequisites
---------------
CSE 250 and (EAS 305 or MTH 411 or STA 301 or MTH 309).

Topic Schedule
---------------
.. role:: red
.. role:: gr
.. tabularcolumns:: |l|l|p{2cm}|

+------------+-----------------------------------+--------------------------------------------------------------+
| Week       | Topic                             | Pre-requisites                                               |
+============+===================================+==============================================================+
| 1          | Introduction and Basics           |                                                              | 
+------------+-----------------------------------+--------------------------------------------------------------+
| **Supervised Learning::Linear Models**                                                                        |
+------------+-----------------------------------+--------------------------------------------------------------+
| 2          | Linear Regression                 | Linear Algebra,Gradient Descent Optimization, Matrix Calculus|
+------------+-----------------------------------+--------------------------------------------------------------+
| 2          | Logistic Regression/Perceptrons   | Newton's Method                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 3          | Support Vector Machines           | Constrained Optimization, Lagrangian Methods                 |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Supervised Learning::Non-linear Models**                                                                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 4          | Non-linear Regression             |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 5          | Regularization                    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 6-7        | Neural Networks                   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| :red:`Spring Break`                                                                                           |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Kernel Methods**                                                                                            |
+------------+-----------------------------------+--------------------------------------------------------------+
| 9          | Kernel Regression                 |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 9          | Kernel Support Vector Machines    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Statistical Learning**                                                                                      |
+------------+-----------------------------------+--------------------------------------------------------------+
| 10         | Generative Models                 | Laws of Probability, Statistical Distributions, Moments      |
+------------+-----------------------------------+--------------------------------------------------------------+
| 11         | Bayesian Learning Methods         | Bayes Rule                                                   |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Bayesian Classification           |                                                              |
|            |                                   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Bayesian Linear Regression        |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Unsupervised Learning**                                                                                     |
+------------+-----------------------------------+--------------------------------------------------------------+
| 13         | Clustering (k-Means/Spectral)     | Linear Algebra (Eigenvalue Decomposition)                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 14         | Mixture Models (Expectation       |                                                              |
|            | Maximization)                     |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 15         | Dimensionality Reduction Methods  |                                                              |
|            | (Principal Component Analysis)    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+


Course Deliverables
-------------------

+---------------+--------------+-----------+
| Deliverable   | Release Date | Due Date  |
+===============+==============+===========+
| Gradiance 0   | Jan 29       |  *Feb 4*  |
+---------------+--------------+-----------+
| Gradiance 1   | Feb 5        |  Feb 11   |
+---------------+--------------+-----------+
| :gr:`PA 1`    | :gr:`Feb 11` |:gr:`Mar 6`|
+---------------+--------------+-----------+
| Gradiance 2   | Feb 12       |  Feb 18   |
+---------------+--------------+-----------+
| Gradiance 3   | Feb 19       |  Feb 25   |
+---------------+--------------+-----------+
| :gr:`PA 2`    | :gr:`Mar 6`  |:gr:`Apr 3`|
+---------------+--------------+-----------+
| Gradiance 4   | Feb 26       |  Mar 3    |
+---------------+--------------+-----------+
| Gradiance 5   | Mar 4        |  Mar 10   |
+---------------+--------------+-----------+
| Gradiance 6   | Mar 11       |  *Mar 24* |
+---------------+--------------+-----------+
| Gradiance 7   | Mar 25       |  Mar 31   |
+---------------+--------------+-----------+
| :gr:`PA 3`    | :gr:`Apr 13` |:gr:`May 8`|
+---------------+--------------+-----------+
| Gradiance 8   | Apr 1        |  Apr 7    |
+---------------+--------------+-----------+
| Gradiance 9   | Apr 8        |  Apr 14   |
+---------------+--------------+-----------+
| Gradiance 10  | Apr 15       |  Apr 21   |
+---------------+--------------+-----------+
| Gradiance 11  | Apr 22       |  Apr 28   |
+---------------+--------------+-----------+
| Gradiance 12  | Apr 29       |  May 5    |
+---------------+--------------+-----------+

.. note::
  * Gradiance quizzes

    * Will be released every Wednesday at 9.00 AM EST
    * Due next Tuesday at 11.59 PM EST
    * Gradiance 0 will not be evaluated (warm up)
    * Gradiance 6 will be released on March 11 but will be due on March 24 due to Spring Recess

  * All assignments are electronically due on Wednesdays by 08.59 AM EST through UBLearns.
  * Hard copies of assignment reports will be due in-class on Wednesdays before the end of the class.

Assignments (Tentative Schedule)
---------------------------------
  * Programming Assignment 1 - This assignment will focus on building linear models for supervised learning. This will include implementing a linear regression model for regression, and three classification models, viz., logistic regression, perceptron, and support vector machine (SVM).
  * Programming Assignment 2 - This programming assignment has two parts. In the first part, you will implement a Naive Bayes Classifier and test it on a publicly available data set. In the second part, you will manipulate the data characteristics to understand how classifiers get impacted by the underlying bias in the training data. After completing this assignment, you should be able to understand:

      * How a Naive Bayes classifier works and how to incorporate prior information into the model?
      * How bias in the training data could lead to a biased and unfair machine learning model? Within this topic you will learn:

           * How to measure bias (or fairness) of an algorithm with respect to bias-sensitive information?
           * How to artificially induce bias in the training data and study the impact of the training data bias on the clasification bias.
  * Programming Assignment 3 - In this assignment, your task is to implement a Multilayer Perceptron the neural network and evaluate its performance in classifying handwritten digits. You will also use the same network to analyze a more challenging hand-drawn images dataset and compare the performance of the neural network against a deep neural network using the TensorFlow library.

Course Texts
---------------
* Tom Mitchell, Machine Learning. McGraw-Hill, 1997.
* Kevin Murphy, Machine Learning: A Probabilistic Perspective, MIT Press, 2012.
* Chris Bishop, Pattern Recognition and Machine Learning, Springer, 2006.
* David Mackay, Information Theory, Inference, and Learning Algorithms, Cambridge Press, 2003.
* Trevor Hastie, Robert Tibshirani and Jerome Friedman, The Elements of Statistical Learning. Springer, 2009.

Grading
---------
* Short weekly quizzes using Gradiance (12) -- 20%
* Programming Assignments (3) -- 45%
* Mid-term Exam (in-class, open book/notes) -- 15%
* Final Exam (in-class, open book/notes) -- 20%

* All components will be individually curved
* Final grade (*Tentative*)

.. hlist::
    :columns: 2

    - A  [92.5,100]
    - A- [87.5,92.5)
    - B+ [82.5,87.5)
    - B  [77.5,82.5)
    - B- [72.5,77.5)
    - C+ [67.5,72.5)
    - C  [62.5,67.5)
    - C- [57.5,62.5)

Exams
---------------
* **Mid-term Exam** March 13, 1.00 PM - 2.00 PM, 20 Knox Hall
* **Final Exam** May 15, 11.45 AM - 02.45 PM, 20 Knox Hall

Expectations
-------------
* Students are expected to act in a professional manner. A student’s grade may be reduced due to unprofessional or disruptive behavior. Examples include coming to class late, texting (or otherwise using your cell phone) during class, your cell phone ringing during class and/or exams, etc.
* Programming assignments will be graded and returned to students.
* :red:`Late submission of assignments will receive a grade of zero.`
* :red:`No late submission of Gradiance quizzes are allowed. The quizzes will automatically become unavailable immediately after the due date and no accomodations will be made for missed quizzes.`
* Students are encouraged to discuss assignments and share ideas, but each student must independently write and submit their own solution.
* Makeup exams will be given in the following circumstances only: 

  1. You contact the instructor prior to the exam
  2. You have a valid and documented reason to miss the exam

Accessibility Services and Special Needs
-----------------------------------------
If you have a disability and may require some type of instructional and/or examination accommodation, please inform me early in the semester so that we can coordinate the accommodations you may need. If you have not already done so, please contact the Office of Accessibility Services (formerly the Office of Disability Services) University at Buffalo, 25 Capen Hall, Buffalo, NY 14260-1632; email: stu-accessibility@buffalo.edu Phone: 716-645-2608 (voice); 716-645-2616 (TTY); Fax: 716-645-3116; and on the web at http://www.buffalo.edu/accessibility/. All information and documentation is confidential. The University at Buffalo and the School of Engineering and Applied Sciences are committed to ensuring equal opportunity for persons with special needs to participate in and benefit from all of its programs, services and activities.

Academic Integrity
-------------------
This course will operate with a zero-tolerance policy regarding cheating and other forms of academic dishonesty. Any act of academic dishonesty will subject the student to penalty, including the high probability of failure of the course (i.e., assignment of a grade of “F”). It is expected that you will behave in an honorable and respectful way as you learn and share ideas. Therefore, recycled papers, work submitted to other courses, and major assistance in preparation of assignments without identifying and acknowledging such assistance are not acceptable. All work for this course must be original for this course. Additionally, you are not allowed to post course homeworks, exams, solutions, etc., on a public forum. Please be familiar with the University and the School policies regarding plagiarism. Read the Academic Integrity Policy and Procedure for more information: http://undergrad-catalog.buffalo.edu/policies/course/integrity.shtml. Visit the Senior Vice Provost for Academic Affairs web page for the latest information at http://vpue.buffalo.edu/policies/

.. highlights:: 

   **Machine Learning Honor Code**
  
   Against the ML honor code to:

   1. Collaborate on Gradiance quizzes
   2. Collaborate or cheat during exams
   3. Submit someone else’s work, including from the internet, as one’s own for any submission
   4. Misuse Piazza forum

   You are allowed to:

   1. Have discussions about homeworks. Every student should submit own homework with names of students in the discussion group explicitly mentioned.
   2. Collaborate in groups of 2 or 3 for programming assignments. One submission is required for each group.

.. warning:: 
   * Violation of ML honor code and departmental policy will result in an automatic F for the concerned submission
   * Two violations ⇒ fail grade in the course
