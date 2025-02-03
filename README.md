# Fama-French-Five-Factor-Model-Replication

This project replicate Fama-French (2015, JFE) from 07/01/1926 to 12/31/2024

You need to have WRDS account to download CRSP and Compustat.

It also compare the replicated results with Ken French's website(https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html). 
The accuracy score is beetween 94 to 99. The accuracy score is calulated by: 50*Corr(R_replicated,R_FF)+25*(1-|/mu_replicated-/mu_FF|)+25*(1-|/sigma_replicated-/sigama_FF|) where correlation is in decimals, and means and standard deviations of returns are in percent per month.
