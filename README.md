# RESI-SR
Residual Symbolic Regression

# Symmary
During Symbolic Regression, it is quite an issue that it punishes the number of concluded variables from your dataset.
Thus the main idea herein, is to fit another models into residual(actual - predicted).
Such process could be repeated: residual of residuals.
Moreover, if repeated, such residual terms could be converged into Gaussian distribution(, or 'noise').
