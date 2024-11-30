# NLP_learning-
NLP_learning


## setp -1 

Text preprocessing

1.Tokenization 
2.stopwords 
3.stemming
4.lematization




# Tokenization

Tokenization in NLP is the process of splitting text into smaller units called tokens

Input: "Tokenization in NLP is essential."
Output: ["Tokenization", "in", "NLP", "is", "essential", "."]


# stopwords
Stopwords are common words in a language that are usually filtered out during (NLP) tasks because they don't carry significant meaning or add much value to the analysis.
"and,is,was"


# stemming  
Stemming is a (NLP) technique used to reduce words to their root or base form, known as the "stem." It removes prefixes, suffixes, and inflections, often resulting in a base word that may not be a valid word in the language but serves as a representative form

Advantages
its fast 
Reduces vocabulary size.
Improves search efficiency.
Faster than lemmatization.
Useful for text analysis with sparse data.

Disadvantages
remove meaning of thw word
Over-stemming can lose meaning.
Under-stemming misses unification.
Reduced precision due to lack of context.
Inferior to lemmatization for linguistic accuracy

use case:-
spam classification
Review classificaton 


"running" → "run"
"happily" → "happi"
"cares" → "care"


# Lemmatization 
Lemmatization is a natural language processing (NLP) technique that reduces words to their base or dictionary form, known as the "lemma," based on the word's meaning and context. Unlike stemming, lemmatization considers the word's part of speech (POS) and ensures that the resulting lemma is a valid word in the language.


Advantages:
Preserves Meaning: Unlike stemming, lemmatization retains the word's meaning by ensuring the lemma is contextually correct.
Improves Accuracy: Suitable for applications that require understanding the context (e.g., sentiment analysis, machine translation).
Produces Valid Words: The result is always a valid dictionary word.

Disadvantages:
Slower than Stemming: Lemmatization requires more processing power as it considers the word’s part of speech and context.
Complex: More computationally expensive and requires a larger set of linguistic rules or a dictionary to process


"running" → "run" (verb)
"better" → "good" (adjective)
"wolves" → "wolf" (noun)





# basic termonologies used in NLP

1. corpus
2. documment
3. vocablary
4. words 


# corpus 
corpus (plural: corpora) refers to a large and structured collection of texts used for training and analyzing language models. A corpus can contain various types of text, such as books, articles, social media posts, or even conversational dialogues, depending on the task.

# document

document refers to any single unit of text that is processed or analyzed. It can be a sentence, paragraph, article, or even a complete book, depending on the context and the task at hand.

# vocabulary

vocabulary refers to the set of all unique words or tokens that appear in a corpus or dataset.

# word

word is a basic unit of text that represents a meaningful concept, and it is typically the smallest standalone unit of language. Words are central to most NLP tasks, such as text processing, sentiment analysis, machine translation,

 "I love programming" → Tokens: ["I", "love", "programming"]



## step 2 

word to vector 

Word to Vector (or Word Embedding) is a technique in natural language processing (NLP) where words are converted into numerical vectors, allowing machines to understand the meaning and relationships between words


1. bag of words
2. TF IDF    TF-IDF (Term Frequency-Inverse Document Frequency)
2. word 2 vec




