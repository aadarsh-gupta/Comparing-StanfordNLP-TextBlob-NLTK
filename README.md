## Sentiment Analysis using StanfordCoreNLP vs TextBlob vs NLTK

A short experiment to analyze the sentiment analysis capabilities of python libraries - <b>StanfordCoreNLP, TextBlob and NLTK, </b> done as part of an academic event at University of Minnesota - MSBA Summer Trends Marketplace. 

#### Experiment setup 

This experiment considered basic off-the-shelf modules from the mentioned three libraries for comparison. After pre-processing seven ambiguous English sentences, the modules were used to determine the sentiment category of each sentence - whether it is Positive, Negative or Neutral. The sentiments determined by the modules were later compared to responses from event visitors to observe the similarity/differences in the results. 

People's opinion of sentiment of the seven sentences varied much (*as seen in Fig.1 below*) , pointing the ambiguity of the sentences chosen

<img src="images/sentences.png" style="zoom:35%;" /> <br>
                                        

<img src="images/opinion.png" style="zoom:35%;" />
                                        
                                        *Figure 1 - People's opinion on sentiments* 


#### Results

Given the complexity in Natural Language Processing in terms of ambiguity, we observed the results from StanfordCoreNLP module having the highest match percent of 59% with people's responses followed by TextBlob with 41% match. 

**This indicates better performance from StanfordCoreNLP module with closest match to people's opinion being the favorable outcome.**

<img src="images/final_score.png" style="zoom:35%;" />
                      
                      *Figure 2 - Match % for sentiment results from each package with people's opinions* 



#### Limitation

The comparison was made between basic off-the-shelf modules with default pre-training done from each of the libraries. The performance would vary based on the following conditions:

* Different pre-processing of input sentences
* Using a different training / pre-trained dictionary for the sentiment classification

#### Future steps

* Using neural network architecture (seq2seq models) to classify sentiments 


#### Contributors
  
[Anirudh Srikant](https://www.linkedin.com/in/anirudh-srikant/) - srika028@umn.edu <br>
[Arnav Sivaram](https://www.linkedin.com/in/arnav-sivaram/) - sivar031@umn.edu <br>
[Karthik Ravishankar](https://www.linkedin.com/in/karthikrc1/) - ravis038@umn.edu <br>
[Mainak Roy](https://www.linkedin.com/in/mainak-roy/)  - roy00083@umn.edu <br>
[Sameeksha Aithal](https://www.linkedin.com/in/sameeksha-aithal/) - aitha010@umn.edu <br>
