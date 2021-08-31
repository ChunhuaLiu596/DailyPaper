

# 210803 
## zenan 
Hi all, in the next reading group, I'll be sharing my thoughts on:
1. Recent findings of table semantic learning (featuring table QA and fact verification task)
2. Problems to be solved in this area and my solutions

table + text understanding 
loss of 2D structure 
data scale
model complexity 

table shrink 
longformer 
most of them use ensemble model 

2D model to capture 2D structure? 


Q: Any strategy for the interection betweeen statement and the table? 

Lea: Edge labelled KG 
more weights to the headers 
 

## biaoyan 
Following zenan's presentation, I will share my current study on:
1. Recent work on incorporating external knowledge for coreference resolution.
2. Problems I have in attempting to incorporate external knowledge to the coreference model.

BioMedical 


Chunhua:
Structure for coreference: 
1. Detect mentions (span representation). 
2. Pair mentions to get coreference score.   

how do they reduce noises? filter out unrelated knowledge triples?

For performance dropped, would it because of the added knowledge is irrelevant?
If you use less external KG, would it decrease a little?

Head embedding or tail embedding? 


Dimensions of KG embedding, 1024? 
xudong: hyper-parameter

xudong: static emb vs joint  
xudong: how to you do the model selection? 
reduce the step for model selection 


haonan: 
the KG is too small, smaller size kg embeddings


## summary Chunhua
zenan's speech hierarchy is pretty clear. 
Model figure, how model work, problems, my thougts. 
Biaoyan presents more details: problem definition, previous work (detailed model), own model, experimental results, questions


# 210809 
## Takashi Wada 

Hi all, tomorrow I’ll share my thoughts and ideas on my research (**Paraphrasing Multiword Expression/Lexical Substitution**)

![image](https://user-images.githubusercontent.com/68045327/128793818-5a632600-aeb3-4d88-9994-4822a842237e.png)


## Chunhua 
1. research topic: generate synonyms for rare/ multi-token words
evaluattion: compare neighbours 

2. Detailed case study and analysis -> limitations/problems -> solutions 

MWE 

### Discussion
Jeyhan: combing the mask and non-mask token embeddings 
1. looking at the  shapre of cosine similarity (one word to multiple other words)
2. Kick the bucket 

## ACL papers 

Tim's favorite papers:
1. ACL best: dancebyte 
2. ACL outstanding MT: active learning, outlier, cannot beat baseline , yejin choi 
3. MT: Mind Your Outliers! Investigating the Negative Impact of Outliers on Active Learning for Visual Question Answering
Siddharth Karamcheti, Ranjay Krishna, Li Fei-Fei and Christopher Manning
4. unreliable metrics 




# 2021.08.17 - Lin Tian
rumour detection 

how to utilise user information?
how to get any user 

![image](https://user-images.githubusercontent.com/68045327/129648211-f398316c-c905-4c44-be37-aa68a9ebe2b6.png)

## Jey Han
user following dirction: following/ followed relations / mutual 


Tim: what would be the semantic differences between 
what source of 
what kind of rumour tree 

would underlying shared interests be more 

Weights of diferent edges between two users: number of mentions, number of retweets. 
I wonder how easy it is to? 
You know, I agree with that example. But I come up with a flip example. 



# 2021.08.17 - Xudong 

How do you set up random seeds? 
Giving a certain num

Jayhan: correct way is to run multiple times report the average and variance 
random seeds influences: 1. bert classifer 2. data order 




# 2108.31- Aili and Simon Suster



![image](https://user-images.githubusercontent.com/68045327/131428902-19117469-3803-467a-b06c-45297c38a265.png)







