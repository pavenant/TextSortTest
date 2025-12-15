# Project: TextABCSort

## User Story

* As a **text analyzer**,  
* I want to reorder and reformat a paragraph of text with the following rules:  
  - Words must be reordered **alphabetically**.  
    *Example: (Zebra Abba) → (Abba Zebra)*  
  - After alphabetical ordering, words must be sorted by **uppercase before lowercase**.  
    *Note: Alphabetical ordering takes precedence.*  
    *Example: (aBba Abba) → (Abba aBba)*  
  - All punctuation characters `(.,;')` must be removed.  
    *Example: (aBba, Abba) → (Abba aBba)*  
  - Duplicate words must **not** be removed.  

* So that I can easily read the words in alphabetical order and clearly identify case variations.

## Notes

- The **user story test** is the highest priority. Other notes are secondary.  
- Additional unit tests may be added if necessary.  
- Ensure the project structure is clean and maintainable.  
- Consider future flexibility, such as replacing the console logger with an event logger.  
- Although this is a simple test, the implementation should follow **production-quality standards**.
