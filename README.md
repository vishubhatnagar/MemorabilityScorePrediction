# MemorabilityScorePrediction

<p>
  This project is an attempt towards <i>Media Memorability</i> section of **mediaeval2019** in which we predict the memorability of a video to the viewers.  
</p>

<p>
  Since last decade, MediaEval offers yearly challenges in the forms of shared tasks.
</p>

<p>
  Video memorability has various applications. In this project, features extracted by a different team have been utlized to predict the short- and long-term memorability of the   videos.
</p>

Features used:  
--------------  
C3D  
captions using tf-idf   
captions with C3D  

Regression techniques used:  
---------------------------  
Linear Regression  
Random forest     
Neural Network  

After analyzing the **spearman's score** for all of them, the best regressor was used for the test set.
