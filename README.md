# Wordle-Algorithm

Wordle as been sweeping the nation for a few weeks now, and I thought it would be a fun challenge to make an algorithm that could solve the problem of the day

If you're seeing this in the future and people aren't posting their Wordle scores anymore, the rules of Wordle are simple:
- You have 6 chances to guess a random 5-letter word
- Each guess has to be a valid 5-letter word
- After every guess you're given feedback:
- If your guess contained a letter that doesn't appear in the target word, that letter is colored grey
- If your guess contained a letter that appears in the target word but wasn't in the right position, that letter is colored yellow
- If your guess contained a letter that appeard in the target word and was in the right position, that letter is colored green

Using this feedback, this algorithm is able to guess the random word in generally 4 to 5 guesses
