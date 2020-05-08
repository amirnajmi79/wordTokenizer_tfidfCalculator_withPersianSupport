# wordTokenizer_tfidfCalculator_withPersianSupport
A project for tokenizign words(including Persian), links, numbers from texts and calculating the 'tfidf' values.

Import your texts(yes it supports multy text files) by writing your texts allocated foldor address.

In first step, this project tokenizes Persian and English words of the text.
Then it tokenizes the links inside the texts and at the end it tokenizes the numbers inside the texts.
(Also it normalizes the junk persian letters into normal mode)
(All done by regular expression and just its not perfect and includes some missings but accuracy is over 98%)

In second step,it sorts the tokens (i used bubble sort for persian words sorting, it was from O(n^2) so 
i just used simple python sort and i will fix that in future developments).

In third step, it calculates the 'tf' , 'idf' , and finally 'tf-idf' values of the words based on the input texts.

