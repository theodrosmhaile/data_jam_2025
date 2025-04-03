# Welcome to the DataJam!

## Getting set-up
If you want to code your solution with the available data you have a few options:
  1. Clone this repository to your computer and get started with your own set-up for Datascience/ML/AI/cognitive modelling.
  
  2. If you *do not* have a set-up, and would like to get started quickly:
     - Go to https://jupyterhub.app.rug.nl/hub/ and log in with your RUG credentials. This is an experimental set-up for a Jupyter Lab server, it might have some bugs, but it works well.
     - Request a **Datascience Environment** from the available server options. This will take about 2 minutes to set-up.
     - Once you see the Jupyter Lab environment, open a Terminal and clone this repository. 
     - I have provided initialized Jupyter notebooks - one with a python kernel and the other with an R kernel, choose whichever you would like and get-started!
  
  3. If you *do not* have a set-up, and would like to get started *slowly*:
     
     I will be on hand to help you get-set up : D 

## Data description
The dataset we will be working with contains student fact learning data with the MemoryLab software in a Cognitive Psychology course here at the RUG. The data are published here  https://doi.org/10.17605/OSF.IO/E28NW, but is also available in this repository for your convenience. It might be informative to look at previous research related to this data, which can be found here https://doi.org/10.18608/jla.2021.6590 and here https://doi.org/10.31234/osf.io/d58n4. They can also serve as good resources. 

The data-set has three main components: 
1. Learning Practice in MemoryLab.
2. Standard Exam questions and scores.
3. Students' final grades in the course. 

A description of the variables follows below. This description also appears in the 

### Learning Practice in MemoryLab: variables

1. **User**: Unique, anonymous identifier for each student. 
2. **session**: Numbers that indicate the specific learning session where the student practiced some facts. This varies across students. 
3. **Sequence.Number**: With in learning sessions, the numbers indicate the sequence in which facts were shown and practiced. This varies across session. 
4. **Chapter.ID**: A code that identifies the chapter from which a specific fact was taken. 
5. **Time**
6. **factId**
7. **Fact**
8. **Number.Of.Alternatives**
9. **repetition**
10. **presentationStartTime**
11. **reactionTime**
12. **correct**
13. **activation**
14. **estimatedAlpha**
15. **estimatedResponseTime** 
