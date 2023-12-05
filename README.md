# CS678_Project-1
# Group project for CS678

## Contributors:
Vishnu Sai Bhonsley, 
Sreedath Somesetty, 
Akhil Kumar Reddy, 


# Project Setup Instructions
 Execution Steps:

1) Download the Project:  Obtain the ZIP file containing the entire project from the Github Repository.

2) Open Project in VS Code: Unzip the downloaded file and open the project folder in Visual Studio Code.

3) Set Up Virtual Environment: Use Conda to create a virtual environment for this project.

4) Run this command in the terminal :
 conda create --name your_environment_name python=3.8
 conda activate your_environment_name

 
5) Install Prerequisites:

   pip install numpy<br>
   pip install torch<br>
   pip install transformers<br>
   pip install pandas<br>
   pip install scikit-learn<br>
   pip install tensorboard<br>
   pip install sentencepiece<br>

6) Execute IPYNB Files:

Open and execute the IPYNB files 



## File Instructions :

### 1)easy mix.ipynb
      Task: Data augmentation using the Easy Mixup technique on the HX (HateXplain) and Latenthate dataset.
  
### 2) entail.ipynb
       Task: Entailment technique on the HX HateXplain dataset.

### 3) HX- Robust.ipynb && Latent Robust.ipynb 

        Task: Evaluate the model's robustness by simulating different types of perturbations in the data and check how well the model performs under noisy conditions.

        #### Techniques to Add Noise

         Synonym Replacement: Replaces words with their synonyms while maintaining sentence structure.
         
         Character Swap: Swaps characters within words to introduce typo errors or misspellings. 
         
         Letter Concatenation: Concatenates adjacent letters within words to create new non-dictionary words.
         
         Random Jumbling of Words: Randomly shuffles or jumbles the order of words in sentences.
         
         Word Dropped:  Randomly removes or drops certain words from sentences.

         Note: For each noise technique listed above, the notebook will access the model and calculate the accuracy after applying that specific noise to the HX dataset.
         This evaluation helps understand how the model's performance is affected when the data is subjected to these different types of noise.

         
         

        


