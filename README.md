# FacebookDecadeCorpora
This repository contains two language corpora of colloquial Sinhala content extracted from Facebook using the Crowdtangle platform. 

## Corpus-Alpha
The larger of the two corpora spans trilingual text posted by 533 Sri Lankan Facebook pages, including politics, media, celebrities, and other categories, from 2010 to 2020. It contains 28,825,820 to 29,549,672 words of text, mostly in Sinhala, English and Tamil (the three main languages used in Sri Lanka). It contains URLs, punctuation and other noise, making it more suitable for discourse analysis and the study of codemixing in colloquial Sinhala.

## Corpus-Sinhala-Redux
The smaller corpus amounts to 5,402,76 words of only Sinhala text extracted from Corpus-Alpha. It has been cleaned of URLs, punctuation and noise.

Both corpora have markers for their date of creation, page of origin, and content type. 

To download either corpus, navigate to /corpus-alpha or /corpus-sinhala-redux in this repository. The file parts there (file_part_xx) are pieces of a CSV file, seperated using the standard Linux split command. file_part_00 contains the header. Either join them using column IDs in whichever programming language you use, or in the linux terminal, use:

```
$ cat file_part* > corpus.csv
```

## Stopwords
Stopwords.txt contains a list of algorithmically derived stopwords extracted from Corpus-Sinhala-Redux.

## Methodology, issues and discussion
https://lirneasia.net/2020/07/sinhala-language-corpora-and-stopwords-from-a-decade-of-sri-lankan-facebook/
  
## License

These datasets are released under the principles of Open Access. As such, this work is licensed under a Creative Commons 4.0 CC BY licence: you may distribute, remix, adapt, and build upon this work, even commercially, as long as you credit the authors for the original creation. You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits. Please see the full license at https://creativecommons.org/licenses/by/4.0/legalcode

## Citing
Wijeratne, Y., de Silva, N. (2020). Sinhala language corpora and stopwords compiled from a decade of Sri Lankan Facebook. LIRNEasia.
