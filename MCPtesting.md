Multiple Comparison Procedures
====================================
In general, if we perform m hypothesis tests, what is the probability of at least 1 false positive?

- P(Making an error) = $ \alpha$
- P(Not making an error) = $1 - \alpha$
- P(Not making an error in m tests) = $(1 - \alpha)^m$
- P(Making at least 1 error in m tests) = $1 - (1 - \alpha)^m$


### What Does Correcting for Multiple Testing Mean?
- When people say “adjusting p-values for the number of hypothesis tests performed” what they mean is controlling the Type I error rate
- Very active area of statistics - many different methods have been described


### Different Approaches To Control Type I Errors
- Per comparison error rate (PCER): the expected value of the numberof Type I errors over the number of hypotheses,
 PCER = E(V)/m
- Per-family error rate (PFER): the expected number of Type I errors, PFE = E(V).
- Family-wise error rate: the probability of at least one type I error FEWR = P(V ≥ 1)
- False discovery rate (FDR) is the expected proportion of Type I errorsamong the rejected hypotheses
 FDR = E(V/R | R>0)P(R>0)
- Positive false discovery rate (pFDR): the rate that discoveries arefalse
 pFDR = E(V/R | R > 0)

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
