TED Talk Transcript Recommender System

As of December 2020, there were over 3,500 TED Talk recordings avaiable on the official TED Talk Website. While this is an incredible milestone for the non-profit company, it can be overwhelming for the average user interested in watching one or two Talks. Information overload prevents users from making informed decisions and limits their interest in watching more TED Talks.

The attached notebook creates a recommender function used within a while loop that filters this large number of talks. The user enters the title of a TED Talk they enjoyed and get recommended 5 similar Talks. The purpose of this system is to improve user satisfaction when selecting a TED Talk to watch and increasing user engagement on the TEDTalk.com website. 

We accomplished this through the following steps:

-Cleaning the data (creating a dataframe, narrowing down the columns, changing datatypes to strings, etc)
-NLP pre-processing (removing puncuation and stop words)
-Creating a TF-IDF Matrix, logging the term frequency. 
-Calculating the Cosine Similarity of the TF-IDF Matrix
-creating the get_recommend function that finds the top 5 talks with the highest similarity score of the talk entered
-the function spits out 5 recommended talks.


To use the system, download and save the"ted_talk_en.csv" file to your machine. Run the entire kernal and make sure the csv file is findable via your directory. Scroll to the final cell. Here you will be presented with a text box prompting you to enter a TED Talk Title. After you enter it, you will be give 5 recommended TED Talks, based on the transcript of the one you typed. For example if the user enters 'Averting the climate crisis' the recommender will recommend 'New thinking on the climate crisis', 'A one-man world summit', 'A climate solution where all sides can win', 'Design and discovery', and 'Can we stop climate change by removing CO2 from the air?'
