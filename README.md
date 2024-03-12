# niche_spellcheck
Practicing NLP Techniques and Learning Spellcheck Algorithms

Autocorrect
1. Word is mispelled 
2. What strings are n edit distance away from spelled word?
3. Are these strings real words? Keep the real words
4. Calculate the most probable word (domain)

Mispelled words are defined as words not in the vocabulary. 

N Edit Distance Possibilities: 
- Insert (Add a letter)
- Delete (Remove a letter)
- Switch (Swap 2 adjacent letters)
- Replace (change 1 letter to another)

Calculating Word Probabilities 
P(w) = Probablility of word
C(w) = Number of times a word appears 
V = Total size of the corpus 

P(w) = C(w) / V