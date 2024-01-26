# AGI-P
**AGI-P: A Gender Identification Framework for Authorship Analysis Using Customized Fine-Tuning of Multilingual Language Model**
<br>
<br>
**ABSTRACT**
<br>
In this investigation, we propose a solution for the author’s gender identification task called AGI-P. This task has several real-world applications across different fields, such as marketing and advertising, forensic linguistics, sociology, recommendation systems, language processing, historical analysis, education, and language learning. We created a new dataset to evaluate our proposed method. The dataset is balanced in terms of gender using a random sampling method and consists of 1944 samples in total. We use accuracy as an evaluation measure and compare the performance of the proposed solution (AGI-P) against state-of-the-art machine learning classifiers and fine-tuned pre-trained multilingual language models such as DistilBERT, mBERT, XLM-RoBERTa, and Multilingual DEBERTa. In this regard, we also propose a customized fine-tuning strategy that improves the accuracy of the pre-trained language models for the author gender identification task. Our extensive experimental studies reveal that our solution (AGI-P) outperforms the well-known machine learning classifiers and fine-tuned pre-trained multilingual language models with an accuracy level of 92.03%. Moreover, the pre-trained multilingual language models, fine-tuned with the proposed customized strategy, outperform the fine-tuned pre-trained language models using an out-of-the-box fine-tuning strategy.
<br>
<br>
![Framework of AGI-P Framework](https://github.com/mumairhassan/AGI-P/assets/50833413/76aac3fb-1055-4afa-95db-836cc18dcd12)
<br>
**Proposed Solution Overview:** Gender classification of authors using LightGBM. Gathered news articles annotated with the author's gender. Utilized 80% of the dataset for training and 20% for testing. Feature extraction included 1800-character n-grams and words (2-10 characters in length). Achieved high accuracy with LightGBM's efficient leaf-wise decision trees. Employed entropy as an uncertainty measure for gender prediction, setting thresholds of 0.280 for Punjabi and 0.870 for English datasets.


