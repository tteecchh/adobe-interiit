![image](https://github.com/tteecchh/adobe-interiit/assets/122744362/31fd06f7-927a-46f5-8dbe-c935feca1441)# Adobe's Behaviour Simulation Challenge

### Problem Statement

1. To simulate behaviour (`likes`) from the content of a tweet
2. To simulate content (`tweet text`) from the tweet metadata

### Data Download

[Task 1 Training Data](https://docs.google.com/spreadsheets/d/1JcESl7qCCBvS6xpWMZplhCXunvmkcNU_/edit?usp=drive_link&ouid=101476968084918341858&rtpof=true&sd=true)

[Task 2 Training Data](https://docs.google.com/spreadsheets/d/1oKN_4cMNQHMNrmTSjzKqiJpvDTQA0dAH/edit?usp=drive_link&ouid=101476968084918341858&rtpof=true&sd=true)

To reproduce the experiments here are the links to the required files.
- [Company data scraped from WikiData](https://drive.google.com/file/d/1nEOwJOBp0nWIwxaEU1pMImIrh3xj2h7l/view?usp=sharing)
- [FAISS index for MPNet embeddings of train data](https://drive.google.com/file/d/1-IZTBq3gaIooGQNaEuEOwAQCFo1z8ETq/view?usp=sharing)
- [Incontext learning embeddings for retrieving best samples](https://drive.google.com/file/d/1mWnxNgHazhulJEHQ_TgXNINTvX9W64QA/view?usp=sharing)
- [Test Prompts for Task2 (company) using incontext learning](https://drive.google.com/file/d/1LgLfdT03r4LhsBjJq3r1iR4hQmXZdcBI/view?usp=drive_link)
- [Test Prompts for Task2 (time) using incontext learning](https://drive.google.com/file/d/1whnimJSZmrCoP60iHfCZiUKAOD_cVLAa/view?usp=drive_link)
- [Test Prompts for Task2 (company) using llama adapter](https://drive.google.com/file/d/1QCl_5EososjKqzLePX3N-V0ZY2whCXq_/view?usp=drive_link)
- [Test Prompts for Task2 (time) using llama adapter](https://drive.google.com/file/d/1NePP7BgMEd3AaxjCXXkfOZHOJvTz9Ivi/view?usp=drive_link)
- [Llama Adapter Weights](https://drive.google.com/file/d/18Aaiby_l8IYooAJu5nx_2WOhgDrygONX/view?usp=drive_link)

**Download and store data in `./data`**

### Utils
We have setup scripts `./utils` to get the data for the usernames for finetuning and inference of the models. These help us fetch important details like usernames' followers, location, twitter description etc.

### [Task 1](./task1/README.md)

### [Task 2](./task2/README.md)

