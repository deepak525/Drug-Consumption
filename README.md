# Drug-Consumption
Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity. All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers. For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day.
Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".

### Problem which can be solved:
- Seven class classifications for each drug separately.
- Problem can be transformed to binary classification by union of part of classes into one new class. For example, "Never Used", "Used over a Decade Ago" form class "Non-user" and all other classes form class "User".
- The best binarization of classes for each attribute.
- Evaluation of risk to be drug consumer for each drug.

References
1. Drug, Wikipedia
URL: https://en.wikipedia.org/wiki/Drug
2. The Five Factor Model of personality Model of Personality and Evaluation of Drug
Consumption risk, E.Fehrman, A.K. Muhammad, E.M. Mirkes, V. Egan, A.N Gorban.
URL: https://arxiv.org/abs/1506.06297
3. Detecting and Assessing Alcohol and Other Drug Use.
URL: https://www.ncbi.nlm.nih.gov/books/NBK236259/
4. Ibid.
5. UCI-Machine Learning Repository
URL: archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29
6. Numpy Documentation
7. Matplotlib Documentation
8. Seaborn Documentation
9. Pandas Documentation.
