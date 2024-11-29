**Sentiment Analysis and Topic Modeling of Customer Reviews**
This repository focuses on analyzing customer reviews to classify sentiments and identify key topics, providing actionable insights for product and service improvements. It leverages advanced NLP techniques and machine learning models to uncover hidden patterns in textual data.

**Overview**
The project explores various machine learning and NLP techniques to perform sentiment analysis and topic modeling on customer reviews. It highlights the transition from traditional models using BERT embeddings to fine-tuning BERT for enhanced performance. Key features include:

**Sentiment Classification:** Achieving high precision and recall through models like XGBoost and Gradient Boosting, optimized for imbalanced datasets.
Topic Modeling: Using LDA to identify core customer concerns.
**BERT Fine-Tuning:** Enhancing classification performance by directly training on customer review data.

**Implementation**
**Step-by-Step Approach:**
**Gradient Boosting Classifier:**
Explored and tuned to handle class imbalance effectively.
**XGBoost:**
Utilized its built-in scale_pos_weight parameter to address imbalanced data issues.
**Transition to BERT Fine-Tuning:**
Moved from pre-trained BERT embeddings with XGBoost to directly fine-tuning BERT on the dataset, aiming for improved sentiment classification accuracy.

**Results**
**Sentiment Analysis:**
Achieved 82% accuracy using FinBERT for overall sentiment classification.
Improved precision to 85% and recall to 80% with BERT embeddings and XGBoost.
**Topic Modeling:**
Identified five key topics in customer reviews with LDA, highlighting pain points in product quality and service.
**BERT Fine-Tuning:**
Demonstrated enhanced classification performance over BERT embeddings combined with traditional ML models.

**Technologies and Tools**
**NLP Models:** FinBERT, BERT (embeddings and fine-tuning)
**Machine Learning Frameworks:** XGBoost, Gradient Boosting
**Topic Modeling:** Latent Dirichlet Allocation (LDA)
**Programming:** Python
**Key Libraries:** Transformers, Scikit-learn, Gensim, Pandas, NumPy

**Usage**
Clone this repository and follow the step-by-step guide in the provided notebook to replicate results or adapt the methods for your own datasets.

**Contributions**
Contributions are welcome! If you'd like to improve the implementation, feel free to open an issue or submit a pull request.

**License: ** This project is licensed under the MIT License.
