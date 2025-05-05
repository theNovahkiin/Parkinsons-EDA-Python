<h1>Prediction of Parkinson's disease by analysis of dysphonia measurements.</h1>
<h2>About</h2>
<p>This project analyzes vocal measurement data from the Parkinsons's dataset in the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/174/parkinsons</p>
<p> Using the datset of various vocal features, we perform:
    <ul>
        <li>Exploratory Data Analysis</li>
        <li>Feature Correlation Analysis</li>
        <li>Classification using Logistic Regression and Random Forest</li>
    </ul>
<p>The dataset comprises of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD) and about six measurements for each patient. The main aim of the data is to discriminate healthy people from those with PD, according to "status" column (0 for healthy and 1 for PD). There are a total of 197 instances for 22 features.</p>
<p>
Matrix column entries (attributes):
<ul>
   <li>name - ASCII subject name and recording number</li>
   <li>MDVP:Fo(Hz) - Average vocal fundamental frequency (base pitch)</li>
   <li>MDVP:Fhi(Hz) - Maximum vocal fundamental frequency (highest detected pitch)</li>
   <li>MDVP:Flo(Hz) - Minimum vocal fundamental frequency (lowest detected pitch)</li>
   <li>MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency or frequency variability (higher jitter values associated with irregularities in vocal vibrations)</li>
   <li>MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA - Several measures of variation in amplitude or amplitude variablity (increased shimmer indicates weakness or unsteadiness in vocal strength)</li>
   <li>NHR, HNR - Two measures of ratio of noise to tonal components in the voice or vocal harmonics quality</li>
   <li>status - Health status of the subject; (1) - Parkinson's, (0) - healthy</li>
   <li>RPDE, D2 - Two nonlinear dynamical complexity measures (RPDE reflects unpredictability of vocal vibration period, D2 reflects complexity of vocal signals)</li>
   <li>DFA - Signal fractal scaling exponent (measures long-term correlation in speech signals)</li>
   <li>spread1, spread2, PPE - Three nonlinear measures of fundamental frequency variation (spread1 & spread2 reflect pitch instability, PPE measures entropy or randomness of the pitch period)</li>
</ul>
Acronyms
<ul>
    <li>MDVP - Multidimensional voice program</li>
    <li>RAP - Relative average perturbation</li>
    <li>PPQ - Period perturbation quotient</li>
    <li>DDP - Average absolute difference of differences between consecutive periods</li>
    <li>APQ3, APQ5 - Amplitude perturbation quotient 3 & 5</li>
    <li>DDA - Difference of differences of amplitude</li>
    <li>NHR - noise-to-harmonics ratio</li>
    <li>HNR - harmonics-to-noise ratio</li>
    <li>RPDE - Recurrence period density entropy</li>
    <li>D2 - Correlation dimension</li>
    <li>DFA - Detrended fluctuation analysis</li>
    <li>PPE - Pitch period entropy</li>
</ul>
</p>
<h2>Key Findings</h2>
<h3>EDA</h3>
  <p>Final analysis committing soon.</p>
<h3>Classification</h3>
  <p>
    <ul>
        <li>RobustScaler was used due to some features containing high number of outliers. This made it such that spread1 and PPE were the two most important features for both classification models. The scaler instance for StandardScaler can be uncommented to see the changes in the most used feature.</li>
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
