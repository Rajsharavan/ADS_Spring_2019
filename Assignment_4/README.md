# Machine Learning Based Classifier

K3G Music enterprises are planning a new music station which would enable listeners to listen to music based on how they feel and their list changes every day, so they want to identify how we can enhance the music experience for the users.We used flask for designing frontend for the website and gave dropdown for 3 countries which are the UK, Canada, and Australia.


### Claat

https://codelabs-preview.appspot.com/?file_id=1ZX82BDnMwQbEm5te_OuNAER27HMOLilnbiYp2MS7bvk#0

### Before execution install below libraries:

•	flask

•	watson_developer_cloud

•	requests

•	flask_wtf

### Data

Dataset used to calculate the metrics for the model

### Instructions to execute files:

#### Step 1: Execute Tone_Analyzer_Final.ipynb

Tone_For_CSV.ipynb - Task is to use Musixmatch API and get the top k list for these 3 countries. And also fetch lyrics for that. For accessing API, need to create an account on Musixmatch, which will generate an API key for accessing lyrics from their site.

#### Step2:
Once we have the list to identify the tone of the songs, we use tone analyzer API from an IBM Watson developer to identify the tone. We created an account on IBM Cloud and created an API key for getting authorization for API and used the key in our code. We got different tones but as per our requirement, checked score for Happy and Sad emotion and whichever is higher kept that as an emotion of the song.

#### Step 3:
Hosting our website on the Heroku platform.

https://k3g-music.herokuapp.com/

#### Step 4:
Tone_Analyzer_Final.ipynb - Based on the provided dataset implemented confusion matrix and calculated F1 score



