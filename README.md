<h1 style="font-size:36px;text-align:center;color:gray"> <b>Kaggle_2019-Data-Science-Bowl</b> </h1>

<h4 style="font-size:36px;text-align:center;color:gray"> <b>Uncover the factors to help measure how young children learn</b> </h4>
 
 <p><b>In this competition I got my first Kagge Medal (Silver)</b></b>
 
<h2 style="color:blue">Discription</h2>

<p>
Uncover new insights in early childhood education and how media can support learning outcomes. Participate in our fifth annual Data Science Bowl, presented by Booz Allen Hamilton and Kaggle.

PBS KIDS, a trusted name in early childhood education for decades, aims to gain insights into how media can help children learn important skills for success in school and life. In this challenge, you’ll use anonymous gameplay data, including knowledge of videos watched and games played, from the PBS KIDS Measure Up! app, a game-based learning tool developed as a part of the CPB-PBS Ready To Learn Initiative with funding from the U.S. Department of Education. Competitors will be challenged to predict scores on in-game assessments and create an algorithm that will lead to better-designed games and improved learning outcomes. Your solutions will aid in discovering important relationships between engagement with high-quality educational media and learning processes.</p>

<h2 style="color:blue">Problem Statement</h2>
<p style="color:gray;font-size:15px">
In this competition, you are provided with game analytics for the PBS KIDS Measure Up! app. In this app, children navigate a map and complete various levels, which may be activities, video clips, games, or assessments. Each assessment is designed to test a child's comprehension of a certain set of measurement-related skills. There are five assessments: Bird Measurer, Cart Balancer, Cauldron Filler, Chest Sorter, and Mushroom Sorter.</br>

 The intent of the competition is to use the gameplay data to forecast how many attempts a child will take to pass a given assessment (an incorrect answer is counted as an attempt). Each application install is represented by an `installation_id`. This will typically correspond to one child, but you should expect noise from issues such as shared devices. In the training set, you are provided the full history of gameplay data. In the test set, we have truncated the history after the start event of a single assessment, chosen randomly, for which you must predict the number of attempts. Note that the training set contains many `installation_id`s which never took assessments, whereas every `installation_id` in the test set made an attempt on at least one assessment.</br>
 
- 3: the assessment was solved on the first attempt
- 2: the assessment was solved on the second attempt
- 1: the assessment was solved after 3 or more attempts
- 0: the assessment was never solved

The file train_labels.csv has been provided to show how these groups would be computed on the assessments in the training set. Assessment attempts are captured in `event_code` 4100 for all assessments except for Bird Measurer, which uses `event_code` 4110. If the attempt was correct, it contains `"correct":true`.
</p>




 
 

