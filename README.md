🔑 Key Parts:
Split into Sentences:

Uses regex re.split() to break the paragraph into individual sentences.

Build Word Frequency Table:

Counts how often each word appears (ignores very short words).

Helps determine which sentences have the most "important" words.

Score Sentences:

Each sentence is given a score based on how many frequent words it contains.

Select Top Sentences:

Sorts sentences by score and selects the top n (based on user input).

User Input:

User pastes a paragraph and chooses how many summary sentences they want.

✅ Example Use Case:
Paste 5-6 lines → It returns the 2 most important ones based on word frequency.
