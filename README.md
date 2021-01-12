# Sample Code
Chen Liang

This repository includes the following graduate research/course projects I worked (mostly on my own).

### Course_Works:
* **Data_Exploration**: A sample data exploration project for MACS 30000 Perspectives on Computational Analysis. I conducted a exploratory analysis of the General Social Survey (GSS) 2018 data, experimented with various methods to visualize the results, and concluded the most interesting findings in **Exploration_WriteUp.ipynb**.
* **Spatial_Data_Science**: Four spatial data science projects, implemented on **DeoDa**. I explored methods of exploratory spatial data analysis, such as spatial autocorrelation statistics for aggregate data, and basic spatial regression analysis for point and polygon data. 
* **amazon_web_service_practice.ipynb**: A sample project of using AWS kinesis to process streaming data and send email alerts.
* **large_scale_ML_pipeline.ipynb**: A sample project of using pyspark and its machine learning pipeline function.

### Expert_Follow_Graph:
*This is the code for my PhD Writing Sample.*  
#### Abstract
The influence of a political idea rarely relies only on a few scholars and politicians. Instead, it emerges, evolves, and transforms into feasible policies when policy experts of various backgrounds and reputations cooperate and communicate through organizations and their personal networks. Previous research on the roles of policy experts in the policy making process, however, focus primarily on celebrities whose personal connections with other political actors are more publicly visible and politically influential. Two narratives are thus missing: First, what are the roles of the majority of lesser-known experts? Second, how much are experts’ cooperation and communication shaped by organizations such as think tanks? To provide a more complete picture, **I construct a Twitter follow graph which covers 609 experts with valid Twitter accounts**, which is about 70% of all listed experts on the websites of the Brookings Institution, the American Enterprise Institute, the Center for American Progress, and the Heritage Foundation. Then, I analyze the structure of this Twitter follow graph and explore the implication and limits of Twitter-based connections. I argue that, because the Twitter connections among experts are highly reciprocal and organizational based, the decision to follow someone appears to be more of a meaningful consideration than a whimsical click. Third, with a **DeepWalk Algorithm**, I show that experts’ online and informal social media connections are strongly bound to their offline and formal organizational affiliations. That is, social media usage seems ineffective in exposing experts to opinions from those beyond the reach defined by their offline constraints. Finally, I briefly discuss the **centrality measures** and a few other directions for future research. In all, I construct a framework to study the expert network through Twitter data and provide a complementary narrative to the existing qualitative discussions on how opinions and information may circulate among policy expert networks.

### SPLC_network: 
In this project (2018-2019), I extracted firm-level supply chain data from the Bloomberge Terminal (**Source Code.xlsx**), and applied a network analysis approach (**Social_Netowrk_Final.R**) to study how the global supply chain has changes in automobile and electric industries. I presented a feasibility report (**SPLC_Report.pdf**) to my Chinese colleagues. 

### Semantic_Modeling_Think_Tank:
*My final project for Computational Content Analysis.* 
#### Abstract
Historically, the conservatism in the U.S. is a mixture of three strands: economic conservatism, traditionalist conservatism, and anti-communism (Busch 2011). Economic conservatives, or libertarians, promote liberty, small government, and free-market principles. Traditionalist conservatives, or social conservatives, oppose to certain changes in social norms and seek for the preservation of conventional family and religious values. Anti-communist conservatives, with less commitment to domestic issues, have evolved into the so-called foreign policy conservatives within the modern Republican Party, with an emphasis on national defense and national security affairs. Despite this ideological faction, current quantitative measures tend to analyze individuals and organizations on a bi-polar spectrum of left and right. I argue that to better understand political polarization, it is important to capture the nuances in how ideologies are interpreted and framed differently and how these differences themselves lead to political consequences. I start by discussing how modern Natural Language Processing (NLP) may help us capture the change in conservative think tank strategies. I will then examine the implications and limitations of these approaches from a processual perspective and propose directions for future research.  
* **data_processing**: I present how I web-scraped think tank websites and preprocessed the scraped articles.
* **analysis_visualization**: I examine 1) the language shift by word frequency and 2) used topic modeling (Doc2Vec and Word2Vec) and Part-of-Speach (POS) analysis to study think tanks' framing strategies.
* **Final_Paper.pdf**: This is the final project for *Computational Content Analysis*. I also used the quantitative result of this research as part of my final paper for *Seminar: Social Process*, in which I discuss both the limits and advantages of using natural language processing to understand policy framing strategies from a processual perspective.


