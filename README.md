# AWESOME Bibliography: NLP for Electronic Health Record

Papers and Resources for NLP for Electronic Health Record

## Presentation Papers

[**ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission**](https://arxiv.org/pdf/1904.05342.pdf)
This paper gives a method to learn the representation of clinical notes by applying BERT to clinical text. BERT is first pre-trained using clinical notes and then fine-tuned to predict 30-day readmissions over time to obtain ClinicalBERT. This paper suggests that ClinicalBERT can learn relationships between medical concepts.

[**On the Automatic Generation of Medical Imaging Reports**](https://www.aclweb.org/anthology/P18-1240.pdf)
This paper proposes a multitask framework to to automate the generation of medical imaging reports, producing the sections of impressions, findings and tags. A coattention mechanism is also proposed to localize the image and write image captions. Finally, a hierarchical LSTM consisting of sentence LSTM and word LSTM is also proposed to generate paragraphs in the findings section.


[**MEDTYPE: Improving Medical Entity Linking with Semantic Type Prediction**](https://arxiv.org/pdf/2005.00460.pdf)
This paper introduces a method to filter out medical entity that is impossible for a word to belong to using semantic type prediction, to improve the candidate generation task within medical entity linking. MEDTYPE is pre-trained on WIKIMED and then finally finetuned on on medical text. It then takes in mentions and candidate concepts to predict the semantic type of the mention based on their context.


[**Learning the Graphical Structure of Electronic Health Records with Graph Convolutional Transformer**](https://arxiv.org/pdf/1906.04716.pdf)
This paper suggests a way to exploit EHR's implicit graph structure in different tasks. If the graph structure of an EHR is unknown as is often the case, graphical convolution transformer is used which starts with the assumption that all nodes are connected and rules out the nodes that don't represent the hierarchical structure of EHR. Conditional probabilities between nodes are calculated to determine EHR structure.

[**COVID-19 Literature Knowledge Graph Construction and Drug Repurposing Report Generation**](https://arxiv.org/pdf/2007.00576.pdf)
This paper introduces a new knowledge discovery framework to extract fine-grained multimedia elements from scientific papers and articles. The knowledge graph is then used for question answering and report generation. First, the paper applies coarse-grained entity extraction and entity linking to extract the relations between concepts. It proposes using figure-separator to separate images and then cross-modal entity grounding to connection captions and visial objects. The information is then presented using a knowledge graph.

## Background Material

Neural Natural Language Processing for Unstructured Data in Electronic Health Records: a Review (to be published)
In this paper, latest applications of NLP to EHR are discussed. This paper has a comprehensive coverage of fields of EHR NLP, including phenotyping, outcome prediction, embeddings, etc and covers an impressive collection of over 260 papers.

[**GRAM: Graph-based Attention Model for Healthcare Representation Learning**](https://arxiv.org/pdf/1611.07012.pdf)
This paper introduces a graph-based attention model to extract hierarchical information of EHR, representing a medical concept as a combination of its ancestors using attention mechanism.

[**De-identification of patient notes with recurrent neural networks**](https://academic.oup.com/jamia/article/24/3/596/2769353)
This paper introduces a method to de-identify EHR using recurrent neural network based on the CRF model to replace previous rule-based approaches.

[**Deep EHR: A Survey of Recent Advances in Deep Learning Techniques for Electronic Health Record (EHR) Analysis**](https://arxiv.org/pdf/1706.03446.pdf)
This paper surveys various deep learning techniques applied to EHR analysis, and gives a clear categorization of EHR tasks including information extraction, representation learning, outcome prediction, phenotyping and de-identification.

[**Readmission Prediction via deep contextual embedding of clinical concepts**](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0195024)
This paper proposes CONTENT, a neural model to predict hospital readmissions by capturing both local and global contexts using a Topic Recurrent Neural Network (TopicRNN).


## Additional Resources

-	MIMIC dataset (https://mimic.physionet.org)
-	PubMed (https://catalog.data.gov/dataset/pubmed)
-	MIMIC-CXR Database (https://physionet.org/content/mimic-cxr/2.0.0/)
- ICD-10 Conversion and Mapping (https://www.aapc.com/icd-10/conversion-mapping.aspx)
- Billing and Coding (https://www.audiologyonline.com/articles/billing-and-coding-2015-update-14038)
- De-identification of Electronic Health Records using NLP (https://medium.com/nedap/de-identification-of-ehr-using-nlp-a270d40fc442)
- Electronic Health Records-Based Phenotyping (https://rethinkingclinicaltrials.org/chapters/conduct/electronic-health-records-based-phenotyping/definitions/)
- Electronic Health Records-Based Phenotyping - References (https://rethinkingclinicaltrials.org/chapters/conduct/electronic-health-records-based-phenotyping/definitions/#references)