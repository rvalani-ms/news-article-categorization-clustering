## Unsupervised News Article Categorization using Sentence Transformers

-   The text in news articles and building an unsupervised learning model to categorize them.

-   The categorization performed by the model can then be validated against human-defined labels to evaluate the overall accuracy of the AI system.

-   The goal is to optimize the categorization process, ensuring timely and personalized content delivery.

### Approach

-   The project will use Sentence Transformers for accessing, utilizing, and training embedding and reranker models. Sentence Transformers can compute embeddings that map sentences and paragraphs into a 384-dimensional dense vector space. These embeddings can then be used for tasks such as clustering and semantic search.

-   Additionally, the project will calculate similarity scores using Cross-Encoder models, which are also part of the Sentence Transformers library.

### Project Evaluation

-   A classification report will be used to evaluate key performance metrics such as precision, recall, F1-score, and support for each class.

### Dataset

-   https://www.kaggle.com/datasets/pariza/bbc-news-summary
