# lauzhack2023

# Challenge Description

## Data Description 
We provide you with data scraped from Swisscom's public website. The data is contained in the file: ```swisscom_webpage.json```

The structure of the elements in the json file is the following: 

* ```vector_field```: List representing the embedding of the text. Dimension: 1536
* ```text```: paragraph of text extracted from the website.
* ```metadata```:
  -  ```source```: link to the source page.
  -  ```language```: language of the text. Can be German (de), French (fr), Italian (it), English (en) or None
  -  ```title```: title of the article containing the text
  -  ```created_at```: data of creating of the text
  -  ```last_modified```: latest modification on the text
  -  ```start_index```: - 
