# Quora_question_similarity-model
ML model predict which of the provided pairs of questions contain two questions with the same meaning
</br></br>
**@author:Akash Kumar**</br>
**linkedin:-https://www.linkedin.com/in/akash-kumar-9b87b5148/**</br></br>
Data Description

The goal of this competition is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.

Please note: as an anti-cheating measure, Kaggle has supplemented the test set with computer-generated question pairs. Those rows do not come from Quora, and are not counted in the scoring. All of the questions in the training set are genuine examples from Quora.

Data fields<br/>
**id** - the id of a training set question pair<br/>
**qid1, qid2** - unique ids of each question (only available in train.csv)<br/>
**question1, question2** - the full text of each question<br/>
**is_duplicate** - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0<br/> otherwise.<br/>

**Zip file contain  (Main files explained)**                
**Data files**</br>
1. train.csv - 6 features<br/>
2. df_fe_without_processing.csv - 11 features<br/>
3. nlp_feature-train.csv- 21 features<br/>
4. final_feature.csv - 797 features   <br/>             

**Jupyter file**<br/>

 5. Quora - Exploratory  analysis of features (on added 11 features)<br/>
 6. Quora_preprocessing - applying Natural language processing(on added 15 features)<br/>
 7. Q_Mean_w2w - applying TFIDF, Word2vec(added 768 new features)<br/>
 8. ML_model - applying XGBoost,linear SVM,logistic regression(on 797 features)<br/>
<br/><br/>

**Note main ML_Model is XGBOOST**

Can't find data
Data link :**https://www.kaggle.com/c/quora-question-pairs/data**

