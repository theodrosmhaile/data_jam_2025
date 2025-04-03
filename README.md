# Welcome to the DataJam!

## Getting set-up
If you want to code your solution with the available data you have a few options:
  1. Clone this repository to your computer and get started with your own set-up for Datascience/ML/AI/cognitive modelling.
  
  2. If you *do not* have a set-up, and would like to get started quickly:
     - Go to https://jupyterhub.app.rug.nl/hub/ and log in with your RUG credentials. This is an experimental set-up for a Jupyter Lab server, it might have some bugs, but it works well.
     - Request a **Datascience Environment** from the available server options. This will take about 2 minutes to set-up.
     - Once you see the Jupyter Lab environment, open a Terminal and `clone` this repository. 
     - I have provided initialized Jupyter notebooks - one with a python kernel and the other with an R kernel, choose whichever you would like and get-started!
  
  3. If you *do not* have a set-up, and would like to get started *slowly*:
     
     I will be on hand to help you get-set up : D 

## Data description
The dataset we will be working with contains student fact learning data with the MemoryLab software in a Cognitive Psychology course here at the RUG. The data are published [here] (https://doi.org/10.17605/OSF.IO/E28NW), but is also available in this repository for your convenience. It might be informative to look at previous research related to this data, which can be found [here](https://doi.org/10.18608/jla.2021.6590) and [here](https://doi.org/10.31234/osf.io/d58n4). They can also serve as good resources. 

The data-set has three main components: 
1. Learning Practice in MemoryLab.
2. Standard Exam scores.
3. Students' final grades in the course. 

A description of the variables follows below. 

## Variables

### Learning Practice in MemoryLab
`year_memorylab_data.csv`
1. **User**: Unique, anonymous identifier for each student. 
2. **session**: Numbers that indicate the specific learning session where the student practiced some facts. This varies across students. 
3. **Sequence.Number**: With in learning sessions, the numbers indicate the sequence in which facts were shown and practiced. This varies across session. 
4. **Chapter.ID**: A code that identifies the chapter from which a specific fact was taken. 
5. **Time**: The date, and time in the day when a student practiced a specific fact. 
6. **factId**: A unique code that identifies each fact. 
7. **Fact**: The actual fact practiced that corresponds to the fact ID. 
8. **Number.Of.Alternatives**: Number of alternative answer options to chose from for a given fact. 
9. **repetition**: How many times a specific fact was practiced. 
10. **presentationStartTime**: The time that a fact was displayed for practice.  
11. **reactionTime**: How long a student takes to provide a response. 
12. **correct**: The accuracy of the students' response. 
13. **activation**: This value represents the likelihood a specific fact is known by the student. 
14. **estimatedAlpha**: This value represents how quickly a specific fact is forgotten by the student. 
15. **estimatedResponseTime**:

### Standard Exam Scores

1. **Username**: Unique, anonymous identifier for each student. 
2. **Chapter.ID**:  A code that identifies the chapter from which a specific fact was taken. 
3. **factId**: A unique code that identifies each fact. 
4. **exam.Q**: A unique code, question number, that identifies each question. 
5. **multiple_choice**: True or False, indicating if the question was a multiplechoice question. 
6. **reps.study**: How many times the fact was practiced by a student.  
7. **PC.study**: 
8. **final.alpha**: 
9. **studied**: 
10. **correct.exam**: The accuracy of the students' response.    


### Students' final grades in the course

1. **User**: Unique, anonymous identifier for each student. 
2. **Grade**: Grade, out of 10, for the course. 
