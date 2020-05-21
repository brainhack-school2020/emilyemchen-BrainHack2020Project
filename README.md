# Classifying EEG Data Using Machine Learning
### BrainHack School Project 2020

#### Contributor: Emily Chen

![BrainHack School](machinelearningimage.jpg)
Source: https://www.futurithmic.com/2019/04/12/why-you-should-study-ai-machine-learning-how-did-it/

## Summary 

My personal goal for this project is to implement 2-3 machine learning classifier algorithms and learn how to use the various visualization tools available for the Python language. Since these goals seem to align well with many other participants' goals, I am very open to collaborating with others and not at all picky about the dataset being used! That being said, for the purposes of this proposal, I found an open source EEG dataset from a study investigating EEG neural responses and music-induced emotion. One possibility for this project would be to teach an algorithm how to recognize and classify the EEG neural responses that correlate to specific emotions induced by listening to music. 

### Key Words
brainhack-school, project, machine-learning, eeg

## Project definition 

### Background

Hello! I am an (incoming) fourth year undergraduate student at McGill University studying computer science and urban health geography with a minor in cognitive science. I am a research assistant with [Isabelle Arseneau-Bruneau](https://github.com/brainhack-school2020/ArsIsabelle_BHS_Project) in the Zatorre Lab and have been learning a lot about neuroscience research while (hopefully) lending some of my technical skills to Isabelle's PhD work exploring the effect of musical training on FFR. I joined the BrainHack School to learn technical research methods (e.g. machine learning) and work with neuroscience data. My main goal for the project I end up working on, whether it's my own or a collaboration with someone else (I am very open to working with others!), is to gain a strong grasp of machine learning, try out containerization, and use appropriate softwares and project organization to ensure reproducibility. 

You can find me on GitHub at [emilyemchen](https://github.com/emilyemchen) and on Twitter at [@emilyemchen](https://twitter.com/emilyemchen). 

### Main Goals
* While I've worked with machine learning using Amazon Web Services to classify city infrastructure before, I am really looking forward to learning how to write machine learning python scripts for neuroscience data. 
* I hope to get a good understanding of project management and reproducibility efforts because I may not be in charge of a research project yet but want to get into the habit for future work. 
* I am very new to neuroscience, so I hope to learn more from the many talented neuroscience researchers/BrainHack School participants through collaboration!  

### Tools 

This project will rely on the following technologies: 
* Python
* [nilearn](https://nilearn.github.io)/[scikit-learn](https://scikit-learn.org/stable/)
* [MNE](https://mne.tools/stable/index.html)
* Git/Github
* Visual Studio Code
* Terminal 
* Jupyter notebook
* Visualization packages ([matplotlib](https://matplotlib.org), [plotly](https://plotly.com))
* [Docker](https://www.docker.com/play-with-docker) (maybe)

### Data 

I have found an open source dataset on [OpenNeuro](https://openneuro.org) titled [*EEG data investigating neural correlates of music-induced emotion*](https://openneuro.org/datasets/ds002721/versions/1.0.1). This dataset is comprised of EEG recordings of 31 healthy adult participants ages 18 to 66 listening to film score excerpts to study the EEG neural correlates of music-induced emotion. The data is in BIDS format and contains EEG data (.tsv), event codes (.JSON), timings (.tsv), and EEG channel information. Seeing as this dataset is quite small, I am still on the hunt for a related dataset that has more participants so that the machine learning algorithm can be trained on a much larger group of participants.  

### Deliverables

At the end of this project, I will have the following:
* README.md file 
* requirements.txt file that outlines the packages needed to run the script
* Jupyter notebook with code that implements a machine learning algorithm, as well as explanations and processes 
* GitHub repository documenting project workflow
* Presentation showing project results 

## Results 

### Progress overview

To get comfortable with using python for neuroscience data visualization, I have followed [Sebastian Urchs' nilearn tutorial](https://github.com/surchs/bhs_nilearn_example). The results from this trial can be found in my project GitHub. I have also explored various datasets and joined two peer clinics to get a broad overview of project possibilities and see what other students at the BrainHack School are thinking about. I would like to practice working with EEG data using python by following the [eeg-notebooks](https://github.com/NeuroTechX/eeg-notebooks) mentioned in  Karim Jerbi's *Introduction to Magneto and Electro Encephalography* lecture. 

### Tools I learned during this project
I hope to be comfortable using Git/GitHub, working with Jupyter notebooks and Visual Studio Code, and creating machine learning python scripts using packages like scikit-learn and MNE.  
 
### Deliverables 

#### Deliverable 1: README.md file
A working version of this file has been completed for the Week 2 presentations. 

#### Deliverable 2: requirements.txt file
To be created at the completion of the project.  

#### Deliverable 3: Jupyter notebook 
To be created at the start of the project. 

#### Deliverable 4: GitHub repository 
My GitHub repository is being updated regularly. 

#### Deliverable 5: Presentation 
To be created at the completion of the project. 
 
## Conclusion and acknowledgement

Thank you to the BrainHack School team for their help and for providing many resources throughout Weeks 1 and 2! I would like to acknowledge my mentor, [Désirée Lussier](https://github.com/dllussier), for her guidance in Week 2. Thank you also to [Andréanne Proulx](https://github.com/brainhack-school2020/anproulx-fMRI-autism), [Liz Izakson](https://github.com/brainhack-school2020/lizizakson_commonalitiesAcrossDomains), and [Mikkel Schöttner](https://github.com/brainhack-school2020/mschoettner_fMRI-ML) for their peer help and for raising helpful issues on this project proposal. Lastly, thank you to [David MacDonald](https://github.com/brainhack-school2020/dnmacdon_ASD_multisite_smri), [Hannah Kiesow](https://github.com/brainhack-school2020/hannahkiesow_bhs_project), and [Elise Douard](https://github.com/brainhack-school2020/BLUP_Brainhack-Learning-Unicorn-Project) for sharing their project ideas with me. 