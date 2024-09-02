# CSST102 Laboratory Activity 1 - Overview of Machine Learning Applications



https://github.com/user-attachments/assets/0fcab725-b130-48f1-95de-16bb59a977f5

# **What is Machine Learning?**
-	The term "machine learning" is frequently, but mistakenly, used interchangeably with Artificial Intelligence (AI). However, machine learning is actually a specific subset of AI. It's also commonly known as predictive analytics or predictive modeling. The phrase "machine learning" was introduced by American computer scientist Arthur Samuel in 1959, describing it as the ability of a computer to learn without explicit programming.

-	Machine learning (ML) is a branch of computer science, data science, and artificial intelligence (AI) that allows systems to learn and improve automatically from data without the need for explicit programming. Instead of following predefined rules, ML models use algorithms and statistical methods to identify patterns in data and make predictions or decisions based on those patterns. As new data is introduced, these models adapt and update their outputs, continuously enhancing their accuracy and effectiveness over time.



---



#**Types of Machine Learning**
1.	Supervised Learning 
-	Supervised machine learning is a technique where a model is trained using a dataset that contains both input features and known outcomes, or labeled data. The model learns to map inputs to the correct outputs by processing these historical input-output pairs and adjusting itself to produce predictions as close to the actual outcomes as possible. 

	- For example, in tornado forecasting, the model might use input features like date, location, temperature, and wind flow patterns to predict tornado activity, which is the labeled outcome. Similarly, in predicting loan defaults, the model could be trained with data on borrower information, where some borrowers have defaulted (labeled as defaults) and others haven't (labeled as non-defaults). Through this process, the model learns to recognize patterns that can predict future events. 

2.	Unsupervised Learning
-	Unsupervised learning algorithms, such as Apriori, Gaussian Mixture Models (GMMs), and Principal Component Analysis (PCA), are used to draw inferences from unlabeled datasets, aiding in exploratory data analysis, pattern recognition, and predictive modeling. Unlike supervised learning, these algorithms do not rely on predefined outcomes but instead discover hidden structures and relationships within the data. 
  - A common unsupervised learning technique is cluster analysis, which groups data points based on value similarity, useful in applications like customer segmentation or anomaly detection. Additionally, association algorithms help data scientists uncover associations between data objects in large databases, which can be beneficial for data visualization and dimensionality reduction.
3.	Reinforcement Learning
-	Reinforcement learning is a dynamic programming approach where algorithms are trained through a system of rewards and penalties. In this method, an agent interacts with a specific environment to achieve a set goal. The agent receives rewards or penalties for its actions based on a predefined metric, usually points, which encourages the agent to repeat beneficial actions and avoid harmful ones. Over time, through repeated trials, the agent learns the most effective strategies. 
  - Reinforcement learning algorithms are commonly used in video game development and are also employed to train robots to perform tasks similar to those done by humans.
  


---



# **Applications of Machine Learning Across Various Domains**
1.	**Healthcare**
-	Machine learning in healthcare depends on gathering patient data. By utilizing systems and tools that organize and categorize this data, machine learning algorithms can uncover patterns within datasets, enabling medical professionals to identify new diseases and forecast treatment outcomes. For example:

- The Problem Being Solved

  - The challenge of predicting and preventing disease outbreaks and identifying risk factors in populations.

- Type of Machine Learning Used

  - Deep learning models, which are a type of artificial neural network (ANN), are trained on labeled datasets where medical data are annotated with information about abnormalities or conditions, which makes it supervised learning
- Impact of the Solution
  - This can significantly improve public health by enabling early intervention, more effective disease prevention strategies, and better tracking of health risks, ultimately reducing the incidence and impact of diseases.
2.	**Finance**
-	In the financial sector, machine learning is employed for tasks such as credit scoring, investment monitoring, fraud detection, and algorithmic trading. It enhances decision-making by improving pricing, risk assessment, and customer behavior analysis. By building models that analyze large datasets and reveal patterns, machine learning helps financial companies develop new business systems and processes. For example:

- The Problem Being Solved
  - Fraud and money laundering which involves deceitful practices intended to gain illicit financial benefits and the process of concealing the origins of illegally obtained money to make it appear legitimate.
- Type of Machine Learning Used
 -  In fraud and money laundering detection, supervised learning is often employed for classification tasks using labeled datasets to identify fraudulent activities, while unsupervised learning can be used for anomaly detection and clustering without prior labels.
- Impact of the Solution
  - Machine learning improves fraud and money laundering detection by increasing accuracy, reducing false positives, enhancing efficiency, and continuously adapting to new patterns and methods.

  3.	Marketing
-	In marketing, machine learning is used to analyze large volumes of customer data to identify patterns and trends, optimize campaigns, and personalize marketing strategies. By leveraging machine learning algorithms, businesses can automate tasks such as audience segmentation, ad targeting, and performance analysis, ultimately enhancing the effectiveness of marketing efforts and driving better results with data-driven insights.
- The Problem Being Solved
  - The inefficiency and uncertainty in marketing campaigns by using machine learning to make data-driven decisions, optimize budget allocation, and automate targeting and content personalization for better return of investment.
- Type of Machine Learning Used
  - Supervised learning is primarily used in marketing for optimizing campaigns, as it involves training models on labeled data to make data-driven predictions and decisions, such as targeting relevant audiences and personalizing content based on historical campaign performance.
- Impact of the Solution
  - The impact of using supervised learning in marketing includes increased efficiency and effectiveness of campaigns, improved return on investment (ROI), better targeting of relevant audiences, and automated personalization of content, leading to more informed decisions and optimized use of marketing budgets.



---


## References 
-	A guide to the types of machine learning algorithms. (n.d.). SAS UK. https://www.sas.com/en_gb/insights/articles/analytics/machine-learning-algorithms.html
-	Machine Learning in Marketing: A Complete guide | Mailchimp. (n.d.). Mailchimp. https://mailchimp.com/resources/machine-learning-in-marketing-guide/
-	Staff, C. (2024, April 3). 3 types of machine learning you should know. Coursera. https://www.coursera.org/articles/types-of-machine-learning
-	Staff, C. (2024a, February 9). What is machine learning in health care? Coursera. https://www.coursera.org/articles/machine-learning-in-health-care
-	Staff, C. (2024c, May 20). A guide to Machine learning in finance. Coursera. https://www.coursera.org/gb/articles/machine-learning-in-finance
-	Types of Machine Learning | IBM. (n.d.). https://www.ibm.com/think/topics/machine-learning-types
