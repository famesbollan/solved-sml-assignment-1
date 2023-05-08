Download Link: https://assignmentchef.com/product/solved-sml-assignment-1
<br>
Q1. Consider the following decision rule for a two-category one-dimensional problem:

Decide <em>ω</em><sub>1 </sub>if <em>x &gt; θ</em>; otherwise decide <em>ω</em><sub>2</sub>.

<ul>

 <li>Show that the probability of error for this rule is given by</li>

</ul>

(1)

<ul>

 <li>By differentiating, show that a necessary condition to minimize P(error) isthat <em>θ </em>satisfy <em>p</em>(<em>θ</em>|<em>ω</em><sub>1</sub>)<em>P</em>(<em>ω</em><sub>1</sub>) = <em>p</em>(<em>θ</em>|<em>ω</em><sub>2</sub>)<em>P</em>(<em>ω</em><sub>2</sub>)</li>

</ul>

Q2. Let the conditional densities for a two-category one-dimensional problem be given by the Cauchy distribution

2                                      (2)

Assuming <em>P</em>(<em>ω</em><sub>1</sub>) = <em>P</em>(<em>ω</em><sub>2</sub>), show that <em>P</em>(<em>ω</em><sub>1</sub>|<em>x</em>) = <em>P</em>(<em>ω</em><sub>2</sub>|<em>x</em>) if <em>x </em>= (<em>a</em><sub>1 </sub>+<em>a</em><sub>2</sub>)<em>/</em>2, i.e., the minimum error decision boundary is a point midway between the peaks of the two distributions, regardless of <em>b</em>.

Q3. Suppose we have three equi-probable categories in two dimensions with the following underlying distributions:

By explicit calculation of posterior probabilities, classify the point x =

for minimum probability of error.

1

Q4. a. Write a procedure to generate random samples according to a normal distribution <em>N</em>(<em>µ,</em>Σ) in <em>d </em>dimensions.

<ol>

 <li>Write a procedure to calculate the discriminant function for a given</li>

</ol>

normal distribution with Σ = <em>σ</em><sup>2</sup><em>I </em>and prior probability <em>P</em>(<em>ω<sub>i</sub></em>).

<ol>

 <li>Compare the discriminant function’s values for two different distributions</li>

</ol>

) and    = 2 dimensions.

Assume the test sample to be and <em>P</em>(<em>ω</em><sub>1</sub>) = 1<em>/</em>3 and <em>P</em>(<em>ω</em><sub>2</sub>) = 2<em>/</em>3.

In a general process, you would be given several samples from two (or more) classes. Counting each class’ frequency will give the priors. With these samples as d dimensional vectors, you can estimate mean and covariance using MLE or other techniques, which is a part of later lecture. This computed info is sufficient for computing discriminants and thereby classifying the sample into one of the classes.

2