# P300_Speller
The following code is realized by Fresco Andrea, Garza Roberto, Giove Morena, Losa Letizia and Molinari Giulia in the context of the "Neuroengineering" course, held by Cerveri Pietro and Pedrocchi Alessandra at Politecnico di Milano.

It consists of a machine learning algorithm to predict the letter thought by a subject given the EEG signal acquired during a letter selection task.

The aim of the code is to:
1) analyze the P300 speller dataset; 
2) extract EEG epochs from the EEG signals and filter them; 
3) Develop a neural network able to classify EEG epochs in two classes (P300 ‐ non-P300); 
4) detect the letters thought by the subjects during the test. 


<h3 align="center">Project Title</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Aim of the project](#aim)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
Individuals living with debilitating conditions, caused by brain or spinal cord injuries, amyotrophic lateral sclerosis or other diseases, are no longer able to voluntary control muscles movement. For these individuals, assistive technologies are required to allow, or ease, communication and mobility. One example of assistive technologies are Brain‐Computer Interfaces (BCI). BCI are based on monitoring the activity of the brain, typically through the electroencephalographic (EEG) signal. P300 BCI are based on the detection of the P300 event related potential (ERP). A P300 ERP is elicited when an auditory, visual, or somatosensory stimulus, which is significant for the subject, is
presented to him/her infrequently and interlarded with insignificant stimuli. The P300 response is visible in the EEG trace as a positive peak at about 300ms after the stimulus onset. The typical setup for a P300 BCI requires the presentation, to the subject, of a matrix of flashing letters and numbers. A P300 response will be elicited when the row, or the column, containing the letter the subject is focusing on flashes. By detecting and identifying the P300 responses, it is possible to determine
which letter or number the subject was focusing on. Since detection of a P300 response is challenging, multiple repetitions of the same stimuli are presented to the subject, and the EEG signals are averaged.

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them.

```
Give examples
```

### Installing
A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>
Explain how to run the automated tests for this system.

### Break down into end to end tests
Explain what these tests test and why

```
Give an example
```

### And coding style tests
Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>
Add notes about how to use the system.

## 🚀 Aim of the project <a name = "aim"></a>
1) analyze the P300 speller dataset; 
2) extract EEG epochs from the EEG signals and filter them; 
3) Develop a neural network able to classify EEG epochs in two classes (P300 ‐ non-P300); 
4) detect the letters thought by the subjects during the test. 

## ⛏️ Built Using <a name = "built_using"></a>
- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>
- [@andreafresco](https://github.com/andreafresco) - Fresco Andrea
- [@capriolosaggio](https://github.com/CaprioloSaggio) - Garza Roberto
- Giove Morena
- Losa Letizia
- Molinari Giulia
