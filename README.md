# FacebookDecadeCorpora
This repository contains two language corpora of colloquial Sinhala content extracted from Facebook using the Crowdtangle platform. 

## Corpus-Alpha. Note: deprecated: this dataset has been removed from public access.
The larger of the two corpora spans trilingual text posted by 533 Sri Lankan Facebook pages, including politics, media, celebrities, and other categories, from 2010 to 2020. It contains 28,825,820 to 29,549,672 words of text, mostly in Sinhala, English and Tamil (the three main languages used in Sri Lanka). It contains URLs, punctuation and other noise, making it more suitable for discourse analysis and the study of codemixing in colloquial Sinhala.

## Corpus-Sinhala-Redux. Note: deprecated: this dataset has been removed from public access.
The smaller corpus amounts to 5,402,76 words of only Sinhala text extracted from Corpus-Alpha. It has been cleaned of URLs, punctuation and noise.

Both corpora have markers for their date of creation, page of origin, and content type. 

## Stopwords
Stopwords.txt contains a list of algorithmically derived stopwords extracted from Corpus-Sinhala-Redux.

## Methodology, issues and discussion
https://lirneasia.net/2020/07/sinhala-language-corpora-and-stopwords-from-a-decade-of-sri-lankan-facebook/


## Unicode issues

It's fairly common for Sinhala text to render as gibberish, even in a programming environment. This has a lot to do with how programs use your system locale to select language. We've run into this issue with RStudio on Windows, for instance, but RStudio on Linux reads just fine. Likewise, Microsoft Excel has thrown issues on Windows, while LibreOffice reads just fine.

A few tips: use UTF-8 when reading these files. Head on to https://www.unicode.org/help/display_problems.html for generic display advice and check Stackoverflow for program-specific problems.

We recommend Perl for language wrangling, especially if you need REGEXs. It's what we've used here for data cleaning.  
  
## License

This work is licensed under a Creative Commons 4.0 CC BY licence: you may distribute, remix, adapt, and build upon this work, even commercially, as long as you credit the authors for the original creation. You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits. Please see the full license at https://creativecommons.org/licenses/by/4.0/legalcode

## Citing
Wijeratne, Y., de Silva, N. (2020). Sinhala Language Corpora and Stopwords from a Decade of Sri Lankan Facebook. LIRNEasia.
