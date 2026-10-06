# Bangla Natural Language Understanding (BNLU) Dataset
This repository contains datasets collected and organized for research on Bangla Natural Language Understanding (NLU).
It is a A multi-domain, multilingual dataset for intent classification, and slot filling in Bangla. 
Every utterance is written in parallel across three linguistic forms: Bangla (Bengali script), English, and Banglish (Romanized Bangla)
to support cross-lingual and code-mixed NLU research for a widely spoken but low-resource language.


## Dataset Structure

The datasets are organized into the following domains:
BNLU Dataset/
├── Healthcare.json
├── Restaurant,Tourist,Travel,Hotel.json
├── E-commerce.json
├── Education.json
├── Mobile_Financial_Services.json
└── Government_Services.json

## Overview
| Property            |                         Value |
| ------------------- | ----------------------------: |
| **Total Dialogues** |                           209 |
| **Languages**       | 3 (Bangla, English, Banglish) |
| **Domains**         |                             9 |
| **Intents**         |                            64 |


## Domain coverage
| Domain                   | Dialogues | Intents |
| ------------------------ | --------: | ------: |
| Education                |        37 |       9 |
| Government Service       |        32 |      19 |
| Healthcare               |        25 |       5 |
| Mobile Financial Service |        25 |       5 |
| E-commerce               |        25 |      10 |
| Restaurant               |        16 |       5 |
| Tourist                  |        14 |       5 |
| Travel                   |        12 |       4 |
| Hotel                    |        10 |       2 |
| **Total**                |   **209** |  **64** |


## Data Format

Each file is a JSON array of dialogue objects. Every dialogue has:

| Field         | Description                                    |
| ------------- | ---------------------------------------------- |
| `dialogue_id` | Unique identifier for the dialogue             |
| `domains`     | List of domain(s) the dialogue belongs to      |
| `intent`      | The single dominant user goal for the dialogue |
| `turns`       | Ordered list of conversational turns           |







