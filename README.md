# About
Exploration of threats in telegram messages. The goall is to fuse and compare modern NLP tools and classic ML approaches to the task.

# Data
The dataset originates from [HuggingFace_repository](https://huggingface.co/datasets/singlelabelmulticlass/ThreatGram101) and is used in accordance with Creative Commons Attribution 4.0 license.

# Workflow
1. Unzip the [archive](/ThreatGram%2520101%2520-%2520Extreme%2520Telegram%2520Replies%2520Data%2520with%2520Threat%2520Levels.zip) with data. It cointains 2 .json files: smaller labeled dataset and larger unlabeled dataset;
2. Run [primary_notebook](/telegram_threats_primary.ipynb) for data exploration, cleaning and NER+Emotion extraction;
3. Run [bert_notebook](/telegram_threats_bert_classifier.ipynb) for training the baseline model for threat classification;
4. Run [modeling](/telegram_threats_modeling.ipynb) for Catboost, Xgboost and Lightgbm training and evaluation.

# About author
CatGamer7 - Zaida Artur - Зайда Артур, студент группы 8ПМ52 НИ ТПУ
