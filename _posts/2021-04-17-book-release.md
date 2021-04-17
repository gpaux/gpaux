---
layout: post
title: Clinical Trial Optimization in drug development
tags: [Biostatistics, clinical trials, optimization, simulations, R]
---


Decision-making is an essential part of any drug development and is often done in the presence of considerable uncertainty. Confronted with the increasing cost, duration and failure rate of new drug development programs, the use of innovative trial designs and analysis strategies has considerably increased over the past decades. Nevertheless, clinical development still remains at risk and decision-making process has to be optimized. Clinical trial sponsors are looking for more efficient and quicker decisions during the drug development, while data and knowledge about a new compound are acquired. Adaptive designs are nowadays more often use in order to incorporate in real time the accumulated data, with the ultimate goal to optimize clinical trial programs by stopping the development of unpromising drugs or accelerating the ones likely to succeed. Similarly, sponsors are increasingly interested in assessing multiple clinical objectives in a single confirmatory clinical trial as a mean to establish as many regulatory claims as possible. However, this strategy has a cost and induces an increase of the probability to erroneously claiming the effectiveness of a new drug, i.e., the Type I error rate. This hot topic has recently attracted significant attention with the release of the [draft guidance on multiple endpoints in clinical trials (FDA)](https://www.fda.gov/downloads/Drugs/GuidanceComplianceRegulatoryInformation/Guidances/UCM536750.pdf) and [draft guideline on multiplicity issues in clinical trials (EMA)](http://www.ema.europa.eu/docs/en_GB/document_library/Scientific_guideline/2017/03/WC500224998.pdf).

In this high-risk context, clinical trial optimization should be part of any drug development program to answer important research questions more efficiently and with less risk. Clinical trial modeling and simulations take crucial and invaluable roles to support a thorough assessment of the operating characteristics of the development decisions and performance of candidate trial designs and analysis strategies.

<center>
  <div class="col-md-6">
    <a href="https://www.crcpress.com/Clinical-Trial-Optimization-using-R/Dmitrienko/p/book/9781498735070" class="img-responsive">
      <img src="assets/img/book.jpg" class="img-responsive"/>
    </a>
  </div>
</center>


Recently the book entitled [Clinical Trial Optimization Using R](https://www.crcpress.com/Clinical-Trial-Optimization-using-R/Dmitrienko/p/book/9781498735070), edited by Alex Dmitrienko and Erik Pulkstenis has been released. This book, fruit of the collaboration between nine statisticians from pharmaceutical industry, provides clinical trial researchers with a unified and efficient approach to clinical trial optimization through a mixture of methodology concepts and practical case studies. The book delves into the Clinical Scenario Evaluation (CSE) framework which facilitates a comprehensive comparison of competing options for clinical development programs and clinical trial design/analyses. This framework was initially introduced by Norbert Benda et al. (2010) and refined by Tim Friede et al (2010) and other publications. From a clinical trial perspective, the CSE framework provides project team with a powerful tool to quantitatively evaluate multiple competing analysis strategies or trial design and examine their sensitivity to potential deviations from original assumptions. In this sense, the CSE framework gives sponsors a comprehensive approach to optimizing drug development. 

This book presents CSE-based clinical trial optimization approaches through a variety of common drug development challenges arising during the different phases of the drug development (multiplicity issues, subgroup analysis, Go/No-Go decision...). Last but not least, to avoid the important gap that can arise between the theoretical approach of the CSE framework and its practical application, an open-source software has been developed ([Mediana R package](http://gpaux.github.io/Mediana), *Gautier Paux and Alex Dmitrienko*). This R package provides to clinical trial researchers a powerful set of tools to facilitate the implementation of simulation-based CSE approaches.

The book is divided into four chapters:

1.  **Clinical Scenario Evaluation and Clinical Trial Optimization**, *Alex Dmitrienko and Gautier Paux*. This chapter will introduce key principles of the CSE framework and its application to Clinical Trial Optimization, along with a description of the [Mediana R package](http://gpaux.github.io/Mediana) that was designed to support CSE-based simulations in clinical trial applications.

2.  **Clinical Trials with Multiple Objectives**, *Alex Dmitrienko and Gautier Paux*. This chapter will introduce key concepts of clinical trial optimization in the context of clinical trials with multiplicity issues. Three case studies will illustrate several approaches to identify efficient multiplicity adjustment procedures and/or parameters set with the goal of maximizing the probability of success in a single trial or development program. Performance assessment is facilitated using the CSE framework and the [Mediana R package](http://gpaux.github.io/Mediana), which provides a turnkey solution in this context.

3.  **Subgroup Analysis in Clinical Trials**, *Alex Dmitrienko and Gautier Paux*. This chapter will approach the topic of subgroup analysis in Phase III trials from a CSE perspective and introduce practical approaches to clinical trial optimization in a confirmatory subgroup analysis setting, i.e., in Phase III clinical trials with pre-defined patient subpopulations. Three case studies will be presented to illustrate optimization procedures based on the general CSE approach, along with Mediana-based implementation.

4.  **Decision Making in Clinical Development**, *Kaushik Patra, Ming-Dauh Wang, Jianliang Zhang, Aaron Dane, Paul Metcalfe, Paul Frewer, and Erik Pulkstenis*. This chapter will approach the topics of Go/No-Go decision making and Probability of Success evaluation from a general CSE perspective. Several proof-of-concept or Phase II trials will be used to illustrate the optimization procedures based on the general CSE approach.

[Mediana R package](http://gpaux.github.io/Mediana) has been widely used to implement the case studies presented in this book. The detailed description and R code of these case studies are available on the package's website.

**References:**

Benda, N., Branson, M., Maurer, W., Friede, T. (2010). Aspects of modernizing drug development using clinical scenario planning and evaluation. Drug Information Journal. 44, 299–315.

Dmitrienko, A., Pulkstenis, E. (editors). (2017). Clinical Trial Optimization Using R. Chapman and Hall/CRC Press, New York.

Friede, T., Nicholas, R., Stallard, N., Todd, S., Parsons, N.R., Valdes-Marquez, E., Chataway, J. (2010). Refinement of the clinical scenario evaluation framework for assessment of competing development strategies with an application to multiple sclerosis. Drug Information Journal. 44, 713–718.

Gautier Paux and Alex Dmitrienko. (2017). Mediana: Clinical Trial Simulations. R package version 1.0.7. [http://gpaux.github.io/Mediana/](http://gpaux.github.io/Mediana)

