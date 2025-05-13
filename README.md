# statistical-learning-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [Statistical-Learning Homework 1 Solved](https://www.ankitcodinghub.com/product/statistical-learning-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93905&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Statistical-Learning Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
• You can use any programming language you want, as long as your work is runnable/correct/readable. Two examples: – In R: it would be nice to upload a well-edited and working R Markdown file (.rmd) + its html output.

– In Python: it would be nice to upload a well-edited and working Jupyter notebook (or similia).

In case of R

If you go for R, to be sure that everything is working, start RStudio and create an empty project called HW1. Now open a new R Markdown file (File &gt; New File &gt; R Markdown…); set the output to HTML mode, press OK and then click on Knit HTML. This should produce a html. You can now start editing this file to produce your homework submission.

• For more info on R Markdown, check the support webpage: R Markdown from RStudio. • For more info on how to write math formulas in LaTex: Wikibooks.

The Data

For this first homework you’ll be working on the WMAP data described at page 45 (Example 4.4) of our purple book. We are talking about a snapshot of our universe in its infancy, something like 379,000 years after the Big Bang, nothing compared to the estimated age of our universe1.

The map above was taken by the Wilkinson Microwave Anisotropy Probe (WMAP) and shows differences across the sky in the temperature of the cosmic microwave background (CMB), the radiant heat remaining from the Big Bang. The average temperature is 2.73 degrees above absolute zero but the temperature is not constant across the sky. The fluctuations in the temperature map provide information about the early universe. Indeed, as the universe expanded, there was a tug of war between the force of expansion and contraction due to gravity. This caused acoustic waves in the hot gas, which is why there are temperature fluctuations.

The strength of the temperature fluctuations f(x) at each frequency (or multipole) x is called the power spectrum and this power spectrum can be used by cosmologists to answer cosmological questions. For example, the relative abundance of different constituents of the universe (such as baryons and dark matter) corresponds to peaks in the power spectrum. Through a complicated procedure (not described here), the temperature map can be reduced to the following scatterplot of power versus frequency:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre># Load the data
</pre>
wmap &lt;- read.csv(“~/wmap.csv”) # Plot

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1…something like 14 billion years!

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
lay.mat = matrix(c(1,1,2,3), nrow = 2, byrow = T) layout(lay.mat)

# All

plot(wmap$x, wmap$y, pch = 21, bg = “yellow”, cex = .7,

<pre>     main = "CMB data (WMAP)", xlab = "Multipole", ylab = "Power")
polygon(c(0,400,400,0),
</pre>
<pre>        c(min(wmap$y), min(wmap$y), max(wmap$y), max(wmap$y)),
</pre>
border = NA, col = rgb(0,0,0,.3)) # First bump

<pre>plot(wmap$x[1:400], wmap$y[1:400], pch = 21, bg = "green", cex = .7,
     main = "Main bump", xlab = "Multipole", ylab = "Power")
</pre>
<pre># Secondary bump(s)
</pre>
<pre>plot(wmap$x[-(1:400)], wmap$y[-(1:400)], pch = 21, bg = "red", cex = .7,
     main = "Secondary bump(s) (?)", xlab = "Multipole", ylab = "Power")
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
<div class="column">
Main bump

100 200 300 400

Multipole

</div>
<div class="column">
400 500

</div>
<div class="column">
600 700 800 900

Multipole

</div>
</div>
<div class="layoutArea">
<div class="column">
0 200 400

</div>
<div class="column">
600 800

Secondary bump(s) (?)

</div>
</div>
<div class="layoutArea">
<div class="column">
CMB data (WMAP)

</div>
</div>
<div class="layoutArea">
<div class="column">
Multipole

</div>
</div>
<div class="layoutArea">
<div class="column">
The horizontal axis is the multipole moment, essentially the frequency of fluctuations in the temperature field of the CMB. The vertical axis is the power or strength of the fluctuations at each frequency. The top plot shows the full data set. The two bottom plots zoom in the first 400 and the next 500 data points. The 1st peak, around x ≈ 200, is obvious. But many

“official” fit (see Fig. 2 in that page) show also a 2nd and 3rd peak further to the right. . .

. . . are they really there? Does the data support (without further a priori info) these secondary features?

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
−10000

</div>
</div>
<div class="layoutArea">
<div class="column">
Power Power

</div>
</div>
<div class="layoutArea">
<div class="column">
0 3000 −10000

</div>
</div>
<div class="layoutArea">
<div class="column">
Power

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part I: Polynomials are good. . .

. . . but smooth piecewise polynomials (a.k.a. splines) are better!

In our initial supervised toy example we tried to recover from samples a non-linear (in the original 1-dimensional feature-space) function using a linear model in a higher-dimensional transformed feature-space (polynomials of degree d) Now, polynomials are fine, but they are global objects (they span the entire real-line in principle) and may not be able to capture local structures of the target function.

recipe for a solution: 1. take a polynomial, 2. break it down is small (almost) free-to-move chunks, 3. shake a bit, 4. glue them back together adding some regularity constraint (continuity, differentiability, etc) as needed. . . a spline is born. . .

more formally: any dth-order spline f(·) is a piecewise polynomial function of degree d that is continuous and has continuous derivatives of orders {1, . . . , d − 1} at the so called knot points. Specifically, how do we build a generic dth-order spline f(·)? We start from a bunch of points, say q, that we call knots ξ1 &lt; ··· &lt; ξq, and we then ask that…

1. . . . f(·) is some polynomial of degree d on each of the intervals: (−∞, ξ1], [ξ1, ξ2], [ξ2, ξ3], . . . , [ξq, +∞);

2. …itsjth derivativef(j)(·)iscontinuousat{ξ1,…,ξq}foreachj∈{0,1,…,d−1}.

The figure below from Chapter 5 of ELS illustrates the effects of enforcing continuity at the knots, across various orders of the

derivative, for a cubic piecewise polynomial.

Splines have some amazing properties, and they have been a topic of interest among statisticians and mathematicians for a very long time (classic vs recent). But, given a set of points ξ1 &lt; ξ2 &lt; · · · &lt; ξq , is there a quick-and-dirty way to describe/generate the whole set of dth-order spline functions over those q knots? The easiest one (not the best!), is to start from truncated power functions Gd,q = {g1(x),…gd+1(x),g(d+1)+1(x),…,g(d+1)+q(x)}, defined as

􏰲g1(x)=1,g2(x)=x,…,gd+1(x)=xd􏰳 and 􏰲g(d+1)+j(x)=(x−ξj)d+􏰳qj=1 where (x)+ =max{0,x}.

Then, if f(·) is a dth-order spline with knots {ξ1, . . . , ξq} you can show it can be obtained as a linear combinations over Gd,q

(d+1)+q

f(x)= 􏰷 βj ·gj(x), forsomesetofcoefficients β=􏰰β1,…,βd+1,β(d+1)+1,…β(d+1)+q􏰱T.

j=1

idea: let’s perform regression on splines instead of polynomials! In other words, as in our initial toy example, given inputs x = {x1, . . . , xn} and responses y = {y1, . . . , yn}, consider fitting functions f(·) that are dth-order splines with knots at some chosen locations, typically the first q quantiles of x 􏰺 this method is dubbed regression splines and it is different from another famous technique called smoothing splines (we will talk about it later as an example of (Mercer) kernel method).

remark: here you have many tuning parameters (the degree d and the number+position of knots) to be selected predictively via Cp or some flavor of cross-validation (sample-splitting, k-fold CV, LOOCV, GCV). Although there is a large literature on knot selection for regression splines via greedy methods like recursive partitioning, here we will go for an easy-to-implement option.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
􏰺 Your job 􏰺

</div>
</div>
<div class="layoutArea">
<div class="column">
1. First of all, briefly explain to me why this idea is yet another manifestation of our “be linear in transformed feature space” mantra. Do you “perceive” any technical difference with the “(orthogonal) series expansion” point of view described in our “extended” Linear Algebra notes (from page 9)? Don’t be shy, give this question at least a try!

2. Plot a few elements of Gd,q with d ∈ {1, 3} and q ∈ {3, 10} equispaced knots in the open interval (0, 1).

3. Following our polynomial regression example, implement regression splines from scratch on the wmap data by considering:

• d ∈ {1, 3} (i.e. linear and cubic-splines only);

• knots on q-equispaced locations (within the x-range) 􏰺 grid-search between a min value qmin and a max value qmax

of your choosing.

You will choose the best (d, q)-combination via GCV and any flavor of CV you like. Of course, the crucial/boring point is

to handmade the n × (d + 1) + q design matrix X having generic entry

X[i,j]=gj(xi) for i∈{1,…,n} and j∈􏰲1,…,(d+1)+q􏰳.

</div>
</div>
<div class="layoutArea">
<div class="column">
After that, you can just use least squares (as implemented in lm(), for example) to determine the optimal coefficients 􏰸􏰸􏰸􏰸􏰸

</div>
</div>
<div class="layoutArea">
<div class="column">
β = 􏰰β1 , . . . , βd+1 , β(d+1)+1 , . . . , β(d+1)+q 􏰱T , which then leaves us with the fitted regression spline (d+1)+q

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰸􏰸 f(x)= 􏰷 βjgj(x).

j=1

4. Now, after having visualized the fit and although we are making no real effort to get a stellar fit, try to (at least qualitatively) compare the best spline fit you got so far with a GCV-tuned polynomial regression. Which one do you prefer? Explain.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Part II: To be parametric or not to be, this is (another) dilemma. . . The Theory

An important use of nonparametric regression is in testing whether a parametric regression model is well–specified or not. Assume that our parametric regression model is given by

i.i.d. 2

yi =f(xi|θ)+εi where εi ∼ N(0,σ ) ∀i∈{1,…,n}, (1)

and f ( · | θ) is some (possibly nonlinear) function completely specified up to the parameter vector θ.

If, for example, f( · | θ) describes a linear model, that is f(x | α, β) = α + β x how can we check whether it is appropriate or not?

One approach would be to add specific departures from linearity, a quadratic term say, and seeing whether the coefficients that go with those terms are significantly non–zero, or whether the improvement in fit is relevant/significant.

But our flexible nonparametric regression, by its very definition, allows you to check for all kinds of possible departures, rather than just a particular one. Hence, the idea could go as follows:

• IF the parametric model is correct2 it should predict better than – or at least as well as – the nonparametric one. Consequently we expect the following mean–squared error difference between the two models

</div>
</div>
<div class="layoutArea">
<div class="column">
T = MSEp􏰮θ􏰯 − MSEnp􏰮f􏰯

T is clearly our test statistics. As usual, we have no hope of working out analytically its distribution under the null H0. So, in

the following, we will resort to a particular parametric bootstrap3 strategy. Here is the procedure in its generality:

<ol start="0">
<li>Get the data D = {(x1,y1),…,(xn,yn)}.</li>
<li>Fit the parametric model to get an estimate θ􏰸. Let MSEp􏰮θ􏰸􏰯 be the in–sample (or training) mean–squared error; that is
􏰮􏰯1􏰷n􏰴􏰮􏰯􏰵2 􏰮 2􏰯
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
to be sufficiently small.

</div>
</div>
<div class="layoutArea">
<div class="column">
yi−f xi|θ􏰸 =mean residuals .

</div>
</div>
<div class="layoutArea">
<div class="column">
MSEp θ􏰸 =n

2. Fit your favorite nonparametric regression by, for example, cross–validation, getting curve f(·) and in–sample

mean–squared error MSE 􏰮f􏰯; that is np 􏰸

</div>
</div>
<div class="layoutArea">
<div class="column">
3. Calculate: t = MSE 􏰮θ􏰯 − MSE

􏰸 p􏰸 np􏰸

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰮􏰯1􏰷n􏰴 􏰵2 􏰮 2􏰯 􏰸n􏰸

</div>
</div>
<div class="layoutArea">
<div class="column">
MSEnp f = yi−f(xi) =mean residuals . i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰮f 􏰯.

<ol start="4">
<li>Simulate from the parametric model in Equation (1) by taking θ = θ􏰸 to get fake data under an approximate null:
D′ = {(x′1,y1′ ),…,(x′n,yn′ )}.
</li>
<li>Fit the parametric model to the simulated data D′ getting estimate θ􏰹 and MSEp􏰮θ􏰹􏰯.
′􏰹􏰹
</li>
<li>Fit the nonparametric model to the simulated data D getting estimate f(·) and MSEnp􏰮f􏰯.</li>
<li>Calculate: t = MSE 􏰮θ􏰯 − MSE 􏰮f 􏰯. 􏰹 p􏰹 np􏰹</li>
<li>Repeat steps 4–7 B times to get an estimate of the distribution of the test statistics T under the null. Please notice that this step takes some time because each replication involves not just generating a new simulation sample, but also cross-validation to pick a bandwidth!</li>
<li>The p-value is then: 1 􏰶B I􏰮tb &gt; t􏰯 = 􏰲proportion of t’s larger than t􏰳. Bb=1􏰹􏰸 􏰹 􏰸</li>
</ol>
2This is the null hypothesis H0: the parametric model is correct.

3See Section 3.3 page 31 of your book or slide 53 and after of my prerequisite notes

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰸

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
􏰺 Your job 􏰺

<ol>
<li>Focus your attention on the second part of the data by dropping the first 400 observations and saving the others in a
dataframe called wmap_sb.
</li>
<li>Considerasimplelinearmodelf(x|θ)=θ0+θ1x.

Fit this model (in R use lm()) and call it lin_fit.

Explore a little bit your fit by looking at summary statistics and diagnostic plot (in R use summary(lin_fit) and plot(lin_fit)).

Plot the data-scatter and add the linear fit.

Do you think this model is any good? Explain.

Finally, evaluate the training mean-squared error and store this value into a variable called MSEp_hat (in R, use the function residuals() on lin_fit to get the residuals).</li>
<li>Fit and tune by using any method you like (Cp, or LOOCV, or GCV, etc) a spline regression model as in Part I to get f_hat and its in–sample mean–squared error to be stored in a variable called MSEnp_hat.

Notice that, in R, the function residuals() can still be applied to extract the model residuals.

Add the nonparametric model to the plot you made before, and qualitatively compare the parametric and the nonpara- metric fit you’ve got so far.</li>
<li>Calculate: t_hat = MSEp_hat – MSEnp_hat</li>
<li>for(b in 1:B) repeat the following four steps (B 􏰻 500):</li>
</ol>
a. Simulate a new data set from the fitted parametric model lin_fit assuming homoskedastic Gaussian noise. The following function does the job, just pass the original x vector as second input.

Explain what it does (i.e. why it makes sense), translate it in Python (if you need), and then use it!

<pre>              # Inputs: linear model (lin_fit), x values at which to simulate (sim_x)
              # Outputs: Data frame with columns x and y
              sim_lm = function(lin_fit, sim_x) {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>  n      = length(sim_x)
  sim_fr = data.frame(x = sim_x)
  sigma  = summary(lin_fit)$sigma
  y_sim  = predict(lin_fit, newdata = sim_fr)
  y_sim  = y_sim + rnorm(n, 0, sigma)
  sim_fr = data_frame(sim_fr, y = y_sim)
  return(sim_fr)
</pre>
}

</div>
<div class="column">
<pre># Add noise
# Adds y column
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Fit the parametric model to the simulated data getting MSEp_tilde[b]</li>
<li>Fit and tune (as done above) the nonparametric model to the simulated data getting MSEnp_tilde[b]</li>
<li>Calculate: t_tilde[b] = MSEp_tilde[b] – MSEnp_tilde[b]</li>
</ol>
6. Once you get a (bootstrapped) p-value, what is the conclusion of your test? Are those secondary bumps there? Finally, look again at the original scatterplot, do you think that all the hypotheses behind the simulation scheme adopted

(double-check above) are reasonable for the data at hand?

More in general, how robust do you think your conclusions are w.r.t. them? Explain.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
