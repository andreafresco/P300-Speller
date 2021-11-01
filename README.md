# P300_Speller
<p align="left"> Project developed during the Neuroengineering course at [Politecnico di Milano](https://www.polimi.it/). The project consisted in the development of a Deep Learning algorithm to identify the alphabetic letter thought by a subject through its electro-encephalographic activity (EEG).
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Dataset](#data)
- [Aim of the project](#aim)
<!-- - [Model](#Model)-->
- [Built Using](#built_using)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>
Individuals living with debilitating conditions, caused by brain or spinal cord injuries, amyotrophic lateral sclerosis or other diseases, are no longer able to voluntary control muscles movement. For these individuals, assistive technologies are required to allow, or ease, communication and mobility. One example of assistive technologies are Brain‐Computer Interfaces (BCI). BCI are based on monitoring the activity of the brain, typically through the electroencephalographic (EEG) signal. P300 BCI are based on the detection of the P300 event related potential (ERP). A P300 ERP is elicited when an auditory, visual, or somatosensory stimulus, which is significant for the subject, is
presented to him/her infrequently and interlarded with insignificant stimuli. The P300 response is visible in the EEG trace as a positive peak at about 300ms after the stimulus onset. The typical setup for a P300 BCI requires the presentation, to the subject, of a matrix of flashing letters and numbers. A P300 response will be elicited when the row, or the column, containing the letter the subject is focusing on flashes. By detecting and identifying the P300 responses, it is possible to determine
which letter or number the subject was focusing on. Since detection of a P300 response is challenging, multiple repetitions of the same stimuli are presented to the subject, and the EEG signals are averaged.

## 💾 Dataset <a name = "data"></a>

The folder Data contains the data that you need to use in the project. In this folder there are several files:
- channels.csv : this .csv file contains the list of the 64 EEG channels used during the recording. Channel #1 in the .csv file (that is Fc5) is the same as Channel #1 in the .mat files
- Subject_A_Train.mat: this file contains several variables for the training sessions of subject A. The variables are:
  - Flashing: 1 when row/column was intensified, 0 otherwise
  - StimulusCode: 1-6 for intensified columns, 7-12 for intensified rows, 0 otherwise
  - StimulusType: 1 when row/column being intensified contained target char, 0 otherwise
  - TargetChar: chars spelled by the subject during the training session
  - Signal: EEG recording matrix for the training session of subject A. It is 3D matrix with the following dimensions: 85 (trials) x SAMPLES x 64 (channels)
- Subject_A_Train_Reduced.mat: this file contains a reduced set (first 5 trials) of the Subjet_A_Train.mat file, that you can use with the provided Colab notebook.
- Subject_A_Test.mat: this file contains all the data for the test sessions of subject A. You don’t have any information about the stimulus type because the goal in the test set is to predict the spelled letters
- Subject_B_Train.mat: the same as explained for subject A, but for subject B
- Subject_B_Test.mat: the same as explained for subject A, but for subject B

## 🚀 Aim of the project <a name = "aim"></a>
1) analyze the P300 speller dataset; 
2) extract EEG epochs from the EEG signals and filter them; 
3) Develop a neural network able to classify EEG epochs in two classes (P300 ‐ non-P300); 
4) detect the letters thought by the subjects during the test. 

<!--## 🔧 Model building <a name = "model"></a>
Explain the model-->

## ⛏️ Built Using <a name = "built_using"></a>
- [Python 3](https://www.python.org/) - Programming language
- [Google Colab](https://colab.research.google.com/) - Cloud service
- [SciPy](https://www.scipy.org/) - Signal filtering
- [Matplotlib](https://matplotlib.org/) - Visualization
- [Tensorflow](https://www.tensorflow.org/) - Deep Learning model building
- [Scikit-learn](https://scikit-learn.org/stable/index.html) - Cross Validation & Hyperparameters tuning

## ✍️ Authors <a name = "authors"></a>
- [@andreafresco](https://github.com/andreafresco) - Fresco Andrea
- [@capriolosaggio](https://github.com/CaprioloSaggio) - Garza Roberto
- Giove Morena
- Losa Letizia
- Molinari Giulia
