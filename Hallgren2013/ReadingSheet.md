# Conducting Simulation Studies in the R Programming Environment - Reading Sheet

***
[Hallgren A. K. 2013. Conducting simulation studies in the R programming environment. Tutor Quant Methods Psychol. ; 9(2): 43–60.](https://doi.org/10.20982/tqmp.09.2.p043) 

***

Hallgren (2014) describes the benefits of using simulations and provides examples of applications.

1)	Please list all the words that you do not know/concepts you do not understand in this paper (except mediation, branching, zero-inflation, ceiling effect, structural equation models, social network exponential random graph).  
    *  
    *  
    *  

2) In your own words, describe which steps are common to all sorts of simulations. Illustrate with simple examples rather than, or in addition to, using terms such as assumptions and parameters.  

"Hmmm...I have a scientific question that is going to be answered by simulating a bunch of information!"
1) "First things first, I'm going to establish some groundwork and background context about how my simulated information is going to work!" 
2) "That sure was fun! With that background context in mind, I'm going to actually simulate that information. Wowee!"
3) "I'm going to start scienceing the heck out of this information! Analyses, maths, oh my! Mustn't forget to write down all the outputs of these analyses though."
4) "Phew, I'm pooped. But wait! There's more to do! I'm going to make another set of information and do the same thing all over again, maybe 999 more times! Soon I'll have a whole range of outputs - an empirical distribution of them, if you like."
5) "Look at this distribution of info! Now I'm going to tweak my groundwork and context so see what happens! Isn't life a thrill?"
6) "Lastly, I can science these distributions from my simulated information, to answer the question I had in the first place!"

3)	In your own words, describe the 3 types of applications for simulations covered by the author.  
Simulations can be used when answering a novel statistical question - in the case of Example 1, a mediation analysis involving the interactions between three intertwined variables, and the significance of their respective causal relationships.
Simulations can be used when estimating a model's statistical power - in the case of Example 2, estimating Example 1's statistical power by diagnosing how often a mediation test is significant (given a previously established selection of parameters and prior assumptions).
Finally, simulations can be used when bootstrapping to resolve the confidence intervals of a sampling distribution (without assuming that said distribution is normal) - in the case of Example 3, bootstrapping the intervals of an indirect effect for Example 1's variables.

4)	Describe, with your own words and/or examples, the 4 limitations to simulations mentioned by the author.  
It is often difficult for simulation studies to accommodate all the complexities of the real world within their parameters; residual errors are especially confounding in this regard. 
Real world population parameters are often difficult to diagnose and thus integrate into simulation studies.
Given that their input data are often extensive, simulation studies often require extensive computational time, which can be logistically difficult.
Using a simulation is often redundant, in that the questions they pose can be answered far more efficiently using established statistical methods.
