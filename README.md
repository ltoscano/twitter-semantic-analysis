Twitter_stream_download.py is used to download data from twitter, it has two arguements:</br>
1. -q to select the twitter keyword.</br>
2. -d to name the download directory.</br>

Data dirctory contains the data captured from twitter.</br>

In this small project, I use keyword "election" to choose twitters. Then use regular expression and punctuation lists to filter the words without any meanings.</br>

Next step is to build o-occurrences words word matrix containing words that come up together and see the most common pairs of words for future interests</br>

Then use what's called Pointwise Mutual Information to compute the distance for each word to the Sentiment Lexicon (positive and negetive words) and final score = positive - negative</br>

Finally, choose keywords: "Trump" and "Clinton" to see the public opinion towards these two candidates.</br>

What I got is that people actually dislike both, which is reasonable and compared to Trump, attitude towards Clinton is more positive. 
