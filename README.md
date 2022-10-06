# BFI API - Banking and Financial Insitutions
the fast, free & **unlimited** API for BFI data taken directly from 
[NRB](https://nrb.org.np/)

This repo acts as the free and open API for the already **publicly** 
available data in the NRB's website.

To know more regarding what this is about please see: 
[/bank-list](https://www.nrb.org.np/bank-list/)

## Features

- All financial institutions all over Nepal 🇳🇵
- Branches of each BFI listed by NRB

## Tech

BFI API uses nothing but [jsdelivr](https://www.jsdelivr.com/) to serve 
the json file directly from the this github repo.

As a result there is no rate limiting, and you get the fastest response 
time ever because jsdelivr is a CDN for serving static js files ( mostly 
).

## How do I use this API ?

#### STEP #1:
Get the list of all the institutions using this endpoint.
`https://cdn.jsdelivr.net/gh/xyznaveen/bfi@latest/list.json`


#### STEP #2:
Use the data from above endpoint and send request to the specific endpoint 
based on the code. 
`https://cdn.jsdelivr.net/gh/xyznaveen/bfi@latest/data/<bfi_code>.json`

For instance: If you want to get the data for BFI code `11001` then you 
would send request to 
`https://cdn.jsdelivr.net/gh/xyznaveen/bfi@latest/data/11001.json`.

Repeat the same pattern for the necessary code.

## F.A.Q

<details>
<summary>Do you scrape the NRB website ?</summary>
Yes, but this is not done frequently. I plan to do this every 1 month or 
so. Because this data doesn't get updated that often.
</details>

<details>
<summary>How do I request or ask something ?</summary>
Simply create issue with (appropriate label?) right here in GitHub.
</details>

<details>
<summary>Are you full time web scraper ?</summary>
NOPE, I'm an Android SE!
</details>

<details>
<summary>Where is the scraping code ?</summary>
Unfortunately I cannot make that public right now. Will I ever? That is 
the question.
</details>
