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

entail.ipynb has entailment technique on both HX HateXplain dataset, by changing few code bits <br />
lang = 'hx' #(can be 'hx' or 'latent' for 2 datasets)<br />
model_choice =8 #(0-10 for different models)<br />
We can get total of 10 models trained for 2 datasets.<br />

