# We Rate Dogs Wrangling Exercise
## by Anthony Andersland


## Dataset

WeRateDogs is a Twitter account setup by Matt Nelson to rate people’s dogs. People post pictures of their dogs with a funny comment for others to rate. The ratings follow a scale of 1 to 10, however most of the ratings are typically over 10. Over the years the site has grown in popularity and achieved international media coverage. [1]

## Gather
The following data was gathered for this project.
* twitter_archive_enhanced.csv - This file was provided through the project details by Udacity as a manual download.
* image_predictions.tsv - This file was provided by Udacity as a url. It required using the Requests library to programmatically download the file.
* tweet_json.txt - This data was available through the Twitter archive using Tweepy. It required the following:
  * Create a Twitter account and sign up for a developer account.
  * Use the Tweepy library to programmatically access the api’s.
  * Authenticate to the Twitter archive API.
  * Add logic to work within the API’s request limits for a developer account.
  * Parse the json returned and write the information to a file.

## Assess
The following steps were performed on the gathered data.
* Load the three files gathered into data frames.
* Perform visual analysis on the data frames using pandas, excel, and sublime.
* Document areas to cleanup from the visual inspection.
* Perform programmatic inspection of the data using pandas.
* Document areas to cleanup from the programmatic inspection.

## Clean
The following steps were performed to cleanup the issues found.
* Write tests for all cleanup items.
* Write code to correct the issues.
* Leverage classroom materials and various websites for the correct syntax to use in cleaning the issues.
* Once the issues were cleaned up the data frames were saved to files.


## Summary of Findings

In this investigation I looked at the image prediction results and how it related to retweet and favorite counts. The results showed that a higher image confidence level also typically had a higher retweet and favorite counts. The Golden Retriever, Labrador Retriever, and Pembroke dogs had the highest retweet and favorite counts. 


## Resources
* http://docs.python-requests.org/en/master/user/quickstart/#response-content
* https://stackabuse.com/reading-and-writing-json-to-a-file-in-python/
* https://stackoverflow.com/questions/7370801/measure-time-elapsed-in-python
* http://docs.tweepy.org/en/v3.2.0/api.html#API
* https://developer.twitter.com/en/docs/basics/rate-limiting
* https://stackoverflow.com/questions/4432208/how-does-work-in-python
* https://www.epochconverter.com/
* https://www.pythoncentral.io/pythons-time-sleep-pause-wait-sleep-stop-your-code/
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html
* https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.melt.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.merge.html
* https://chrisalbon.com/python/data_wrangling/pandas_join_merge_dataframe/
* https://pandas.pydata.org/pandas-docs/stable/options.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.contains.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.title.html
* http://jonathansoma.com/lede/foundations/classes/pandas%20columns%20and%20functions/apply-a-function-to-every-row-in-a-pandas-dataframe/
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.apply.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.to_numeric.html
* https://matplotlib.org/gallery/statistics/barchart_demo.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sort_values.html
* https://stackoverflow.com/questions/25146121/extracting-just-month-and-year-from-pandas-datetime-column-python
* https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.replace.html
* https://stackoverflow.com/questions/12625636/python-string-function-to-strip-the-last-comma
* https://pandas.pydata.org/pandas-docs/stable/options.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.extract.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.astype.html