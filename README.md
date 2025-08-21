# Text Analytics on Los Angeles Restaurant Reviews

## Business Problem

Restaurants in Los Angeles face intense competition across diverse dining options. Yelp reviews strongly influence customer decisions, and a single negative review can dissuade potential patrons—translating into lost revenue. To remain competitive, restaurants must understand the factors that drive customer satisfaction and uncover common pain points.

## Analytics Approach

**1. Preprocessing:**
- Remove stopwords, punctuation, whitespace, and numbers using quanteda, stringr, textstem.

**2. Text Analytics:**

- Tokenization, stemming/lemmatization, n-grams (tidytext, stopwords).
- Word frequency and TF-IDF analysis for early exploration.

**3. Advanced Analysis:**
- Latent Semantic Analysis (LSA) using lsa, tm.
- Sentiment Analysis using sentimentr, syuzhet.
- Visualization: Insights visualized with ggplot2.

## Key Insights
**1. Weekday ratings are more polarized while weekend ratings are milder:**
-   Weekday customers are more critical
-   Weekend users may be more relaxed as they enjoy themselves at weekend

**2. What drives and what hurts satisfaction?**

High-rating guests value 
- Consistent flavor
- Place ambiance
- Attentive service 

⇒ These factors help make strong impression and customer returns.

Common issues are 
- Inconsistent food quality
- Poor staff attitude
- Billing/order errors
- Poor payment experience

⇒ Staff-related issues, especially attitude and service consistency, are the main pain points of the customers.

## Recommendations
**1. Improve service quality**
- Positive reviews are often tied to attentive service and ambience.
- Invest in staff training and encourage emotional connection through personalized experiences.

**2. Control theme authenticity**
- Ensure restaurant’s concept aligns with customer expectations especially when it comes to specialized cuisine styles (e.g., Laotian, Dim Sum)

**3. Weekday and weekend assignment**
- Assign strong staff during weekdays to ensure quality consistency
- Use weekends to test new offerings or service improvements


