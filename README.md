# Sentiment-Analysis-of-the-Copom-document-using-Vader
A sentiment analysis of the last document of the meeting of the Brazilian central bank's Copom (Monetary Policy Committee) was performed using the Vader (Valence Aware Dictionary and sEntiment Reasoner)

Sentiment analysis is the process of identifying and categorising the opinions expressed by human utterances through computational techniques using natural language processing. There are several tools to do this. Sentiment analysis is an application of the Natural Language Processing (NLP), which is the subfield of artificial intelligence that deals with computational algorithms which supports computers and humans’ interactions.
The Vader (Valence Aware Dictionary for sEntiment Reasoning), is a tool for
sentiment analysis to find good predictive accuracy to measure emotional state. Vader
lexicon was originally developed by C.J hutto based on rule-based methods, The Vader doesn’t need to be trained as it is built on a lexicon with standard sentiment library. The sentiment lexicon used by Vader is validated as gold standard tested by humans. 
The aim of this study was analyze the sentiment of the document of the meeting of Copom using Vader. 
First, the data were extracted from the PDF file and these data were cleaned, removing the noise texts. The items of this document were isolated. The sentiment analysis was performed in each selected items. As vader only works in the English language, a Vader's fork called LeIA (Léxico para Inferência Adaptada) was used to avoid having to translate the texts.
The results of the sentiments (i.e. positive, neutral and negative) obtained per each item were plotted in barplot using the seaborn module. Like this example:  

https://github.com/Andre-Luis-Lopes-da-Silva/Sentiment-Analysis-of-the-Copom-document-using-Vader/issues/1#issue-1345627533

As conclusion, the score 'compound' was presented in a table per each item, like this: 

https://github.com/Andre-Luis-Lopes-da-Silva/Sentiment-Analysis-of-the-Copom-document-using-Vader/issues/2#issue-1345628223

We can say that the macroeconomic scenario for Brazil is still not very favorable according this sentiment analysis. 
