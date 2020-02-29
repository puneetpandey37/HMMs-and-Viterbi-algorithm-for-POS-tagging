# HMMs-and-Viterbi-algorithm-for-POS-tagging
Viterbi algorithm to solve the problem of unknown words using various techniques.  We used the Treebank dataset of NLTK with the 'universal' tagset. The Universal tagset of NLTK comprises only 12 coarse tag classes as follows: Verb, Noun, Pronouns, Adjectives, Adverbs, Adpositions, Conjunctions, Determiners, Cardinal Numbers, Particles, Other/ Foreign words, Punctuations.  We have used three forms of Viterbi algorithm: 

1- Vanilla Viterbi algorithm. 

2- Modified Viterbi algorithm to use the the Transition Probability to tag the unknown word. 

3- Modified Viterbi algorithm to tag the unknown words with the custom Rule based tagger.  


We followed below steps to gradually increase the tagging accuracy:  

Step-1: Used the Vanila Viterbi algorithm and tagged the validation and test dataset

tep-2: Tagged the words in Test and Validation datesets using vanilla Viterbi algorithm. 

Step-3: Checked the tag sequence of correctly and incorrectly tagged words. Found the accuracy of vanilla Viterbi algorithm to be 90.65% 

Step-4: Modified the vanilla Viterbi algorithm to tag the unknown words considering the Transition probability. 

Step-5: Tagged the words in Test and Validation datesets using this modified Viterbi algorithm. 

Step-6: Checked the tag sequence of correctly and incorrectly tagged words. Found the accuracy of Viterbi modified-I algorithm to be 93.91% 

Step-7: Compared the words tagged differently by the vanilla Viterbi and the modified Viterbi algorithms. 

Step-8: Modified the Viterbi algorithm to tag the unknown words with a custom Rule based tagger. 

Step-9: Tagged the words in Test and Validation datesets using the again modified Viterbi algorithm. 

Step-10: Checked the tag sequence of correctly and incorrectly tagged words. Found the accuracy of Viterbi modified-II algorithm to be 95%
