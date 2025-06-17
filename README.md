# llm-cluster (Under Construction)

This is the repo about using LLM as the backbone for clustering problems.

datasets/

    - clinicSmallCleaned_4472samples_150topics.csv -> this is the manual cleaned version of the original clinic data from Zhang et al. (2023). We removed the mis-labelled records documented in clinicSmall_correction_notes.csv

    - clinicSmall_correction_notes.csv -> documented the mis-labelled records for the original clinic data.

    - codex review -> data augmentation: remove sensitive information and split the multi-topic reviews to multiple 1 topic review. Only maintain those comments regarding the presentation, remove the follow-up discussion under a specific comment. Remove duplicate results.

results/

    - clinicSmallCleaned -> stored the 5 independent output results from our method

