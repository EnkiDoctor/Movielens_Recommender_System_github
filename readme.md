## Readme File 
****
  
*Movie recommender system and algorithm comparison*  

*SID: 56641800&emsp; &emsp; Name: Du Junye*  

****
**Python Verison and Package version:**   
**Note:** *Please make sure that the packages are installed correctly to make the program run normally.*    
**Python version and cuda configuration:**
+ Python 3.9.7
+ cuda 11.0     

**Missing value handling and processing:**
+ missingno  0.5.1
+ ast.literal_eval 

**Scientific calculation package:**
+ Numpy 1.21.5
+ Pandas 1.3.4  
+ Scipy 1.8.0

**Machine Laerning tools:**
+ scikit-learn 1.0.2
+ torch                     1.10.1+cu113             
+ torchaudio                0.10.1+cu113            
+ torchvision               0.11.2+cu113  
+ tenserflow with keras     

**Visualization tools:**
+ Matplotlib 3.4.3
+ Seaborn 0.11.2
+ Plotly 5.5.0
+ Cufflinks 0.17.3
****
<b> Outline: </b>  
 
I. <b>Data pre-processing</b><br>  
> Missing value handling   
> Movie information extraction   
> Feature engineering   
> Addition data modification 

II. <b>Data exploration and visualization</b><br>   
> Introduce weighted rating   
> Trend of quantities of different types of films 

III. <b>Collabrative Filtering Algorithms</b><br> 
> Baseline, SVD, KNN with means methods   
> Performance comparison 


IV. <b> Movie Recommender Implementation</b><br> 
> User-rating based recommender   
> Description based recommender   
> Keyword based recommender   
> Hybrid recommender   
> Deep Learning method 

****
**Device Information:**  
*CPU:* Intel(R) Xeon(R) Gold 5216R CPU @ 2.10GHZ   
*GPU:* Tesla V100S*2   

**Estimated running time:**  
+ *Data processing part: 5-6 min*
+ *CF part: 2 min* 
+ *Deep learning part: 5 min* 


****
<b> References: </b>
<li>Hands on Machine Learning with Scikit-Learn & TensorFlow by Aurélien Géron (O'Reilly). CopyRight 2017 Aurélien Géron  </li>
<li>https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html</li>
<li>Xiangnan He, Lizi Liao, Hanwang Zhang, Liqiang Nie, Xia Hu and Tat-Seng Chua (2017).Neural Collaborative Filtering. In Proceedings of WWW '17, Perth, Australia, April 03-07, 2017.</li>
<li>Reference Lecture Note of SDSC3002




