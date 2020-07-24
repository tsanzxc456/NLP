Lab 4 Assignment

Warning: All work should be in the MTurk Sandbox

Teams
For this assignment, work in teams (same teams as final project teams). 


MTurk Requester name must be as follows: NCTU_{Team_Name}, for example NCTU_Team_Pudding
Make sure it appears correctly on the Worker Sandbox website.
Files to submit
lab4_<Team_Name>.ipynb/lab4_<Team_Name>.py: Colab Notebooks/Python scripts to upload the HITs, then download the assignments and generate results.csv
credentials.csv: credentials from Amazon AWS for user with read-only permissions for MTurk
results.csv: CSV file with tweet scores
Homework
Homework has 3 phases:

Upload HITs

Write a Colab script to upload the HITs. In addition, create and upload HTML file(s) to the external server. Test your HITs.

Deliverable: 
Upload HITs; Make sure your HITs can be found when searching for “NCTU” on Worker Sandbox website.
Submit on e3: The script for uploading the HITs.

Colab Notebook ( lab4_<Team_Name>.ipynb) and Python script (lab4_<Team_Name>.py) 

(for example, lab4_Team_Pudding.ipynb, lab4_Team_Pudding.py )

Submission: per team
Open: Friday 5/22 09:00
Due: Wednesday 5/27 22:00:
Cutoff: Thursday 5/28 22:00 (-10 points). 
No submission after cutoff (score 0)


Be an MTurker!

Task: Work on HITs between Thursday 5/28 22:00 ~ Saturday 5/30 22:00

Each team member must complete at least 50 of their own team’s HITs.

In addition, each team member must complete at least 10 HITs for at least 3 other teams (in total: at least 30 HITs). If your team has 2 members, your team must complete at least 60 HITs for other teams. If your team has 3 members, your team must complete at least 90 HITs.

Find other teams’ HIT by searching for “NCTU”.

Deliverable: After completing the HITs, complete the MTurker Quiz on e3.

Submission: per student
Open: Thursday 5/28 22:00
Due: Saturday 5/30 22:00
No submission after due date (score 0)

Get Results

Task:  download and process your completed assignments using a Colab script.

Deliverable: submit on e3, the script for downloading the HITs and computing the results.
Colab Notebook (lab4_<Team_Name>.ipynb) and Python script (lab4_<Team_Name>.py) (for example, lab4_Team_Pudding.ipynb, lab4_Team_Pudding.py)
credentials.csv (user has read-only permissions)
results.csv


Submission: per team
Open: Saturday 5/30 22:00
Due: Monday 6/1 22:00
Cutoff: Tuesday 6/2 10pm (-10 points)
No submission after cutoff (score 0)
Input

Tweet data is at https://bit.ly/nlp-amt-data (raw data at https://gist.githubusercontent.com/bshmueli/c99fc0abf56460e644bd610bf3024e83/raw/720285d133c85d94e0aa3fe3edcc199f6d99e3f7/lab4-data.csv)

Data description:
idx: tweet index
text: tweet text (UTF-8)
Output
Results in file results.csv
Data description:
idx: tweet idx
avg_valence: average valence (1.0~5.0)
avg_arousal: average arousal (1.0~5.0)
avg_dominance:: average dominance  (1.0~5.0)
avg_time: average time spent by workers (seconds)
assignments: number of completed assignments (1~3)

MTurk HITs information
Clear and easy-to-understand title and description
Keywords should be attractive (include also the keyword “nctu” for easy search)
Each HIT is one tweet
Each HIT will have 3 assignments
Worker should read tweet and rate its VAD score
Provide clear explanations to workers
Payment for each assignment:
$0.50 for short tweets
$1.00 for long tweets
Submit button must be disabled for a reasonable time proportional to tweet length
HIT lifetime: 8 weeks
Time to work on each tweet: 30 minutes
Payment to worker: 1 hour after completion
Worker qualification:
Must reside in TW or an English-speaking country
Must accept to work with offensive tweets
ExternalQuestion will be hosted on an external website
Resources
Colab Example
https://colab.research.google.com/drive/1i5mtERv-VYAXVbAXPGcSxl-KrwCDKJuz?usp=sharing
VAD Resources
Emotion classification https://en.wikipedia.org/wiki/Emotion_classification
VAD (PAD) dimensional model: https://en.wikipedia.org/wiki/PAD_emotional_state_model
Amazon Resources
Mechanical Turk
https://www.mturk.com/
https://requester.mturk.com/
Sandbox
https://requestersandbox.mturk.com/
https://workersandbox.mturk.com/
Amazon Web Services
https://aws.amazon.com/
Developer Reference
https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMechanicalTurkRequester/

PDF: https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMechanicalTurkRequester/amt-dg.pdf
API Reference
https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/
https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/amt-API.pdf
Python SDK (Boto 3)
https://boto.readthedocs.io/en/latest/ref/mturk.html
The REAL Mechanical Turk :)
https://zh.wikipedia.org/wiki/土耳其行棋傀儡

https://en.wikipedia.org/wiki/The_Turk

