Nonparametric inference for thresholds of risk
======

This repository includes source code for R functions which implement the nonparametric methods for inference on risk thresholds detailed
in [Nonparametric inference for immune response thresholds of risk in vaccine studies](https://www.ncbi.nlm.nih.gov/pubmed/31285781) by Donovan, Hudgens, and Gilbert (2019).  An example analysis using these methods on simulated datasets can be found [here](https://kmdono02.github.io/Risk_Threshold/).

The files are summarized below:

1) index.html : HTML document illustrating use of these methods using simulated datasets (see website above)

2) index.Rmd: R markdown file from which Thres_SimData_Exs.html was created

* Note: Files 1) and 2) are found in the **docs** subfolder

3) Thres_CrossSect.R : R source code for function which implements nonparametric estimator (weighted and unweighted) for cross-sectional data at a single time point (Sections 2 and 3 in paper)

4) Thres_Surv.R : R source code for function which implements nonparametric estimator (weighted and unweighted) for time to event data (Section 4 in paper)

* Note: These functions require the dataset to be in a specific format; see source code for details

5) sim_data_logit.R : R source code for function to simulate dataset under a logit model for cross-sectional data; used with examples in document index.html

6) sim_data_logistic.R : R source code for function to simulate dataset under a logitistic model for cross-sectional data; used with
                         examples in document index.html
