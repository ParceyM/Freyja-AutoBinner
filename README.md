# Freyja-AutoBinner
A basic R script and methodology for binning aggregated Freyja outputs over a reporting period.  
Briefly: 
* The R scripts takes the output from freyj aggregate as an input and separates the data by line.
* The date and site is derived from the sample name. This will have to be customized to fit the naming structure used.
* The data is "dealiased" to the full pangolinage designation (e.g. EG.5 to XBB.1.9.2.5).
* Lineages are averaged over the reporting period and aggregated with their parents until the designated threshold has been met.
* All lineages aggregated in this way that surpass the threshold are used for binning.

Sample data supplied.

### This script will not be updated or maintained.
