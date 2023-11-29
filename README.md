# Welcome to Swisscom@Lauzhack2023

Dear participants, 

We are happy to welcome you to the Swisscom Challenge for Lauzhack 2023. This year, we are all about revolutionising customer interactions. Find the description of the challenge bellow together with some information about the data we provide you. Also, if you would like to use AWS resources for your implementation, do not hesitate to contact us or the AWS team :) 

We are happy to answer your questions on site or in our discord space. 

Happy hacking! 

## Challenge Description

Join us in revolutionising customer interactions! Your mission is to engineer a retrieval system that extracts vital information from our company website. This will help us empower our support team to answer customer queries with lightning speed, enhancing the overall user experience. We will provide you with data from the website already scraped and a set of questions and answers so that you can test your model. You are free to use LLM APIs, small NLP models or any trick you can come up with, we are looking for a creative, interactive and user-friendly solution that ensures seamless access to critical data. 

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


## Example Questions you can use to test your solution:

#### Question:
What does Swisscom offer as part of the Hybrid Client Onboarding for banking customers?

#### Answer:
Client Onboarding is the hybrid solution for new customer acquisition and is independent of time, place and device. It digitises and standardises processes, automates tasks in the front and back office, uses both the in-branch and self-service channel, improves the efficiency of processes and increases security.
What’s in it for you:
* Hybrid account opening process without the need for paperwork and no loss of data
* All Client Onboarding steps adapted to your processes
* Seamless digital client support in front and back office

Source: https://www.swisscom.ch/en/business/enterprise/offer/banking/process-outsourcing/clm-suite.html

---

#### Question:
How many hours of recording can I store if I have Swisscom Blue TV M?

#### Answer:
250 hours simultaneous programme recording, of which 50 hours can be archived

Source: https://www.swisscom.ch/en/residential/tv/tv-subscription/blue-tv-m.html

---

#### Question:
Which are the 2023 measures taken to promote inclusion for employees at the workplace? 

#### Answer:
* Promotion of flexible working models for women and men to be pursued further.
* Promotion of diversity with additional, business unit-specific measures will also be continued.
* The majority of job advertisements will be published with an employment level of 60–100%.

Source: https://www.swisscom.ch/en/about/sustainability/targets.html

---

#### Question:
Which are the 2023 measure taken to ensure we can meet the goal of being Climate-neutral by 2025?

#### Answer:
* Refurbishment of buildings and heating systems, replacement of fossil fuel-burning heating systems with heat pumps.
* Electrification of the vehicle fleet and use of hybrid drives(opens in new tab).
* Agreements with A suppliers.
* Promotion of supplier participation in the Carbon Disclosure Project (CDP), dialogue with individual suppliers.

Source: https://www.swisscom.ch/en/about/sustainability/targets.html

---

#### Question:
How much does Swisscom's network rely on renewable energy? Since when? 

#### Answer:
Swisscom has been operating its entire network with 100% renewable energy for over 10 years, since 2010.

---
