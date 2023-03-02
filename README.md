# Death-Row-Last-Statement-Topic-Modeling

## Introduction

This project showcases web scraping using BeautifulSoup to scrape last messages of inmates on death row, perform natural language processing and topic model these messages using BERTopic.

## Webscraping

Messages were scraped from the link [here](https://www.tdcj.texas.gov/death_row/dr_executed_offenders.html)

## Findings 

![newplot-3](https://user-images.githubusercontent.com/113895589/215968618-48a08043-1329-4ccd-a04d-27bd59e44538.png)

In summary, we have managed to cluster last statements of inmates into five different topics.

### Topic 0: Forgiveness

#### Topic Representative:

<img width="1391" alt="Screenshot 2023-02-01 at 2 38 56 PM" src="https://user-images.githubusercontent.com/113895589/215970005-29843152-596e-4d88-a7b6-e8e060241249.png">


### Topic 1: Love and Acceptance

#### Topic Representative:

<img width="1384" alt="Screenshot 2023-02-01 at 2 41 41 PM" src="https://user-images.githubusercontent.com/113895589/215970563-f8bb842a-d5a2-4b74-97dd-c3310a09b06c.png">



### Topic 2: Love, Family and Frustrations

#### Topic Representative:

<img width="1375" alt="Screenshot 2023-02-01 at 2 42 05 PM" src="https://user-images.githubusercontent.com/113895589/215970586-24c0d0e3-ace6-4968-a91a-4a39195b6a8b.png">

### Topic 3: Religion

#### Topic Representative:

<img width="1386" alt="Screenshot 2023-02-01 at 2 39 22 PM" src="https://user-images.githubusercontent.com/113895589/215970092-9b9d9e83-50ac-4475-bc6d-9a66cd641065.png">

### Topic 4: No last statement

#### Topic Representative:

<img width="1356" alt="Screenshot 2023-02-01 at 2 42 16 PM" src="https://user-images.githubusercontent.com/113895589/215970527-b7421f81-a3b0-4ead-ab48-65a5b3ff8a1d.png">

## Intertopic Distance

https://user-images.githubusercontent.com/113895589/215971504-bfd5b172-0fe5-48ae-8632-c7e2ddc253fe.mp4

Based on the plot above, we can see that topics 0, 2 and 3 are similar to each other and topics 1 and 4 are similar to each other. We can also see that between topics 0, 2, 3 and topics 1 and 4, there is a great distance which shows low similarity between the two groups.
