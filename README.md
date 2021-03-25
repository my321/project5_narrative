# Project 5 
<p>
  
### Project Title:
Are we haunted by our past? Analyzing the changing narratives of George W. Bush and Hillary Clinton?
</p>

<p>
  
### Description: 
Perception of public figures changes over time. As time passes, past mistakes are often forgotten. Can we see this forgetfulness in the articles written about public figures? What does influence the narrative written about them? I focus on George W. Bush and Hillary Clinton because of the sheer number of articles written about them, it allows for more data to analyze. Both are politicians, belong to political families, and divide public opinion. They are obviously different because of gender, political affiliation, and presisdential election success. Because they have similarities and differences, I can contrast their narrative in addtion to tracking changes within their narrrative. I initially conduct topic modeling to identify topics and see how the representation of topics changes over time. After George W. Bush leaves office and steps out of the public eye, discussion and criticism of the Iraq was also disappear. As Hillary Clinton changes roles from a senator running a presidential campaign to secretary of state, we also see her dominate topic change. In addition to broad topics, narrative is also dictated by word choices. I train a word2vec model on the entire corpus of abstracts and find that more unique names are semantically similar to words used to describe that individual. The name "George" is very common and only assocaited with other names, but names like "Hillary" and "Barack" are associated with words that are clearly used to describe the two. In the word2vec analysis, I see the appearance of obviously gendered and subtly gendered language. 

</p>

<p>
  
### Models Used:
Tried NMF and LSA topic modeling to identify topics, decided on NMF. Trained a word2vec model on the entire corpus of abstracts to identify semantic similarity of the words. Then used T-SNE to reduce the vectors down disply in 2-Dimensions. 

</p>

<p>
  
### Data Used:
Scraped articles abstracts from the NYTimes API. Gathered info on close to 50,000 abstracts from 2000 to March 2021. 

</p>

<p>
  
### Tools Used:
Python, Jupyter Notebook, NLTK, ScikitLearn, Gensim, Keynote, git, and gitbhub.
</p>
<p>
  
### Possible impacts of your project: 
This project highlights how a public figure can change the narrative surrounding them. Although there appear to be some gendered constraints, the news media seems willing to move on from the past and really focus on an indiviual's present actions. 

</p>
