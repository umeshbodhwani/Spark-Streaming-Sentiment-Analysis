# Spark-Streaming-Sentiment-Analysis

### Calculated the average sentiment of selected tweets and drawn a dynamic graph that shows how this average sentiment is changing over time.

<li>Create a twitter stream listener</li>
<li>Collect tweets in batches</li>
<li>Get the sentiment associated with each tweet</li>
<li>Create windows on the stream</li>
<li>Calculate the average sentiment within each window</li>
<li>Create a dynamic graph that updates every x seconds with the window time on the x axis and the average sentiment in the window on the y-axis</li>



<h3>Resources required</h2>
<li><span style="color:blue">streaming twitter</span>: based on the java twitter library <span style="color:blue">twitter4j</span>, this library provides Spark streaming support for twitter</li>
<li>Stanford CoreNLP: For the sentiment analysis</li>
<li>JFree Chart: a Java library for drawing charts (<a href="http://www.jfree.org/jfreechart/">http://www.jfree.org/jfreechart/</a>)</li>
