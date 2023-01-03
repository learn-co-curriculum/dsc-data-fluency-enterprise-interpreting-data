# Data Fluency - Interpreting Data

So now you have some idea of where you could go looking for data, the next step is to think about how to interpret data and glean important insights from that data. In this section, you will cover three different important topics for interpreting data: descriptive analytics, predictive analytics, and data visualization.

## Descriptive analytics

Descriptive analytics focuses on understanding and describing what has happened in the past. In other words, it provides a way of seeing what your organization’s historical data describes to you about trends or patterns in your business. It involves summarizing data and presenting it in a way that makes it easy to understand and interpret. Descriptive analytics tools and techniques also include things like charts, graphs, and tables, which can be used to visualize data and identify trends and patterns. The goal of descriptive analytics is to provide a clear and concise summary of what has happened in the past, and to understand the factors that may have contributed to certain outcomes. It is a useful tool for understanding historical data and can help inform decision making, but it does not attempt to predict future outcomes or prescribe actions.

One main focus of descriptive analytics is to identify summarization techniques that can help to provide insights in ways that looking at the raw data itself are unable to. This type of analytics can be used to get to know the data, based on its variables. From a structured data perspective, you may be interested in looking for what an “expected value” would be for a column. A column of data in this structured sense is often called a variable. Since the column of data will likely vary and not just be the same value throughout the data, “variable” is a nice phrase for this component. You can use descriptive analysis to examine relationships between variables in the data and whether there are specific portions of one variable related to portions of another variable. For example, maybe you are interested in tracking how shipments are delayed based on daily temperatures or precipitation measures across different seasons in a five year period.

![eda](https://user-images.githubusercontent.com/9215614/210279685-1ab32a0e-8541-4662-8556-be14366defad.png)

Often the first step in descriptive analytics is to explore the variable in the data. This is often called, aptly, exploratory data analysis. This involves searching for patterns and relationships in the data and gauging the main properties of each variable in the data. This can also involve identifying which questions of interest should be examined further and which kinds of problems can actually be addressed with this data. Techniques such as determining the mean, median, and mode (depending on the type of data each variable represents), the variability in each variable, and also the correlation between variables to identify how increases in one variable tend to relate to another variable.

## Predictive analytics

![prediction](https://user-images.githubusercontent.com/9215614/210279762-0c373802-a14d-4c8a-aa01-09e7a48acc8a.jpeg)

As descriptive analytics focuses on addressing characteristics in the data that has been collected, predictive analytics aims to identify trends in the current data and project them into the future using algorithms and further testing.

Predictive analytics is a type of data analysis that uses statistical algorithms and machine learning techniques to identify the likelihood of future outcomes based on historical data. The goal of predictive analytics is to make predictions about unknown future events. There are many different types of machine learning algorithms, including:

  - Supervised learning algorithms: These algorithms are trained on labeled data, meaning that they are given input data and the corresponding correct output. Patterns are identified by these statistical algorithms to understand explanations for the values of the output given particular input data. Examples include linear regression and support vector machines.
  - Unsupervised learning algorithms: These algorithms are not given any labeled training data. Instead, they must discover the relationships in the data through techniques such as clustering. Examples include k-means, anomaly detection, and hierarchical clustering.
  - Reinforcement learning algorithms: These algorithms learn by interacting with their environment and receiving rewards or punishments for certain actions. An example is Q-learning.
  - Deep learning algorithms: These algorithms are inspired by the structure and function of the brain, and are made up of multiple layers of artificial neural networks. They have been particularly successful in image and speech recognition tasks. Examples include convolutional neural networks and long short-term memory networks. They can be used in both supervised and unsupervised machine learning procedures.

Some examples of predictive analytics in business include:

  - Fraud detection: Predictive analytics can be used to identify patterns in data that are indicative of fraudulent activity. For example, a bank might use predictive analytics to detect unusual patterns of card usage that could indicate fraudulent activity on a credit card.
  - Customer churn prediction: Predictive analytics can be used to predict which customers are likely to churn (i.e., stop doing business with a company). This can be useful for identifying customers who might be at risk of churning and taking action to prevent it.
  - Predictive maintenance: Predictive analytics can be used to predict when equipment is likely to fail, allowing companies to schedule maintenance before a failure occurs. This can help to reduce downtime and save money.
  - Supply chain optimization: Predictive analytics can be used to optimize the flow of goods through a supply chain by predicting demand and identifying bottlenecks.
  - Healthcare: Predictive analytics can be used to predict patient outcomes, such as the likelihood of a patient being readmitted to the hospital after being discharged. This can help healthcare providers to proactively address issues that could lead to negative outcomes.
  - Streaming video: Reinforcement learning is used to help identify which types of movies or shows you may want to watch next based on the ratings that you have provided to the service so far.
  - Marketing: Predictive analytics can be used to predict which marketing campaigns are likely to be most effective, allowing companies to allocate their marketing budget more effectively.

Predictive analytics can be used in a wide range of industries and applications to make more informed decisions, improve efficiency, and achieve better outcomes.

## Data visualization

Data visualization is important because it can help you understand complex datasets and communicate your findings to others in a clear and concise manner. When you visualize data, you can quickly see patterns and trends that may not be immediately apparent when looking at raw data. This can help you identify relationships and make more informed decisions. Additionally, data visualization allows you to communicate your findings to others in a way that is easy for them to understand, which is especially useful when presenting results to non-technical audiences. Next, you will dig into an example that shows the power of visualization where summary descriptive analysis may lead you in a different direction.

### Anscombe's quartet

![Anscombe's quartet data](https://user-images.githubusercontent.com/9215614/210279802-c17f4066-24d4-40ce-a943-9572833ab919.png)

What do you think a plot would look like when comparing the x variable to the y variable in each of the four sources? Would the plots be identical? Would the points all fall in the same pattern? 

When you visualize this data, you see that the actual data for these four sources is quite different. This is known as Anscombe's quartet created in the 1970s by Francis Anscombe. It's meant to show the power of data visualization and how outliers can skew statistical results.

![Anscombe's quartet visualized as scatterplots](https://user-images.githubusercontent.com/9215614/210279928-b91b9e71-7e0b-4f07-b320-edf96d0844f7.png)


### Datasaurus dozen

In 2016, Alberto Cairo created an extension of this called the Anscombosaurus or the Datasaurus Dozen to further accentuate this. It's a fun example that was pretty simply created using the available computational power.

![Datasaurus Dozen](https://blog.revolutionanalytics.com/downloads/DataSaurus%20Dozen.gif)


### Best practices

A good data visualization should effectively communicate the insights and findings of a data set. There are several characteristics that can make a data visualization effective:

  - Clarity: The visualization should clearly convey the message it is intended to, without any unnecessary distractions.
  - Accuracy: The visualization should accurately represent the data it is based on.
  - Simplicity: A good visualization uses the simplest and most efficient means to communicate its message.
  - Effectiveness: The visualization should effectively communicate the message it is intended to, and should be able to convince the viewer of its conclusions.
  - Aesthetically pleasing: While not the most important factor, a well-designed visualization can make it more engaging and appealing to the viewer.
  - Flexibility: The visualization should be able to effectively communicate different messages, depending on the audience and the context in which it is used.

The main goal of a meaningful data visualization is to communicate information clearly and effectively, so that the viewer can easily understand the insights and findings that have been derived from the data.

### Things to avoid

There are several things that should be avoided when creating data visualizations:

  - Clutter: A visualization should not have too many elements, as this can make it difficult for the viewer to understand the message being conveyed.
  - Distracting design elements: The design of the visualization should support and enhance the message, rather than distract from it.
  - Misleading or inaccurate representation of data: It is important to ensure that the visualization accurately represents the data it is based on.
  - Omitting important information: The visualization should include all relevant information, rather than leaving out important details.
  - Overuse of chartjunk: Chartjunk refers to visual elements that do not add value to the visualization and can actually detract from its effectiveness.
  - Confusing or hard-to-read visualizations: The visualization should be easy to understand and interpret, rather than being confusing or difficult to read.

In summary, it is important to avoid anything that could hinder the effectiveness of the visualization in communicating its message.

## Assessment/learning check questions

After reading the content above, take approximately 30 minutes answer this question below:

1. Find at least one "bad" graphic online in your field, lay out what is wrong with it, and how it could be improved to better tell a truthful, clarifying story.


