# Language-Detection-using-Natural-Language-Processing

Dataset can be found here [http://www.statmt.org/europarl/](http://www.statmt.org/europarl/)

The primary goal of this project is to develop a system capable of accurately classifying text written in 19 distinct languages.

Initially, the project involves gathering diverse datasets, all accessible through the above-specified link. These datasets are then combined to create a comprehensive and varied corpus of text examples. The subsequent step revolves around preprocessing the amassed text. This preprocessing phase includes tasks such as text cleaning, tokenization, and potentially stemming or lemmatization, in order to standardize the text and ensure uniformity.

One pivotal element of the project is the utilization of a vectorizer. This tool transforms the processed text data into numerical representations that machine learning algorithms can understand and operate on. This step is crucial as it bridges the gap between the textual nature of the data and the mathematical operations that algorithms perform.

For the actual classification task, two distinct algorithms are employed: Multinomial Naive Bayes and Decision Tree Classifier. The culmination of these efforts is impressive: a remarkable accuracy of 97% is achieved when evaluating the system's performance on test data. This accuracy score serves as a testament to the robustness and effectiveness of the implemented approach in accurately discerning the languages of the provided text samples.
