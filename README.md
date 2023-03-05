# dog-predictions-with-three-different-datasets

Introduction


In real world, data rarely comes clean. Most of the time, we even have to gather it, assess it before 
proceed to the cleaning part. How ? Using Python and its librairies. It’s called Data Wrangling. In this 
project, i wrangled, analyzed and visualised a dataset. It was actually a good way to pratice and learn 
more about everything i learned through this course. The dataset is the tweet archive of Twitter user 
@dog_rates, also known as WeRateDogs. As we can see it in his name, it’s a Twitter account that 
rates people’s dogs with a humorous comments about the dog. Let’s start with the gathering part In 
that part, i imported three datasets i worked on. It was amazing to apply three differents form of 
gathering a datasets. The only thing i regret is that i didnt get the approval of Twitter for the Twitter 
API keys. I would learn more. Then i started assessing the 3 datasets. Here, i looked through my three 
datasets progammatically and also visually. I noticed eight quality issues and two tidiness issues. The 
three datasets had untidy structure, invalid values in some columns, also wrong types for some 
datatypes, incorrect values and also some irrelevant columns. I dealed with them in the cleaning 
step. This step permitted me to clean correctly the three datasets, and then merge them in one 
dataset. I also iterated as long as it was important to make the final dataset as clean as i can. But now, i will detail step by step the wrangling part.

Wrangling

First, i would like to thank Udacity for this opportunity. I would also like to excuse myself if i make some mistakes in my English. I studied in French and for English, i’m more good at listening, reading than writing. The Project was really interesting and hard to start for me. I got a problem with my computer, then i waited for more than one week for a Twitter Api key, but i didnt get it. Then i decided to use the tweet_json file Udacity provide us.
For the gathering part, gathering twiiter_archive and images datasets was very easy for me. I used the algorithms i learned in the course. But, for the tweet_json file, i didnt know how to make it as a pandas dataframe. I wanted to ask my session leader, but instead, i went on stackoverflow and finally figure it out. So the gathering part was very interesting, but it would be more instructives if i got the Twitter API keys.
Now, about the Assessing part, i started it looking into the datasets manually or maybe i would say visually, to see the structure. Then i looked for info () and and describe () about each datasets, looked if they have duplicated values and null ones, print some columns value_counts to see if they have weird or invalid values. Also, for some columns, i went deeply into them to see if they got issues. Then, i wrote in a markdown cell about 8 quality issues and 2 Tidiness isuues i resolved in the cleaning part
Finally, i proceeded to the best and hard part, cleaning the datasets and eventually merge them into 2 or one dataset. In my case, i merge them into one dataset. But before merging them, i cleaned them individually. I merge some columns into only one columns, deal with invalid values and completely clean the dataset i called it twitter_archive_master

Analysis

After the wrangling part, i asked myself three questions. Since we’re talking about dogs, in our 
cleaned dataset, what’s the famous dog_class ? the top 5 names of dogs in our dataset ? and finally 
about the ratings, i wanted to know how the ratings was for most of our dogs, if we had good dogs or 
bad ones. 
 The famous dog type was the pupper one
 The top five name was : Charlie, Lucy, Cooper then Tucker (in that order)
 And Finally, i noticed that we literally have only good dogs in our dataset since the 
mean was 1,16 which is actually good
