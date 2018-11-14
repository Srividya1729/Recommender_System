# Matching seekers and helpers in online health support groups

# Weekly Updates :

<h1>
11/14 - 11/21
</h1>

**Challenges Overcome / Questions :**

   1) Long review texts for each user. 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**
   
  * 1 and 3 Completed
  * 2 We are finalizing on the architecture for the final model and validating it with the advisor tomorrow

**Upcoming Tasks:**

   1) Implement Sentence encoding based representation for user reviews
   2) Finalize and start implementing the final architecture (flat attention + memory / flat attention) 
   3) Compare its performance with NARRE and DeepCoNN results
   4) Strategy to combine deep learning based representations with previously developed handcrafted feature based representations to have a hybrid recommendation system
   
  
<h3> Srividya Potharaju </h3>

     
**Status of Previous week Tasks :**
   
  * 1 and 3 Completed
  * 2 We are finalizing on the architecture for the final model and validating it with the advisor tomorrow

**Upcoming Tasks:**

   1) Implement Sentence encoding based representation for user reviews
   2) Finalize and start implementing the final architecture (flat attention + memory / flat attention) 
   3) Compare its performance with NARRE and DeepCoNN results
   4) Strategy to combine deep learning based representations with previously developed handcrafted feature based representations to have a hybrid recommendation system
   

<h1>
11/07 - 11/14
</h1>

**Challenges Overcome / Questions :**

   1) Rating matrix intuition from the data. 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**
   
  * 1 and 2 After discussing with Prof, we trained with binary values in ratings matrix
  * 3 Completed

**Upcoming Tasks:**

   1) Literature survey on different memory network based architecture that can fit user thread recommendation scenario
   2) Implement flat attention with LSTM based architecture for user representation from the comments.
   3) Implement hierarchical attention (word and sentence level) with LSTM based architecture for user representation from the comments.
   
  
<h3> Srividya Potharaju </h3>

     
**Status of Previous week Tasks :**

  * 1 and 2 After discussing with Prof, we trained with binary values in ratings matrix
  * 3 Completed

**Upcoming Tasks:**

   1) Literature survey on different memory network based architecture that can fit user thread recommendation scenario
   2) Implement flat attention with LSTM based architecture for user representation from the comments.
   3) Implement hierarchical attention (word and sentence level) with LSTM based architecture for user representation from the comments.
   


<h1>
10/31 - 11/07
</h1>

**Challenges Overcome / Questions :**

   1) Data preprocessing with multiple comments by user on same item. 
   2) Open Question, large variance on the ratings. 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**
   
   1) Since we went deeper with CNN, we plan to discuss with Advisor regarding LSTM.
   2) and 3. We experimented with DeepCoNN and NARRE( Neural Attentional Regression with Review-level Explanations) that jointly uses users and thread representations using TextCNN.
   

**Upcoming Tasks:**

   1) End to End training of DeepCoNN including threads' body content. (subject to change after discussing with Prof ).
   2) End to End training of NARRE including threads' body content.
   3) Explore Deep AutoEncoder based approach for recommendations 
   
  
<h3> Srividya Potharaju </h3>

     
**Status of Previous week Tasks :**
   
   1) Since we went deeper with CNN, we plan to discuss with Advisor regarding LSTM
   2)  and 3 We experimented with DeepCoNN and NARRE( Neural Attentional Regression with Review-level Explanations) that jointly uses users and thread representations using TextCNN.
   

**Upcoming Tasks:**

   1) End to End training of DeepCoNN including threads' body content. (subject to change after discussing with Prof )
   2) End to End training of NARRE including threads' body content.
   3) Explore Deep AutoEncoder based approach for recommendations 
      

<h1>
10/24 - 10/31
</h1>

**Challenges Overcome / Questions :**

   1) For Aspect Level Sentiment, pretrained models not satisfactory, annotated corpus not available 
   2) For NER features, pretrained apis not satisfactory, need annotated corpus 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   1 and 2 partially completed, with not satisfactory results, needs discussion with mentor
   3. Completed 

**Upcoming Tasks:**

   1) Implement LSTM based representation of the User's comments and threads' content
   2) Implement CNN based representation of User's content
   3) Train End to End with previous representations including matching process.
   
  
<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**
     
   1 and 2 partially completed, with not satisfactory results, needs discussion with mentor
   3. Completed 
  

**Upcoming Tasks:**

   1) Implement LSTM based representation of the User's comments and threads' content
   2) Implement CNN based representation of User's content
   3) Train End to End with previous representations including matching process.
   


<h1>
10/17 - 10/24
</h1>

**Challenges Overcome / Questions :**

   1) Handling large data to train Neural Model (cuda memory issues)
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   1. Completed
   2. Completed - Neural MLP and CF-based KNN Model
   3. Completed - Experimented with Cosine and Dot 
   4. Completed

**Upcoming Tasks:**

   1) Extract NER features and incorporate those features in matching
   2) Aspect level sentiment analysis
   3) Literature survey on other possible neural networks for matching process
   
  

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**
     
   1. Completed
   2. Completed - Neural MLP and CF-based KNN Model
   3. Completed - Experimented with Cosine and Dot 
   4. Completed

**Upcoming Tasks:**

   1) Extract NER features and incorporate those features in matching
   2) Aspect level sentiment analysis
   3) Literature survey on other possible neural networks for matching process


<h1>
10/10 - 10/17
</h1>

**Challenges Overcome / Questions :**

   1) Handling sparseness of vocabulary for higher order n-gram features
   2) LDA, K-means clustering takes very long time 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   1. Completed (Performed detailed metadata analysis, and realized that extent of sparsity is too much - need to discuss further whether to use or not)
   2. Completed 
   3. Partially completed and need to confirm with Prof
   
   Additionally, have done extra tasks:
   
   1. Implemented k-means clustering of unigram
   2. SVD on the co-occurence matrix and plotted the clusters and analyses the clusters formed
   3. LDA based topic modeling


**Upcoming Tasks:**

   1) Perform statistical analysis to identify the most likely time period for matching 
   2) Design and implement matching mechanism using different models
   3) Come up with the best suited distance metric for above models.
   4) Extract LDA based topics and incorporate them in user-representation
   
  

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**

   1. Completed (Performed detailed metadata analysis, and realized that extent of sparsity is too much - need to discuss further whether to use or not)
   2. Completed 
   3. Partially completed and need to confirm with Professor.
   
   Additionally, have done extra tasks:
   
   1. Implemented k-means clustering of bigram and analyzed the clusters
   2. LDA based topic modeling


**Upcoming Tasks:**

   1) Perform statistical analysis to identify the most likely time period for matching 
   2) Design and implement matching mechanism using different models
   3) Come up with the best suited distance metric for above models.
   4) Extract LDA based topics and incorporate them in user-representation

<h1>
10/03 - 10/10
</h1>

**Challenges Overcome / Questions :**

   1) Validating the neural approach on sparsity of metadata particular to the case of cancer survivor network 
  

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   * (1 and 3) fully Completed, 2 partially completed 


**Upcoming Tasks:**

   1) Complete feature engineering of user metadata for the given task
   2) Implement a bag of words based feature vector using unigrams for user-content part of user profile.
   3) Decide on the relevant metrics and validate the above approach for the chosen metric
   
  

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**

   * (1 and 3) fully Completed, 2 partially completed 
  

**Upcoming Tasks:**

   1) Complete feature engineering of user metadata for the given task
   2) Implement tf-idf based feature vector using bigrams for user-content part of user profile
   3) Decide on the relevant metrics and validate the above approach for the chosen metric


<h1>
09/26 - 10/03
</h1>

**Challenges Overcome / Questions :**

   1) Had an elaborate discussion with Prof Ed and decided to shift focus to content based feature extraction to facilitate user-user recommendation, whilst keeping the implemented KNN approach as the baseline
   2) Designed a plan and defined sub tasks including fingerprinting, matching and tracking for user-user recommendation

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   * Completed 3 (full) and 1 (partial)
   * Based on the mid week discussion with Prof Ed, we prioritized stretch goal over the other tasks for the week


**Upcoming Tasks:**

   1) Based on the discussion with Prof Ed, create a document summarizing the approach for handling multiple components of the system with timely update of results
   2) Obtain Metadata for users and do feature engineering on it for the given task
   3) Explore neural approaches to deal with sparsity in user metadata
   
  

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**

   * Completed 3 (full) and 1 (partial)
   * Based on the mid week discussion with Prof Ed, we prioritized stretch goal over the other tasks for the week


**Upcoming Tasks:**

   1) Based on the discussion with Prof Ed, create a document summarizing the approach for handling multiple components of the system with timely update of results
   2) Obtain Metadata for users and do feature engineering on it for the given task
   3) Explore neural approaches to deal with sparsity in user metadata
   
  

<h1>
09/19 - 09/26
</h1>

**Challenges Overcome / Questions :**

   1) Data splitting (Chronology, random etc)
   2) Formulating K-NN approach with above split mechanism
   3) Metrics on which the value of K is chosen

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**

   * Completed  
   * Recommended slight modification of user-user similarity task formulation to improve the results 
   

**Upcoming Tasks:**

   1) Implement the modified version of user-user similarity task using KNN.
   2) Implement the modified version of user-user similarity task using PMF.
   3) Statistical analysis supporting the chronological split of training - dev data.
   4) Stretch goal: Start looking at the content of the comments to extract additional features.
  

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**

   * Completed
   * Recommended slight modification of user-(user+thread) similarity task formulation to improve the results 


**Upcoming Tasks:**

   1) Implement the modified version of user-thread similarity task using KNN.
   2) Implement the modified version of user-user similarity task using PMF.
   3) Exploring metrics for evaluating the above approaches (F1, MAP, MRR etc).
   4) Stretch goal: Start looking at the content of the comments to extract additional features.
  


<h1>
09/12 - 09/19
</h1>

**Challenges Overcome / Questions :**

   1) Handling Threads with no creator information
   2) Diagonal elements in User - User and User - Thread Matrix's imputation strategy
   3) Handling threads with irrelevant/no body content
   4) Handling Sparse data

<h3> Anusha Prakash </h3>

**Status of Previous week Tasks :**
   Completed 
   

**Upcoming Tasks:**

   1) Survey the best practices for user-user recommendation adapted by Twitter, Facebook and other Social Recommendation Systems.
   2) Implement a baseline K Nearest Neighbor based user-user recommendation system using user-user similarity.
   3) Implement a baseline K Nearest Neighbor based user-user recommendation system using user-(user + thread) similarity.
   4) Presentation for CSN group meeting with people working on different tasks for CSN project. 

<h3> Srividya Potharaju </h3>

**Status of Previous week Tasks :**
    Completed 


**Upcoming Tasks:**

   1) Survey the best practices for user-user recommendation adapted by Twitter, Facebook and other Social Recommendation Systems.
   2) Implement a baseline K Nearest Neighbor based user-user recommendation system using user-thread similarity.
   3) Implement a baseline K Nearest Neighbor based user-user recommendation system using user-(user + thread) similarity.
   4) Presentation for CSN group meeting with people working on different tasks for CSN project. 

 
 

# **09/05 - 09/12**


<h3> Anusha Prakash </h3>

1) Understanding the data and do extensive statistical data analysis
2) Obtain basic realizations / properties of the data in terms of user / thread interactions
3) Survey state of the art PMF techniques to be applied on the dataset in coming weeks 
4) Dataset creation for user-user and user-thread recommendation tasks from the raw data dump


<h3>Srividya Potharaju</h3>


1) Understanding the data and do extensive statistical data analysis
2) Life cycle analysis of user / thread
3) Survey state of the art Collaborative Filtering techniques to be applied on the dataset in coming weeks 
4) Dataset creation for user-user and user-thread recommendation tasks from the raw data dump

   

<h1> Progress Update Since May Presentation :</h1>


1) Performed further Literature Survey of Classical and Neural Approaches
2) Obtained ACS consent to access data dump
3) High-level Task Break Down of the Project

 



