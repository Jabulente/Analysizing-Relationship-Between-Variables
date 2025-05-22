<samp>
  <h1 align='center'>Analysis of Variance (ANOVA)</h1>


  <p>In many data analysis tasks, especially when comparing the effect of one or more categorical factors on a continuous outcome, it's important to determine whether differences in group means are statistically significant. Analysis of Variance (ANOVA) is a statistical method used to compare the means of three or more groups. It does this by analyzing the variation within groups and between groups to assess whether the observed differences in sample means are likely due to a real effect or could have occurred by random chance. ANOVA is widely used because it allows for the evaluation of multiple groups simultaneously while controlling the overall error rate.
  </p>

  
  <p>This project showcases the application of <span class="highlight">statistical analysis</span> techniques to compare group means using both <strong>One-Way</strong> and <strong>Two-Way ANOVA</strong>. The emphasis lies in <em>validating key assumptions</em> such as normality and homogeneity of variance prior to analysis, ensuring rigorous and reliable conclusions.</p>

  <h2>🎯 Purpose</h2>
  <p>The primary objective of this analysis is to investigate whether statistically significant differences exist in the means of a continuous variable across multiple groups defined by one or two categorical factors. By incorporating assumption testing and subsequent ANOVA, the project delivers robust insights into the relationships between variables.</p>

  <h2>🛠 Skills & Technologies Demonstrated</h2>
  <ul>
    <li><strong>Python Programming:</strong> Writing clean, modular code for data processing and statistical analysis.</li>
    <li><strong>Data Manipulation:</strong> Utilizing <code>pandas</code> for effective dataset cleaning and transformation.</li>
    <li><strong>Statistical Testing:</strong> Implementing <code>scipy.stats</code> functions like <code>shapiro()</code> and <code>levene()</code> for assumption checks.</li>
    <li><strong>ANOVA Modeling:</strong> Using <code>statsmodels</code> for performing One-Way and Two-Way ANOVA.</li>
    <li><strong>Visualization:</strong> Creating residual and diagnostic plots with <code>matplotlib</code> and <code>seaborn</code> to support assumption validation.</li>
    <li><strong>Data Presentation:</strong> Summarizing results in clear, structured DataFrames and markdown tables for interpretability.</li>
  </ul>

  <h2>📊 Statistical Methods Used</h2>
  <ul>
    <li><strong>Shapiro-Wilk Test:</strong> To assess normality of residuals.</li>
    <li><strong>Levene’s Test:</strong> To check homogeneity of variances across groups.</li>
    <li><strong>One-Way ANOVA:</strong> For comparing means across groups based on a single factor.</li>
    <li><strong>Two-Way ANOVA:</strong> To evaluate the influence and interaction of two categorical factors.</li>
    <li><strong>Post-Hoc Analysis:</strong> Identifies specific group differences after significant ANOVA results.</li>
  </ul>

  <h2>🔄 Workflow Overview</h2>
<p>The analytical process follows a clear, step-by-step workflow:</p>
<ol>
  <li><strong>Data Preparation:</strong> Load and clean data, ensuring consistent column names and proper formatting.</li>
  <li><strong>Data Exploration:</strong> Conduct exploratory data analysis to understand the distribution, identify outliers, and summarize key statistics for all relevant variables.</li>
  <li><strong>Assumption Validation:</strong> Use Shapiro-Wilk and Levene’s tests to verify normality and variance homogeneity.</li>
  <li><strong>ANOVA Execution:</strong> Conduct One-Way and Two-Way ANOVA analyses based on research questions.</li>
  <li><strong>Result Interpretation:</strong> Evaluate ANOVA output, perform post-hoc tests if needed, and interpret findings.</li>
  <li><strong>Visualization & Reporting:</strong> Generate diagnostic plots and summarize results in an accessible format.</li>
</ol>


  <h2>📁 Project Files</h2>
  <ul>
    <li><code>anova_analysis.ipynb</code>: Jupyter notebook containing the full analysis workflow.</li>
    <li><code>data.csv</code>: Example dataset used in the analysis.</li>
    <li><code>README.md</code>: This documentation file.</li>
  </ul>

  <h2>⚙️ Setup Instructions</h2>
  <p>Ensure you have <code>Python 3.7+</code> installed along with the required libraries:</p>
  <pre><code>pip install pandas scipy statsmodels matplotlib seaborn</code></pre>

  <h2>📌 Additional Notes</h2>
  <p>This project is designed to be adaptable across domains such as agriculture, healthcare, education, and social sciences. It assumes familiarity with basic statistics and Python programming. The structured approach guarantees reproducible and reliable results, making it suitable for research and professional portfolios.</p>

  <footer>
    &copy; 2025 Portfolio Project by [Your Name]. All rights reserved.
  </footer>

</samp>

