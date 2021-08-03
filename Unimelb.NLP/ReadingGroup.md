

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

Chunhua: 

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





