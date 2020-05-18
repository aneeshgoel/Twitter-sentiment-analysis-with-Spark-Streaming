# Twitter-sentiment-analysis-with-Spark-Streaming-
<h1>Twitter Streaming Assignment</h1>
In this assignment, you need to calculate the average sentiment of selected tweets and draw a dynamic graph that shows how this average sentiment is changing over time. Roughly, you need to:

<li>create a twitter stream listener</li>
<li>collect tweets in batches</li>
<li>get the sentiment associated with each tweet</li>
<li>create windows on the stream</li>
<li>calculate the average sentiment within each window</li>
<li>create a dynamic graph that updates every x seconds with the window time on the x axis and the average sentiment in the window on the y-axis</li>

<h2>The graph</h2>
<li>Note that the graph will pop up in a separate window</li>
<li>Which may be behind your browser - so look for it!</li>


<h2>Resources required</h2>
<li><span style="color:blue">streaming twitter</span>: based on the java twitter library <span style="color:blue">twitter4j</span>, this library provides Spark streaming support for twitter</li>
<li><span style="color:blue">stanford corenlp</span>: for the sentiment analysis</li>
<li><span style="color:blue">JFree Chart</span>: a java library for drawing charts (<a href="http://www.jfree.org/jfreechart/">http://www.jfree.org/jfreechart/</a></li>
