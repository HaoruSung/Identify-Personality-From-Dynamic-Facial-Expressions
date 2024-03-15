# Personality Prediction from Dynamic Facial Expressions

## Overview
This project is dedicated to predicting an individual's personality through dynamic facial expressions. Leveraging a variety of data analysis methodologies and machine learning algorithms, we've developed a system to analyze and predict personality traits effectively.

## Data Collection
- Collected basic demographic information and responses to the IPIP-NEO personality test from 73 participants.
- Recorded videos of participants' facial expressions using a desktop camera.

## Data Analysis
- **Personality Test Data**: Utilized the IPIP-NEO test to measure five major personality traits: Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism.
- **Facial Expression Data**: Employed the Crowdemotion API for real-time analysis of dynamic facial expressions.

## Algorithms
- **Hierarchical Clustering**: Implemented using complete-linkage, average-linkage, and single-linkage methods, along with K-means clustering based on Euclidean distance for personality categorization.
- **Markov Model**: Applied to describe transition probabilities between six different emotional states derived from facial expression data.
- **Naïve Bayes Classifiers**: Predicted personality types by calculating average emotion transition probabilities for people with similar personality traits.

## Results
- **Personality Prediction**: Found Naïve Bayes Classifier predictions, based on facial expressions, to surpass acquaintance-based predictions and to be comparable to those by close friends.
- **Predictive Accuracy**: Achieved an average predictive accuracy of 0.431, outperforming friends' average accuracy of 0.287.
- **Leave One Out and Random Subsampling Tests**: Determined that the optimal number of personality clusters depends on the methodology, with excessive fragmentation potentially reducing accuracy.

## Conclusion
Facial expression analysis has been proven to be a reliable method for predicting personality within a brief interaction, demonstrating near-equal accuracy to that of an acquaintance's assessment and similar reliability to that of a close friend. For enhanced stability of predictions, an increase in data set and sample diversity is recommended.

## Practical Applications
- **Digital Interfaces**: Tailoring user experiences based on inferred personality traits from facial expressions.
- **Mental Health Services**: Assisting professionals in assessing client personalities more swiftly and objectively.
- **HR and Team Building**: Improving recruitment processes and team dynamics with deeper personality insights.
- **Educational Technology**: Creating adaptive learning environments responsive to students' emotional and cognitive states.
- **Customer Service Bots**: Empowering bots with the ability to understand clients' needs and emotional responses more effectively.
- **Gaming Industry**: Adapting game narratives and difficulty in response to players' emotional cues.
- **Marketing and Advertising**: Tailoring campaigns to different personality profiles to increase engagement and conversion rates.

The implications of this research are vast, suggesting a future in which technology interacts more intuitively with human emotions and personalities.
