# Sentiwordnet-as-a-Table
As you know, one of the most used lexical resources for sentiment analysis that is publicly available is Sentiwordnet. It has released as a text file where each row shows a synset, its definition, part of speech, positive and negative polarity, and words that one of their senses belongs to that synset, For example, this is one row of the file.
a 00015720 0.125 0.5 rife#2 plethoric#1 overabundant#1 excessively abundant
As you see, it is not easy to work with this file. So I convert it to a table where each row shows one sense of a word.
Here you can download this table as a CSV file and import it to a table.
Having Sentiwordnet as a table helps you to retrieve information by writing SQL queries.
