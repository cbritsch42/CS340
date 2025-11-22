**Spellcheck - CS340, Project 4**

This program performs a spellcheck of a given word against a dictionary of words from the novel *Pride and Prejudice*.

Each word is compared using a sequence alignment algorithm with the following penalties:
  Exact Match = 0;
  Consonant/Consonant Mismatch = 1
  Vowel/Vowel Mismatch = 
  Gap = 2
  Vowel/Consonant Mismatch = 3

After clicking the submit button, the ten best matches will be displayed, along with their respective alignment scores.  A timer function has been added to the page to measure execution performance, which should be directly proportional to the number of entries in the dictionary file (7032) times the number of characters in the submission, modified by processor speed.

Performance times on my personal machine range from ~17.5ms (a) to ~68.5ms (incorrigibility)
