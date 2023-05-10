# Twitter-datapipeline-using-Airflow
using apache airflow doing poc on Twitter datapipeline 
youtubelink:https://www.youtube.com/watch?v=q8q3OFFfY6c&list=PLV7zzNuFrio-JU2MZkle_Bp0ABForx6o8


step1:
prerequisites:

1.install python above 3.5 

steps for mac user:
open terminal and run this  below command:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

after successfully installed type below command:

brew --version

if brew command not rognized please follow below steps:

echo 'export PATH="/opt/homebrew/bin:$PATH"' >> ~/.zshrc

Close and reopen Terminal, or run the following command to refresh your terminal:

and type

source ~/.zshrc

then type 
brew --version

then install latest version of python

brew install python

step2:
how to create twitter api

https://developer.twitter.com/en/docs/twitter-api

use case to get the developer account:

Our company is building a social media analytics tool that helps businesses and organizations analyze their Twitter presence and engagement. To do this, we use Twitter's API to collect data on our clients' Twitter accounts, including their tweets, followers, and engagement metrics. Our tool provides insights such as most popular tweets, trending topics, and sentiment analysis. This information is used to help our clients better understand their audience and improve their social media strategy. We will use Twitter's data and API in accordance with Twitter's policies and guidelines and will not share any user data with third parties without explicit consent.

2.saved the api keys 
3.go to the visual studio and create twitter_etl.py
   open command propmt and install
    pip3 install pandas
    pip3 install tweepy (to install twitter data)
    pip3 install s3fs (use to store read or write data from the s3 bucket)
    






