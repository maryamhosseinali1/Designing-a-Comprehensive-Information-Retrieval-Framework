# Advanced Information Retrieval System  

## Description  
A Python-based system for handling complex information retrieval tasks, including spelling corrections (Levenshtein distance), wildcard queries (bigram indexing), boolean logic, and Soundex encoding for phonetic similarity. The system preprocesses text, builds inverted indexes, and efficiently retrieves relevant documents for queries.  

## Features  
- **Spelling Correction:** Suggests corrections for typos.  
  Example: `schol → ['school', 'scholar']`  
- **Wildcard Queries:** Matches patterns with `*` using bigram indexing.  
  Example: `bl*h → ['blah', 'blush']`  
- **Boolean Logic:** Processes queries with AND, OR, and NOT operators.  
  Example: `bl*h AND NOT dean → [Document IDs]`  
- **Soundex Encoding:** Computes phonetic codes.  
  Example: `Maryam → M650`  

