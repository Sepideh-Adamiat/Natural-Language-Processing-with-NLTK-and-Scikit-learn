# Natural-Language-Processing-with-NLTK-and-Scikit-learn

This is a sentiment analysis project using NLTK and Scikit-learn libraries. In this jupyter notebook, well-known machine learning algorithms are trained on a Twitter dataset and then applied to the "The National University of Singapore SMS Corpus dataset".

Finally, the percentage of positive and negative messages is compared based on 10 different countries.

## Requirements:
All python packages needed are listed in requirements.txt file and can be installed simply using the pip command.

- [pandas](https://pandas.pydata.org/)
- [Nltk](https://www.nltk.org/)
- [re](https://docs.python.org/3/library/re.html)
- [wordcloud](https://pypi.org/project/wordcloud/)
- [numpy](http://www.numpy.org/)
- [Scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](https://matplotlib.org/)
 
## Data:
Public access to the dataset is provided by The National University of Singapore. This dataset contains 67,093 text messages (SMSs) taken from the corpus on Mar 9, 2015 and mostly is comprised of messages from Singaporeans and students attending the University. You can download it from [this](https://static-assets.codecademy.com/skillpaths/nlp/portfolio-project/clean_nus_sms.csv.zip).
 
## Roadmap
### Preprocessing 
- Changing to lowercase and removing punctuation,
- Removing empty messages
- Tokenizing the messages
- Removing stopwords
- Creating bag of word(BOW)
- Vectorizing
And for better visualization of the dataset, the word clouds of positive and negative sets are plotted.

### Training the classifiers
Eight well-known machine learning classifiers are trained on the Twitter dataset, and the accuracy of the validation set is printed in a table. The models are built with the Scikit-Learn library.


### Testing and printing the results

The classifiers are applied to the dataset from the National University of Singapore, and the calculated predicted negative and positive percentages are printed for the entire dataset as well as for each country.
 
 
 
## Acknowledgment:
This project is done as the proposed portfolio of https://www.codecademy.com/learn/paths/natural-language-processing.
