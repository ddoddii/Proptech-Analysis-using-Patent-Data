# Patent analysis in real estate tech field 
Industrial Statistical Lab Yonsei

I am trying to solve.. 

## Research Question
1. Which patents can be defined as proptech related patent?
2. What are the subfields of proptech and how can we classify them?
3. What are the hot and cold topics of proptech based on time series analysis?
4. Which technology will be combined in the future? 

## How do I solve these propblems?
### Data
- 2000~2022 patent data from USPTO 
- Keywords: 'real estate' , 'property' + { 'blockchain', 'transaction', 'valuation', 'virtual reality', 'augmented reality', 'listing', 'sale', 'finanace', 'mortgage'}
- All total 2558 patent data

### Methodology
1. Word2vec to gather synonyms 
2. Dynamic LDA to classify corpus into topics and analyze them in a time series view
3. BERTopic
4. Time series analysis
