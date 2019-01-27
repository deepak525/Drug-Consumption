# Drug-Consumption
Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity. All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers. For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day.
Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".

### Problem which can be solved:
- Seven class classifications for each drug separately.
- Problem can be transformed to binary classification by union of part of classes into one new class. For example, "Never Used", "Used over a Decade Ago" form class "Non-user" and all other classes form class "User".
- The best binarization of classes for each attribute.
- Evaluation of risk to be drug consumer for each drug.

#### References
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

### Data Set Information:

> Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity.<br><br>
> All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers.   <br><br>
> For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day.
Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".


### Attribute Information:
<p align="center">
    <right>
    
> 1. **ID:** ID is number of record in original database. Cannot be related to participant. It can be used for reference only.
> 2. **Age:** Age is the age of participant and has one of the values: 

|   Value  |    Meaning   |  Cases  |  Fraction  |
|----------|--------------|---------|------------|
| -0.95197 |    18 - 24   |   643   |   34.11%   |
| -0.07854 |    25 - 34   |   481   |   25.52%   |
|  0.49788 |    35 - 44   |   356   |   18.89%   |
|  1.09449 |    45 - 54   |   294   |   15.60%   |
|  1.82213 |    55 - 64   |   93    |    4.93%   |
|  2.59171 |    65+       |   18    |    0.95%   |

> 3.**Gender:** Gender is gender of participant:

|   Value  |    Meaning   |  Cases  |  Fraction  |
|----------|--------------|---------|------------|
|  0.48246 |    Female    |   942   |   49.97%   |
| -0.48246 |    Male      |   943   |   50.03%   |

> 4. **Education:**  Education is level of education of participant and has one of the values: 

|   Value  |                  Meaning              |  Cases  |  Fraction  |
|----------|:-------------------------------------:|:---------|------------|
| -2.43591 |      Left School Before 16 years      |   28    |    1.49%   |
| -1.73790 |      Left School at 16 years          |   99    |    5.25%   |
| -1.43719 |      Left School at 17 years          |   30    |    1.59%   |
| -1.22751 |      Left School at 18 years          |   100   |    5.31%   |
| -0.61113 | Some College,No Certificate Or Degree |   506   |   26.84%   |
| -0.05921 |    Professional Certificate/ Diploma  |   270   |   14.32%   |
|  0.45468 |            University Degree          |   480   |   25.46%   |
|  1.16365 |              Masters Degree           |   283   |   15.01%   |
|  1.98437 |             Doctorate Degree          |   89    |    4.72%   |

> 5. **Country:** Country is country of current residence of participant and has one of the values:

|   Value  |         Meaning         |  Cases  |  Fraction  |
|----------|-------------------------|---------|------------|
| -0.09765 |         Australia       |   54    |   2.86%    |
|  0.24923 |          Canada         |   87    |   4.62%    |
| -0.46841 |        New Zealand      |    5    |   0.27%    | 
| -0.28519 |          Other          |  118    |   6.26%    | 
|  0.21128 |   Republic of Ireland   |   20    |   1.06%    |
|  0.96082 |            UK           |  1044   |   55.38%   | 
| -0.57009 |           USA           |   557   |   29.55%   |

> 6.**Ethnicity:** Ethnicity is ethnicity of participant and has one of the values: 

|   Value  |         Meaning         |  Cases  |  Fraction  |
|----------|-------------------------|---------|------------|
| -0.50212 |        Asian            |    26   |   1.38%    |
| -1.10702 |        Black            |    33   |   1.75%    |
|  1.90725 |    Mixed-Black/Asian    |     3   |   0.16%    | 
|  0.12600 |    Mixed-White/Asian    |    20   |   1.06%    |
| -0.22166 |    Mixed-White/Black    |    20   |   1.06%    |
|  0.11440 |         Other           |    63   |   3.34%    |
| -0.31685 |         White           |  1720   |  91.25%    |

> 7. **Nscore:** Nscore is NEO-FFI-R Neuroticism. Neuroticism is one of the Big Five higher-order personality traits in the study of psychology. Individuals who score high on neuroticism are more likely than average to be moody and to experience such feelings as anxiety, worry, fear, anger, frustration, envy, jealousy, guilt, depressed mood, and loneliness. Possible values are presented in table below:   

|Nscore|  Value | Nscore|  Value | Nscore|  Value | Nscore|  Value | 
|------|--------|-------|--------|-------|--------|-------|--------|
|  12  |-3.46436|  24   |-1.32828|  36   |0.04257 |  48   |1.23461 |
|  13  |-3.15735|  25   |-1.19430|  37   |0.13606 |  49   |1.37297 | 
|  14  |-2.75696|  26   |-1.05308|  38   |0.22393 |  50   |1.49158 |
|  15  |-2.52197|  27   |-0.92104|  39   |0.31287 |  51   |1.60383 | 
|  16  |-2.42317|  28   |-0.79151|  40   |0.41667 |  52   |1.72012 |
|  17  |-2.34360|  29   |-0.67825|  41   |0.52135 |  53   |1.83990 |
|  18  |-2.21844|  30   |-0.58016|  42   |0.62967 |  54   |1.98437 |
|  19  |-2.05048|  31   |-0.46725|  43   |0.73545 |  55   |2.12700 |
|  20  |-1.86962|  32   |-0.34799|  44   |0.82562 |  56   |2.28554 |
|  21  |-1.69163|  33   |-0.24649|  45   |0.91093 |  57   |2.46262 |
|  22  |-1.55078|  34   |-0.14882|  46   |1.02119 |  58   |2.61139 |
|  23  |-1.43907|  35   |-0.05188|  47   |1.13281 |  59   |2.82196 |
|   -  |    -   |   -   |    -   |   -   |    -   |  60   |3.27393 |

> 8. **EScore:** Escore (Real) is NEO-FFI-R Extraversion. Extraversion is one of the five personality traits of the Big Five personality theory. It indicates how outgoing and social a person is. A person who scores high in extraversion on a personality test is the life of the party. They enjoy being with people, participating in social gatherings, and are full of energy. Possible values are presented in table below: 

|Escore|  Value | Escore|  Value | Escore|  Value | Escore|  Value | 
|------|--------|-------|--------|-------|--------|-------|--------|
|  16  |-3.27393|   27  |-1.76250|   38  |-0.30033|   49  | 1.45421| 
|  17  |-3.00537|   28  |-1.63340|   39  |-0.15487|   50  | 1.58487| 
|  18  |-3.00537|   29  |-1.50796|   40  | 0.00332|   51  | 1.74091| 
|  19  |-2.72827|   30  |-1.37639|   41  | 0.16767|   52  | 1.93886| 
|  20  |-2.53830|   31  |-1.23177|   42  | 0.32197|   53  | 2.12700|  
|  21  |-2.44904|   32  |-1.09207|   43  | 0.47617|   54  | 2.32338|  
|  22  |-2.32338|   33  |-0.94779|   44  | 0.63779|   55  | 2.57309|  
|  23  |-2.21069|   34  |-0.80615|   45  | 0.80523|   56  | 2.85950|  
|  24  |-2.11437|   35  |-0.69509|   46  | 0.96248|   57  | 2.85950| 
|  25  |-2.03972|   36  |-0.57545|   47  | 1.11406|   58  | 3.00537| 
|  26  |-1.92173|   37  |-0.43999|   48  | 1.28610|   59  | 3.27393|


> 9. **Oscore:** Oscore (Real) is NEO-FFI-R Openness to experience. Openness is one of the five personality traits of the Big Five personality theory. It indicates how open-minded a person is. A person with a high level of openness to experience in a personality test enjoys trying new things. They are imaginative, curious, and open-minded. Individuals who are low in openness to experience would rather not try new things. They are close-minded, literal and enjoy having a routine. Possible values are presented in table below:

|Oscore|  Value | Oscore|  Value | Oscore|  Value | 
|------|--------|-------|--------|-------|--------|
|  24  |-3.27393|   38  |-1.11902|   50  | 0.58331| 
|  26  |-2.85950|   39  |-0.97631|   51  | 0.72330|
|  28  |-2.63199|   40  |-0.84732|   52  | 0.88309| 
|  29  |-2.39883|   41  |-0.71727|   53  | 1.06238| 
|  30  |-2.21069|   42  |-0.58331|   54  | 1.24033| 
|  31  |-2.09015|   43  |-0.45174|   55  | 1.43533| 
|  32  |-1.97495|   44  |-0.31776|   56  | 1.65653| 
|  33  |-1.82919|   45  |-0.17779|   57  | 1.88511| 
|  34  |-1.68062|   46  |-0.01928|   58  | 1.15324| 
|  35  |-1.55521|   47  | 0.14143|   59  | 2.44904| 
|  36  |-1.42424|   48  | 0.29338|   60  | 2.90161| 
|  37  |-1.27553|   49  | 0.44585|  NaN  |  NaN   | 

> 10. **Ascore:**  Ascore(Real) is NEO-FFI-R Agreeableness. Agreeableness is one of the five personality traits of the Big Five personality theory. A person with a high level of agreeableness in a personality test is usually warm, friendly, and tactful. They generally have an optimistic view of human nature and get along well with others. Possible values are presented in table below: 

|Ascore|  Value | Ascore|  Value | Ascore|  Value | 
|------|--------|-------|--------|-------|--------|
|  12  |-3.46436|   34  |-1.34289|   48  | 0.76096| 
|  16  |-3.15735|   35  |-1.21213|   49  | 0.94156| 
|  18  |-3.00537|   36  |-1.07533|   50  | 1.11406| 
|  23  |-2.90161|   37  |-0.91699|   51  | 1.2861 |
|  24  |-2.78793|   38  |-0.76096|   52  | 1.45039| 
|  25  |-2.70172|   39  |-0.60633|   53  | 1.61108| 
|  26  |-2.53830|   40  |-0.45321|   54  | 1.81866| 
|  27  |-2.35413|   41  |-0.30172|   55  | 2.03972| 
|  28  |-2.21844|   42  |-0.15487|   56  | 2.23427| 
|  29  |-2.07848|   43  |-0.01729|   57  | 2.46262| 
|  30  |-1.92595|   44  | 0.13136|   58  | 2.75696| 
|  31  |-1.77200|   45  | 0.28783|   59  | 3.15735| 
|  32  |-1.62090|   46  | 0.43852|   60  | 3.46436| 
|  33  |-1.47955|   47  | 0.59042|  NaN  |  NaN   |

> 11. **Cscore:** Cscore (Real) is NEO-FFI-R Conscientiousness. Conscientiousness is one of the five personality traits of the Big Five personality theory. A person scoring high in conscientiousness usually has a high level of self-discipline. These individuals prefer to follow a plan, rather than act spontaneously. Their methodic planning and perseverance usually makes them highly successful in their chosen occupation. Possible values are presented in table below: 

|Cscore|  Value | Cscore|  Value | Cscore|  Value | 
|------|--------|-------|--------|-------|--------|
|  17  |-3.46436|   32  |-1.25773|   46  | 0.58489| 
|  19  |-3.15735|   33  |-1.13788|   47  | 0.7583 |
|  20  |-2.90161|   34  |-1.01450|   48  | 0.93949| 
|  21  |-2.72827|   35  |-0.89891|   49  | 1.13407| 
|  22  |-2.57309|   36  |-0.78155|   50  | 1.30612| 
|  23  |-2.42317|   37  |-0.65253|   51  | 1.46191| 
|  24  |-2.30408|   38  |-0.52745|   52  | 1.63088| 
|  25  |-2.18109|   39  |-0.40581|   53  | 1.81175| 
|  26  |-2.04506|   40  |-0.27607|   54  | 2.04506| 
|  27  |-1.92173|   41  |-0.14277|   55  | 2.33337| 
|  28  |-1.78169|   42  |-0.00665|   56  | 2.63199|
|  29  |-1.64101|   43  | 0.12331|   57  | 3.00537| 
|  30  |-1.51840|   44  | 0.25953|   59  | 3.46436| 
|  31  |-1.38502|   45  | 0.41594|  NaN  |  NaN   |

> 12. **Impulsive:** Impulsive (Real) is impulsiveness measured by BIS-11. In psychology, impulsivity (or impulsiveness) is a tendency to act on a whim, displaying behavior characterized by little or no forethought, reflection, or consideration of the consequences. If you describe someone as impulsive, you mean that they do things suddenly without thinking about them carefully first. Possible values are presented in table below: 

|Impulsiveness| Cases |  Fraction  | 
|-------------|-------|------------|
|   -2.55524  |   20  |    1.06%   |
|   -1.37983  |  276  |   14.64%   | 
|   -0.71126  |  307  |   16.29%   | 
|   -0.21712  |  355  |   18.83%   | 
|    0.19268  |  257  |   13.63%   | 
|    0.52975  |  216  |   11.46%   | 
|    0.88113  |  195  |   10.34%   | 
|    1.29221  |  148  |    7.85%   | 
|    1.86203  |  104  |    5.52%   | 
|    2.90161  |    7  |    0.37%   | 

> 13. **Sensation:** SS(Real) is sensation seeing measured by ImpSS. Sensation is input about the physical world obtained by our sensory receptors, and perception is the process by which the brain selects, organizes, and interprets these sensations. In other words, senses are the physiological basis of perception. Possible values are presented in table below: 

|      SS     | Cases |  Fraction  | 
|-------------|-------|------------|
|   -2.07848  |   71  |    3.77%   |
|   -1.54858  |   87  |    4.62%   |
|   -1.18084  |  132  |    7.00%   | 
|   -0.84637  |  169  |    8.97%   | 
|   -0.52593  |  211  |   11.19%   | 
|   -0.21575  |  223  |   11.83%   | 
|    0.07987  |  219  |   11.62%   | 
|    0.40148  |  249  |   13.21%   | 
|    0.76540  |  211  |   11.19%   | 
|    1.22470  |  210  |   11.14%   | 
|    1.92173  |  103  |    5.46%   |



> The remaining columns are divided inti 7 classes:

|  Value  |    Description   |
|---------|-------------------------|
|   CL0   |       Never Used        |
|   CL1   |  Used over a Decade Ago |
|   CL2   |    Used in Last Decade  |
|   CL3   |     Used in Last Year   | 
|   CL4   |     Used in Last Month  | 
|   CL5   |     Used in Last Week   | 
|   CL6   |     Used in Last Day    |




</p>
