# Indonesian-Quran-Entity-Linking-IndQEL-

This research discusses the role of knowledge base in artificial intelligence, focusing on entity linking. In the context of constructing a knowledge base, entity linking is the process of linking named entity mentioned in the text to relevant entities in the knowledge base. This process involves identifying named entity and linking entity in the text and connecting them to related entity in the knowledge base, such as Wikipedia or Freebase.

In the context of Indonesian translation of the Quran, the IndQNER study has constructed a guideline dataset for named entity recognition. However, there is currently no guideline dataset for entity linking, and the author proposes the development of a guideline dataset for entity linking in Indonesian translation of the Quran (IndQEL).

The research methodology includes selecting the IndQNER dataset as a reference, creating guidelines for labeling named entity, and the labeling process involving students majoring in Quranic exegesis. The evaluation of labeling results is done manually by comparing the results from two labelers. The evaluation outcomes serve as the basis for developing the IndQEL guideline dataset.

The author also conducts experiments on a multilingual entity linking system to assess the quality of the IndQEL guideline dataset. The experiments involve the MAG system and the GERBIL platform. MAG generates 1933 links from 2456 named entities and 523 NIL entities in the IndQEL dataset. The experimental results indicate that the IndQEL dataset can serve as a reliable metric for evaluating named entity disambiguation systems. The WAT application from GERBIL is identified as the best application, achieving a recall of 0.7486 and an F1 score of 0.7573.

Overall, this research successfully constructs a guideline dataset for named entity disambiguation in the translation of the Al-Quran into Indonesian (IndQEL) and proves its quality through experimental evaluation. This dataset is expected to be a significant contribution to the development of Natural Language Processing (NLP) technology in the fields of Islam and Al-Quran translation.

# Annotation Stage

The manual annotation of IndQEL, in Indonesian Translation of Al-Quran, was carried out by non-volunteer native speakers. The annotators comprised students in their fourth year of bachelor studies from the Quran and Tafseer department at State Islamic University Syarif Hidayatullah Jakarta. There were 2 annotators as follows:

1. Rosyidatul Liulinnuha
2. Azmi Muchtar

# Experiment

To showcase the utility of IndQEL as a benchmark dataset, it was used to evaluate cutting-edge EL systems in multilingual settings using the GERBIL framework. The EL systems included Babelfy, DBpedia Spotlight, MAG, and WAT. Steps to perform the evaluation can be found <a href="https://github.com/dice-group/gerbil/wiki/How-to-setup-GERBIL">here</a>. Evaluation results are as follows:
