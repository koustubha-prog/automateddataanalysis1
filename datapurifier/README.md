<!---
## List of Functions and Class In Auto EDA.
-->

### An Automated Exploratory Data Analysis Library For Machine Learning and Deep Learning in Python.

## Steps in Auto EDA

- [x] 1. **Shape** of dataset
- [x] 2. **Sample** of dataset
- [x] 3. **Number of categorical and numerical** attributes
- [x] 4. **Null values** in the dataset (number & %) => recommend to drop higher %
- [x] 5. **Value count** of attribute (unique) in the dataset
- [ ] 6. **Describe** the data (5 point summary) => inference (min, max, dist) => recommend columns to watch out for => outliers.
- [ ] 7. **Distribution** of dataset
        a. Skewed or Normal
- [ ] 8. Perform **grouping/aggregation** wherever necessary 
- [ ] 9. **Recommend Columns** or attribute to remove
        a. Column with all value as unique (e.g: ID)
- [ ] 10. Give **insight from the data** and suggest ml algorithms, techniques, cleaning, etc hints, tips and tricks
- [x] 11. **Correlation** matrix (Heatmap)
- [ ] 12. **Distribution Plot**
- [x] 13. Joint Plot 
- [x] 14. Pair plot
- [x] 15. Pie Chart
- [ ] 16. Box or Violen plot

## Steps in NLP EDA

- Summarize main characteristics of data.

- [ ] EDA for NLP (https://towardsdatascience.com/exploratory-data-analysis-for-natural-language-processing-ff0046ab3571)
- [ ] Works for both input `dataframe`, `text string`
- [ ] Model For Sentiment Analysis
- [ ] Model For finding absuive words
- [ ] Word Frequency Analysis
  - [ ] Total words which ocuur one, two or 3 times only
- [ ] Top Word (Visulize it via word cloud)
- [ ] Given the word, finds it count
- [ ] Check For
  - [ ] Emoji
    - [ ] Give a list of emoji present and perform a sentiment analysis on that.
  - [ ] Contractions
  - [ ] URLS
  - [ ] HTML tags
  - [ ] Phone Numbers
  - [ ] Accented Characters


## Reference

[Towards Data science blog](https://towardsdatascience.com/nlp-part-3-exploratory-data-analysis-of-text-data-1caa8ab3f79d)

[Vidhya Analysis blog](https://www.analyticsvidhya.com/blog/2020/04/beginners-guide-exploratory-data-analysis-text-data/)

[Medium](https://medium.com/analytics-vidhya/how-to-begin-performing-eda-on-nlp-ffdef92bedf6)

[Kaggle](https://www.kaggle.com/wil2210/eda-nlp-ml)


## List of Functions and Class In Data Purifier

## Steps

- [ ] Machine Learning
  
  - [ ] Data Distribution
    - [ ] Gaussian
    - [ ] Probability
    - [ ] Binomial 
    - [ ] Poisson

  - [ ] Missing Value Techniques
      - [ ] Deleting Row
      - [ ] Deleting Column
      - [ ] Missing Value Imputation
      - [ ] Numerical Value Imputation
      - [ ] IterativeImputer

  - [ ] Feature Scaling Techniques
      - [ ] Standard Scaler
      - [ ] MinMax
      - [ ] Robust 
      - [ ] Log Transformation
      - [ ] Quantile Transformer Scaler
      - [ ] MaxAbsScaler
      - [ ] Unit Vector Scaler/Normalizer
      - [ ] Power Transformer Scaler

  - [ ] Encoding Techniques
      - [ ] Label 
      - [ ] One hot
      - [ ] Dummy 
      - [ ] Effect 
      - [ ] Binary 
      - [ ] BaseN 
      - [ ] Hash 
      - [ ] Target 
  
- [ ] Deep Learning
  
- [ ] Natural Language Processing 
  - [ ]  Text Preprocessing
    - [ ]  Stop words removal
    - [ ]  punctuation removal
    - [ ]  Quotes word to normal word conversation
    - [ ]  Number removal
  - [ ] Emoji removal
  - [ ] HTML left-outs removal 
  
- [ ] Suggest Data Cleaning Techniques and methods

## Final Goals

- [ ] Automated Data Cleaning
- [ ] Automated Data Preprocessing
- [ ] Test on atleast 50 dataset before publishing.
- [ ] Display the outputs using `termcolor`
- [ ] Release the beta version to 15 testers
- [ ] Test the library for jupyter and spyder IDE
- [ ] Performing all operations/steps column-wise

        

## Points to Remember & Small Tasks

- [ ] Always write and keep track of inferences from all the steps.
- [ ] Divide into functions and classes
- [ ] Plots should be interactive (plotly)
- [ ] Params to Functions
  - [ ] Can choose to show outputs/data while performing EDA 
  - [ ] Display all columns (True or False)


## TODO

- [ ] Summary of EDA (Append all the inference of each step) => autoeda.summary()
- [ ] Test on atleast 50 dataset before publishing.
- [ ] Display the outputs using `termcolor`
- [ ] Release the beta version to 15 testers
- [ ] Test the library for jupyter and spyder IDE
- [ ] Performing all operations/steps column-wise
- [ ] Instead of performing all EDA, option to perform `basic` EDA (given as parameter to constructor)
- [ ] user can access special class variables which are set after analysis (like mleda.cat_columns)