# Publications
NoBIAS Publications for Open Source Access 

## Quantile Encoder: Tackling High Cardinality Categorical Features in Regression Problems
#### by _Carlos Mougan, David Masip, Jordi Nin, Oriol Pujol_ 
#### (International Conference on Modeling Decisions for Artificial Intelligence 2021)
Regression problems have been widely studied in machine learning literature resulting in a plethora of regression models and performance measures. However, there are few techniques specially dedicated to solve the problem of how to incorporate categorical features to regression problems. Usually, categorical feature encoders are general enough to cover both classification and regression problems. This lack of specificity results in underperforming regression models. In this paper, we provide an in-depth analysis of how to tackle high cardinality categorical features with the quantile. Our proposal outperforms state-of-the-encoders, including the traditional statistical mean target encoder, when considering the Mean Absolute Error, especially in the presence of long-tailed or skewed distributions. Besides, to deal with possible overfitting when there are categories with small support, our encoder benefits from additive smoothing. Finally, we describe how to expand the encoded values by creating a set of features with different quantiles. This expanded encoder provides a more informative output about the categorical feature in question, further boosting the performance of the regression model.\
[Paper](https://github.com/nobias-project/Publications/blob/main/mougan2021quantile.pdf) 

## Logic programming for XAI: A technical perspective
#### by _Laura State_ 
#### (1st Workshop on Machine Ethics and Explainability - The Role of Logic Programming, 2021)
Our world is increasingly shaped by Artificial Intelligence systems, from search engines over automated hiring algorithms to self-driving cars. Being also used in high-stake decisions, their impact on the life of individuals is huge. Thus it becomes exceedingly important to sceptically review their limitations. One alarming problem is their uptake and reinforcement of existing social biases, as found in many different domains (criminal justice, facial recognition, credit scoring etc). It is complemented by the inherent opaqueness of the most accurate AI systems, making it impossible to understand details of their internal workings. The field of Explainable Artificial Intelligence is trying to address these problems. However, there are several challenges in the field, and we will start this work by pointing them out. We put forward a set of technical pathways, drawing from Logic Programming. Specifically, we propose using Constraint Logic Programming to construct explanations that incorporate prior knowledge, as well as Meta-Reasoning to track model and explanation changes over time.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/state2021logic.pdf)

## Desiderata for Explainable AI in statistical production systems of the European Central Bank
#### by _Carlos Mougan, Georgios Kanellos, Thomas Gottron_ 
#### (Workshop on bias and fairness in AI at ECML PKDD 2021)
Explainable AI constitutes a fundamental step towards establishing fairness and addressing bias in algorithmic decision-making. Despite the large body of work on the topic, the benefit of solutions is mostly evaluated from a conceptual or theoretical point of view and the usefulness for real-world use cases remains uncertain. In this work, we aim to state clear user-centric desiderata for explainable AI reflecting common explainability needs experienced in statistical production systems of the European Central Bank. We link the desiderata to archetypical user roles and give examples of techniques and methods which can be used to address the user’s needs. To this end, we provide two concrete use cases from the domain of statistical data production in central banks: the detection of outliers in the Centralised Securities Database and the data-driven identification of data quality checks for the Supervisory Banking data system.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/mougan2021desiderata.pdf)

## Measuring Shifts in Attitudes Towards COVID-19 Measures in Belgium
#### by _Kristen Scott, Pieter Delobelle, Bettina Berendt_ 
#### (Computational Linguistics in the Netherlands Journal, Vol. 11, 2021)
With the COVID-19 pandemic and subsequent measures in full swing, people voiced their opinions of these measures on social media. Although it remains an open problem to correctly interpret these voices and translate this to public policy, we work towards this by tracking support for corona-related measures in Belgium, a densely-populated trilingual country in Western Europe. To this end, we classify seven months’ worth of Belgian COVID-related tweets using multilingual BERT and a manually labeled training set. The tweets are classified by which measure they refer to as well as by their stated opinion towards the curfew measure, for which we introduce a custom classification scheme (too strict, ok, too loose). Using this classification, we examine the change in topics discussed and views expressed over time and in reference to dates of related events such as the implementation of new measures or COVID-19 related announcements in the media. With these promising results, our contributions include (i) multiple multilingual BERT models trained on manually labeled data accompanied by (ii) historical analysis of the support for the curfew measure on Twitter and (iii) a thorough analysis of limitations and risks, together with best practices and a reference code book.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/scott2021measuring.pdf)

## A survey on bias in visual datasets
#### by _Simone Fabbrizzi, Symeon Papadopoulos, Eirini Ntoutsi, Ioannis Kompatsiaris_ 
#### (Computer Vision and Image Understanding, Volume 223, 2022)
Computer Vision (CV) has achieved remarkable results, outperforming humans in several tasks. Nonetheless, it may result in significant discrimination if not handled properly. Indeed, CV systems highly depend on training datasets and can learn and amplify biases that such datasets may carry. Thus, the problem of understanding and discovering bias in visual datasets is of utmost importance; yet, it has not been studied in a systematic way to date. Hence, this work aims to: (i) describe the different kinds of bias that may manifest in visual datasets; (ii) review the literature on methods for bias discovery and quantification in visual datasets; (iii) discuss existing attempts to collect visual datasets in a bias-aware manner. A key conclusion of our study is that the problem of bias discovery and quantification in visual datasets is still open, and there is room for improvement in terms of both methods and the range of biases that can be addressed. Moreover, there is no such thing as a bias-free dataset, so scientists and practitioners must become aware of the biases in their datasets and make them explicit. To this end, we propose a checklist to spot different types of bias during visual dataset collection.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/fabbrizzi2022survey.pdf)

## Introducing explainable supervised machine learning into interactive feedback loops for statistical production system
#### by _Carlos Mougan, George Kanellos, Johannes Micheler, Jose Martinez, Thomas Gottron_ 
#### (IFC-Bank of Italy Workshop on “Data Science in Central Banking: Applications and tools” 2022)
Statistical production systems cover multiple steps from the collection, aggregation, and integration of data to tasks like data quality assurance and dissemination. While the context of data quality assurance is one of the most promising fields for applying machine learning, the lack of curated and labeled training data is often a limiting factor.
The statistical production system for the Centralised Securities Database features an interactive feedback loop between data collected by the European Central Bank and data quality assurance performed by data quality managers at National Central Banks. The quality assurance feedback loop is based on a set of rule-based checks for raising exceptions, upon which the user either confirms the data or corrects an actual error.
In this paper we use the information received from this feedback loop to optimize the exceptions presented to the National Central Banks thereby improving the quality of exceptions generated and the time consumed on the system by the users authenticating those exceptions. For this approach we make use of explainable supervised machine learning to (a) identify the types of exceptions and (b) to prioritize which exceptions are more likely to require an intervention or correction by the NCBs. Furthermore, we provide an explainable AI taxonomy aiming to identify the different explainable AI needs that arose during the project.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/mougan2022introducing.pdf)

## Semantic Web technologies and bias in artificial intelligence: A systematic literature review
#### by _Paula Reyero Lobo, Enrico Daga, Harith Alani, Miriam Fernandez_ 
#### (Semantic Web, Volume 14, Number 4, 2023)
Bias in Artificial Intelligence (AI) is a critical and timely issue due to its sociological, economic and legal impact, as decisions made by biased algorithms could lead to unfair treatment of specific individuals or groups. Multiple surveys have emerged to provide a multidisciplinary view of bias or to review bias in specific areas such as social sciences, business research, criminal justice, or data mining. Given the ability of Semantic Web (SW) technologies to support multiple AI systems, we review the extent to which semantics can be a “tool” to address bias in different algorithmic scenarios. We provide an in-depth categorisation and analysis of bias assessment, representation, and mitigation approaches that use SW technologies. We discuss their potential in dealing with issues such as representing disparities of specific demographics or reducing data drifts, sparsity, and missing values. We find research works on AI bias that apply semantics mainly in information retrieval, recommendation and natural language processing applications and argue through multiple use cases that semantics can help deal with technical, sociological, and psychological challenges.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/lobo2023semantic.pdf)

## Time to Question if We Should: Data-Driven and Algorithmic Tools in Public Employment Services
#### by _Pieter Delobelle, Kristen M. Scott, Sonja Mei Wang, Milagros Miceli, David Hartmann, Tianling Yang, Elena Murasso, Karolina Sztandar-Sztanderska, Bettina Berendt_ 
#### (International workshop on Fair, Effective And Sustainable Talent management using data science 2022)
Algorithmic and data-driven systems have been introduced to assist Public Employment Services (PES) in various countries. However , their deployment has been heavily criticized. This paper is based on a workshop organized by a distributed team of researchers in AI ethics and adjacent fields, which brought together academics, system developers , representatives from the public sector, civil-society organizations, and participants from industry. We report on the workshop and analyze three salient discussion topics, organized around our research questions: (1) the challenge of representing individuals with data, (2) the role of job counsellors and data-driven systems in PES, and (3) questions around the interactions between job seeker, counsellor, and system. Finally, we consider lessons learned from the workshop and describe plans aiming at involving a multiplicity of stakeholders in a co-design process.
\
[Paper](https://github.com/nobias-project/Publications/blob/main/delobelle2022time.pdf)

## Explainability in Practice: Estimating Electrification Rates from Mobile Phone Data in Senegal
#### by _Laura State, Hadrien Salat, Stefania Rubrichi, Zbigniew Smoreda_ 
#### ()

\
[Paper]()

## Predicting and explaining employee turnover intention
#### by _Matilde Lazzari, Jose M. Alvarez, Salvatore Ruggieri_ 
#### ()

\
[Paper]()

## Fairness Implications of Encoding Protected Categorical Attributes
#### by _Carlos Mougan, Jose Manuel Alvarez, Salvatore Ruggieri, Steffen Staab_ 
#### ()

\
[Paper]()

## Policy advice and best practices on bias and fairness in AI
#### by _Jose M. Alvarez, Alejandra Bringas Colmenarejo, Alaa Elobaid, Simone Fabbrizzi, Miriam Fahimi, Antonio Ferrara, Siamak Ghodsi, Carlos Mougan, Ioanna Papageorgiou, Paula Reyero, Mayra Russo, Kristen M. Scott, Laura State, Xuan Zhao, Salvatore Ruggieri_ 
#### ()

\
[Paper]()

## Can We Trust Fair-AI?
#### by _Salvatore Ruggieri, Jose M. Alvarez, Andrea Pugnana, Laura State, Franco Turini_ 
#### ()

\
[Paper]()

## Domain Adaptive Decision Trees: Implications for Accuracy and Fairness
#### by _Jose M. Alvarez, Kristen M. Scott, Bettina Berendt, Salvatore Ruggieri_ 
#### ()

\
[Paper]()

## Counterfactual Situation Testing: Uncovering Discrimination under Fairness given the Difference
#### by _Salvatore Ruggieri, Jose Manuel Alvarez_ 
#### ()

\
[Paper]()

## Causal Fairness-Guided Dataset Reweighting using Neural Networks
#### by _Xuan Zhao, Klaus Broelemann, Salvatore Ruggieri, Gjergji Kasneci_ 
#### ()

\
[Paper]()

## Reason to Explain: Interactive Contrastive Explanations (REASONX)
#### by _ _ 
#### ()

\
[Paper]()

## Explaining short text classification with diverse synthetic exemplars and counter-exemplars
#### by _ _ 
#### ()

\
[Paper]()

## Declarative Reasoning on Explanations Using Constraint Logic Programming
#### by _ _ 
#### ()

\
[Paper]()

## The Explanation Dialogues: Understanding How Legal Experts Reason About XAI Methods
#### by _ _ 
#### ()

\
[Paper]()

## Careful Explanations: A Feminist Perspective on XAI
#### by _ _ 
#### ()

\
[Paper]()

## Constructing Meaningful Explanations: Logic-based Approaches
#### by _ _ 
#### ()

\
[Paper]()

## Causal Perception
#### by _ _ 
#### ()

\
[Paper]()

## A Causal Framework for Evaluating Deferring Systems
#### by _ _ 
#### ()

\
[Paper]()

## Uncovering Algorithmic Discrimination: An Opportunity to Revisit the Comparator
#### by _ _ 
#### ()

\
[Paper]()

## Enhancing Fairness through Reweighting: A Path to Attain the Sufficiency Rule
#### by _ _ 
#### ()

\
[Paper]()

## Link recommendations: Their impact on network structure and minorities
#### by _ _ 
#### ()

\
[Paper]()

## Algorithmic Tools in Public Employment Services: Towards a Jobseeker-Centric Perspective
#### by _ _ 
#### ()

\
[Paper]()

## Bias in Hate Speech and Toxicity Detection
#### by _ _ 
#### ()

\
[Paper]()

## Explanation Shift: Detecting distribution shifts on tabular data via the explanation space
#### by _ _ 
#### ()

\
[Paper]()

## Fairness in Agreement With European Values
#### by _ _ 
#### ()

\
[Paper]()

## Studying bias in visual features through the lens of optimal transport
#### by _ _ 
#### ()

\
[Paper]()

## Beyond Demographic Parity: Redefining Equal Treatment
#### by _ _ 
#### ()

\
[Paper]()

## The Initial Screening Order Problem
#### by _ _ 
#### ()

\
[Paper]()

## Supporting Online Toxicity Detection with Knowledge Graphs
#### by _ _ 
#### ()

\
[Paper]()

## Counterfactual Explanation for Regression via Disentanglement in Latent Space
#### by _ _ 
#### ()

\
[Paper]()

## Monitoring Model Deterioration with Explainable Uncertainty Estimation via Non-parametric Bootstrap
#### by _ _ 
#### ()

\
[Paper]()

## How to Data in Datathons
#### by _ _ 
#### ()

\
[Paper]()

## Estimating Ground Truth in a Low-labelled Data Regime: A Study of Racism Detection in Spanish
#### by _ _ 
#### ()

\
[Paper]()

## Affinity Clustering Framework for Data Debiasing Using Pairwise Distribution Discrepancy
#### by _ _ 
#### ()

\
[Paper]()

## The Role of Large Language Models in the Recognition of Territorial Sovereignty: An Analysis of the Construction of Legitimacy
#### by _ _ 
#### ()

\
[Paper]()

## Context matters for fairness -- a case study on the effect of spatial distribution shifts

#### by _ _ 
#### ()

\
[Paper]()

