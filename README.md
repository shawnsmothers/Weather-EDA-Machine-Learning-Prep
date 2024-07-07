# Weather-EDA-Machine-Learning-Prep

### Very Brief Description of the Process

<p>I began with <b>Exploratory Data Analysis (EDA)</b>, where I performed initial data examination and cleaning. This included converting the <code>Date</code> column to datetime format, extracting the month from the <code>Date</code> column to add it as a feature, and calculating the average temperature (<code>AvgTemp</code>) by taking the mean of <code>MinTemp</code> and <code>MaxTemp</code>.</p>

<p>Next, I moved on to <b>Feature Engineering</b>. I created new features from the existing data to enrich the dataset and subsequently dropped unnecessary columns like <code>Date</code>.</p>

<p>For <b>One-Hot Encoding</b>, I converted categorical variables into numeric form to make them compatible with machine learning algorithms. This ensured that all columns in the dataset were numeric.</p>

<p>I then applied <b>Min-Max Scaling</b> to normalize the numerical features. This step ensured that all numerical features were within the same range, thereby improving model performance.</p>

<p>To determine <b>Feature Importance</b>, I used a logistic regression model. I fitted the logistic regression model on a sample of the dataset to quickly compute feature importance. The top 10 features based on their coefficients from the logistic regression model were then plotted, as seen in the provided bar chart.</p>

<p>Here are the recommended features based on their coefficients:
<ul>
  <li><b>RISK_MM:</b> 25.961086</li>
  <li><b>Humidity3pm:</b> 8.522127</li>
  <li><b>WindGustSpeed:</b> 6.472121</li>
  <li><b>Sunshine:</b> -6.187657</li>
  <li><b>Pressure3pm:</b> -5.203720</li>
  <li><b>Pressure9am:</b> 1.963852</li>
  <li><b>Rainfall:</b> 1.889929</li>
  <li><b>Cloud3pm:</b> 1.328668</li>
  <li><b>Evaporation:</b> -1.291791</li>
  <li><b>Location_MountGinini:</b> -1.245833</li>
</ul>
</p>

<p>This process helps in identifying the most impactful features for the machine learning model preparation.</p>
