# Social-Emotion-Cause-Identification
This repo contains the dataset for Social Emotion Cause Identification (SECI) in paper：

Xiao, X., Mao, W., Sun, Y., & Zeng, D. (2023). A cognitive emotion model enhanced sequential method for social emotion cause identification. Information Processing & Management, 60(3), 103305.

The dataset comprises 1,500 Chinese online news documents for six common emotion types, joy, distress, gratitude, anger, admiration and reproach, with each emotion type containing 250 documents evenly.

# Example
This is a example document in SECI dataset: 
```
id	weibo_id	clause_id	emotion_id	is_cause	text

20	I87BItl27	1		2		0		北京时间9月22日，
20	I87BItl27	2		2		0		2019年国际排联女排世界杯第6轮在日本展开，
20	I87BItl27	3		2		1		中国女排鏖战五局以3-2力挫劲敌巴西，
20	I87BItl27	4		2		1		虽丢积分仍夺取六连胜。
20	I87BItl27	5		2		0		恭喜中国队的姑娘们！
20	I87BItl27	6		2		0		好样的！
```
The ```emotion_id``` represents the social emotion type of the document:
```
emotion_id	Social emotion type

1		distress
2		joy
3		anger
4		gratitude
5		reproach
6		admiration
