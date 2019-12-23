# Cancer_diagnosis
Machine learning model to help  molecular pathologist to classify the variations (9 classes)


We understand that analyzing text represents a difficult challenge, but believe it or not is the current state of the art when it comes to interpretation of genetic variants.

The workflow is as follows

A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze
The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest
Finally this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated.



- We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that  human experts/pathologists use to classify the genetic mutations. 
- Both these data files are have a common column called ID
- <p> 
    Data file's information:
    <ul> 
        <li>
        training_variants (ID , Gene, Variations, Class)
        </li>
        <li>
        training_text (ID, Text)
        </li>
    </ul>
</p>


<h2>Performance matric</h2>

Metric(s): 
* Multi class log-loss 
* Confusion matrix 
