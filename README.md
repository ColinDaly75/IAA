# IAA for Enterprise Search
Inter-Annotator Agreement (IAA) in Enterprise Search
In this notebook, I calculate the following Agreement coefficients

    Percentage Agreement
    Cohen's Kappa (three variants)
    Krippendorff's Alpha (thee variants)

The dataset used to test the quality of the annotations includes 565 judgements for QD pairs, using two independent expert annotators (judges from within the organisation). The columns are presented with a Likert-scale as follows:-
![fig-proforma](https://github.com/ColinDaly75/IAA/assets/51714656/e8d14914-fc20-4ca8-9a94-59586e2f272c)



When building the ENTRP-SRCH dataset, a large portion of annotated documents were
judged by a single rater for a given query. For the 20 query topics in the dataset, the 2544
documents were rated by just 15 raters in total. To verify that this approach was valid,
an experiment was conducted to test the agreement between two independent raters. The
experiment was designed to answer the question whether the annotations in the ENTRP-
SRCH dataset are reliable, given that a large portion of the QD pairs were judged by a single
rater for a given query.

Regardless of how we interpret the spacing of measurement levels, the calculated ordinal and
interval α scores (0.703 and 0.730 respectively) are both greater than Krippendorff’s mini-
mum requirement of 0.67, above which ‘tentative conclusions’ can be drawn [86]. Similarly,
the ordinal and interval κ scores (0.626 and 0.707 respectively) both fit the interpretation of
‘substantial agreement’ [85]. In conclusion, this IAA experiment shows that the single rater
approach did not adversely impact the integrity of the ENTRP-SRCH datase
