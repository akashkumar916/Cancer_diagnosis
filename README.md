# Cancer_diagnosis
Machine learning model to help  molecular pathologist to classify the variations (9 classes)</br></br>
**@author:Akash Kumar**</br>
**linkedin:-https://www.linkedin.com/in/akash-kumar916/**</br></br>


We understand that analyzing text represents a difficult challenge, but believe it or not is the current state of the art when it comes to interpretation of genetic variants.

The workflow is as follows

1. A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze<br/>
2. The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest<br/>
3. Finally this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them

<br/>
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated.


There are nine different classes a genetic mutation can be classified on.

This is not a trivial task since interpreting clinical evidence is very challenging even for human specialists. Therefore, modeling the clinical evidence (text) will be critical for the success of your approach.

Both, training and test, data sets are provided via two different files. One (training/test_variants) provides the information about the genetic mutations, whereas the other (training/test_text) provides the clinical evidence (text) that our human experts used to classify the genetic mutations. Both are linked via the ID field.

Therefore the genetic mutation (row) with ID=15 in the file training_variants, was classified using the clinical evidence (text) from the row with ID=15 in the file training_text

Finally, to make it more exciting!! Some of the test data is machine-generated to prevent hand labeling.



Data Link: **https://www.kaggle.com/c/msk-redefining-cancer-treatment/data**<br/>

- We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that  human experts/pathologists use to classify the genetic mutations. 
- Both these data files are have a common column called ID
- <p> 
    Data file's information:
    <ul> 
        <li>
        <b>training_variants (ID , Gene, Variations, Class)</b>
        </li>
        <li>
            <b>training_text (ID, Text)</b>
        </li>
    </ul>
</p>


<h2>Performance matric</h2>

Metric(s): <br/>
**Multi class log-loss**<br/>
**Confusion matrix**




