# Alphabet Soup Challenge
![funding business](https://user-images.githubusercontent.com/112433621/227254359-c6f9885c-5996-48dd-8811-2bc2864ac1f4.jpg)
### Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
-INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively
# NEURAL NETWORK MODEL REPORT
![Report image](https://user-images.githubusercontent.com/112433621/228268907-476beaf9-6df6-41c2-be80-2cc358646b26.jpg)
# DATA PROCESSING
## Removing non-beneficial columns
<img width="916" alt="Before an after screen shot removing nan values" src="https://user-images.githubusercontent.com/112433621/228286740-c316e99c-6897-4105-8dba-4d7ef87f7fc4.png">

The optimisation process started with removing columns that had missing data and was not beneficial to the model. The idea was to get rid of values that may be negative or columns with NAN values as this could contribute to the overall score but in a negative way.


## Secondly, two more layers of hidden nodes were added to the model to try and improve efficiency 
<img width="593" alt="extra layers" src="https://user-images.githubusercontent.com/112433621/228287504-de0fb845-68f9-4156-849a-7889afb55d51.png">


## The number of epochs with this new dataset was reduced
<img width="554" alt="21 epoches" src="https://user-images.githubusercontent.com/112433621/228288373-f9a5dae3-b146-4a60-9550-6e636b74b927.png">

- Since some of the columns were reduced the model had a better accuracy score when the epochs were fewer than 100
# SUMMARY RESULTS
In summary changing the features did indeed make a difference as the accuracy indeed increased. However The target of 75% was not met. The best result was 74% accuracy. In future It would be beneficial to spend moe time understanding how the models work to know exactly what feature to edit in order to improve the perfomance. I watched videos and read some articles including the documentation but I feel it requires more time.

