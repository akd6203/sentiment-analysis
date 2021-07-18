# sentiment-analysis
In this repository, I am going to perform sentiment analysis on food reviews dataset step by step.
<!-- wp:image {"id":109,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/sentiment-analysis-scaled-1.jpg?w=1024" alt="" class="wp-image-109"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>Requirements</h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>python (<a href="https://www.python.org/downloads/"><em>https://www.python.org/downloads/</em></a>)</li><li>sklearn (<em>pip install sklearn</em>)</li><li>pysttsx3 (<em>pip install pysttsx3</em>)</li><li>numpy (<em>pip install numpy</em>)</li><li>matplotlib (<em>pip install matplotlib</em>)</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3>DOWNLOAD CODE :</h3>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li>Download the code from <a href="https://github.com/akd6203/brain-tumor-detection/tree/master">github</a></li><li>Download all above mentioned dependencies.</li><li>Open downloaded folder inside jupyter notebook.</li><li>Now cells as per your requirements.</li></ol>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3> STEP 1: Load Dependencies </h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Here you need to import all the required libraries. I have used<strong> </strong> <strong>pysttx3</strong> for text to speech conversion. You can skip this part if you want to show prediction in text format only. </p>
<!-- /wp:paragraph -->

<!-- wp:image {"align":"left","id":116,"sizeSlug":"large","linkDestination":"none"} -->
<div class="wp-block-image"><figure class="alignleft size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-1.png?w=700" alt="" class="wp-image-116"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>STEP 2: Load and prepare data</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Note: You can find dataset  inside github repository link (given above). In repository, you will find a file named "Restaurant_Reviews.tsv"</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":117,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-2.png?w=701" alt="" class="wp-image-117"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>STEP 3: Data Cleaning</h3>
<!-- /wp:heading -->

<!-- wp:image {"id":118,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-3.png?w=791" alt="" class="wp-image-118"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>STEP 4: Split Data</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Now, we have to split data into training and testing dataset. So that, we can train model on raining data and check its accuracy on unseen data.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":120,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-4.png?w=820" alt="" class="wp-image-120"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>STEP 5: Tokenization </h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Now, we have to convert text data into numeric form. I have used CountVectorizer() for this.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":122,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-5.png?w=701" alt="" class="wp-image-122"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 6: Model Training</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>As we have done the required data preprocessing, now it is the time to train mode. Here, I will use two different model and I will compare the performance of these two model. Eventually, I will pick best fit model.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":124,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-6.png?w=709" alt="" class="wp-image-124"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 7: Make Prediction</h3>
<!-- /wp:heading -->

<!-- wp:image {"id":126,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-7.png?w=700" alt="" class="wp-image-126"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 8: Evaluation</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Now it is the time to compare performance of <em>Logistic Regression </em>and <em>Naive Bayes </em>Algorithms on given dataset.</p>
<!-- /wp:paragraph -->

<!-- wp:gallery {"ids":[129,137],"linkTo":"none"} -->
<figure class="wp-block-gallery columns-2 is-cropped"><ul class="blocks-gallery-grid"><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-8.png?w=716" alt="" data-id="129" data-link="https://cwadtech.wordpress.com/untitled-8/" class="wp-image-129"/></figure></li><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-12.png?w=701" alt="" data-id="137" data-full-url="https://cwadtech.files.wordpress.com/2021/07/untitled-12.png" data-link="https://cwadtech.wordpress.com/untitled-12/" class="wp-image-137"/></figure></li></ul></figure>
<!-- /wp:gallery -->

<!-- wp:paragraph -->
<p>As we can see in the result above, <em>Logistic Regression </em>performed comparatively well. So we can continue with <em>Logistic Regression </em>Model.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3> STEP 9: Parameter Tuning [Optional]</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>You can find best value for parameters using Grid Search CV method.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":132,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-9.png?w=730" alt="" class="wp-image-132"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 10: Result Visualization</h3>
<!-- /wp:heading -->

<!-- wp:image {"id":136,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-11.png?w=664" alt="" class="wp-image-136"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 11: Check Models' performance on real data</h3>
<!-- /wp:heading -->

<!-- wp:image {"id":134,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-10.png?w=950" alt="" class="wp-image-134"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 12: Export Model To pkl file</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>It is clear now that LR model is best fit model for that particular data. However, parameter tuning can be done in order to import its score. Now we will export model and tokenizer to pkl files and then we will deploy this model to a small desktop application.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":138,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-13.png?w=670" alt="" class="wp-image-138"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3> STEP 13: Create simple desktop application using Tkinter.</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In this step, I have created a simple desktop application to predict food reviews. I have used <em>pyttsx3</em> model to convert text prediction into voice.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":140,"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-14.png?w=810" alt="" class="wp-image-140"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>RESULTS</h3>
<!-- /wp:heading -->

<!-- wp:gallery {"ids":[143,144],"linkTo":"none"} -->
<figure class="wp-block-gallery columns-2 is-cropped"><ul class="blocks-gallery-grid"><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-15.png?w=715" alt="" data-id="143" data-link="https://cwadtech.wordpress.com/untitled-15/" class="wp-image-143"/></figure></li><li class="blocks-gallery-item"><figure><img src="https://cwadtech.files.wordpress.com/2021/07/untitled-16.png?w=677" alt="" data-id="144" data-full-url="https://cwadtech.files.wordpress.com/2021/07/untitled-16.png" data-link="https://cwadtech.wordpress.com/untitled-16/" class="wp-image-144"/></figure></li></ul></figure>
<!-- /wp:gallery -->

<!-- wp:heading {"level":4} -->
<h4>VISIT MY YOUTUBE CHANNEL FOR MORE DETAILS: <a href="https://youtu.be/D2t-P3zEeSk">https://youtu.be/D2t-P3zEeSk</a></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->
