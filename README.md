# DataBiasAssignment
Data Assignment 2 for I 310D

Using the Perspective API, I was able to observe and understand a variety of biases depending on the categories or topics mentioned or discussed. After looking through the data available, I chose to analyze the toxicity scores and the differences based on gender-distinct vocabulary. I sought to compare the toxicity scores for comments on men as opposed to comments on women, but further evaluating how other gender specific vocabularly, like "female" and "male" or "girl" and "boy" may change the score. 


I began by evaluating the same phrase but changing the gender-distinct word. Then, I used different words from each gender category to see if certain words resulted in a higher toxicity score. The results were definitely a little surprising. Through this analysis, I found that words associated with being female resulted in a higher toxicity score than words associated with being male. Furthermore, certain words that are female-distinct resulted in higher toxicity scores. For example, the phrase "women are stupid" had a higher toxicity score than "girls are stupid".

These results introduced an interesting discrepancy in the Perspective API and the database. When the phrases compared were the exact same expect for the gender-distinct word, the female-distinct words, when used in the phrase, alwasy resulted in a higher score. This means that the algorithm is registering the female-distinct words as more toxic or negative in general. As if it is making the assumption that the use of female-distinct words will automatically have a more toxic context or meaning. Does the algorithm find that female-distinct vocabulary is more toxic than male-distinct vocabulary? Furthermore, does the context of the phrase influence this discrepency?

To test this, I evaluated generally positive phrases with different gender-distinct vocabulary. When comparing "men are nice" with "women are nice", the phrase using female-specific vocabulary still produced a higher toxicity score. This finding helped me to explore the notion that the context and phrasing around the gender-distinct vocabulary doesn't matter --- the female-specific vocabularly still ranked more toxic than male-specific vocabulary.

While it's difficult to understand why there is such a distinction between genders and the toxicity in their reference, I believe that at least identifying and recognizing this discrepency is important so we can recognize and combat such biases.
