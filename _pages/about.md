---
permalink: /
title: "Basic Information"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**<font size=5>Highest Education:</font>**

&emsp;MSE in Data Science at University of Pennsylvania;  GPA: 3.97

**<font size=5>Areas of Expertise:</font>**
1. **Learning Science** and **Cognitive Science** (6 years of experience, B.S., M.Ed)
    - Human Learning and Knowledge Storage
    - Learning Task Design
2. **Natural Language Processing** (3 years of experience, MSE)
    - Event Extraction
    - Event Reasoning in Natural and Symbolic Language<br>
      <font size=3>e.g. Schema Generation, Event and Entity Pre- and Post- Condition Generation</font>

------

# Publications
- [Human-in-the-Loop Schema Induction.](https://aclanthology.org/2023.acl-demo.1.pdf)
    **Tianyi Zhang**, Isaac Tham, Zhaoyi Hou, Jiaxuan Ren, Liyang Zhou, Hainiu Xu, Li Zhang, Lara J. Martin, Rotem Dror, Sha Li, Heng Ji, Martha Palmer, Susan Brown, Reece Suchocki, Chris Callison-Burch. ACL Demo 2023
    
- [PROC2PDDL: Predicting Domain Definitions Based on Natural Language for Symbolic Planning.](https://tianyi0608.github.io/tianyizhang/files/proc2pddl.pdf)
    **Tianyi Zhang**, Li Zhang, Zhaoyi Hou, Ziyu Wang, Yuling Gu, Peter Clark, Chris Callison-Burch, Niket Tandon. 2023, In submission

- [Argument Role Labelling Question-Answer Pair Data Augmentation.](https://tianyi0608.github.io/tianyizhang/files/AE-QG.pdf)
    **Tianyi Zhang**, Elior Sulem, Dan Roth. 2023, In submission

------

# Education
  - MSE in Data Science,   Jan. 2021 - Dec. 2022<br>
    <font size=3>University of Pennsylvania, Philadelphia, America</font>
  - M.Ed in Learning Science and Technology,   Sept. 2018 - Dec. 2019<br>
    <font size=3>University of Pennsylvania, Philadelphia, America</font>
  - B.S in Educational Technology,   Sept. 2014 - Jun. 2018<br>
    <font size=3>Beijing Normal University, Beijing, China</font>

------

# Research Experience

1. **Research Assistant: NLP Group at UPenn**, May. 2022 - Jul. 2023
    - Event **schema generation** using GPT-3
      <blockquote style="font-style:normal;"><font size=3>
        <ul>
        <li><strong>Design the scaffold prompts</strong> (cause, plan, procedure, effect, etc.) for GPT-3 to generate inclusive events</li>
        <li>Apply SRL and constituency parsing to summarize and <strong>extract structured events</strong></li>
        <li>Build schema graphs by adding temporal relations to the events</li>
        <li><strong>Ground the graph nodes</strong> into the ontology through the semantic inference or the semantic similarity</li>
        <li>Outcome: "Human-in-the-Loop Schema Induction" paper</li>
        </ul>
      </font></blockquote>
    - Natural language to **symbolic language** translation for **reasoning**
      <blockquote style="font-style:normal;"><font size=3>
        <ul>
        <li>Focus on open-domain natural language (wikiHow) to symbolic language (PDDL) generation with GPT-4</li>
        <li><strong>Decompose the task</strong> into three stages: extraction, inference, and translation</li>
        <li>Identify strong <strong>text extraction and entity states inference</strong> abilities with increasingly complex wikiHow text (~5000 words)</li>
        <li>Acknowledge a weak <strong>translation capability</strong> to predefined symbolic pattern</li>
        <li>Improve the performance using <strong>CoT</strong> and <strong>instructions</strong> on translation.</li>
        <li>Outcome:"PROC2PDDL" paper</li>
        </ul>
      </font></blockquote>
2. **Research Assistant: Cognitive Computation Group at UPenn**, Mar. 2020 – Dec. 2022   
    - Event **trigger identification** and **classification** using **sequence tagging**
      <blockquote style="font-style:normal;"><font size=3>
        <ul>
        <li>Build 1-of-N (72) joint model and <strong>BIO identification + event type classification</strong> pipeline model</li>
        <li><strong>Transfer learning</strong> with target language auxiliary dataset, e.g. OntoNotes Arabic</li>
        </ul>
      </font></blockquote>
    - Event **argument identification** and **classification** using **QA**
        <blockquote style="font-style:normal;"><font size=3>
        <ul>
        <li><strong>Design fixed questions</strong> for each argument role and convert argument role labeling task to question answering task</li>
        <li>Build has-and-no-answer joint model and <strong>has/no answer classification + has answer identification</strong> pipeline model</li>
        <li>Transfer learning with auxiliary QA dataset, e.g. SQuAD, QAMR</li>
        </ul>
      </font></blockquote>
    - Event **data augmentation** using **answer extraction (AE)** and **question generation (QG)**
        <blockquote style="font-style:normal;"><font size=3>
        <ul>
        <li>Train <strong>AE-QG T5 model</strong> to extract QA pairs from unlabeled event text</li>
        <li>Train <strong>AEwSRL-QG Bert-T5 model</strong> to extract QA pairs from unlabeled event text</li>
        <li><strong>Evaluate on joint-QA and pipeline-QA model</strong> and prove effectiveness of the above data augmentation approach</li>
        <li>Paper in submission</li>
        </ul>
      </font></blockquote>

