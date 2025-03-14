## Document Dataset Tools

This repository contains tools for constructing datasets from documents.

- [x] [scraping](./scraping.ipynb): Tools for scraping documents from Digital Corpora [1] which contains 8 Mio toal and ~900.000 german pdf files.
- [ ] [sync](): Tools for syncing the documents to a remote server.
- [x] [tesseract](./tesseract.ipynb): Tools for using tesseract to extract text from scraped pdf-files.
- [ ] [postprocessing](): Tools for postprocessing the text extracted from the pdf-files. This includes removing duplicates or empty documents as well as filtering out non-german documents, etc. (TODO)
- [ ] [prediction](): Tools for predicting the category of the documents using LLMs (TODO)
- [ ] [embedding](): Tools for embedding the documents into a vector space for classification (TODO)
- [ ] [packaging](): Tools for creating a dataset from documents and target values (TODO)

[1] https://digitalcorpora.org/corpora/file-corpora/cc-main-2021-31-pdf-untruncated/