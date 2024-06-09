# Psy2R - unleashing post-hoc contrast confidence intervals into reproducible workflows   

<br>

**A list of contributors so far**

Kelly Garner, Jessica Lee, Julie Chow, Josh Wooley, Josh Mosse-Robinson, Lydia Barnes,  Kateryna Marchenko,  Ambica Golyala, Sonny Li, Kevin Bird  

<br>

## About

To move beyond binary decision-making in the interpretation of the outcomes from statistical models, we need to estimate and communicate the size of our estimated effects, and our uncertainty in the estimated effect size. This requires that we report both estimated effect sizes and the confidence intervals around those effects. Psy is a windows-based software that enables computation of 

Translating the Psy software package to R Code and functions

**What Psy does**
Specify contrasts of interest for which you want to compute confidence intervals

 1.  Indvidual confidence intervals: CI for each contrast in the set.
 2.  Simultaneous confidence intervals (where the magic is)  
    a) *Bonferonni t* for between, within and between*within family  
    b)  Post hoc intervals:  
          Between main effects: Scheffe method  
          Within main effects: Hotelling's $T^2$  
          Between/within: Roy's GCR Method  
    c) Balanced 2 factor between subjects: Boik's SMR CIs  
 3. Scaling options (go into after replication 1 & 2)  

    



**Resources**  
<br>
[PSY](https://www.unsw.edu.au/science/our-schools/psychology/our-research/research-tools/psy-statistical-program)  
<br>
[R package for Approximating GCR Critical Statistic](https://github.com/cran/RMTstat)  
<br>
[Good webpage for contrast coding](https://marissabarlaz.github.io/portfolio/contrastcoding/)  
<br>
[Guide to test stats for MANOVA in R](https://rpubs.com/aaronsc32/manova-test-statistics)  
<br>
[emmeans source code](https://github.com/rvlenth/emmeans/tree/master/R)
<br>
