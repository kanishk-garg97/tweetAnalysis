# tweetAnalysis

TASK 1: Model Selection
Whenever you develop a new classifier or other text analytics software, you must select the best possible model considering the resource and show that your system outperforms state of the art on certain conditions. This part of the assignment aims to explore the landscape of offensive speech classification. 

TASK 2: Devising and training your own classifier
For this task, you will develop your own offensive speech classifier models selected in Task 1. Doing this will involve:
• Identifying the approaches and features you want to extract;
• Developing code to extract these features from the text (and weigh them if you want to use
more than simply binary features);
• Train a classifier that uses these features;
• Evaluate the performance of the classifier using a scientifically sound methodology.
• You must use Google Colab’s GPU for the deep learning methods, which will make your
training faster.
• Initially, start with a subset of the large datasets. Subsequently, scale the classifier to include
more and more data until you use the entire dataset or very large parts. 

TASK 3: Data Size Effect
For this task, you will use models to train on different data sizes and testing on it. Doing this will involve:
• Splitting training data into 4 sub-sets of [25%, 50%, 75%, and 100%] of the original dataset
• Train all your models on these 4 sub-sets and report the results
• You will have to report both validation and testing set performance as a plot with X-axis as
data size and Y-axis as a performance measure. 
