# Zipf's Law
Jupyter Notebook Project for proof of Zipfs Law
### PROOF OF ZIPF'S LAW 
Zipf's law was originally formulated in terms of quantitative linguistics, stating that 
given some corpus of natural language utterances, the frequency of any word is inversely 
proportional to its rank in the frequency table. 

eg: in a language, the top  most used words are ABC, DEF, GHI, JKL  in that order.
    Then the word DEF will appear 1/2 times as ABC, GHI will appear 1/3 and JKL
    will appear 1/4 times as ABC. If a word is the nth most used word in a language then its
    frequency will be 1/n of the most used word


Although Zipf's Law holds for all languages, 
even non-natural ones like Esperanto,[12] the reason is still not well understood. 

We will be trying to prove Zipfs law at 3 levels:
#
1. Independant Books - We will prove that the law holds true for independant English 
    language books from the Gutenberg Corpus

2. Genres - We will prove that the law holds true for different genres of English language 
    books from the Brown Corpus

3. Languages - We will prove that the law holds true for different languages from the UDHR Corpus


In every case, the maximum frequency will be normalised to 1000
