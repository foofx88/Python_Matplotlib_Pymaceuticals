<h3>Python Matplotlib - Pymaceuticals</h3>
<hr>

<p>Visualizing <a href="/data/Mouse_metadata.csv">dataset</a> with Matplotlib plots.</p>

<p>Before analysis, the metadata was cleaned by checking for any mouse ID with duplicate time points and remove any data associated with that mouse ID.</p>
<p>The cleaned data then used for the following:</p>
<ul>
  <li>Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen</li>
  <li>Generate a bar plot to show the number of total mice for each treatment regimen throughout the course of the study</li>
  <img src= "/images/mice_treatment.png">
  <li>Generate a pie plot to shows the distribution of female or male mice in the study</li>
  <img src= "/images/mice_genderdist.png">
  <li>Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.</li>
  <li>Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.</li>
</ul>  

<p>Matplotlib was then used to generate a box and whisker plot of the final tumor volume for all four treatment regimens and potential outliers were highlighted with different color</p>
<img src= "/images/mice_4drugs.png">

<p>User input was included to get user to select a mouse that was treated with Capomulin. A line plot of tumor volume vs. time point then generated for that mouse. </p>
<img src= "/images/mice_capomulin.png">

<p>A scatter plot with a correlation coefficient and linear regression model of mouse weight versus average tumor volume for the Capomulin treatment regimen and </p>
<img src= "/images/miceweight_avgtum.png">


Observations and Jupyter Notebook can be explored <a href="/pymaceuticals_starter.ipynb">here</a>
