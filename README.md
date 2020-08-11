# Natural-Language-Processing
<b>How to install Natural Language Processing environment for windows </b><br>
Step 1: Download and Install Anacoda for Windows from https://www.anaconda.com/products/individual or Direct link: https://repo.anaconda.com/archive/Anaconda3-2020.07-Windows-x86_64.exe <br>
    -> Just run click Next -> Next -> Next -> Select all Advanced Options and then Install.
Step 2:  Create a vitrual environment <br>
    -> Create text file named nlp_env.yml as below:
    
           name: nlp
           channels:
             - defaults
          dependencies:
             - pip=18.1
             - spacy=2.0.16
             - numpy=1.15.4
             - keras
             - matplotlib=3.0.1
             - pandas=0.23.4
             - nltk=3.3.0
             - scikit-learn=0.20.1
             - jupyter=1.0.0
        prefix: C:\Users\quynhtv\Anaconda3\envs\nlp <br>

  -> Open Anacoda Prompt or Command Prompt ->   Go to folder contain nlp_env.yml file and type "conda env create -f nlp_env.yml" without quote (")  <br>
  ->Type "conda activate nlp" without quote (")<br>
 Step 3:  Type "jupyter notebook" without quote (") to start interactive python3 session <br>

 Good luck!

