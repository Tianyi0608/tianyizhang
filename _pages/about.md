---
permalink: /
title: "Tianyi Zhang's personal website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

------

# Basic Information
## Highest Education: 
MsE in Data Science at University of Pennsylvania;  GPA: 3.97
## Knowledge Background:
1. Learning Science and Cognitive Science (6 years experience: B.S., M.Ed)
    - Human Learning and Knowledge Storage
    - Learning Task Design
2. Natural Language Processing (3 years experience: M.E)
    - Event Extraction
    
      e.g. Event and Argument Identification and Classification

    - Event Reasoning in Natural and Symbolic Language
    
      e.g. Schema Generation, Event and Entity Pre- and Post- Condition Generation

------

# Publication
"Human-in-the-Loop Schema Induction."
Tianyi Zhang, Isaac Tham, Zhaoyi Hou, Jiaxuan Ren, Liyang Zhou, Hainiu Xu, Li Zhang et al. (ACL Demo 2023)
"PROC2PDDL: Predicting Domain Definitions Based on Natural Language for Symbolic Planning."
Tianyi Zhang, Li Zhang, Zhaoyi Hou, Ziyu Wang, Yuling Gu, Peter Clark, Chris Callison-Burch, Niket Tandon. (2023, In submission)

------

# Education
  - M.S in Data Science, Jan. 2021 - Dec. 2022
  
    University of Pennsylvania, Philadelphia, America
  
  - M.Ed in Learning Science and Technology, Sept. 2018 - Dec. 2019
  
    University of Pennsylvania, Philadelphia, America
  
  - B.S in Educational Technology, Sept. 2014 - Jun. 2018
  
    Beijing Normal University, Beijing, China

------

# Research Experience

1. **Research Assistant: NLP Group at UPenn**, May. 2022 -
    - Event schema generation using GPT-3
        - Design the scaffolds (cause, plan, procedure, effect, etc.) for GPT-3 to generate inclusive events
        - Apply SRL and constituency parsing to summarize and extract structured events
        - Build schema graphs by adding temporal relations to the events
        - Outcome: "Human-in-the-Loop Schema Induction" paper
    - Natural language to symbolic language translation for reasoning
        - Focus on open-domain natural language (wikiHow) to symbolic language (PDDL) generation with GPT-4
        - Decompose the task into three stages: extraction, inference, and translation
        - Identify strong text extraction and entity states inference abilities with increasingly complex wikiHow text (~5000 words)
        - Acknowledge a weak translation capability to predefined symbolic pattern
        - Improve the performance using CoT and instructions on translation.
        - Outcome:"PROC2PDDL"paper
2. **Research Assistant: Cognitive Computation Group at UPenn**, Mar. 2020 – Dec. 2022
   <font size=3>
    - Event trigger identification and classification using sequence tagging
        - 1-of-N (72) joint model and BIO identification + event type classification pipeline model
        - Transfer learning with target language auxiliary dataset, e.g. OntoNotes Arabic
    - Event argument identification and classification using QA
        - Design fixed questions for each argument role and convert argument role labeling task to question answering task
        - Has-and-no-answer joint model and has/no answer classification + has answer identification pipeline model
        - Transfer learning with auxiliary QA dataset, e.g. SQuAD, QAMR
    - Event data augmentation using answer extraction (AE) and question generation (QG)
        - Train AE-QG T5 model to extract QA pairs from unlabeled event text
        - Train AEwSRL-QG Bert and T5 model to extract QA pairs from unlabeled event text
        - Evaluate on joint-QA and pipeline-QA model and prove effectiveness of the above data augmentation approach
        - Paper in submission
  </font>


**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
