Download Link: https://assignmentchef.com/product/solved-ie567-homework-9-using-the-gaussian-copula-model-of-correlated-default-times
<br>



<ol>

 <li><strong>Using the Gaussian copula model to simulate losses due to default.</strong></li>

</ol>

Consider a bank loan portfolio consisting of 100 loans each with a loan amount of $8 million and 20 large loans each with an amount of $20 million.  You want to use the Gaussian copula to estimate the distribution of losses due to default.  Your horizon is one year (you are interested in defaults that occur during the next one year).  For each loan, the probability of a default during the next year is 0.012 or 1.2%, and for each loan the loss given default (LGD) is LGD = 50%.




<ul>

 <li>Initially, assume that defaults on the 120 loans are independent.  Please estimate the distribution of possible losses due to the possible defaults of the 120 loans.</li>

</ul>




<em>Remark</em>:  Because the defaults are independent, it is possible to answer part (a) without using simulation.  However, you are welcome to use simulation to answer this part.




<ul>

 <li>) Next, assume that the copula correlation between each pair of loans is 0.30 or 30%. Using this copula correlation, estimate the distribution of possible losses due to the possible defaults of the 120 loans.</li>

</ul>




<em>Hint</em>.  Since the copula correlations between each pair of obligors are the same, you can use the single-factor Gaussian copula model.




<ul>

 <li>Next, assume that you have a population of 2,000 obligors, each with default probability of 1.2%. If the copula correlation is 30%, what is your estimate of the default correlation between different obligors?</li>

</ul>




<ul>

 <li> Continue to assume that you have a population of 2,000 obligors, each with default probability of 1.2%. If the copula correlation is 30%, what is your estimate of the standard deviation of the annual default rate on the portfolio?</li>

</ul>

<em> </em>

<ul>

 <li> Using actual (not simulated) data, you have estimated that the standard deviation of the annual default rate is 0.02 or 2%. Using the cross-section of 2,000 obligors, please find the copula correlation that is consistent with the standard deviation of 2%.</li>

</ul>




<ol start="2">

 <li><strong>Economic capital. </strong> Let<em> EL</em> denote the expected default losses on a loan portfolio, and let <em>Q</em>(0.999) denote the 99.9% quantile of the loss distribution.   Some banks define the Economic Capital <em>EC</em> to be</li>

</ol>




<em>EC</em> = <em>Q</em>(0.999) – <em>EL</em>;




it is interpreted as the amount of capital beyond the expected losses needed to cover all losses up to the 99.9% quantile.  It is common to use a horizon of one year, i.e. the loss distribution is the distribution of losses over the next year.

<strong> </strong>

<ul>

 <li> If the losses are independent, what is the Economic Capital required to support the loan portfolio?</li>

</ul>




<ul>

 <li> What is the Economic Capital if the copula correlation is 30%?</li>

</ul>




<em>Remark</em>.  Note that the economic capital is very sensitive to the correlation.

<strong> </strong>

<ol start="3">

 <li><strong> Hedging “excess” concentrations using a first-loss tranche</strong> (total 3 points) Your bank is unhappy with the distributions of default losses that you estimated in Question 1, and is considering hedging the possible default losses using a kind of credit default swap (CDS) known as a first-loss tranche.  (The counterparty of the CDS will be a hedge fund.)  If your bank enters into the CDS, it will synthetically transfer the credit exposure of one-half of each of the 20 large loans to a special purpose vehicle (SPV).  Thus, a total of 20 × (1/2) × $20 million = $200 million of credit exposure will be transferred to the SPV.  The hedge fund will insure the first $40 million of losses on the $200 million of exposure transferred to the SPV.  Your bank will be responsible for any losses greater than $40 million on the exposure transferred to the SPV.  Your bank will of course also be responsible for the losses on the exposures not transferred to the SPV.</li>

</ol>




<ul>

 <li> Please estimate the distribution of possible losses due to the possible defaults of the 120 loans, taking account of the protection provided by the hedge. Assume that defaults on the 120 loans are independent.</li>

</ul>




<ul>

 <li> What are the expected losses on the loan portfolio, taking account of the hedge? What is the Economic Capital?</li>

</ul>




<ul>

 <li> Please estimate the distribution of possible losses due to the possible defaults of the 120 loans, taking account of the protection provided by the hedge and assuming that the copula correlation is 0.30 or 30%. What are the expected losses on the loan portfolio, taking account of the hedge?  What is the Economic Capital?</li>

</ul>




<em>Remark.</em> Of course your bank pays (and the hedge fund receives) a CDS premium.  In this question it is not necessary to consider the CDS premium.




<ol start="4">

 <li><strong>Allowing for random recovery.</strong> (total 2 points)  Questions 1, 2, and 3 make the simplifying assumption that LGD = 50%.   A more reasonable assumption is that LGD is random, with an expected value that will differ depending on the terms of the loan.  (For example, secured loans will typically have higher recoveries).  For this question, assume that recovery is given by $<em>F</em> × <em>x</em>, where $<em>F</em> is the amount of the loan (either $8 million or $20 million) and <em>x</em> is a random variable.  The distribution of <em>x</em> is beta, with parameters α = β = 2.   Assume that recoveries on the different loans are independent.</li>

</ol>




<ul>

 <li>(1 point) Assume random recovery given by the beta distribution and that defaults on the 120 loans are independent.  Please estimate the distribution of possible losses due to the possible defaults of the 120 loans.</li>

</ul>




<ul>

 <li> Next, assume that the copula correlation between each pair of loans is 0.30 or 30%. Using this copula correlation, estimate the distribution of possible losses due to the possible defaults of the 100 loans.  Continue to assume that recovery is random and given by the beta distribution.</li>

</ul>





