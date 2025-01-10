# Universal Named Entity Recognition (NER) with GLiNER

## Short summary
This repository documents the Congruence Engine’s experiments with fine-tuning a version of [GLiNER (Generalist and Lightweight Model for Named Entity Recognition)](https://github.com/urchade/GLiNER). This Named Entity Recognition (NER) model is part of a new wave of NER models commonly referred to as ‘Universal NER’ – the key distinction from traditional NER being that the model is not restricted to previously established entity types, but can extract entities based on user-defined labels. 

You can view the fine-tuned model developed by the project (along with documentation) by visiting its [model card on Huggingface](https://huggingface.co/congruence-engine/gliner_2.5_textile_industry_historic). 



## Research questions:
- How useful are Universal NER models in the context of museums cultural heritage?
- What kinds of linkage do these new models lead to?


## People
**Max Long**

Investigation, Data curation, Formal analysis, Methodology, Writing

**Arran Rees** 

Investigation, Data curation, Formal analysis, Methodology, Writing

**Kaspar Beelen**

Methodology, Software 

**Ben Russell**

Data curation


## Data sources (used or developed)
- GLiNER machine learning NER models (Huggingface)
- Textile machinery datasets from the Science Museum Group, National Wool Museum, and Bradford Industrial Museum. 
- Historic textile glossaries sourced from archive.org.
- Sample data from the [Pile-NER-type](https://huggingface.co/datasets/Universal-NER/Pile-NER-type) dataset. 


## Investigation methods/ tools/ code/ software 
- Named Entity Recognition (NER)
- Text Classification
- Large Language Models including Chat GPT
- Huggingface


## Outputs  
- [Fine-tuned GLiNER model](https://huggingface.co/congruence-engine/gliner_2.5_textile_industry_historic)
- Huggingface demo of the fine-tuned model in action
- Google Colab notebook tutorial on how to fine-tune the model in the context of cultural heritage
- Forthcoming book chapter in *Emergent Histories: New Work in the Digital History of Industry and Collections from the Congruence Engine Project*


## Licence 
This work is licensed under a [Creative Commons Attribution 4.0 License - CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
