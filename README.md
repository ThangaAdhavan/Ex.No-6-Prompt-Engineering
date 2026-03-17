## Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

## Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.
___________________________________________________________________________________________________________________________________________________________________

## Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.<br>
___________________________________________________________________________________________________________________________________________________________________

## Input:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = input("  ")
print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
___________________________________________________________________________________________________________________________________________________________________
## Output:
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/973885d3-2a95-4a89-95b8-9a063f36fb37" />
<br>
_______________________________________________________________________________________________________________________________
## Result: 
The given response run successfully without any irregular correption.
