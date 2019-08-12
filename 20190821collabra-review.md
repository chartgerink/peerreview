# General comments and summary of recommendation

Describe your overall impressions and your recommendation, including changes or revisions. Please note that you should pay attention to scientific, methodological, and ethical soundness only, not novelty, topicality, or scope. A checklist of things to you may want to consider is below:
 - Are the methodologies used appropriate?
 - Are any methodological weaknesses addressed?
 - Is all statistical analysis sound?
 - Does the conclusion (if present) reflect the argument, is it supported by data/facts?
 - Is the article logically structured, succinct, and does the argument flow coherently?
 - Are the references adequate and appropriate? *

The manuscript presents two cross-sectional studies on parameter specification for normally distributed priors and how these may be affected by sex, status, and researcher confidence of the respondent. The manuscript proposes a new measurement of researcher confidence and finds ultimately finds that sex affects prior specification, which may be mediated by researcher confidence. 

Let me preface my review by stating that I am confident in the study design itself. None of my comments invalidate the study design and simply seek to improve the study analyses or sharpen its discussion.

One of my main points for improvement is the use of gender throughout the text. The text uses the social construct gender (e.g., woman) and the biological construct sex (e.g., female) interchangeably. That these constructs are not equivalent is an important distinction, but absent in the manuscript. I would recommend to specify the paper towards sex, because it is what is in the data. I made some suggestions in the attached document for wording sentences to be more inclusive and less instrumental for people who are not included in the analyses (e.g., "could not be used in the test of our key hypothesis"). For a bit more elaboration see for example https://doi.org/10.1161/CIRCOUTCOMES.116.002660 second paragraph.

With respect to the researcher confidence scale, I feel like there is a lot of information that remains absent to properly understand and have confidence in this measure that is central to the results. As the authors state, it is an unvalidated scale, hence, I think that the results would be more convincing if the authors make a case for and how this scale is valid. The authors indicate this is part of a separate manuscript, which in itself is a good thing. However, it seems like a scale validation and factor score calculation should occur prior to using the scores in an analysis. I dove into the OSF files and found out several things that I think require addressing in the manuscript (and now are merely alluded to). 

The dimensionality of the researcher confidence scale is now not examined and simply assumed. Although implicitly examined when the model fit is inspected, no comments are made that a bad fit (RMSEA >.08) is an indication of too few factors in the model. The authors also seem to minimize this into "not a great fit" and "mediocre fit."

Subsequently, the sum score (average is an equivalent structure) is used without further justification. This is a highly restrictive model. All reliability measures also rely on this assumption and require a justification. I looked at the code and results file (thank you for sharing) and saw that there is some variation on the loadings. Given the nature of the questions, I think it makes sense that not all questions provide equivalent indicators for RC. If the authors do not want to do more in-deep analysis in this paper, which I would recommend nonetheless for more valid measurement of the tested construct, I would at least expect a discussion throughout the paper on these issues. It may also invalidate the findings with respect to the effects of researcher confidence if the measurement is not well constructed. This preprint might be interesting for the authors regarding sum-scores as factor scores  https://doi.org/10.31234/osf.io/3wy47

Another of my main points for improvement is the discussion about priors. More specifically, the manuscript currently does not explain that the parameters studied currently are for a subset of priors. For example, nothing is said about how this study is restricted to the specification for a normally distributed prior, but that there are an array of other priors (e.g., beta, gamma, etc). How might these results (not) extrapolate, or what are other considerations? I would be happy to see some more discussion about this.

I would be keen to see a stronger contextualization of how this sex difference in prior specification (overconfidence in males?) affects how the "game of psychological science" is played (doi.org/10.1177/1745691612459060). It seems like there is a worthwhile discussion there to be had to indicate how sex differences might arise when the system is set up to prefer significant results in publications, which are easier to find by questionably investigating small sample studies, which are more likely to occur if you're overestimating the effect to begin with (e.g., in power analyses). In other words, what are possible second- or third-order effects of the results presented here? That might be a fruitful exercise for further research.

I would like to note that when trying to reproduce the RMarkdown file (+100 to the authors for doing this) the `printMainPathModel()` calls around line 536 give errors. As a result, I was unable to reproduce the results this manuscript presents. 

Other points:

+ Of interest to paragraph 3 ("Incorporating individual ...") may be Silberzahn et al 2018 (https://doi.org/10.1177/2515245917747646), which indicates that variation also occurs outside of Bayesian analysis.
+ The URLs referred to are tinyurl.com. I hope these will be replaced with the public OSF links instead of referring to a viewonly specific link? Otherwise high risk of link rot.
+ The manuscript repeatedly mentions "did not reach significance", which I'd recommend to replace with simply stating "was nonsignificant"
+ Scale reliability measure is undefined and only the sign alpha is given, please explicate the measure used.
+ Table 4 does not explain why the path a row is merged
+ Path d is not defined in the text or Tables
+ p = .000 should be replaced with p < .0001 or similar (e.g., Table S7)
+ there is no discussion about correcting for multiple testing. Please correct for this and how it affects the results (this was not discussed in the preregistration)
+ Plus points for preregistration and sticking to it! :)

# Figures/tables/data availability:
Please comment on the author’s use of tables, charts, figures, ifrelevant. Please acknowledge that adequate underlying data is available to ensure reproducibility (see open data policies per discipline of Collabra here). *

+ Figure 4 is not referenced in the text
+ Table S6 is not referenced in the main text
+ All data and code are available to attempt reproducibility (see review)


# Ethical approval:
If humans or animals have been used as research subjects, and/or tissue or field sampling, are the necessary statements of ethical approval by a relevant authority present? Where humans have participated in research, informed consent should also be declared.
If not, please detail where you think a further ethics approval/statement/follow-up is required. *

No a priori ethics approval is included. 

After a bit of digging in the OSF page I could find the consent form through the following link, and I'd recommend to include it in the OSF page for findability. Consent was part of the survey process.
http://stagingup.cinecoup.com/2015/dr_cat/inf-stg-0025c6dc4d2c45209.07979963.pdf

# Language:
Is the text well written and jargon free? Please comment on the quality of English and any need for improvement beyond the scope of this process. *

The text is well written, could benefit from a bit of revising of statistical language (e.g., "failed to reach significance", "nearing significance")
