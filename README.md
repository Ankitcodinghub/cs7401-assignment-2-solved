# cs7401-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS7401 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs7401-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91717&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS7401 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
General Instructions

<ol>
<li>You should implement the assignment in Python.</li>
<li>Ensure that the submitted assignment is your original work. Please do not copy any part from any source, including your friends, seniors, and/or the internet. If any such attempt is caught, serious actions, including an F grade in the course, are possible.</li>
<li>A single .zip file needs to be uploaded to the Courses Portal.</li>
<li>Your grade will depend on the correctness of answers and output. Due consideration will also be given to the clarity and details of your answers and the legibility and structure of your code.</li>
<li>Please start early to meet the deadline. Late submissions won’t be evaluated.</li>
</ol>
1 About

Modern distributional semantic algorithms (also known as word embedding algorithms) can be found inside many intelligent systems dealing with natural language. The goal of developing such embeddings is to learn meaningful vectors (embeddings), such that semantically similar words have mathematically similar vectors. The different types of word embeddings can be broadly classified into two categories:

<ul>
<li>Frequency-based Embedding:

There are generally three types of vectors that we encounter under this category: Count Vector, TF-IDF Vector, Co-occurrence Matrix with a fixed context window.</li>
<li>Prediction-based Embedding:

Word2vec is a popular method for training such representations, which can be implemented using either of these two models: Continuous Bag of Words (CBOW) and Skip-Gram (SG).

The computation of word2vec training algorithm in its vanilla implementation involved high compu- tational costs due to the calculation of gradients over the entire vocabulary. To reduce this computation and provide a good approximation to the process, variants such as Hierarchical Softmax output, Negative Sampling and Subsampling of frequent words were proposed to the simplistic architecture.

This assignment aims to make you familiar with the above algorithms by implementing one of the approaches in frequency-based modeling and comparing it with the embeddings obtained using one of the variants of word2vec. Specifically, you’ll first try out getting embeddings using Singular Value De- composition (SVD) method using a corpora specified. Next, you’d implement the CBOW implementation of word2vec with Negative Sampling. A short analysis would follow, highlighting the differences in the quality of embeddings obtained.

Note on terminology: The terms “word vectors” and “word embeddings” are often used interchangeably. The term “embedding” refers to the fact that we are encoding aspects of a word’s meaning in a lower- dimensional space. As Wikipedia states, “conceptually it involves a mathematical embedding from space with one dimension per word to a continuous vector space with a much lower dimension”.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 Questions &amp; Grading Total marks: 100

2.1 Theory

Explain negative sampling. How do we approximate the word2vec training computation using this tech- nique? [10 marks]

2.2 Implementation

<ol>
<li>ImplementawordembeddingmodelandtrainwordvectorsbyfirstbuildingaCo-occurrenceMatrix followed by the application of SVD. [25 marks]</li>
<li>Implement the word2vec model and train word vectors using the CBOW model with Negative Sam- pling. [35 marks]</li>
</ol>
2.3 Analysis

Report these for both models after you’re done with the training.

<ol>
<li>Display the top-10 word vectors for five different words (a combination of nouns, verbs, adjectives,
etc.) using t-SNE (or such methods) on a 2D plot. [10 marks]
</li>
<li>What are the top 10 closest words for the word ’camera’ in the embeddings generated by your program? Compare them against the pre-trained word2vec embeddings that you can download off-the-shelf. [10 marks]</li>
</ol>
2.4 Presentation

We would check these points at the time of individual evaluations that would involve code walk-through, explanation of the report analysis, and questions based on the implementation.

• Implementation efficiency &amp; quality

• Report quality

• Inclusion of a readme along with the code

• Crisp &amp; clear explanation of the code during evals

[10 marks]

3 Training corpus

Please train your model on the corpus linked here:

<pre>http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Electronics_5.json.
gz
</pre>
4 Submission format

Zip the following into one file and submit it on the Moodle course portal: 1. Source code (Should include .py files only.)

2. Pre-trained model and the generated embeddings

3. Report answering all the questions

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
4. Readme file (should contain instructions on how to execute the code, restore the pre-trained model, and any other information necessary for clarity)

Name the zipped file as &lt;roll number&gt;_&lt;assignment2&gt;.zip, e.g.: 2021xxxxxx_assignment2.zip.

Note: If the pre-trained models and embeddings cross the file size limits, upload them to a OneDrive/G- Drive and share the read-only accessible links in the readme file.

5 FAQs

<ol>
<li>Do we train the embeddings for all the unique words we see in the corpus?

You can place a limit: words with a frequency less than five can be ignored. If you have enough compute, you can train for as many words as possible.</li>
<li>Do I need to ignore the stop words?

Usually, stop words occur with very high frequency. It won’t help if you blindly ignore the stop words from the corpus. To avoid the effect of the terms that occur very frequently, you can use sub-sampling, which is another technique to decrease the compute cost in word2vec training.</li>
<li>Do I need to use lemmatization before feeding the samples to the model? No, for the sake of this assignment, you may not perform lemmatization.</li>
<li>I do not have enough compute. Can I reduce the working corpus size?

Yes, you may reduce the vocabulary size. But make sure you train the model on enough no. of sentences, which should be a minimum of 30,000 sentences.</li>
<li>Can I submit my code in Jupyter Notebooks?

No, the final submission should be a Python script. You may work using a Jupyter Notebook, but make sure to convert it to .py file before submitting.</li>
<li>Explain the stuff we have to report under analysis.

We have asked you to report these two results per model:

<ol>
<li>(a) &nbsp;For displaying the top 10 words:

You can pick the 10 nearest words for a particular word in terms of cosine similarity. After having picked the top 10 words, plot them on a 2D plot. You can use t-SNE (or such) to reduce dimensions before plotting.</li>
<li>(b) &nbsp;For comparing against pretrained word2vec embeddings from a library:

Download any pre-trained vectors for English that are available. Get the 10 closest words for the word “camera” in the embeddings generated by you as well as the downloaded model, and compare the two outputs.</li>
</ol>
You can use libraries like Scikit-learn and Gensim to read vector files and pick the nearest k words for a query word.
</li>
</ol>
6 Resources

6.1 Papers

1. Efficient Estimation of Word Representations in Vector Space

2. Distributed Representations of Words and Phrases and their Compositionality

6.2 Explanatory supplements

1. Stanford lecture notes – SVD &amp; word2vec

2. A simple, intuitive explanation of word2vec, with Negative Sampling included

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3. Skip Gram with Negative Sampling

4. word2vec Explained: Deriving Mikolov et al.’s Negative-Sampling Word-Embedding Method 5. On word embeddings in general

</div>
</div>
</div>
