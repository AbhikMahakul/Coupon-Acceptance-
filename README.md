<h2> Determining the Acceptance of a Coupon </h2>
<br>
<p> To determine if a coupon will be accepted, we will be using a log reg machine learning algorithim. Prior to training the model, a considerable amount of time was spent cleaning the data. We had a lot of non-numeric data that had magnitude, and for the model to comprehend this, we needed to spend time encoding this. An example would be education level. The values for this were all non-numeric('Some High School','High School Graduate','Some college - no degree','Associates degree', 'Bachelors degree', 'Graduate degree (Masters or Doctorate)'), however to indicate that certain levels of education are greater than others, we spent time encoding this variable along with others. </p>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Coupon-Acceptance-/blob/main/Images/Variable%20Classification.png" /></p>
<br>
<p> After cleaning the data, we began training our model. For this project we are using logistic regression. Our cross validation score was 63.92%. Below is the learning curve. </p>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Coupon-Acceptance-/blob/main/Images/logreglearningcurve.png" /></p>
<br>
<p> To optomize our model, we utilized parameter tuning. Our cross validation score was 64.02%. Below is the learning curve.</p>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Coupon-Acceptance-/blob/main/Images/logregtunedlearningcurve.png" /></p>
<br>
<p> To simplify the model, we are using PCA. The cross validation score was 64.11%. Below is our learning curve.</p>
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Coupon-Acceptance-/blob/main/Images/PCALogreg.png" /></p>
<br>
<p> Finally we tuned the PCA model. Our cross validation score was 63.71%. Below is the learning curve.</p?
<p><img alt="Image" title="icon" src="https://github.com/AbhikMahakul/Coupon-Acceptance-/blob/main/Images/PCALogREgTuned.png" /></p>
