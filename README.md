<h1>Twitter Streaming Project</h1>
In this project, I have calculated the average sentiment of selected tweets and drew a dynamic graph that shows how this average sentiment is changing over time. Roughly, the steps involved:

<li>creating a twitter stream listener</li>
<li>collecting tweets in batches</li>
<li>getting the sentiment associated with each tweet</li>
<li>creating windows on the stream</li>
<li>calculating the average sentiment within each window</li>
<li>creating a dynamic graph that updates every x seconds with the window time on the x axis and the average sentiment in the window on the y-axis</li>

<h2>The graph</h2>
<li>Note that the graph will pop up in a separate window</li>
<li>Which was behind the browser</li>


<h2>Resources required</h2>
<li><span style="color:blue">streaming twitter</span>: based on the java twitter library <span style="color:blue">twitter4j</span>, this library provides Spark streaming support for twitter</li>
<li><span style="color:blue">stanford corenlp</span>: for the sentiment analysis</li>
<li><span style="color:blue">JFree Chart</span>: a java library for drawing charts (<a href="http://www.jfree.org/jfreechart/">http://www.jfree.org/jfreechart/</a></li>


<h2>Twitter keys</h2>
<li>Get twitter API keys <a href="https://developer.twitter.com/en/docs/basics/getting-started">Getting started with twitter API</a> (use the standard API)</li>
<li>Then assign them to various twitter4j objects</li>
