# Pfam Protein Sequence Classification

This short project addresses a Kaggle problem focused on classifying protein domain functions using amino acid sequences from the Pfam dataset. The task involves multi-class classification, where each sequence must be assigned to one of approximately 18,000 possible protein families. Given the large dataset and inherent class imbalance, a reduced subset of the 100 most common families was selected to improve computational efficiency.

Two models were implemented and evaluated: a Convolutional Neural Network (CNN) and a Transformer-based model leveraging ESM2 embeddings. The CNN, using one-hot encoded sequences, efficiently captured local sequence features, achieving a high classification accuracy of 99.32%. The Transformer-based model, designed to capture long-range dependencies, achieved a test accuracy of 92.40%, indicating potential for improvement with additional computational resources and hyperparameter tuning.

The solution was specifically designed to run on basic hardware, emphasizing computational feasibility. Early stopping and sequence truncation were used to optimize training efficiency. Results indicate that CNNs are highly effective for protein sequence classification under hardware constraints, while Transformer-based models may offer advantages for larger-scale implementations. Future work could explore enhanced embedding strategies and more powerful architectures to improve generalization across all protein families. Please see the attached pdf for a detailed description of data analysis, method explanation and result analysis.
