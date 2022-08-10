# arabic-ner
This repository will be used to store results of my research in Spring 2022, which tackles Named-Entity Recognition (NER) in the arabic language. 
## Scraper:
![image](https://user-images.githubusercontent.com/71970059/177956076-0a62fd1a-4520-4a82-87fe-30d57af4295f.png)

In order to collect the textual data needed for Named Entity Recognition, I have scraped all articles on wikipedia darija. The resulting corpus is comprised of 2M+ words, with an abundant amount of named entities. 

The data is now stored on google drive in 63 corpora, with an average of 34,000 words per corpus. 

![image](https://user-images.githubusercontent.com/71970059/177958072-d35e1d21-1b04-4d61-a198-f134d801c88d.png)

The dataset can be shared with the research community upon demand. 
## Annotation on doccano: 
Doccano, an open source tool, was used for data annotation. I hosted an instance of doccano on Heroku App. 
![image](https://user-images.githubusercontent.com/71970059/183910257-94893a7e-1318-4e7c-b6ec-1b4e3424bfd3.png)

## JSONL to CoNLL: 
The data exported from doccano is in JSONL format, I wrote a converter using camel-tools. Full colab notebook on `json-to-conll`. 
![image](https://user-images.githubusercontent.com/71970059/183910577-f9f4dd7b-4a2d-40cf-a3c1-8f4e81171ca8.png)
