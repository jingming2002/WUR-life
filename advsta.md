# Advanced statistics review

## General idea about a population
--- Question about population  
--- Take sample   
--- Test hypothesis in the sample   
--- Take into account variation among samples  
--- Draw a conclusion about the population

## Confidence interval (CI)  
An interval that is expected to typically contain the parameter being estimated    
CI=Point Estimate±(t critical)×(Standard Error)  

Point Estimate: Exp. point estimate of popilation mean(&mu;) is sample's mean(x&#772;) 
 
T critical: Width of interval and Df(degrees of freedom) 
 
Standard Error: Size and variation of the sample  

## t-test
Degrees of freedom determine the shape of t-distribution; larger df will cause it more normality, if df → ∞, it will be exactly a normal distribution.  

### Single-sample t-test
Sample's mean compared with known &mu;   
1. H<sub>0</sub>: x&#772; = &mu;  
H<sub>a</sub>: x&#772; != &mu;  or  x&#772; > &mu; or x&#772; < &mu;  
2. t = (x̄ - μ₀) / (s/√n)
3. Under H<sub>0</sub>, t~t<sub>df = (n - 1)</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion
### Independent two-sample t-test
***SAME VARIANCE!!!!!!!!!!!!!***  
Comparing the two samples' means  
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= (x̄₁ - x̄₂) / [sₚ × √(1/n₁ + 1/n₂)]  
sₚ= √{ [ (n₁ - 1)s₁² + (n₂ - 1)s₂² ] / (n₁ + n₂ - 2) }  
df = n₁ + n₂ - 2
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

#### Welch's t-test
Normally, we do not have two samples with exactly the same variances, so Welch's t-test could be applied.  
It is essentially the same as the t-test, but offers more conservative calculations and a lower probability of false positivity.
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= (x̄₁ - x̄₂) / [sₚ × √(1/n₁ + 1/n₂)]  
sₚ= √{ [ (n₁ - 1)s₁² + (n₂ - 1)s₂² ] / (n₁ + n₂ - 2) }  
***df = [ (s₁²/n₁ + s₂²/n₂)² ] / [ (s₁²/n₁)²/(n₁-1) + (s₂²/n₂)²/(n₂-1) ]***
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

### Paired-sample t-test
Check there is any difference between one sample in two conditions.
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= d̄ / (s_d / √n)
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

