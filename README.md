# Phishing-Websites-Detection
Since the boom of the Internet, every organization and individual has shifted to the digital world, where every piece of information can be accessed. Due to this, an attacker can retrieve confidential information through the Internet about a particular user or organization. Phishing attack is a type of attack where the adversaries can collect data about a user without his/her consent either through emails or websites or text messages which can lead to a deceptive page where the user can be persuaded into entering vital information. Phishing begins with a fake email or other kind of communication intended to entice a victim.
There are various phishing detecting techniques. We have taken the URL-based type of phishing detection technique which is done using Machine learning algorithms. Machine learning’s importance falls into this consideration if we need to protect users from phishing attacks. 
<hr>
The main objective of the project is to show how phishing attacks can be detected using machine learning models. The performance of the models used will be compared to find the best fit for the purpose of detection.The machine learning algorithms we used, will examine numerous banned and valid URLs and their attributes in order to properly detect phishing websites, including zero-hour phishing websites. The main objective of using machine learning models to detect phishing attacks in websites is because machine learning models have always shown promising results for classifying hostile behaviors like phishing attacks. 
<hr>
<b>Dataset:</b>
<br>
The data is taken from UCI repository’s ‘Phishing website detection’ dataset. This dataset describes the different parameters to judge whether a website is a phishing website or not. It consists of different attributes with information regarding a website URL which will determine if it belongs to a phishing website or not.
<hr>
<b> Methodology Used:</b>
<br>
Machine learning has shown to be an effective approach for classifying hostile behaviors or artifacts such as phishing websites. The majority of these approaches need training data, which is luckily available in the form of phishing website samples that can be used to train a machine learning model. For the project, the dataset was collected from the UCI on phishing website URLs.
<br>
The machine learning models used for phishing websites detection are;
<ul>
  <li>Random Forest Classification uses a process in which n-number of decision trees are generated from the training data and then testing data is applied on these decision trees to conclude the accuracy of the model and its efficiency in new test data. Larger number of decision trees makes the random forest algorithm more accurate.</li> 
  <li?Logistic regression is a supervised classification algorithm. For a given collection of characteristics (or inputs), X, the target variable (or output), y, can only take discrete values in a classification issue. A linear relationship between input and output variables is not required for logistic regression.</li>
  <li>A Neural Network is made up of layers that are connected to operate on the structure and function of the human brain. It learns from massive amounts of data and trains a neural network using complicated algorithms. A recurrent neural network (RNN) is a form of artificial neural network that works with time series or sequential data.</li>
</ul>
