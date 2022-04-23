# Portfolio
A collection of some of my work. Please visit my [GitHub profile](https://github.com/rajkumar464) for more. 

# [Project 1 : Music-Classifier](https://github.com/rajkumar464/Music-Classifier)
![](https://github.com/rajkumar464/Portfolio/blob/main/images/Classifier-survey.png =400x400)
<img src="https://github.com/rajkumar464/Portfolio/blob/main/images/Classifier-survey.png" width="100" height="100">
![](https://github.com/rajkumar464/Portfolio/blob/main/images/RFC%20performance.png)
![](https://github.com/rajkumar464/Portfolio/blob/main/images/Bass.png)
* Built a Python web application to classify user-provided input song into 1 of 10 genres and also perform source separation into vocals, bass, drums and accompaniments for music producers, educators and streaming platforms' classification systems. </br>
* Fabricated an ensemble Random Forest Classifier model and trained it on 1000 different songs (100 per genre) and performed better than previous methods based on waveform analysis with an accuracy of 70%.</br>
* Created 4 CNN masking models to predict binary masks for isolating each element i.e. vocals, bass, percussion and accompaniments, with the bass masking model achieving an accuracy of 96.3%.</br>
* The system was proposed and published at the IEEE-Sponsored International Conference on Advancements in Electrical, Electronics, Communication, Computing and Automation (2021). Link to the publication : [IEEE](https://ieeexplore.ieee.org/document/9675518)</br>
For more information, please check out this presentation : [Presentation](https://docs.google.com/presentation/d/1D4YVrl-OZT2HIdfohhjBfBVMJv2G5B1J7Qx2KvqL_6Y/edit?usp=sharing)</br>

# [Project 2 : User Profiling on Social Media](https://github.com/rajkumar464/User-Profiling-on-Social-Media)
![](https://github.com/rajkumar464/Portfolio/blob/main/images/Accuracy.png)
![](https://github.com/rajkumar464/Portfolio/blob/main/images/Loss.png)
* The aim of the project is to build a system that automatically predicts the age category, gender, and personality scores of Facebook users when given input of status updates, profile picture, and "likes" of the users. We have been given 9500 training instances of real sensitive Facebook user data. The program takes input from a source specified by the user and also outputs the results to a user-specified directory.</br>
* The project is three-pronged with 3 team members each using a different source. The three sources used are : </br>
1. Text</br>
2. Image</br>
3. Likes </br>
* Built a deep learning model based on VGG-16 architecture and trained on 9500 RGB JPEG images of varying dimensions sourced from Facebook to predict 1334 users' characteristics.</br>
* Rendered results in XML files stored in a custom local directory upon executing a Linux shell command that took input from a directory specified by the user.</br>
* For more information, please contact me as the report contains sensitive information.</br>

# [Project 3 : YouTube Channel Analytics Dashboard](https://github.com/rajkumar464/YouTube_Dashboard)
![](https://github.com/rajkumar464/Portfolio/blob/main/images/Analytics%20Dashboard.png)
* An interactive dashboard to view your channel's performance over several different measures and also analyze each video's performance, built using Streamlit.</br>
* The dataset contains 4 .csv files pertaining to a YouTuber's channel. Source : Kaggle
*  The dashboard has two sections :
1. Aggregate Metrics
* This section displays a few metrics comparing performance over the last 6 months with the entire year.
2. Individual Video Analysis
* Here, one can select a particular video and view the geographic distribution of viewers and also their subscriber status.
* Also, one can observe the rate at which the number of views increases over time, with the 20th percentile, 80th percentile, 50th percentile (median) and increase in views over the first 30 days for the selected video.
