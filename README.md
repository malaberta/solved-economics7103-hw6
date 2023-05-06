Download Link: https://assignmentchef.com/product/solved-economics7103-hw6
<br>
This assignment uses the data from the previous homework.

You have imaginary data on the monthly yields for Pacific fish trawling companies (<em>fishbycatch.csv</em>). An environmental nonprofit targeted these firms and implemented a program designed to reduce bycatch. As part of the program, the nonprofit contacted firm managers and provided information about best practices to reduce bycatch. The program was implemented in two phases. In January 2018, the nonprofit contacted half of the firms. The next year in January 2019, the nonprofit contacted the remaining firms.

You are interested in whether the program worked or not and decide to use this panel data to empirically estimate the effect of the program. You realize that you have a treatment and control group in pre- and post-treatment periods due to the program’s rollout, so you think a difference-in-differences design is a good approach. You have the following data:

<table width="422">

 <tbody>

  <tr>

   <td width="67">Variable</td>

   <td width="355">Description</td>

  </tr>

  <tr>

   <td width="67"><em>firm</em></td>

   <td width="355">Firm identification number</td>

  </tr>

  <tr>

   <td width="67"><em>shrimp*</em></td>

   <td width="355">Pounds of shrimp in month *</td>

  </tr>

  <tr>

   <td width="67"><em>salmon*</em></td>

   <td width="355">Pounds of salmon in month *</td>

  </tr>

  <tr>

   <td width="67"><em>bycatch*</em></td>

   <td width="355">Pounds of bycatch in month *</td>

  </tr>

  <tr>

   <td width="67"><em>firmsize</em></td>

   <td width="355">Size of fishing fleet</td>

  </tr>

  <tr>

   <td width="67"><em>treated</em></td>

   <td width="355">=1 if firm received information treatment in January 2018</td>

  </tr>

 </tbody>

</table>

Table 1: Variable descriptions for homework 5.

<ol>

 <li>You now would like to allow and control for firm-specific fixed-effects. In particular, you would like to allow for an unobserved effect <em>c<sub>i </sub></em>that varies at the firm level but not over time:</li>

</ol>

<em>bycatch</em><em>i,t </em>= <em>c</em><em>i </em>+ <em>λ</em><em>t </em>+ <em>δtreat</em><em>i,t </em>+ <em>βX</em><em>i,t </em>+ <em>u</em><em>i,t.                                                         </em>(1)

<ul>

 <li>Generate indicator variables for each firm. Include these indicator variables in your OLS regressionto control for fixed effects directly.</li>

 <li>Perform the “within-transformation” on all of the dependent and independent variables by demeaning each variable (i.e. instead of estimating <em>y<sub>i,t </sub></em>= <em>βx<sub>i,t </sub></em>+ <em>ξ<sub>i,t</sub></em>, estimate <em>y<sub>i,t </sub></em>− <em>y</em>¯<em><sub>i </sub></em>= <em>β</em>(<em>x<sub>i,t </sub></em>− <em>x</em>¯<em>i</em>) + <em>e</em><em>i,t</em>).</li>

 <li>Display the results of your estimates from (a) and (b) in the same table, using the same standarderrors or confidence intervals from Homework assignments 3 and 4. Omit the estimates of the coefficients on the month and firm indicators in your table. How do the results from (b) compare to (a)? How do these estimates compare to the previous estimates of the treatment effect and how does the interpretation change? (Note for the future that standard errors from (a) are typically “wrong”, but do not worry about that for this homework. In addition, (a) is computationally costly when the panel size is large—in general you should use the within transformation to control for fixed effects.)</li>

</ul>

1