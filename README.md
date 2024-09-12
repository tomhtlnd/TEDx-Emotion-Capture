# Emotional expressions among TEDx speakers 


Vanessa Figini, Akanksha Chatterjee, Tom Heitland, Sahir Dhanani, Caleb Agoha


# Introduction

Emotional expression plays a pivotal role in effective communication (Nguyen et al., 2012), influencing how the audience perceives and understands a presentation. In the context of TEDx talks, a platform where speakers aim to inspire, educate, and engage the audience, the subtleties in a speaker’s emotional expressions become highly relevant. 

Emotional expressivity refers to the extent to which individuals express their emotions, including behavioural features such as facial expressions and verbal cues. Research indicates a gender disparity in emotional expressivity, with women generally exhibiting higher levels than men (Fiorentini, 2013). Additionally, studies have shown that attire significantly influences the subjective ratings of presentations and the perceived competence of the presenter [(Gurung et al., 2014)](https://www.zotero.org/google-docs/?NTLfSx). 

Given these insights, this report investigates the relationship between emotional expression, gender, and attire to explore these differences using systematic measurements derived from TEDx talk videos. By delving into these dynamics on a facial, verbal, and textual level, we aim to shed light on the potential differences and correlations, contributing to a deeper understanding of the multimodal nature of effective public speaking.


## Research Question: 

How do emotional expressions vary among TEDx speakers based on gender and attire?


# Hypotheses

H<sub>0 </sub>(null): There is no significant difference in emotional expression among TEDx speakers regardless of gender and attire.

**Formal and Informal**

H<sub>1 </sub>: TEDx speakers dressed informally will exhibit a greater intensity of facial action units than speakers dressed formally

H<sub>2</sub>: There is a difference in textual sentiment between formally and informally dressed speakers

**Male and female** 

H<sub>3 </sub>: Female speakers show more happy emotions than male speakers

H<sub>4 </sub>: There is a difference in the variation of vocal pitch between male and female speakers.


# Methodology

In order to adequately test our hypotheses within our limited time and computing budget, we compiled a total of eight YouTube Shorts videos from the TEDx channel. In order to make sure the emotional expression of speakers would not be greatly affected by the subject matter, all videos chosen followed the theme of personal development. With an average run time of about one minute, we gathered four videos each from male and female speakers, of which two were dressed formally and the other informally. The videos were then processed with Mexca (Lüken et al. 2024) to gather multimodal data. To ensure comparability, all eight videos were standardised to 50 seconds, and any missing values were excluded. Additionally, frames with a face probability lower than 0.9 were omitted from the analysis.


# Results


## **H<sub>1</sub>**: TEDx speakers dressed informally will exhibit a greater intensity of facial action units than speakers dressed formally

![alt_text](Facial%20Action%20Unit%20Graphs/formal%20vs%20informal%20over%20time.png)
_Fig 1: Mean activation of Action Units over time: Formal vs Informal_

Fig. 1 presents the aggregated mean activation of 27 action units (AU) over time, comparing speakers in formal and casual attire. The mean activation for formal speakers is 0.237, whereas informally dressed speakers had a slightly lower mean of 0.229. Despite the marginal difference, it's worth noting that formally dressed speakers exhibit a slightly higher activation.

![alt_text](Facial%20Action%20Unit%20Graphs/fomal%20vs%20informal%20bar.png)
_Fig 2: Mean activation of Action Units: Formal vs Informal_

Fig. 2 illustrates the average activation of each unit including confidence intervals. In alignment with the previously discussed outcomes, no substantial difference was found, given that the confidence intervals overlap. One notable observation is a high activation of AU 25, corresponding to a parting movement of the lips. This aligns with the speaking patterns and can be attributed to an expressive communication style.

In summary, no difference in the intensity of action units was found. Consequently, the H<sub>1</sub> can be rejected.


## H<sub>2</sub>: There is a difference in textual sentiment between formally and informally dressed speakers

![alt_text](Sentiment%20Analysis%20Graphs/formal%20vs%20informal%20compound%20sentiment.png)
_Fig 3: Sentiment comparison: Formal vs Informal_

This figure presents the average compound sentiment score for both formal and informal speakers. The mean line for both groups is approximately 0.01, indicating a very marginal difference between the two. Consequently, we can confidently reject H<sub>2</sub>.


## H<sub>3</sub>: Female speakers show more happy emotions than male speakers

Based on the facial action unit system theory (Ekman & Friesen, 2003), we focused on AU 6 and AU 12 for the happiness comparison. To assess Mexca's ability to detect happy emotions, we examined the activation of these action units in one of the videos. The screenshot below displays a female speaker with a joyful expression, evident in the peak activations on the graph at second five. To account for varying baselines, the activation values of the two action units were standardised using the min-max normalisation method.

![alt_text](Facial%20Action%20Unit%20Graphs/female%20formal%202%20happiness.png)
_Fig 4: Mean activation of Action Units over time: [Female Formal 2](https://youtube.com/shorts/3FIR2pkfhI8?si=gOSA-pxw2FN8OV5K)_

Subsequently, we identified peaks in the activation of both action units surpassing a threshold of 0.8. In this specific video, six instances of happiness expressions were detected using this method.

![alt_text](Facial%20Action%20Unit%20Graphs/female%20vs%20male%20peaks.png)

_Fig 5: Happiness comparison: Male vs Female_

A comparison of all videos revealed a significant difference between female and male speakers: Female speakers show more joyful expressions during their speeches. Based on these results, H3 can be accepted.

![alt_text](Sentiment%20Analysis%20Graphs/male%20vs%20female%20compound%20sentiment.png)
_Fig 6: Sentiment comparison: Male vs Female_

This is further illustrated through the sentiment scores for male and female speakers. Overall, female speakers show a smaller number of high peaks (positive sentiment scores) than male speakers; however female mean compound sentiment is higher than male’s because it has fewer negative peaks (negative sentiment scores). This suggests that female speakers generally show happier emotions due to relatively limited fluctuations, whereas male speakers use a wider range of positive and negative sentiments. 


## H<sub>4 </sub>: There is a difference in the variation of vocal pitch between male and female speakers

Vocal pitch was higher for female speakers than male.

![alt_text](Vocal%20Pitch%20Analysis%20Graphs/male%20vs%20female%20pitch.png)

_Fig 7: Vocal pitch comparison: Male vs Female_

Vocal pitch did not vary significantly between female and male speakers with formal attire. However, there was a significant difference in pitch between female and male speakers with informal attire.

![alt_text](Vocal%20Pitch%20Analysis%20Graphs/formal%20vs%20informal.png)
_Fig 8: Vocal pitch comparison: Formal vs Informal_

Male speakers who wore formal attire exhibited higher vocal pitch than their informal counterparts, while the difference was the opposite for female speakers. However, neither difference is significant.

![alt_text](Vocal%20Pitch%20Analysis%20Graphs/cross%20comparison.png)
_Fig 9: Vocal pitch comparison: Cross comparison_

Speech data were also divided into segments, with the separator of five consecutive frames without pitch data. The aim of this was to represent each sentence or phrase as a segment, so that “uptalk” and “downtalk” could be measured (eg. whether the sentence finished with a higher or lower pitch than it started).

![alt_text](Vocal%20Pitch%20Analysis%20Graphs/start%20vs%20ending.png)
_Fig 10: Start vs Ending pitch difference_

While formally dressed speakers seem to exhibit “downtalk” more often (pitch ending lower than it starts, so a positive pitch difference), there is no statistically significant finding, mostly due to the low sample size.

With these results, we can reject H<sub>4</sub> - while there were differences in vocal pitch between male and female speakers, there was no significant difference in the _variation _of their vocal pitch


# Conclusion

The findings suggest that there are gender-based differences in emotional expressions, with female speakers generally displaying more joyful expressions than male. This is supported by the facial action unit analysis and a textual sentiment comparison and aligns well with existing research in this field. 

Surprisingly, the choice of attire did not show significant effects on facial expressions or textual sentiment. Despite existing literature emphasising the impact of attire on perceived capability, our analysis could not find indicators of this being reflected in emotional expressions, vocal emphasis, or sentiment. Thus, while formal attire may enhance perceived capability, it does not translate into actual differences in presentation styles and use of emotional expressions. This implies that factors beyond attire, such as cognitive biases linking formal clothing with competence and authority, as well as cultural norms and symbols of professionalism, play a pivotal role in shaping the perception of capability.

Further, attire is a rather temporary and superficial part of a person’s identity, while emotional expressions and behaviour are more closely tied to intrinsic personality traits. In this regard, the observed gender difference underscores the significance of gender as a key category in shaping people's social identity and influencing the use of emotions and presentation styles.


# Limitations

While writing the report, even though we were able to find interesting insights, we were limited due to the short research duration. Due to the long period of time to run MEXCA pipeline on the videos, we could only use eight videos in total. A longer period of time would have allowed us to explore a bigger sample and generate findings that, potentially, could be generalised more widely. Furthermore, it was difficult to use MEXCA on VS Code and JupyterLab, which meant we could only work with Google Colab. 

During the facial expression analysis of the TEDx videos, we encountered certain limitations of Mexca. The software faced challenges with changing camera angles, leading to instances where it registered high activation of various action units even when no face was present in the frame. Although we addressed this issue by implementing a face probability threshold of 0.9, we could not verify all instances. Additionally, we observed variations in baseline values for the action units, creating inconsistencies in unit activation. To address this, we standardised the values.


# Bibliography

Ekman, P., & Friesen, W. V. (2003). Unmasking the Face: A Guide to Recognizing Emotions from Facial Clues. ISHK.

Fiorentini, C. (2013). Gender and emotion expression, experience, physiology and well being: A psychological perspective. Gender and emotion. An interdisciplinary perspective, 15-42.

Gurung, R. A. R., Kempen, L., Klemm, K., Senn, R., & Wysocki, R. (2014). Dressed to Present: Ratings of Classroom Presentations Vary With Attire. Teaching of Psychology, 41(4), 349–353. https://doi.org/10.1177/0098628314549710]

Lüken, M., Moodley, K., Viviani, E., Pipal, C., & Schumacher, G. (2024, January 18). MEXCA - A simple and robust pipeline for capturing emotion expressions in faces, vocalization, and speech. PsyArXiv. [https://doi.org/10.31234/osf.io/56svb](https://doi.org/10.31234/osf.io/56svb)

How to make a perfect apology #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/GuKVarb9qAY](https://www.youtube.com/shorts/GuKVarb9qAY)

How to plan for the long term #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/pRlsfwxyuHQ](https://www.youtube.com/shorts/pRlsfwxyuHQ)

Layoffs? You’re more than your job #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/pAg5DjUt_qQ](https://www.youtube.com/shorts/pAg5DjUt_qQ)

Nguyen, A., -T. Chen, W., [&](https://www.zotero.org/google-docs/?cKRgku) Rauterberg, M. (2012) Online feedback system for public speakers. IEEE Symposium on E-Learning, E-Management and E-Services, Kuala Lumpur, Malaysia, 2012, pp. 1-5, doi: 10.1109/IS3e.2012.6414963.

Stop looking for your passion #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/3FIR2pkfhI8](https://www.youtube.com/shorts/3FIR2pkfhI8)

Stop trying to change yourself #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/uWoa-gsGtaw](https://www.youtube.com/shorts/uWoa-gsGtaw)

Teach Girls Bravery, Not Perfection. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/zXRjpcRc6Rs](https://www.youtube.com/shorts/zXRjpcRc6Rs)

What Makes You Special? @TED #shorts #tedxtalk. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/yFlC6pV9_ok](https://www.youtube.com/shorts/yFlC6pV9_ok)

What you can do to make your social posts accessible #shorts #tedx. (n.d.). Retrieved 23 February 2024, from[ https://www.youtube.com/shorts/yW82PWxaKWg](https://www.youtube.com/shorts/yW82PWxaKWg)
