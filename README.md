# Spyridon Mouselinos

_Machine Learning and Software Engineer_

[Email](mailto:mouselinos.spur.kw@gmail.com) / [LinkedIn](https://www.linkedin.com/in/spyridon-mouselinos/) / [GitHub](https://github.com/SpyrosMouselinos) / [Scholar](https://scholar.google.com/citations?user=D6TDBuUAAAAJ&hl=en)


## 💼 Academic Experience
(Oct  2021 – Now): **PhD Student, University of Warsaw**<br>
**Research Area:** Reasoning in Deep Learning Models<br>
My research focuses on the exploration of reasoning capabilities of deep learning models in the challenging modalities of vision, language as well as their interplay.
<br><br>
- My initial project, **Measuring CLEVRness: Black-box Testing of Visual Reasoning Models**, showcased at **ICLR 2022**, aimed to advance our grasp of reasoning in visual-language scenarios through a novel dual-agent setup. This method, diverging from standard visual QA and adversarial tests, bypasses the need for direct model access like gradients or probabilities. Instead, inspired by zero-sum game theory, it transforms a visual question-answering scenario into a contest between a reasoning agent and a scene-manipulating agent, evaluating reasoning via significant, context-relevant scene changes.  Thus, we unveiled the shortcomings of prevalent data-driven approaches, challenging the accuracy of their claimed super-human visual QA performances. By analyzing agent interactions, we also uncovered model biases masquerading as logical reasoning. Ultimately by leveraging these results, we introduced fine-tuning strategies, leading to more robust multimodal reasoning akin to human processes.<br>
- In the subsequent work,  **A Simple, Yet Effective Approach to Finding Biases in Code Generation** presented at **ACL 2023**, we explored the reasoning capabilities of various Large Language Models within the evolving and critical field of code generation. Our work breaks new ground by formalizing and evidencing three primary bias sources in coding challenges, termed *Blocks of Influence*: function names, problem specifications, and examples. A novel framework designed to automate the assessment of LLMs was introduced, revealing issues related to models' over-reliance on example demonstrations, biases in naming conventions, and difficulties in linking language descriptions to corresponding tasks. By investigating several open-source models, we validated our claims by managing to pinpoint the exact sources of memorized code and naming dependence in their datasets. Building on these insights, we utilized these identified biases as training augmentations against various open-source LLMs. We achieved significant robustness against such phenomena, reflected in improved coding abilities across all tested models.<br>
- In my latest study, **Beyond Lines and Circles: Unveiling the Geometric Reasoning Gap in Large Language Models**, we delved into the intricate world of constructive geometry with LLMs, introducing three key methodological innovations. Our first innovation is a dynamic prompting technique inspired by Retrieval Augmented Generation, significantly improving LLMs' adaptability and contextual awareness. Based on their relevance in solving progressively complex problems, this technique uses past interactions and reranks results. Secondly, we introduced a novel prompting technique that effectively tackles LLMs' need for 2D spatial awareness, facilitating precise problem extraction and applicability to models without inherent visual capabilities. Finally, the centerpiece of our research is the novel multi-domain and multi-role agent framework. Our approach demonstrates significant improvements in performance on mathematical and geometric QA tasks, outperforming vanilla multi-agent systems and setting new benchmarks for the complex problem-solving capabilities of LLMs. Crucially, our methodologies prove highly transferable to smaller LLMs, which greatly benefit from the enhanced reasoning and problem-solving capacities introduced by our innovations.
<br><br>

(Oct  2021 – Now): **Teaching Assistant, University of Warsaw**<br>
Responsible for conducting laboratories in the *Natural Language Processing* 
and *Visual Recognition* courses of master’s degree study cycle in University of Warsaw.
Proud to have supervised the creation of the student project: Distilled HerBert (https://huggingface.co/BartekK/distilHerBERT-base-cased) a BERT-based Language Model trained on Polish Language.
<br><br>


(March 2021 – Oct 2021): **Research Assistant, University of Warsaw** <br>
**Research Area:** Visual Reasoning and Neurosymbolic Approaches. <br>
Under the supervision of Henryk Michalewski and Mateusz Malinowski,
we investigate the effect of Neurosymbolic Neural Networks as well as 
Adversarial Agents towards testing the limits of VR/VQA tasks.
During this work, an interactive application that acts as a neural 
network testbed has been created, enabling better understanding of
pretrained visual reasoning architectures.
<br><br>

## 🔧 Work Experience
(Nov 2018 – February 2021): **Lead Machine Learning Engineer** - Deepsea Technologies (https://deepsea.ai/) <br>
As a Lead, I was responsible for the following projects:<br>
-	Uncertainty Estimation/ Anomaly Detection.<br>
Used Deep Quantile Networks to forecast and report anomalies on tankers and cargo ships of 5 major 
worldwide corporations. Proposed better engine usage schemas and reduced fuel costs by 4%, as well as
detected oil-theft on various ships.<br>

-   Deep Learning Based Ship Route Optimization.<br>
Used Generative Adversarial Networks to Simulate Ship Performance 
under different weather conditions and created a better Deep Learning
boosted variant of the Graph Based A*(A star) algorithm. Managed to 
automatically create routes for over 100 ships at real-time, with the algorithm 
outperforming current competitor solutions by 8-10%.<br>

-	AIS System Based - Fuel and Hull Fouling Estimation over Sparse Data.
Used Time Series Deep Neural Networks and Feature Engineering based on Geolocation
Trajectories in order to report fuel consumption and power consumption based solely 
on sparse and corrupt AIS Data. Created a robust system that can classify performance 
deterioration and assess the overall state of a ship.
<br><br>

(Dec 2017 – Nov 2018): **Machine Learning Engineer** - Deepsea Technologies (https://deepsea.ai/)<br>
As an ML Engineer, I was responsible for the following projects:<br>
-	Product Pipeline Design.<br>
Successfully containerized and published all Deep Learning Projects with Docker and Flask. 
Created a multi-worker high-availability system with Gunicorn, and balanced incoming traffic using Nginx.
Finally, all projects were deployed on AWS Cloud and a combination of Jenkins and Coverage were used 
to maintain CI/CD. That lead to the creation of a “click-and-play” Deep-Learning  project base for over 200 
ships and 5 different companies.<br>

-	Modeling “Aging” Phenomenon on Mechanical Parts.<br>
In this project we aimed to model the magnitude of  “aging” on different mechanical parts 
and automatically suggest their Remaining Useful Life (RUL).
We used a combination of classical Machine Learning and Dilated Convolutional Neural Networks 
and built a real-time monitor/tracker that was deployed on every ship. By suggesting maintenance 
and repair we reduced costs of ship maintenance by 10%.
<br><br>

## 📜 Publications
**Beyond Lines and Circles: Unveiling the Geometric Reasoning Gap in Large Language Models** <br>
[LINK](https://arxiv.org/abs/2402.03877)<br>
**A Simple, Yet Effective Approach to Finding Biases in Code Generation** _(ACL 2023)_<br>
[LINK](https://arxiv.org/abs/2211.00609)<br>
**Measuring CLEVRness: Blackbox testing of Visual Reasoning Models** _(ICLR 2022)_<br>
[LINK](https://arxiv.org/abs/2202.12162)<br>
**MAIN: Multi-Head Attention Imputation Networks** _(IJCNN 2021)_<br>
[LINK](https://arxiv.org/pdf/2102.05428.pdf)<br>
**Optimized Generation of Hardware CNN Inference Engines** _(MDPI Technologies 2020)_<br>
[LINK](https://www.mdpi.com/2227-7080/8/1/6)<br>
**TF2FPGA: A Framework for Projecting and Accelerating CNNs on FPGA Platforms** _(IEEE Mocast 2019)_<br>
[LINK](https://ieeexplore.ieee.org/document/8741940)
<br><br>



## 💬 Languages
**Greek**: Native <br>
**English**: C2 <br>
**German**: B1 <br>
<br><br>

## 🏫 Education
**PhD Studies** Topic: Reasoning in Deep Learning Models<br>
[University of Warsaw](https://www.mimuw.edu.pl/) _(Apr 2021 - Now)_<br>
Supervisors: Henryk Michalewski and Mateusz Malinowski<br>

**Master of Science** in Data Science and Machine Learning<br>
[Athens University of Economics and Business](https://datascience.aueb.gr/)_(2019 - 2021)_<br>

**Summer School** - Graph Theory and Randomized Computing <br>
[Gdańsk Technical University](https://pg.edu.pl/en)_(2019)_<br>

**Bachelor and Master of Engineering** in Electrical and Computer Engineering<br>
[National Technical University of Athens](https://www.ece.ntua.gr/en)_(2013-2018)_<br>