# OpenSet_CrossScene_HSI
Hyperspectral Classification in Presence of Domain Shift and Unknown Samples
* The manuscript describing our methodology is being submitted for peer review.
<br>
These codes are supposed to classify land covers using images taken by HSI sensors in which the target image exhibits domain shift and contains unknown samples that are not associated with any of the defined labels seen on the source image during training of the network.
<br>
The codes were written in Python in the Jupyter Notebook environment and are implemented on three datasets: Botswana, Pavia, and Salinas.
<br>
The implementation for Botswana can be found in 1-Botswana.ipynb.
<br>
 The implementation for Pavia can be found in 2-Pavia.ipynb.
<br>
 The implementation for Salinas can be found in 3-Salinas.ipynb
<br>
The methodology consists of three steps which are described in the manuscript.The pretrained weights for each step are also provided. To execute the code more quickly, you can skip the trainings and load these pretrained weights. In the ipynb file, there is a note before each snippet of training that describes how you can load the weights and skip that snippet of training.
<br>
Alternatively, you can run the ‘Quickrun’ version of the ipynb files, which skips the trainings and loads the pretrained weights during execution.
<br>
It is also possible to run the codes directly in Google Colab by using this pattern as URL:
<br>
(colab.research.google.com/github/amirmah/OpenSet_CrossScene_HSI/blob/main/*notebook_file_name*)
<br>
For example, you may use these URLs to run the ‘Quickrun' versions in Colab:
<br>
Botswana:
<br>
https://colab.research.google.com/github/amirmah/OpenSet_CrossScene_HSI/blob/main/4-Botswana-Quickrun.ipynb
<br>
Pavia:
<br>
https://colab.research.google.com/github/amirmah/OpenSet_CrossScene_HSI/blob/main/5-Pavia-Quickrun.ipynb
<br>
Salinas:
<br>
https://colab.research.google.com/github/amirmah/OpenSet_CrossScene_HSI/blob/main/6-Salinas-Quickrun.ipynb


