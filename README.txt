Text summarization is the process of distilling the most 
important information from a source (or sources) to produce
 an abridged version for a particular user (or users) and 
task (or tasks).

Reading a dozen lengthy interviews wasn’t the most attractive 
proposition though. I decided to implement a very simple 
approach to Text Summarization to pare down the interviews 
into the most important bits; Weighted Frequency of 
Occurrence. In short, we find the frequency that each word 
occurs in the text, weight every sentence by the frequency of
the words it contains, and return only the n highest-weighted
sentences. In this article, I’m going to walk you through 
that process.