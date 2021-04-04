# Medical Transcription Keywords Extraction
#### _The aim of this repository is mainly to extract keywords from medical transcription. The dataset obtained from an open medical transcription dataset._

#
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H146AUD)
#

## Preprocessing
Remove symbols, stopwords, empty spaces after comma, multiple spaces, etc. Basicly it will keep only the words with a single space separator. The clean dataset  [here](https://github.com/nadhirfr/medical_transcript_keyword_extract/blob/main/datasets.csv)

## The model
- Pipeline
-- Vectorize the word
-- TF-IDF Transformer
-- OneVsRestClassifier with SGD Classifier
- Input: ```['a string sentences', 'another string sentences']```
- Output: ```['keywords separated by a single space', 'another extracted keywords']```
- Serialized model here [here](https://github.com/nadhirfr/medical_transcript_keyword_extract/blob/main/sgd_pipeline1.pkl)

## Credits

We used a number of open source projects to work properly:

- [Datasets] - Where the story begin!
- [Sklearn] - The most used machine learning Framework
- [NLTK] - Linguistic libray.
- [Pandas], [Keras], [Numpy], and many others

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [Datasets]: <https://www.kaggle.com/tboyle10/medicaltranscriptions>
   [Sklearn]: <https://scikit-learn.org/>
   [NLTK]: <https://www.nltk.org/>
   [Pandas]: <https://pandas.pydata.org/>
   [Keras]: <https://keras.io/>
   [Numpy]: <https://numpy.org/>
   
