# Complete-Life-Cycle-of-a-Data-Science-Project :-

credit: all corresponding resources

as data science is fastly developing field i found these few new techinques which make your work easier-https://github.com/achuthasubhash/Tips


1.Data collection

a.web scraping  best article to refer-https://towardsdatascience.com/choose-the-best-python-web-scraping-library-for-your-application-91a68bc81c4f

    1.beautifulsoup
   
    2.scrapy
   
    3.selenium
   
    4.request to access data 
  
b.3rd party API'S 

c.big data engineering to collect data

d.databases

e.free online resource

    1)kaggle
   
    2)movielens
   
    3)data.gov:   https://data.gov.in/
   
    4)uci
   
    5)quandi
    
    6)world3bank  https://data.world/
   
    7)UCIMachineLearning
   
    8)online hacktons
   
    9)image data from Google_Search
   
    10)image data from Bing_Search
   
    11)https://www.columnfivemedia.com/100-best-free-data-sources-infographic
   
    12)Reddit:https://lnkd.in/dv5UCD4
   
    13)https://datasets.bifrost.ai/?ref=producthunt
   
    14)data.world:https://lnkd.in/gEK897K
   
    15)https://data.world/datasets/open-data
   
    16)FiveThirtyEight :-  https://lnkd.in/gyh-HDj
   
    17)BuzzFeed :- https://lnkd.in/gzPWyHj
   
    18)Google public datasets :- https://lnkd.in/g5dH8qE
   
    19)Quandl :- https://www.quandl.com
   
    20)socorateopendata :- https://lnkd.in/gea7JMz
   
    21)AcedemicTorrents :- https://lnkd.in/g-Ur9Xy
   
    22)labelimage:- https://github.com/wkentaro/labelme  ,  https://github.com/tzutalin/labelImg
   
    23)tensorflow_datasets as tfds
   
    24)https://datasets.bifrost.ai/?ref=producthunt
   
    25)https://ourworldindata.org/
   
    26)https://data.worldbank.org/
   
    27)google open images:https://storage.googleapis.com/openimages/web/download.html
   
    28)https://data.gov.in/
    
    29)imagenet dataset-http://www.image-net.org/

2.Feature engineering

     Data cleaning-Pyjanitor-https://analyticsindiamag.com/beginners-guide-to-pyjanitor-a-python-tool-for-data-cleaning/
     
     remove duplicate data

   a.handle missing value
   
     1.if missing data too small then delete it 
     
     2.replace mean,median,mode
     
     3.apply classifier algorithm to predict missing value
     
     4.knn imputer
     
     5.apply unsupervised 
     
     6.Random Sample Imputation
     
     7.Adding a variable to capture NAN
     
     8.Arbitrary Value Imputation
     
     9.hot deck Imputation
     
     10.regression Imputation
    
     
   b.handle imbalance
   
     1.Under Sampling - mostly not prefer because lost of data
     
     2.Over Sampling  (RandomOverSampler (here new points create by same dot)) ,  SMOTETomek(new points create by nearest point so take long time)
     
     3.class_weight give more importance(weight) to that small class
     
     4.use kfold to keep the ratio of classess constant
  
   c.remove noise data
   
   d.format data
   
   Numerical variables: Discrete numerical variable,Continuous numerical variable
   
   e.handle categorical data   Ordinal,Nominal categorical variables  
   
     1.One Hot Encoding
     
     2.Count Or Frequency Encoding
     
     3.Target Guided Ordinal Encoding
     
     4.Mean Encoding
     
     5.Probability Ratio Encoding
     
     6.label encoding
     
     7.probability ratio encoding
     
     8.woe(Weight_of_evidence)
     
     9.one hot encoding with multi category (keep most frequently repeated only)
     
     10.feature hashing 
     
   f.normalisation of data
   
       1.Standardization
     
       2.Min Max Scaling
     
       3.Robust Scaler
      
       4.Q-Q plot is used to check whether feature is guassian or normal distributed  required for linear regression,logistic regression to improve performance
     
           a.Guassian Transformation
        
           b.Logarithmic Transformation
        
           c.Reciprocal Trnasformation
        
           d.Square Root Transformation
        
           e.Exponential Transdormation
        
           f.BoxCOx Transformation
        
           g.log(1+x) Transformation
        
   g.remove low variance data by using VarianceThreshold
   
   h.same variable in feature then remove feature
   
   i.outilers   removing outilers depond on problem we are solving
    
      eg: incase of fraud detection outilers are very important
      
      methods to find outiler: zscore,boxplot,IQR

3.Exploratory Data Analysis(eda)
  
    Explore the dataset by using  python or microsoft excel or tableau or powerbi etc...
  
  
4.Feature selection

    1.pearson correleation
   
    2.heatmap
  
    3.Feature Importance
  
       a.ExtraTreesClassifier
    
       b.SelectKBest
    
       c.stepforward and stepbackward method
    
       d.Random_forest_importance
  
    4.statics to select important feature
  
    5.keep in mind  curse of dimensionality
  
    6.highly correleated then remove 1 feature (multicollinearity)
  
    7.dimension reduction
  
    8.lasso and ridge regression to penalise unimportant features
    
    9.filter method
    
    10.threshold based method 
    
    11.hypothesis testing
    
    12.model based selection
  

5.Model selection

Machine learning
   
   A.Supervised learning (have label data)
   
     1.regression (output feature in continous data form)
     
       linear regression,polynomial regression,support vector machine,Decision Tree Regression,Random Forest Regression,
       
       least square method,Random Forest Regression,xgboost,ridge,lasso,catboost,gradientboosting,adaboost,
       
       elsatic net,light gbm,Ordinal Regression,ordinary least squares
   
     2.classification (output feature in categorical data form)
     
        Logistic Regression,K-Nearest Neighbors,Support Vector Machine,Kernel SVM,Naive Bayes,Decision Tree Classification,
        
        Random Forest Classification,xgboost,adaboost,catboost,gaussian NB,LGBMClassifier,LinearDiscriminantAnalysis,
        
        passive aggressive classifier algorithm
   
  
   B.Unsupervised learning(no label data)
   
     1.Dimensionality reduction - PCA,SVD,LDA
   
     2.Clustering :https://scikit-learn.org/stable/modules/clustering.html
   
     3.Association Rule Learning - support,lift,confidence
   
     4.Recommendation system -
     
         a.collaborative Recommendation system,
         
         bcontent based Recommendation system 
         
         c.utility based Recommendation system 
         
         d.knowledge based Recommendation system 
         
         e.demographic based Recommendation system 
         
         f.hybrid based Recommendation system 
   
   C.Ensemble methods
   
     1.Stacking models
   
     2.Bagging models
   
     3.Boosting models
   
   D.Reinforcement learning
   
      agent apply action to environment get corresponding reward so that it learn environment
      
      1.Q-Learning
      
      2.Deep Q-Learning
      
      3.Deep Convolutional Q-Learning
      
      4.Twin Delayed DDPG
      
      5.A3C 
   
   E.Deep-learning  (use when have huge data and data is highly complex and state of art for unstructured data)
   
   1.Multilayer perceptron(MLP)
   
     1.Regression
   
     2.Classification
   
   2.Convolutional neural network ( use for image data)
   
     1.classification of image
     
       create own model,lenet,alexnet,resenet,inception,vgg
     
     2.localization of object in image
     
     3.object detection and object segmentation 
     
       rcnn,fastrcnn,fatercnn,yolo v1,yolo v2,yolo v3,yolo v4,fast yolo,yolo tiny,yolo lite,yolo tiny++,yolo act++,
       
       maskrcnn,ssd,detectron,detectron2,mobilenet,retinanet,detr facebook
       
       3 kind of object segmentation  available semantic segmentation,instance segmentation,panoptic segmentation
     
     4.pose estimation
   
   3.recurrent neural network (use when series of data)
   
     1.RNN
     
     2.GRU
     
     3.LSTM (have memory cell,forget gate  etc..)
     
     all above have bidirectional also based on problem statement use bidirectional 
  
   4.Generative adversarial network
   
   5.Autoencoder
   
   6.Boltzmann_Machines
   
   7.Self Organizing Maps (SOM) unsupervised learning using deeplearning
   
   8.Natural language processing
   
     clean data(remove stopwords depond on problem ,lowering data,tokenizatio,postagging,stemmimg or lemmatization depond on problem,skipgram,tokenization)
     
     NLU,NLG,NER,text summarization,machine translation
      
     1.bag of words
     
     2.Tfidf
     
     3.using rnn,lstm,gru
     
     4.attention
     
     5.self attention
     
     6.wordembedding
        
        a.using pretrained model 
          
          i)word2vec( cbow,skipgram)
          
          ii)glove
          
          iiI)fasttext
        
        b.own embedding  (use when have huge data)
        
          i)word2vec library
          
          ii)keras embedding 
        
     7.encoder and  decoder(sequence to sequence)
      
     8.Transformer  big breakthrough in NLP
      
     9.BERT,ROBERTA,DISTILBERT,GPT,GPT2,GPT3
   
   F.Time Series
   
      here data split is different (train,test,validate)
      
      here handling missing data different 
      
      generally used  to impute data in Time Series
      
      1.ffill
      
      2.bfill
      
      3.do mean of previous or future x samples and impute
      
      4.take previous year value and impute
      
      uses 
      
      1.Arima
      
      2.Autoregressive model
      
      3.moving average
      
      4.lstm(neural network)
      
      5.autoregressive
      
      6.navie forecasts
      
      7.smoothing (moving average,exponential smoothing)
      
      8.facebook prophet
   
      best article-https://www.analyticsvidhya.com/blog/2018/02/time-series-forecasting-methods/
      
   G.self supervised learning
   
   H.active learning
   
   I.transfer learning
   
   J.deep dream,style transfer

hyperparameter tuning
  
    a.GridSearchCV (check every given parameter so take long time)
  
    b.RandomizedSearchCV (search randomly narrow down our time)
  
    c.Bayesian Optimization -Automate Hyperparameter Tuning (Hyperopt)
  
    d.Sequential Model Based Optimization(Tuning a scikit-learn estimator with skopt)

    e.Optuna
  
    f.Genetic Algorithms 
    
 cross validation techniques
    
     1.loocv
     
     2.kfoldcv
     
     3.stratfied cross validation
  

6.Testing model

generally used metrics
 
    1.Regression task - mean-squared-error, Root-Mean-Squared-Error,mean-absolute error, R², Adjusted R² etc and are used according to the task and data used for the task.
    
    2.classification task-Accuracy, Precision, and Recall,F1 Score,Binary Crossentropy,Categorical Crossentropy,AUC
    
    3.Reinforcement learning - total rewards
    
    4.Incase of machine translation use bleu score
    
    5.unsupervised then use silhouette score

if not giving good performance go back to Data collection or  Feature engineering to increase performance of model


7.deployment

    1.azure
    
    2.heroku
    
    3.Amazon Web Services
    
    4.google cloud platform

    app- flask,streamlit
    
    use of tensorflow lite to reduce size of model

8.mointoring model



BEST ONLINE COURSES

    1.coursera

    2.UDEMY

    3.EDX

    4.DATACAMP


BEST YOUTUBE CHANNEL TO FOLLOW

    1.Krish Naik-https://www.youtube.com/user/krishnaik06

    2.Abhishek thakur-https://www.youtube.com/user/abhisheksvnit

    3.AIEngineering-https://www.youtube.com/channel/UCwBs8TLOogwyGd0GxHCp-Dw

    4.ineuron-https://www.youtube.com/channel/UCb1GdqUqArXMQ3RS86lqqOw


BEST BLOGS TO FOLLOW 

    1.towards data science-https://towardsdatascience.com/

    2.analyticsvidhya-https://www.analyticsvidhya.com/blog/?utm_source=feed&utm_medium=navbar

    3.medium-https://medium.com/
    
    4.machinelearningmastery-https://machinelearningmastery.com/blog/

BEST RESOURCES

    1.paperswithcode-https://paperswithcode.com/methods

    2.madewithm-https://madewithml.com/topics/

    3.Deep learning-https://course.fullstackdeeplearning.com/#course-content

    4.pytorch deep learning-https://atcold.github.io/pytorch-Deep-Learning/

    5.deep-learning-drizzle-https://deep-learning-drizzle.github.io/

    6.Fastaibook-https://github.com/fastai/fastbook
    
    7.TopDeepLearning-https://github.com/aymericdamien/TopDeepLearning
    
    8.NLP-progress-https://github.com/sebastianruder/NLP-progress
    
    9.EasyOCR-https://github.com/JaidedAI/EasyOCR
    
    10.Awesome-pytorch-list-https://github.com/bharathgs/Awesome-pytorch-list
    
    11.free-data-science-books-https://github.com/chaconnewu/free-data-science-books
    
    12.arcgis-https://github.com/Esri/arcgis-python-api
    
    13.data-science-ipython-notebooks-https://github.com/donnemartin/data-science-ipython-notebooks
    
    14.julia-https://github.com/JuliaLang/julia
    
    15.google-research-https://github.com/google-research/google-research
    
    16.reinforcement-learning-https://github.com/dennybritz/reinforcement-learning
    
    17.keras-applications-https://github.com/keras-team/keras-applications  ,  https://github.com/keras-team/keras
    
    18.opencv-https://github.com/opencv/opencv
    
    19.transformers-https://github.com/huggingface/transformers
    
    20.code implementations for research papers-https://chrome.google.com/webstore/detail/find-code-for-research-pa/aikkeehnlfpamidigaffhfmgbkdeheil
    

Follow leaders in the field to update yourself in the field

    1.Linkedin

    2.Twitter
    
 Free CPU/GPU/TPU
 
    1.Google cloab
    
    2.Kaggle kernel
    
    
So what next ?

participate online competition and apply interships

online competitions:

1.Kaggle-https://www.kaggle.com/

2.hackerearth-https://www.hackerearth.com/challenges/

3.machinehack-https://www.machinehack.com/

4.analyticsvidhya-https://datahack.analyticsvidhya.com/contest/all/

5.zindi-https://zindi.africa/competitions



