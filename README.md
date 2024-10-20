# ASR_challenge_Telepathy
ASR Challenge, Interview 21st October - Lorenzo Concina

I wrote two different notebooks for the two tasks: Task_1_Telephaty.ipynb and Task_2_Telephaty.ipynb
I used Colab as Dev enviroment, and two different virtual env for each notebook to be able to present them easily the day of the interview.
We will go trough the code togheter interctivly, but if you want to try the notebooks before, these are the steps:

To use the notebooks"
```python
#clone the repository
git clone https://github.com/Lorenzoncina/ASR_challenge_Telepathy.git

#cd into the repo
cd ASR_challenge_Telepathy

#create and activate a python virtual env for Task 1
python3 -m venv venv_challenge_task_1
source venv_challenge/bin/activate

#install all necessary dependencies
pip install requirements_task_1.txt

#I didn't version data into a remote storage for this challenge with DVC due to some Google Drive issues. 
#In this case, manually copy then data folder tl_speech_challenge inside the repository folder
cp -r ..some_location/tl_speech_challenge .

#adjust the paths of clean_audio_folder_path and enviroment_noises_folder_path in the third cell to actual folders (in my notebook they point to my drive where I worked)

#Task 2
#install requirements_task_1.txt in a new virtual env
#adjust absoluth path to folder resources like for task 1 

```


