
# Mood Guesser

## Level 3: Testing

Accuracy on the 5 practice sentences: **80%**

1. The sentence "Today was a great day" went wrong because the word "great" is not included in my happy_words list. The program found no clue words and labelled it Sad because of the tie-breaking rule.

2. One change that would make my program better: I could improve the word lists by adding more useful mood-related words.

## Learning questions

1. Total score of "good party today" and its mood: **+3, Happy**.

2. Total score of "bad exam day" and its mood: **-3, Sad**.

3. The word "exam" got a score of 0 because it appeared once in a Happy sentence and once in a Sad sentence. This is useful because the word alone does not indicate a particular mood.

4. "Not good" is labelled Happy because the method counts the word "good" but does not understand the meaning of "not". This could be improved by adding a method to detect negative words and handle negation.

## AI declaration

I used an AI tool: **Yes**

If yes, what I asked it:

I used ChatGPT to understand the assignment, get help with Python programming, test my Mood Guesser program and understand the GitHub uploading process.

## Reflection

What was hardest, and what I learned that I did not know before:

[Write in your own words what you found difficult and what you learned while completing this project.]
