# Project Details

* Name: Mohamed Hussein   
* Project title: Why do they Switch? Determinants of Primary School Switching in Kenya
* Abstract: Adolescent girls in the Kibera slums of Kenya switch schools at an unusually high rate, with no clear explanation as to why. The importance of understanding this pattern stems from fears of the negative effects school switching may have on later life outcomes, such as earnings. Given the importance of the qualifying exams at the end of the primary stage, girls could be switching schools strategically in order to receive better schooling, in which case switching is unlikely to have negative consequences. Alternatively, switching schools could be cause by unstable family structure, leading girls to end up at worse quality schools and harming them in the long run. This paper exploits a unique dataset of schooling history of 11-14 year-old Kenyan girls currently residing in Kibera, Nairobi. The results provide suggestive evidence that school switching does not occur strategically. 






#Introduction: 
Recent research highlights the poor state of education in Kenya, which is characterized by under-performing schools and a declining teacher-to-student ratio, despite the prioritization of education by recent Kenyan governments (Oketch and Somerset 2010).  Of particular concern are ‘slums,’ informal settlements in urban areas characterized by squalor and substandard housing that house up to 60% of Nairobi’s current population, or about 2 million individuals. These areas suffer from extremely high levels of poverty, a lack of basic infrastructure, and exclusion from most government initiatives. Perhaps unsurprisingly, data on schooling in slums are scarce, which hampers any attempts at understanding the role education might play as a tool to alleviate poverty in such areas. If we believe education to be an effective way of improving life outcomes for low income populations in general, then it becomes imperative to better understand the educational environment in Kenya’s slums. 

The Kibera slum in Nairobi is Africa’s biggest slum with a population that ranges between 250,000 to 800,000 inhabitants and is the focus of this paper. Similar to other slums it is characterized by a high unemployment rate (50%), low access to electricity (less than 20% of households), and a none-existent sewage system (up to 50 households share a latrine, a hole in the ground for the collection of feces). Unique to Kibera is an unusually high school switching rate among adolescent girls during their primary education. Figure 1 contrasts the proportion of Kibera girls who have switched schools at least once with the rates of girls enrolled in a similar study in Wajir, located in the north eastern part of Kenya. Whereas more than half (63%) of all girls in Kibera have switched schools at least once, only 3% of girls in Wajir have switched schools before. Conditional on switching, the number of switches per girl is considerably higher in Kibera at 2, compared to Wajir’s 1.3 switches per girl. Even compared to similar urban slums in the city of Nairobi, Kibera’s school switching rate among adolescent girls in this study is higher (e.g. Harambee 32% in Oketch et al. 2010). 

![](Draft3_files/figure-html/unnamed-chunk-3-1.png)<!-- -->

School switching is of particular concern for fear of its negative effects. A growing body of literature in developed countries highlights the negative consequences school switching may have on future life outcomes. Tønnessen, Telle, and Syse (2016), for instance, trace the relocations of more than 960,000 Norwegians born between 1965 and 1980. They find switching residents and schools negatively impacts education, income, and reproductive health outcomes, especially for those who moved during their adolescence. Langenkamp (2014) finds similar results in the US, showing that school switchers have fewer friends and are more likely to fail at school. Ong and Witte (2003), using a regression discontinuity design, similarly show that school switching negatively affects educational outcomes, by increasing the probability of dropping out of school before completing secondary stage. To the best of my knowledge, there has been no similar research done in developing countries. Given these robust results of the negative effects of schools switching, understanding this phenomenon in the Kenyan context seems relevant to efforts of development. 

It is unclear why Kibera possesses such a high rate of school switching. One popular hypothesis is ‘strategic switching.’ In Kenya, each student must sit a qualifying exam (KCPE) in eighth grade that determines their high school placement, which in turn affects their university placement. Given that high-quality schools are often expensive, it is entirely conceivable that a forward-looking parent with limited financial resources would ‘save money’ by sending their kids to a cheaper school for the first few years of their education, before transferring to a better-quality school in preparation for the KCPE. There are three immediate testable implications of this hypothesis. First, on average, we would expect the switchers to change schools closer to the KCPE, which takes place in grade eight. Second, students are expected to switch towards schools of ‘better quality.’ Finally, students may commute for larger distances in order to reach these new schools. This project contributes to the thin literature available on education in slum areas by assessing these three implications, examining in the process potential determinants of school switching. 

#Data 

The data come from a collaborative project, called Adolescent Girls Initiative – Kenya, piloted by the Population Council, the UK Department for International Development, and the African Population and Health Research Centre. The project itself is a randomized trial that compares the impact of four different intervention packages on young girls’ life outcomes. The data I use come from the 2015 participant baseline survey, during which the team collected data on the participants, their household characteristics, their schooling history, and the quality of the schools they currently attend. The sample size consists of 2,311 girls residing in Kibera at the time of the survey, all between the ages of 11 and 15.

Since the families of the participants agreed to enroll them in the program, there is no guarantee that the sample is unbiased. If families that enrolled did so for the benefit of their daughters, then the bias is likely to be positive, meaning that our results are an underestimate of the true relationship. If, however, the families enrolled the girls for the sake of their own benefit (i.e. the enrollment does not reflect their care for the daughter but rather reflects their ‘neglect’), then the results are likely to be overestimates. Since this bias is unresolvable with the current data structure, this project makes no claims as to the external validity of these results. That is, the results presented here may not generalize to outside this sample. 


#Results:
![](Draft3_files/figure-html/unnamed-chunk-6-1.png)<!-- -->

Figure 2 presents the distribution of school switches by grade. For the girls who switched at least once, the histogram shows the exact grade after which they switched. The bulk of the switches, it appears, takes place early on in the girls’ educational career, given that the average switch occurs between grades three and four and that the mode switch occurs after grade four. This point is made clearer by the cumulative distribution function of school switching displayed in figure 3. By the third grade, half of all the switches have already occurred and about 70% take place by grade four. Combined, these two figures provide suggestive evidence against the first implication of the hypothesis: the bulk of the switching does not take place directly before KCPE as one would expect if switching occurred strategically. 

![](Draft3_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

It is possible that parents are being _overly_ strategic in that the switching is taking place even before the expected (and arbitrary) fifth grade threshold. If this were the case, then we would expect the switching to be oriented towards better quality schools. In the context of Kenya, public schools are often seen as having better quality than private schools. This is especially true of ‘informal’ private schools, which are typically made of metal shacks with no access to electricity or running water and which form the majority of ‘private’ schools in slum areas. Figure 3 shows the breakdown of switches by grade and by whether the switched occurred towards a public (high-quality) or private (low-quality) school. The green line represents the cumulative density function for girls who switched into public schools, while the red line shows the cumulative distribution function for those who switched to private schools. If a girl switched more than once, the most recent switch was chosen, since it would reflect the quality of the school she attends closest to the KCPE. Superficially, there appears to be some differences between the two groups. For example, while approximately 16% of all switches occurred after the first grade for girls who switched to public schools, only 12% of switches took place for girls who switched to private schools. The difference is also noticeable for switches after grade five, where about 87% of all public-school switches have occurred but only 84% of private-switches took place. 

--------------------------------------------------------------------------
           &nbsp;              Estimate   Std. Error   t value   Pr(>|t|) 
----------------------------- ---------- ------------ --------- ----------
 **Difference b/w Public and   0.00228     0.00248      0.918     0.359   
          Private**                                                       

       **(Intercept)**          0.998      0.00168       595        0     
--------------------------------------------------------------------------

Table: Fitting linear model: ever_switched ~ switch_to_public


--------------------------------------------------------------------------
           &nbsp;              Estimate   Std. Error   t value   Pr(>|t|) 
----------------------------- ---------- ------------ --------- ----------
 **Difference b/w Public and  -5.78e-16    5.99e-16    -0.965     0.336   
          Private**                                                       

       **(Intercept)**            1        4.16e-16    2.4e+15      0     
--------------------------------------------------------------------------

Table: Fitting linear model: ever_switched ~ switch_to_public

A statistically significant difference between private and public switching would provide evidence in support of the strategic switching hypothesis.  Table 1 provides the results of a naïve regression, which functionally acts as a t-test. The results show that there is no statistically significant difference between private and public switching for the overall sample, neither is there a difference for the switches occurring directly after the fifth grade. The differences coefficients are not only imprecise but also small in size. This table, then, is further evidence against the strategic switching hypothesis. 



The final piece of evidence this paper presents to test the strategic switching hypothesis is related to distance. It is well established within development literature that distance is correlated with education. Anbesu and Junge (1988), for example, find that the majority of pupils in Ethiopia lived within 30 minutes’ walk of their schools, implying that enrolment was influenced by school accessibility. Glick and Sahn (2006) find that distance has a strong negative effect on demand for schooling in Madagascar. Colclough, Rose, and Tembon (2000) confirm these findings and point out that, compared to male students, enrollment of female adolescent students is more heavily impacted by an increase in the travel distance to schools. If the families were being ‘strategic’ about the switch, we would expect the switchers to be attending schools that are relatively close by in order to minimize the time and effort wasted in transportation. Alternatively, the parents could be sending their daughters to further away schools in pursuit of better-quality education. In either case, we would expect a difference between the switchers and non-switchers in terms of the distance to their schools. 
<!--html_preserve--><div id="htmlwidget-9915" style="width:672px;height:480px;" class="leaflet html-widget"></div>

This interactive map shows the households of participants, as well as the schools they currently attend and the Euclidian path between the two points. Visually, there appears to be no difference between girls who have switched at least once and those who have never switched schools in terms of the distance they travel to attend school. This is confirmed by a t-test of the difference in distance between the two groups, which shows a statistically insignificant coefficient (p-value = 0.198) and whose results are presented in table 2. There is, thus, no difference in either direction in the distance travelled by girls to school between the switchers and the non-switchers. 


#Discussion 
The three refuted implications so far provide strong evidence against the strategic switching hypothesis. Parents, on average, do not seem to be switching their daughters between schools in this sample in preparation for the KCPE. If this is indeed the case, the question then becomes: what factors determine school switching? Since this dataset is plagued with endogeneity, the best we can do in this situation is establish potential correlations between factors and school switching. In order to do so, I run the following model: 

$Pr(Switch_i) = \alpha_i + \beta_1\vec{ability_i}+\beta_2\vec{household_i} +\beta_3\vec{confidence} +\beta_4 distance_i +\varepsilon_i$, where $\vec{ability_i}$ measures ability via the Raven Test, a cognitive ability proxy.$\vec{household_i}$ represents a vector of covariates that controls for the employment status of the parents and whether they live at home. $\vec{confidence}$ denotes a set of agree/disagree questions that try to measure how safe and 'in control' a given girl feels in her community. 


--------------------------------------------------------------------------
           &nbsp;              Estimate   Std. Error   z value   Pr(>|z|) 
----------------------------- ---------- ------------ --------- ----------
    **Raven Test Score**       -0.0706      0.0814     -0.867     0.386   

        **Distance**           0.00217     0.00181      1.19      0.232   

     **Father Employed**        -0.21       0.251      -0.835     0.404   

     **Mother Employed**        -0.143       0.19      -0.754     0.451   

   **Father living in HH**      0.347       0.251       1.38      0.166   

   **Mother living in HH**      -0.394      0.323       -1.22     0.224   

 **Mother education (year)**   -0.0138      0.0314      -0.44      0.66   

  **Girl E(Marriage Age)**      0.0404      0.0184      2.19      0.0284  

   **Male Friends (no.)**      -0.0129      0.0449     -0.287     0.774   

  **Female Friends (no.)**     -0.00421     0.0186     -0.226     0.821   

 **Feel Safe in Community**    -0.00672     0.292      -0.023     0.982   

   **In control of life**      -0.0496      0.164      -0.303     0.762   

 **Influence surroundings**     -0.256      0.163       -1.58     0.115   

        **Intercept**           -0.106       0.66      -0.161     0.872   
--------------------------------------------------------------------------

Table: Fitting generalized (binomial/logit) linear model: ever_switched ~ raven_std + distance + hh_prnt_fathemp + hh_prnt_mothemp + hh_prnt_fathinhh + hh_prnt_mothinhh + hh_prnt_motheducyr + mar_expectedage + saf_good_friendsm + saf_good_friendsf + saf_walk_dark_com + loc_owndoing + loc_infl


-----------------------------------------------
           &nbsp;              2.5 %    97.5 % 
----------------------------- -------- --------
    **Raven Test Score**        -1.4     1.19  

        **Distance**           -0.23    0.089  

     **Father Employed**      -0.00139 0.00572 

     **Mother Employed**       -0.702   0.283  

   **Father living in HH**     -0.515   0.229  

   **Mother living in HH**     -0.145   0.839  

 **Mother education (year)**   -1.03     0.24  

  **Girl E(Marriage Age)**    -0.0753   0.0477 

   **Male Friends (no.)**     0.00427   0.0766 

  **Female Friends (no.)**     -0.101   0.0751 

 **Feel Safe in Community**   -0.0407   0.0322 

   **In control of life**      -0.579   0.566  

 **Influence surroundings**    -0.37    0.271  

        **Intercept**          -0.575   0.0624 
-----------------------------------------------

Table 3 presents the regression results from the above model. At first glance, there seems to be no relationship between the covariate vectors of ability, household characteristics, and self-efficacy with school switching. Table 4 shows the confidence intervals associated with the logistic regression. Since the lower and upper bound are always of different signs, we fail to reject the null hypothesis that there is no relationship between these covariates and school switching. These results may be reflective of opposing forcing within subsamples that cancel each other out. Consequently, I estimate the aforementioned regression for those who switched to a public school and those who switched to a private school, on the premise that these two groups are different. 

--------------------------------------------------------------------------
           &nbsp;              Estimate   Std. Error   z value   Pr(>|z|) 
----------------------------- ---------- ------------ --------- ----------
    **Raven Test Score**        0.206       0.0922      2.24      0.0253  

        **Distance**           0.00993     0.00212      4.69     2.75e-06 

     **Father Employed**        0.358       0.292       1.23      0.221   

     **Mother Employed**        -0.362      0.204       -1.78     0.0756  

   **Father living in HH**      -0.284      0.282       -1.01     0.314   

   **Mother living in HH**      0.635       0.376       1.69      0.0916  

 **Mother education (year)**   -0.00161     0.0346     -0.0466    0.963   

  **Girl E(Marriage Age)**      0.0117      0.0198      0.592     0.554   

   **Male Friends (no.)**      -0.0922      0.0569      -1.62     0.105   

  **Female Friends (no.)**      0.0351       0.02       1.75      0.0794  

 **Feel Safe in Community**    -0.0268      0.323      -0.0831    0.934   

   **In control of life**       0.191       0.181       1.06       0.29   

 **Influence surroundings**     -0.125      0.179      -0.698     0.485   

        **Intercept**           -2.36       0.741       -3.19    0.00142  
--------------------------------------------------------------------------

Table: Fitting generalized (binomial/logit) linear model: switch_public ~ raven_std + distance + hh_prnt_fathemp + hh_prnt_mothemp + hh_prnt_fathinhh + hh_prnt_mothinhh + hh_prnt_motheducyr + mar_expectedage + saf_good_friendsm + saf_good_friendsf + saf_walk_dark_com + loc_owndoing + loc_infl


-----------------------------------------------
           &nbsp;              2.5 %    97.5 % 
----------------------------- -------- --------
    **Raven Test Score**       -3.82    -0.912 

        **Distance**           0.0255   0.387  

     **Father Employed**      0.00578   0.0141 

     **Mother Employed**       -0.215   0.931  

   **Father living in HH**     -0.762   0.0373 

   **Mother living in HH**     -0.837   0.269  

 **Mother education (year)**   -0.103    1.37  

  **Girl E(Marriage Age)**    -0.0693   0.0661 

   **Male Friends (no.)**     -0.0271   0.0505 

  **Female Friends (no.)**     -0.204   0.0193 

 **Feel Safe in Community**   -0.00412  0.0744 

   **In control of life**      -0.66    0.606  

 **Influence surroundings**    -0.163   0.546  

        **Intercept**          -0.476   0.226  
-----------------------------------------------

When the outcome variable is whether a given girl has ever switched to a public school (i.e. the variable equals zero if the girl has never switched or she has switched to a private school), we see some correlations. More specifically, on average, girls who switched to a public school have higher standardized Raven test scores (i.e. higher cognitive ability), commute a further distance to school, are more likely to have a working mother and have their mother live in the same household. They are also report having more good female friends, perhaps a reflection of a more robust social network. Combined, these correlations paint an image of stable lives and well-developed girls who attend good quality schools. Needless to say, these may be the product of going to a good public school in the first place. 

--------------------------------------------------------------------------
           &nbsp;              Estimate   Std. Error   z value   Pr(>|z|) 
----------------------------- ---------- ------------ --------- ----------
    **Raven Test Score**        -0.258      0.0865      -2.98    0.00284  

        **Distance**           -0.00895     0.0024      -3.73    0.000191 

     **Father Employed**        -0.533      0.264       -2.02     0.0435  

     **Mother Employed**        0.181       0.203       0.893     0.372   

   **Father living in HH**      0.682       0.286       2.38      0.0172  

   **Mother living in HH**      -0.941      0.322       -2.92    0.00354  

 **Mother education (year)**   -0.0118      0.0334     -0.353     0.724   

  **Girl E(Marriage Age)**      0.0352      0.0191      1.85      0.065   

   **Male Friends (no.)**       0.0798      0.0563      1.42      0.156   

  **Female Friends (no.)**     -0.0489      0.0246      -1.99     0.047   

 **Feel Safe in Community**     0.0285      0.317      0.0899     0.928   

   **In control of life**       -0.238      0.176       -1.35     0.176   

 **Influence surroundings**     -0.188      0.173       -1.09     0.275   

        **Intercept**           -0.139      0.681      -0.203     0.839   
--------------------------------------------------------------------------

Table: Fitting generalized (binomial/logit) linear model: switch_private ~ raven_std + distance + hh_prnt_fathemp + hh_prnt_mothemp + hh_prnt_fathinhh + hh_prnt_mothinhh + hh_prnt_motheducyr + mar_expectedage + saf_good_friendsm + saf_good_friendsf + saf_walk_dark_com + loc_owndoing + loc_infl


------------------------------------------------
           &nbsp;              2.5 %    97.5 %  
----------------------------- -------- ---------
    **Raven Test Score**       -1.47      1.2   

        **Distance**           -0.428   -0.0886 

     **Father Employed**      -0.0136  -0.00425 

     **Mother Employed**       -1.05    -0.0156 

   **Father living in HH**     -0.216    0.578  

   **Mother living in HH**     0.121     1.24   

 **Mother education (year)**   -1.57    -0.309  

  **Girl E(Marriage Age)**    -0.0772   0.0536  

   **Male Friends (no.)**     -0.00219  0.0726  

  **Female Friends (no.)**    -0.0305    0.19   

 **Feel Safe in Community**   -0.0972  -0.000642

   **In control of life**      -0.592    0.649  

 **Influence surroundings**    -0.584    0.107  

        **Intercept**          -0.527    0.15   
------------------------------------------------

In contrast, when the outcome variable is a switch to a private school, the girls’ lives appear less stable. Not only do they have lower Raven Test scores, reflecting lower cognitive ability, and are less likely to report having good female friends, but also their mothers are less likely to be living in the same household and their fathers are both less likely to be employed and are less likely to live in the same household. Overall, this reflects an unstable family structure. 

#Conclusion: 
The results of this project may look scattered at a cursory glance but they paint a consistent and clear picture. In the critically underdeveloped slum of Kibera, young adolescent girls switch schools often. Those who switch to public schools tend to come from stable family structures, whereas those who switch to private schools seem to have less stable families. While there is little evidence to support a strategic switching hypothesis, wherein girls switch in preparation for the exam they sit at the end of the eighth grade, this paper suggests that those who switch to a public school enjoy ‘better-quality’ lives than non-switchers and switchers into private, mostly informal, primary schools. Since AGIK project will continue for four more years, gathering annual data on each girl, the new data structure could resolve some of the uncertainly that the current project is unable to address—-namely panel data will allow for introducing person-fixed effects, which account for time invariant characteristics unique to each girl, allowing us to better estimate a causal relationship between different factors and school switching. Without such a setup, it is too early to make a policy recommendation based on the evidence provided thus far, but it remains clear that understanding school switching is important to fully understanding the educational dynamics in the Kibera slum in Kenya.   

#References: 
Anbesu and B. Junge. Problems in Primary School Participation and Performance in Bahir Dar Awraja, Ministry of Education and UNICEF, Addis Ababa (1988). 

Colclough, Ch., Rose, P., & Tembon, M. (2000). Gender inequalities in primary schooling: The roles of poverty and adverse cultural practice. International Journal of Educational Development, 20, 5–27. 

Daily Nation. “Minister sets date for radical 8-4-4 reforms.” December 31 2015. Accessed April 24 2016. http://www.nation.co.ke/news/Minister-sets-date-for-radical-8-4-4-reforms/-/1056/3015518/-/15dg74j/-/index.html

Daily Nation. “Poor Education Pulls Down Kenya Ranking.” October 5 2015. Accessed April 28 2016. http://www.nation.co.ke/news/Poor-education-pulls-down-Kenya-ranking/-/1056/2899790/-/1018t6f/-/index.html

Glick, P., & Sahn, D. E. (2006). The demand for primary schooling in Madagascar: Price, quality, and the choice between public and private providers. Journal of Development Economics, 79, 118–145. 

Huisman, J., & Smits, J. (2009). Effects of household-and district-level factors on primary school enrollment in 30 developing countries. World development, 37(1), 179-193.

Kenyatta, Uhuru. “Speeches by his Excellency Honorary Uhuru Kenyatta.” The Presidencey—Official Website of the President. August 23 2015. Accessed May 1 2016. http://www.president.go.ke/ 

Lakin, Jason and John Kinuthia. “The Right Priorities? What Kenya’s National Government Spends Money On.” International Budget Partnership. May 2015. Accessed May 2016. http://www.internationalbudget.org/wp-content/uploads/What-Does-the-Kenyan-Government-Spend-Money-On.pdf

Oketch, M., & Somerset, A. (2010). Free Primary Education and After in Kenya: Enrolment impact, quality effects, and the transition to secondary school.