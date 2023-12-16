# Data Science Thesis Work - Classification of Companies industries by leveraging text and free datasets and datasources available

Retrieve text data from company websites for classification. These steps collectively contribute to a comprehensive framework for classifying companies based on the content of their websites, incorporating web scraping, NLP, machine learning, and visualization techniques.

The application of these tools lies in the domain of data science and natural language processing (NLP), with a specific focus on classifying companies by industry based on the content extracted from their websites. The initial web scraping process is designed to systematically gather textual information from diverse company websites, creating a rich dataset that reflects the linguistic nuances and thematic variations across industries. The subsequent application of NLP tools, including lemmatization, stopwords handling, and tokenization, ensures the transformation of raw text into structured and analyzable data.

The integration of topic modeling techniques, such as Latent Dirichlet Allocation (LDA) and word embeddings through Gensim, adds a layer of sophistication to the analysis. These methods facilitate the identification of latent topics within the textual data, revealing the inherent themes and subject matter prevalent across different industries. Furthermore, the use of BERT, a state-of-the-art transformer model, enhances the natural language processing capabilities, enabling a more nuanced understanding of the textual content and fostering improved classification accuracy.

The classification framework, implemented using the TensorFlow machine learning framework, leverages the derived features and insights to categorize companies into industry segments. The process is not only confined to categorization but extends to uncovering relationships, patterns, and similarities among companies based on their online presence. This comprehensive approach to text classification not only aids in organizing and structuring large datasets but also serves as a valuable tool for industry analysis, market research, and business intelligence, contributing to the broader landscape of data-driven decision-making in the corporate sector.

See below clarification of techniques used in this project. 

Web Scraping:
Use Python with requests and BeautifulSoup for website content extraction. Ensure extraction of English text from websites.

Data Processing Libraries:
Utilize libraries like pandas for data manipulation and NumPy for numerical operations.

NLP Processing:
Apply Natural Language Toolkit (NLTK) for text processing tasks.
Implement lemmatization, stopwords handling, and tokenization.

Vectorization:
Convert text data into numerical vectors using CountVectorizer.

Dimensionality Reduction:
Use manifold for dimensionality reduction in the data.

Visualization:
Employ Matplotlib and Seaborn for data visualization.

Word Embeddings:
Utilize Gensim for topic modeling and document similarity.

BERT for NLP:
Implement BERT for natural language processing tasks using Transformers library.

Latent Dirichlet Allocation (LDA):
Apply LDA for topic modeling and unsupervised classification.
Use LDA for uncovering underlying themes in textual data.

TensorFlow Framework:
Use TensorFlow for machine learning applications in text classification.

Model Evaluation:
Leverage scikit-learn for metrics and evaluation of machine learning models.
