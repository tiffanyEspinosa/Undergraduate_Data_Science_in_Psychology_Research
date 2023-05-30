<h1>Undergraduate Data Science in Psychology Research: Classification of Anxiety vs. Depression on Social Media using Neural Network Models</h1>

[Click here to view the final poster!](https://github.com/tiffanyEspinosa/Undergraduate_Data_Science_and_Psychology_Research/files/11606612/NAU.poster.2023.pdf)


<h2>Description</h2>

<p>I was a member of an all-women Data Science undergraduate research lab led by Dr. Sara Kien. Our lab focused on expanding Dr. Kien's previous research in psychology and data science.</p>


<h3>Integration Test</h3>

<p>In the integration test, Dr. Kien replicated the study conducted by Murarka et al. (2021) to compare the performance of RoBERTa and BERT in classifying subreddit posts into mental health categories. She found that RoBERTa outperformed BERT in most categories; however, the anxiety and depression categories had the lowest accuracy. Murarka et al. (2021) suggested that this could be due to the comorbid nature of anxiety and depression.</p>


<h3>Baseline Model</h3>

<p>She refined the baseline model by focusing solely on the depression and anxiety data. This resulted in a training dataset of 5,480 posts and a test dataset of 496 posts. There was evidence of overfitting, so she reduced the number of epochs from 10 to 4. There was a statistically significant improvement in accuracy compared to the integration test.</p>


<h3>Enhanced Data and Labeling Techniques</h3>

<p>To enhance the classification accuracy, we conducted four additional experiments. In the first experiment, we collected data from Patient.Info's Depression and Anxiety forums and merged it with the existing subreddit posts. Subsequently, we attempted to label the posts using codebooks based on the Beck Depression Inventory and the Beck Anxiety Inventory. Unfortunately, these attempts did not result in significant improvements in the accuracy of the BERT or RoBERTa models.</p>


<h3>Comorbidity</h3>

<p>Next, we wanted to see how well RoBERTa could differentiate between anxiety, depression, and comorbidity. We adopted two approaches to address comorbidity. The first approach involved self-labeling comorbidity by identifying individuals who posted in both the Depression and Anxiety forums. In the second approach, we combined self-labeling with inventory coding, utilizing keywords from the Beck Depression Inventory and the Beck Anxiety Inventory. Comparatively, the second approach demonstrated better discrimination among the three categories.</p>


<h3>Results</h3>

<p>Our findings indicate that the second approach, incorporating self-labeling and inventory coding, achieved better discrimination among the categories.</p>


<h3>Confusion Matrices</h3>

<p>The Self-labeled comorbidity model exhibited high confusion within the comorbid class, resulting in an accuracy of 26% for comorbidity. However, it achieved relatively high accuracies of 81% for anxiety and 90% for depression.</p> 

<p>The Self-labeled + inventory coding model (4 epochs) demonstrated reduced confusion within the comorbid class but had lower accuracy (65%) for depression compared to anxiety (93%).</p> 

<p>Finally, the Self-labeled + inventory coding model (10 epochs) achieved the highest accuracy (75%) for the comorbid class but had the lowest accuracy (49%) for depression. This could be due to potential comorbidity or overlap in the symptoms.</p> 

<h2>Tools/Technologies Used:</h3>

 - <b>Excel</b><br />
 - <b>Python</b><br />
 - <b>PowerPoint</b><br />
 - <b>Google Colab</b><br />
