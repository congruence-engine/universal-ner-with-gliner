## NER Datasets
This file contains datasets created at various stages of the NER/GLiNER investigation for the purpose of fine-tuning a GLiNER model. Some of these datasets have been optimised for fine-tuning a [GLiNER model](https://github.com/urchade/GLiNER), while others were produced in the course of data gathering but may still prove useful for other cultural heritage NER projects. 

You can view the GLiNER model fine-tuned by the *Congruence Engine* project [here](https://huggingface.co/congruence-engine/gliner_2.5_textile_industry_historic).

## Overview
Datasets contained here:
* ***all-glossaries-classified-6-dec-4o-OR.csv***: a CSV file containing extracted terms and definitions from textile glossaries in four specialist books published in the United Kingdom and the United States between 1884 and 1932.
* ***synthetic_data_glossaries_pile_ner_6_dec.json***: a json file containing synthetic data generated with GPT-4o using the terms extracted from textile glossaries in four specialist books published in the United Kingdom and the United States between 1884 and 1932. A version of this is available on [Huggingface](https://huggingface.co/datasets/max-long/textile_glossaries_and_pile_ner). 
* ***combined_new_4_october_all.csv***: a CSV file containing a combination of synthetic data generated with GPT-4o based on terms extracted from textile glossaries, and labelled text snippets from Roberts Beaumont's [*Woollen and Worsted Cloth Manufacture*](https://archive.org/details/woollenandworst00beaugoog/page/n7/mode/2up) (1890). You can find a copy of this on [Huggingface](https://huggingface.co/datasets/max-long/textiles_combined_ner_4_oct/tree/main). 
