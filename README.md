# Soccer Analytics Resources

Collection of references, datasets and software libraries for soccer analytics.

## References

### Valuing On-the-Ball Actions

#### Valuing Actions by Estimating Probabilities (VAEP)
* [Actions Speak Louder Than Goals: Valuing Player Actions in Soccer (V1)](https://arxiv.org/pdf/1802.07127v1). **Tom Decroos, Lotte Bransen, Jan Van Haaren, Jesse Davis.** *arXiv.* Preprint paper. Appeared on 18 February 2018.
* [Actions Speak Louder Than Goals: Valuing Player Actions in Soccer (V2)](https://arxiv.org/pdf/1802.07127v2). **Tom Decroos, Lotte Bransen, Jan Van Haaren, Jesse Davis.** *International Conference on Knowledge Discovery & Data Mining.* Conference paper. Appeared on 25 July 2019.
* [Interpretable Prediction of Goals in Soccer](https://tomdecroos.github.io/reports/interpret_vaep.pdf). **Tom Decroos, Jesse Davis.** *StatsBomb Conference.* Conference paper. Appeared on 17 October 2019.
* [Valuing the Art of Pressing](https://lirias.kuleuven.be/retrieve/557306). **Pieter Robberechts.** *StatsBomb Conference.* Conference paper. Appeared on 17 October 2019.
* [Valuing On-the-Ball Actions in Soccer: A Critical Comparison of xT and VAEP](https://dtai.cs.kuleuven.be/sports/blog/valuing-on-the-ball-actions-in-soccer:-a-critical-comparison-of-xt-and-vaep). **Maaike Van Roy, Pieter Robberechts, Tom Decroos, Jesse Davis.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 18 December 2019.
* [Valuing On-the-Ball Actions in Soccer: A Critical Comparison of xT and VAEP](https://lirias.kuleuven.be/retrieve/558069). **Maaike Van Roy, Pieter Robberechts, Tom Decroos, Jesse Davis.** *Workshop on Artifical Intelligence in Team Sports.* Workshop paper. Appeared on 08 February 2020.
* [Exploring How VAEP Values Actions](https://dtai.cs.kuleuven.be/sports/blog/exploring-how-vaep-values-actions/). **Pieter Robberechts.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 27 April 2020.
* [Introducing Atomic-SPADL: A New Way to Represent Event Stream Data](https://dtai.cs.kuleuven.be/sports/blog/introducing-atomic-spadl:-a-new-way-to-represent-event-stream-data). **Tom Decroos, Pieter Robberechts, Jesse Davis.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 05 May 2020.
* [VAEP: An Objective Approach to Valuing On-the-Ball Actions in Soccer](https://lirias.kuleuven.be/retrieve/593249). **Tom Decroos, Lotte Bransen, Jan Van Haaren, Jesse Davis.** *International Joint Conference on Artificial Intelligence.* Conference abstract. Appeared on 07 January 2021.
* [Valuing Actions: Knowing When Your Model Doesn't Have a Clue](https://www.opengoalapp.com/quantifying-uncertainty). **Charles William.** *openGoal.* Blog post. Appeared on 22 February 2021.
* [Versatile Verification of Soccer Analytics Models](https://dtai.cs.kuleuven.be/sports/blog/versatile-verification-of-soccer-analytics-models). **Laurens Devos, Wannes Meert, Jesse Davis, Pieter Robberechts.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 14 July 2021.

#### Expected Threat (xT)
* [Introducing Expected Threat (xT)](https://karun.in/blog/expected-threat.html). **Karun Singh.** *Karun Singh.* Blog post. Appeared on 15 February 2019.
* [Valuing On-the-Ball Actions in Soccer: A Critical Comparison of xT and VAEP](https://dtai.cs.kuleuven.be/sports/blog/valuing-on-the-ball-actions-in-soccer:-a-critical-comparison-of-xt-and-vaep). **Maaike Van Roy, Pieter Robberechts, Tom Decroos, Jesse Davis.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 18 December 2019.
* [Valuing On-the-Ball Actions in Soccer: A Critical Comparison of xT and VAEP](https://lirias.kuleuven.be/retrieve/558069). **Maaike Van Roy, Pieter Robberechts, Tom Decroos, Jesse Davis.** *Workshop on Artifical Intelligence in Team Sports.* Workshop paper. Appeared on 08 February 2020.

#### Possession Value (PV)
* [Introducing a Possession Value Framework](https://www.statsperform.com/resource/introducing-a-possession-value-framework/). **Nils Mackay.** *Stats Perform.* Blog post. Appeared on 03 October 2019.
* [Evolving Our Possession Value Framework](https://www.statsperform.com/resource/evolving-our-possession-value-framework/). **Jonny Whitmore.** *Stats Perform.* Blog post. Appeared on 07 October 2020.

#### Goals Added (g+)
* [Goals Added: Introducing a New Way to Measure Soccer](https://www.americansocceranalysis.com/home/2020/4/22/37ucr0d5urxxtryn2cfhzormdziphq). **John Muller.** *American Soccer Analysis.* Blog post. Appeared on 04 May 2020.

#### Other
* [A Framework for Tactical Analysis and Individual Offensive Production Assessment in Soccer Using Markov Chains](http://nessis.org/nessis11/rudd.pdf). **Sarah Rudd.** *New England Symposium on Statistics in Sports.* Conference presentation. Appeared on 24 September 2011.
* [STARSS: A Spatio-Temporal Action Rating System for Soccer](https://lirias.kuleuven.be/retrieve/465691). **Tom Decroos, Jan Van Haaren, Vladimir Dzyuba, Jesse Davis.** *Workshop on Machine Learning and Data Mining for Sports Analytics.* Workshop paper. Appeared on 18 September 2017.
* [Attacking Contributions: Markov Models for Football](https://statsbomb.com/2019/02/attacking-contributions-markov-models-for-football/). **Derrick Yam.** *StatsBomb.* Blog post. Appeared on 21 February 2019.
* [Expected Potential (xPo)](https://thecomeonman.github.io/xPo/). **Aditya Kothari.** *The Come On Man.* Blog post. Appeared on 05 April 2020.
* [Our Thoughts on American Soccer Analysis' G+ Metric](https://dtai.cs.kuleuven.be/sports/blog/our-thoughts-on-american-soccer-analysis'-g+-metric). **Jesse Davis, Tom Decroos, Pieter Robberechts, Jan Van Haaren, Lotte Bransen.** *DTAI Sports Analytics Lab.* Blog post. Appeared on 15 May 2020.
* [Deep Soccer Analytics: Learning an Action-Value Function for Evaluating Soccer Players](https://link.springer.com/article/10.1007/s10618-020-00705-9). **Guiliang Liu, Yudong Luo, Oliver Schulte, Tarak Kharrat.** *Data Mining and Knowledge Discovery.* Journal paper. Appeared on 21 July 2020.

## Datasets
* [StatsBomb Open Data](https://github.com/statsbomb/open-data). Event dataset for men's and women's soccer.
* [Wyscout Match Event Dataset](https://figshare.com/collections/Soccer_match_event_dataset/4415000). Event dataset for men's soccer.
* [SkillCorner Open Data](https://github.com/SkillCorner/opendata). Broadcast tracking dataset for nine matches.
* [Metrica Sports Sample Data](https://github.com/metrica-sports/sample-data). Tracking and event dataset for two anonymized matches.

## Python Libraries
* [codeball](https://github.com/metrica-sports/codeball)
* [football-packing](https://github.com/samirak93/Football-packing)
* [kloppy](https://github.com/PySport/kloppy/)
* [matplotsoccer](https://github.com/TomDecroos/matplotsoccer)
* [mplsoccer](https://github.com/andrewRowlinson/mplsoccer)
* [soccer-xg](https://github.com/ML-KULeuven/soccer_xg)
* [socceraction](https://github.com/ML-KULeuven/socceraction)
* [soccerplots](https://github.com/Slothfulwave612/soccerplots)
* [statsbomb-parser](https://github.com/imrankhan17/statsbomb-parser)
* [statsbombapi](https://github.com/Torvaney/statsbombapi)
* [statsbombpy](https://github.com/statsbomb/statsbombpy)
* [tyrone_mings](https://github.com/FCrSTATS/tyrone_mings)

