Multiple Comparison Procedures
====================================
In general, if we perform m hypothesis tests, what is the probability of at least 1 false positive?

- P(Making an error) = $ \alpha$
- P(Not making an error) = $1 - \alpha$
- P(Not making an error in m tests) = $(1 - \alpha)^m$
- P(Making at least 1 error in m tests) = $1 - (1 - \alpha)^m$



<!------------------------------------------------------------------------->

### Bonferroni Correction
The Bonferroni correction is an adjustment made to P-values when several dependent or independent statistical tests are being performed simultaneously on a single data set. To perform a Bonferroni correction, divide the critical P-value ($ \alpha$) by the number of comparisons being made. 

For example, if 10 hypotheses are being tested, the new critical P value would be $ \alpha$/10. 
The statistical power of the study is then calculated based on this modified P value.

<!------------------------------------------------------------------------->

### False Discovery Rate (FDR)

<!------------------------------------------------------------------------->

### Family Wise Error Rate (FWER)

<!------------------------------------------------------------------------->
