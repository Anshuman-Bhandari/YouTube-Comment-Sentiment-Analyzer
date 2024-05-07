

<h1>YouTube Comment Sentiment Analyzer</h1>

<p>This project is a machine learning model that extracts comments from YouTube videos, analyzes their sentiment, and provides insights into the engagement level of the video based on the comments.</p>

<h2>How It Works</h2>

<p>This model extract comments for YoutTube video using YouTube Developer Key and video id. The model uses natural language processing techniques TF IDF to lemmatize comments from YouTube videos. It then performs sentiment analysis on these comments to determine whether they are positive, negative, or neutral. Based on this analysis, the model provides an output indicating the overall sentiment of the comments and how many people liked the video based on their comments.</p>

<h2>Installation</h2>

<ol>
  <li>Clone the repository:</li>
</ol>
<pre><code>git clone https://github.com/Anshuman-Bhandari/YouTube-Comment-Sentiment-Analyzer.git
</code></pre>

<ol start="2">
  <li>Install the required dependencies:</li>
</ol>
<pre><code>pip install regex
</code></pre>
<pre><code>pip install google-api-python-client
</code></pre>
<pre><code>pip install pandas
</code></pre>
<pre><code>pip install textblob
</code></pre>
<pre><code>pip install nltk
</code></pre>
<pre><code>pip install scikit-learn
</code></pre>

<h2>Usage</h2>

<ol>
  <li>Run the <code>main.py</code> script:</li>
</ol>
<pre><code>python main.py
</code></pre>

<ol start="2">
  <li>Enter the URL of the YouTube video you want to analyze when prompted.</li>
  <li>The model will extract comments from the video, analyze them, and provide an output indicating the sentiment of the comments and the number of people who liked the video based on their comments.</li>
</ol>

<h2>Contributing</h2>

<p>Contributions are welcome! Please fork the repository and submit a pull request with your changes.</p>
