# Programming Word Challenges

 A place for programming teachers to find resources related to word challenges. 

 ## Colab (Python) Template

 The Google Colab template for doing these challenges in Python can be found [here](https://github.com/pbeens/Programming-Word-Challenges/blob/main/Word_Challenges_Template_Colab_Python.ipynb).

## Example Challenges

1. What are the longest words in the list?
1. If a-1, b=2, etc., what words add up to 100?
1. What is the longest word that ends with "ar".
1. What is the most common letter? Vowel? Consonant?
1. How many palindromes are in the list?
1. What's the longest word ladder list you can make. (A word ladder is a sequence of words where only one letter changes at a time. e.g., "hit" → "hot" → "dot")
1. What's the longest list you can make where you start with a two letter word, and then by reusing those letters and adding one more you can come up with another word. e.g., "or" → "for" → "fort")

The following challenges have been submitted by Ross Jamieson:

8. **All Vowels** - Find all sets of 5 words that have each of the vowels in the same position. Example sets: MATE, METE, MITE, MOTE MUTE; BAT, BET, BIT, BOT, BUT.
1. **Most Letters** - Find the 26 words with the most of each of the letters of the alphabet. Breaking ties part 1: If two words have the same number of a letter, the "better” answer is the shorter word. BUBBLE is better than BUBBLING. Breaking ties part 2: If two words have the same number of a letter, and the same length, the word that doesn’t start with the letter is “better”. HUBBUB is better than BUBBLE.
1. **Murica** - List all the words that can be spelled using only the [2-letter shortcodes](https://raw.githubusercontent.com/jasonong/List-of-US-States/master/states.csv) for the 50 American states. (AL, AK, AZ, AR, CA, CO, CT, …)
Example: VANDAL (Virginia, North Dakota, Alabama).
1. **Backwards** - List all words for which the reversed word is also a word, but not a palindrome. Example: STRESSED
1. **Odd/Even** - List all words for which the odd/even letters make another word. The “odd letters” are the 1st, 3rd, 5th, etc, and the “even letters” are the 2nd, 4th, 6th, …. Only words of 5+ letters (for odd) and 6+ letters (for even) should be considered, i.e. the resulting word must be 3+ letters. Examples: DERBY (which makes DRY), UNBUNDLED (which makes NUDE)
1. **Crossword Solver** - Given a String parameter in the form “??E?R”, find all words that fit.Example: “?R?EFA??” → ARTEFACT, FREEFALL.
Example: “??A?M” → ALARM, CHARM, CHASM, PSALM, SWARM…
1. Additional challenges from Ross can be found [here](https://github.com/pbeens/Programming-Word-Challenges/blob/main/Resources/Ross-Jamieson-Word-Challenges.docx) (Word document).

## Other Text-Based Challenges

These text-based challenges do not rely on the importing of a text file:

1. **Blobs** - A blob is an arrangement of at least 5 letters of the same kind that are connected... [[Link]](https://github.com/pbeens/Programming-Word-Challenges/blob/main/Challenges/Blobs_Programming_Challenge.ipynb)

## Other Resources

1. [Here](https://github.com/pbeens/Programming-Word-Challenges/blob/main/Resources/Ross-Jamieson-Word-Challenges.docx) is Ross Jamieson's original Word Doc of challenges. 
1. [Here](https://github.com/pbeens/Programming-Word-Challenges/blob/main/Resources/5_Letter_Words.ipynb) is the notebook that was used to create the [5-letter words datafile](https://raw.githubusercontent.com/pbeens/Programming-Word-Challenges/main/Datafiles/5-letter-words.txt) that is needed for one challenge. 

## Text Files

1. [5-Letter Words](https://raw.githubusercontent.com/pbeens/Programming-Word-Challenges/main/Datafiles/5-letter-words.txt)
1. [A "clean" dictionary](https://raw.githubusercontent.com/pbeens/Programming-Word-Challenges/main/Datafiles/cleandict.txt) with over 80,000 words in it. If you spot any inappropriate words in it, please open an issue above. 
1. [Top 1000 words](https://raw.githubusercontent.com/pbeens/Programming-Word-Challenges/main/Datafiles/1000-top-words.txt)

## Looking for Contributors

If you have any ideas for additional challenges, add an "Issue" above, email them directly to me at pbeens at gmail dot com, or share with me via twitter at [@pbeens](https://twitter.com/pbeens).
