# RNN-Text-Tweet-Classification

Purpose: To apply text classification to a real-world problem. First, I chose the two people I am interested in and used the function to scrape the 2000 tweets for each person. Then, I saved these tweets to my own drive as text files with two folders. Next, I tokenized, padded the sequences and split data to training and validation. Finally, I used three different models to classify the words.

Motivations: I selected Paris Hilton and Kim Kardashian to scrape the 2000 tweets because I am curious about them after reading the stories between them and watching the video that Uncle Roger (Nigel Ng) commented about the first episode of Cooking with Paris featuring Kim. The video was very funny, and I am also curious about other people's comments. Though they look friendly to each other and Kim also attended Paris's wedding, the friendship still looks somewhat fake. The two people have got a lot of media coverage for over 14 years! I am sure that you are also curious about their friendship, their chemistry, and what other people talked about them.

Model Results:
Model 1: Accuracy of 89%
Model 2: Accuracy of 88%
Model 3: Accuracy of 91%

Conclusion:
Changing the max length and the most common words slightly improved the accuracy. Since both the max length and the most common words increased, the time of running the model became longer. In addition, Model 3 with the stacked layers improved the performance. Increasing the recurrent dropouts can also help turn off the noise.
