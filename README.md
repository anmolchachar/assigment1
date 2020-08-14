2K18 - CSM - 21 Anmol Chachar
                                          SUMARRY1

Measuring Software Testability Modulo Test Quality

1:Authors:  
Valrio Teragani
Pasquale salsa
Mauro puzze

2:Universities:
USI Università della Svizzera italiana Switzerland valerio.terragni@usi.ch
University of Zurich Switzerland salza@ifi.uzh.ch
USI Università della Svizzera italiana Schaffhausen Institute of Technology Switzerland mauro.pezze@usi.ch
DATE: ICPC ’20, October 5–6, 2020, Seoul, Republic of Korea

INTRODUCTION: Software testing is an essential, labor-intensive and time-consuming activity of the software lifecycle. Making testing easier is important for many software companies, as it lowers development costs while increasing the number of detected faults. A software system with a high degree of test ability results in slow test effort. In their recent comprehensive literature review of 208 papers on software test ability. Most studies on measuring and predicting test ability investigate on the relation between class-level metrics in object oriented systems , but suffer from two limitations: (i) the data sets are of small size, and (ii) mostly ignore the quality of the test suites. 
Small sample size. Previous studies involved at most eight software projects [22]. Such a small number of analyzed projects does not guaran teeth ability of there results: specific development styles, frameworks, and practices can influence the correlation results and produce different results for different projects[3].  Ignoring the test quality. Previous studies measured the test effort in terms of the size of the test classes, while mostly ignoring.
Design properties and test effort; • publicly releasing our data set for further studies 2. The paper is organized as follows. Section 2 presents the objective of this study, introduces the considered metrics, and motivates and explain sour normalization procedure. Section3 presents the results, which address the main research questions that validate the hypothesis that “ normalizing by the test quality” achieves better correlation than not using the normalization. Section4 discusses there work. Section5 summarizes the main results presented in the paper.

ABSTRACT:
Comprehending the degree to which software components support testing is important to accurately schedule testing activities, train developers, and plan effective refactoring actions. Software test ability estimates such property by relating code characteristics to the test effort. The results confirm that normalizing the test effort with respect to the test quality largely improves the correlation between class metrics and the test effort. Better correlations result in better prediction power, and thus better prediction of the test effort. This paper contributes to a better comprehension of software test ability by: 
• presenting the by-far largest study on the correlation of class and test-effort metrics in terms of analyzed metrics, classes and projects; 
• extending the test ability measurements by normalizing the test effort, with respect to the quality of the test suites; *showing that the proposed normalization improves the correlation between class metrics and test effort. 
• giving important in sight son software test ability that confirm some of the findings of previous studies as well as uncover.

CONCLUSIONS: This paper proposes a new software test ability approach that extends current practice with the novel idea of normalizing test effort with respect to test quality. It also presented the results of an extensive study that involves 9,861 pairs of Java classes (with a total of 1,594,309 lines of code ) and corresponding Unit test cases taken from 1,186 GitHub projects. Our results indicate that normalizing test effort with test quality largely increases the correlation between class metric and test effort. An improved correlation between class metric and test effort means a better prediction of test effort. In this paper, we introduced the normalization process under the assumption  optional growth of the test effort with respect to the test quality. For example, if five test cases (T-NOT = 5) achieve a branch coverage of 50%, our normalization assumes we need ten test cases (T-NOT = 10) to have a branch coverage of 100%. One avenue for future work is to study the impact of this assumption on the correlation between class and test-effort metrics.



                                        Summary 2

AIMMX: Artificial Intelligence Model Metadata Extractor

Authors:
Jason Tsay Jason
Alan Braz 
Martin Hizrail

Universities:
IBM Research Yorktown Heights, New York, USA
IBM Research São Paulo, Brazi
IBM Research Yorktown Heights, New York, USA

Date: MSR ’20, October 5–6, 2020, Seoul, Republic of Korea

INTRODUCTION:

The combination of suﬃcient hardware resources, the availability of large amounts of data, and innovations in artiﬁcial intelligence (AI) models has brought about a renaissance in AI research and practice. For this paper, we deﬁne an AI model as all the software and data artifacts needed to deﬁne the statistical model for a given task, train the weights of the statistical model, and/or deploy the trained model weights for prediction in a service or application. Our deﬁnition of model includes both traditional machine learning (ML) and deep learning models. One avenue for standardization is that software and AI development share many of the same languages and tools, such as version control systems. Existing software repository tools and services, such as GitHub, are popular with AI developers to store model deﬁnition code and development artifacts such as conﬁgurations and training logs. These connections may also enable automated training or deployment in future tools. This paper makes the following contributions: 
• Tool for extracting AI model-speciﬁc metadata from software repositories with currently ﬁve extraction modules (Section 2). 
• Evaluation of our tools against a dataset of 7,998 models (Section 3). This AI model metadata dataset is also available as part of a replication package. 
• Preliminary usage of extracted metadata via an exploratory analysis of the data and method reproducibility of AI models in our dataset and implementation of a cataloging tool (Section 4).

ABSTRACT:
Despite all of the power that machine learning and artiﬁcial intelligence (AI) models bring to applications, much of AI development is currently a fairly ad hoc process. Software engineering and AI developments hare many of the same languages and tools, but AI development as an engineering practice is still in early stages. The extractors have ﬁve modules for extracting AI model-speciﬁc metadata: model name, associated datasets, references, AI frameworks used, and model domain. Our collected models are searchable in a catalog that uses existing metadata to enable advanced discovery features for eﬃciently ﬁnding models.

CONCLUSIONS: 
This paper describes AIMMX which we intend as a step towards furthering engineering support for AI development through providing standardized metadata for existing AI models. We envision that generating analyzable metadata for disparate models is both the ﬁrst step towards managing models at scale and adapting existing mining software repositories techniques to AI models.



                                             SUMMARY 3
          Developer-Driven Code Smell Prioritization

Authors:
Fabiano Pecorelli,
 Fabio Palomba,
 Foutse Khomh,
 Andrea DeLucia

Universities:
1SeSaLab-University of Salerno, Italy— 2École Poly technique de Montréal, Canada

Date: MSR ’20, October 5–6, 2020, Seoul, Republic of Kore

INTRODUCTION:
As a software system evolves, continuous modifications are required to a daptit to new requirement sand/ or changing environment so even fixed effects that can preclude its correct functioning [69]. One of the main indicators of technical debt is represented by the presence of code smells [26], which are poor Code smells have been of ten associated to a decrease of program comprehensibility [1], maintainability [38,59], testability [28] as well as an increase of maintenance effort and costs [80]. These findings have motivated researchers to propose automated mechanisms to support developrs in both the identification [4,18,21] and removal [51] of code smells, obtaining promising results. While some researchers provided initial attempts toward the prioritization of code smells using measures of severity derived from software metrics [3,25,49,93], the available solutions either rely on predefined heuristics that have not been empirically assessed or do not address the problem of providing developers with recommendations aligning with their perception of design issues, thus possibly being still in effective in practice The main result of the study high lights that the devised approach can classify the developer’s perceived criticality of code smells with an F-Measure ranging between 72% and 85%. Moreover, we discovered that, depending on the code smell type, specific features are more relevant to classify its criticality.

ABSTRACT
 Code smells are symptoms of poor implementation choices applied during software evolution. While previous research has devoted effort in the definition of automated solutions to detect them, still little is known on how to support developers when prioritizing them. Some works attempted to deliver solutions that can rank smell instances based on their severity, computed on the basis of software metrics. However, this may not be enough since it has been shown that the recommendations provided by current approaches do not take the developer’s perception of design issues into account. In this paper, we perform a first step toward the concept of developer-driven code smell prioritization and propose an approach based on match in earning able to rank code smells according to the perceived criticality that developers assign to them. We evaluate our technique in an empirical study to investigate its accuracy and the features that are more relevant for classifying the developer’s perception. Finally, we compare our approach with a state-of-the-art technique. Key findings show that the our solution has an F-Measure up to 85% and out performs the base line approach

CONCLUSION 
This paper presented a novel code smell prioritization approach based on the developers’ perceived criticality of code smells. We exploited several aspects related to code quality to predict he criticality of code smells, computed by collecting feed back from original developers about their perception of 1,332 code smell instances. Then, we applied several machine learning techniques to classify the code smell criticality in a three-level variable, and compared their results with a state-of-the-art tool. The results reported Random Forest to be the best machine learning algorithm with an F-measure rang between 72% and 85%. More over,we found that our approach is, on average, 20% more accurate than the considered base line when classifying the perceived criticality of code smells. Future work includes (1) further improvement soft the approach, e.g., by considering social network analysis metrics, (2) an experimentation with a large r number of code smells, and (3) an in-vivo assessment of our technique.
