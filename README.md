<h1>Prediction of Parkinson's disease by analysis of dysphonia measurements.</h1>
<h2>About</h2>
<p>This project analyzes vocal measurement data from the Parkinsons's dataset in the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/174/parkinsons</p>
   <p> Using the datset of various vocal features, we perform:
    <ul>
        <li>Exploratory Data Analysis</li>
        <li>Feature Correlation Analysis</li>
        <li>Classification using Logistic Regression and Random Forest</li>
    </ul>
        The dataset comprises of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD) and about six measurements for each patient. The main aim of the data is to discriminate healthy people from those with PD, according to "status" column (0 for healthy and 1 for PD). There are a total of 197 instances for 22 features.
    </p>
<h2>Key Findings</h2>
<h3>EDA</h3>
  <p>Final analysis committing soon.</p>
<h3>Classification</h3>
  <p>
    <ul>
        <li>RobustScaler was used due to some features containing high number of outliers. This made it such that spread1 and PPE were the two most important features for both classification models.</li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
  </p>
  <h2>Libraries</h2>
  <p>
    <ul>
      <li>Pandas</li>
        <li>Seaborn</li>
        <li>Matplotlib</li>
        <li>NumPy</li>
        <li>SciPy</li>
        <li>Scikit-learn</li>
    </ul>
<h2>References</h2>
<ol>
   <li>Little, M. A., McSharry, P. E., Roberts, S. J., Costello, D. A., & Moroz, I. M. (2007). Exploiting nonlinear recurrence and fractal scaling properties for voice disorder detection. BioMedical Engineering OnLine, 6(1), 23. https://doi.org/10.1186/1475-925x-6-23</li>
   <li>Little, M., McSharry, P., Hunter, E., Spielman, J., & Ramig, L. (2008). Suitability of dysphonia measurements for telemonitoring of Parkinson’s disease. IEEE Transactions on Biomedical Engineering, 56(4), 1015–1022. https://doi.org/10.1109/tbme.2008.2005954</li>
</ol>
