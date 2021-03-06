# Foreword

## Situation in Present Day

Following World War II, the Korean Peninsula was divided into a Northern and Southern half which eventually became the North and South Koreas we know today. The Korean war further drove a wedge between the two Koreas and the situation remains tense to the present day.

> The division of Korea between North and South Korea was the result of the Allied victory in World War II in 1945, ending the Empire of Japan's 35-year rule of Korea. The United States and the Soviet Union occupied the country, with the boundary between their zones of control along the 38th parallel. With the onset of the Cold War, negotiations between the United States and the Soviet Union failed to lead to an independent, unified Korea. In 1948, UN-supervised elections were held in the US-occupied south only. This led to the establishment of the Republic of Korea in South Korea, which was promptly followed by the establishment of the Democratic People's Republic of Korea in North Korea. The United States supported the South, and the Soviet Union supported the North, and each government claimed sovereignty over the whole Korean peninsula. The Korean War (1950–1953) left the two Koreas separated by the Korean Demilitarized Zone (DMZ) in the later part of the Cold War and beyond.

From Wikipedia, [the Division of Korea](https://en.wikipedia.org/wiki/Division_of_Korea)

## Korean War

> The Korean War (in South Korean Hangul: 한국전쟁; Hanja: 韓國戰爭; RR: Hanguk Jeonjaeng, "Korean War"; in North Korean Chosŏn'gŭl: 조국해방전쟁; Hancha: 祖國解放戰爭; MR: Choguk haebang chǒnjaeng, "Fatherland Liberation War"; 25 June 1950 – 27 July 1953) began when North Korea invaded South Korea. The United Nations, with the United States as the principal force, came to the aid of South Korea. China came to the aid of North Korea, and the Soviet Union gave some assistance.

From Wikipedia, [the Korean War](https://en.wikipedia.org/wiki/Korean_War)

## Potential for Escalation

![trump](http://i.imgur.com/Q1xzzj4.png "Trump North Korea")

Source: [The Australian](http://www.theaustralian.com.au/news/world/the-times/trump-tells-senator-he-is-prepared-to-go-to-war-over-north-korea/news-story/ef6283a4a11717820f1f9548ed43d5d9)

![northkorea](http://i.imgur.com/6chVdBJ.png "North Korea Missile Test")

Source: [CNN](http://edition.cnn.com/2017/07/31/asia/north-korea-missile-test-catchup/index.html)

# Aim

At the time of undertaking this project, the likelihood of a war between South Korea and North Korea seems to be escalating. With this in mind, we would like to investigate the historical trends in the media leading up to "similar" conflicts in history and compare this with the trends in the media today relating to a renewed South-North conflict in Korea.

# Methodology

We proceeded in the following manner:

1. Define Case Studies of "Similar Conflicts" to be investigated
2. Pick Media Variables to Investigate
3. Collect Data
4. Analyse Data with Python 

We limited our investigation to the defined case studies and historical english sources of news.

## Case Studies

### Vietnam War

| Start Date | 1 November 1955 |
| Data Collection Period | 1 November 1953 - 31 October 1955 |
| Beligerents | North Vietnam, South Vietnam, China, Soviet Union, United States of America |

![vietnamwar](http://jackietywls.weebly.com/uploads/1/7/2/7/17279018/7394841_orig.png "Vietnam War")

### Korean War

| Start Date | 25 June 1950 |
| Data Collection Period | 25 June 1948 - 24 June 1950 |
| Beligerents | China, United States of America (+ UN Allies), Soviet Union, South Korea, North Korea |

![koreanwar](https://kollathdesign.com/wp-content/uploads/2017/01/map_korean_war-800x389.png "Korean War")

## Media Variables Investigated

### Sentiment Analysis

We will make use of the TextBlob python library to provide sentiment analysis on the media sources we find.

> TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

From the pypi entry for [TextBlob](https://pypi.python.org/pypi/textblob)

From this we will retrieve numerical values for the positivity/negativity (polarity) and subjectivity/objectivity (subjectivity) of the news articles we find. TextBlob handles these values as follows:

> The polarity score is a float within the range \[-1.0, 1.0\]. The subjectivity is a float within the range \[0.0, 1.0\] where 0.0 is very objective and 1.0 is very subjective.

### Keyword Frequency

Trends were analysed for the following keywords:

UN, resolution, intervention, sanction, negotiation, escalation, warning, victim, damages, killed, violence, aggression, confrontation, rivalry, tension, fear, attack, terror, war, fight, forces, air, naval, troops, invasion, armed, conflict

## Dataset

Our dataset can be found here, the directory tree is laid out as follows:

```
	Dataset/
		CountryName/
			NewsItems
```

The data was collected from the [New York State Historical Newspapers archive](http://nyshistoricnewspapers.org/).

## Data Analysis

Correlation, Sequence Analysis

# Findings

Our findings were as follows:

# Interpretation

In Conclusion

# Contributors

- Robert Focke, B.Sc. Computer Engineering Student
- Jaehyuk Kim, B.A. Political and Social Sciences Student
