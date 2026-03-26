# Industry Datasets

A curated list of business datasets from the fields of Machine Learning, Marketing, Economics, Transportation, Operations, and Computer Science.

## Contents

- [LLM Interaction Datasets with Sequential Feedback](#llm-interaction-datasets-with-sequential-feedback)
- [General e-Commerce](#general-e-commerce)
- [A/B Tests and Experiments](#ab-tests-and-experiments)
- [Browsing and Search](#browsing-and-search)
- [Video Search and Recommendation](#video-search-and-recommendation)
- [Video Engagement](#video-engagement)
- [News and Media](#news-and-media)
- [Product and Reviews](#product-and-reviews)
- [Sales and Forecasting](#sales-and-forecasting)
- [Supermarkets and Grocery](#supermarkets-and-grocery)
- [Financial Transactions](#financial-transactions)
- [Fashion](#fashion)
- [Cars and Used Cars](#cars-and-used-cars)
- [Discrete Economic Choices](#discrete-economic-choices)
- [Travel](#travel)
- [Music](#music)
- [Procurement and Online Auctions](#procurement-and-online-auctions)
- [Display Advertising and Sponsered Search Auctions](#display-advertising-and-sponsered-search-auctions)
- [Healthcare](#healthcare)
- [Logistics](#logistics)
- [Driving, Mobility, GPS Traces](#driving-mobility-gps-traces)
- [Human Trajectories](#human-trajectories)
- [Check-in and Location Data](#check-in-and-location-data)
- [Housing and Residential Prices](#housing-and-residential-prices)
- [Research Datasets and Collections](#research-datasets-and-collections)
- [Competitions](#competitions)
- [Gaming](#gaming)
- [Others](#others)

---

## LLM Interaction Datasets with Sequential Feedback

Datasets capturing multi-turn dialogues with LLMs, including quality feedback and preference signals.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **LMSYS-Chat-1M** | 1M real-world conversations with 25 LLMs from 210K unique IPs in 154 languages, with content moderation and safety annotations. Avg 2.0 turns per conversation with rigorous PII removal; research-validated at ICLR 2024. | [Source](https://huggingface.co/datasets/lmsys/lmsys-chat-1m) |
| **DiQAD** | 100K real-world user dialogues with 6-dimension quality assessment (grammaticality, relevance, consistency, empathy, proactivity, informativeness) scored 0-2. Avg 8 turns per conversation; published at EMNLP 2023 with expert inter-annotator agreement. | [Source](https://github.com/yukunZhao/Dataset_Dialogue_quality_evaluation) |
| **USS** | 6,800 dialogues with 5-level satisfaction labels spanning e-commerce, task-oriented, and recommendation domains. Very long conversations (avg 32.3 turns); research-validated with high inter-annotator agreement (Fleiss Kappa 0.574). | [Source](https://github.com/sunnweiwei/user-satisfaction-simulation) |
| **ConvAI Dataset** | 4,750 human-to-bot dialogues with per-utterance thumbs up/down feedback and dialogue-level quality scores across engagement, breadth, and overall quality (1-5). Avg 10.5 turns; strong metric correlations (r=0.86-0.87). | [Source](http://convai.io/2017/data/dataset_description.pdf) |
| **Arena Human Preference (55K)** | 55K+ real-world conversations with human preference labels from Chatbot Arena, featuring pairwise model comparisons and user votes. Used in Kaggle competition with diverse model coverage. | [Source](https://huggingface.co/datasets/lmarena-ai/arena-human-preference-55k) |

## General e-Commerce

Datasets focusing on online retail transactions, customer behavior, and product information.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Brazilian eCommerce** | 100,000 orders (2016-2018) from Olist marketplaces across Brazil, structured in 9 relational tables (customers, orders, payments, products, geolocation, reviews). | [Source](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) |
| **Open CDP**         | Open-source Customer Data Platform by REES46 aggregating omnichannel interactions (web, app, POS) with AI-driven identity resolution and event tracking (14+ types). | [Source](https://rees46.com/en/datasets)                            |
| **JD.com (2011-2014)** | Consumer behavior (2011-2014), 15/987 categories, ~2M users, >100k products, 60M+ reviews (positive/negative/overall), purchase behavior, ratings, metadata.    | [Source](https://www.yongfeng.me/dataset/)                            |
| **JD.com 2020 (MSOM-20)** | Transaction-level data (March 2018) featuring 2.5M customers (457k purchasers) and 31,868 SKUs, emphasizing purchase conversion pathways.                     | [Source](https://connect.informs.org/msom/events/datadriven2020)    |
| **Alibaba Ads (IJCAI-18)** | 6 billion display ad/click logs over 8 days from 100 million users and 70 million items.                                                                     | [Source](https://tianchi.aliyun.com/dataset/147588)                 |
| **Alibaba Mobile (6GB)** | Mobile e-commerce user behavior data, including clicks, purchases, user profiles.                                                                                | [Source](https://www.yongfeng.me/dataset/)                            |
| **Coveo Shopping (SIGIR-21)** | Session-based dataset with 30M+ browsing events, featuring query vectors, image vectors, and description embeddings for recommendation and purchase intent tasks. | [Source](https://github.com/coveooss/SIGIR-ecom-data-challenge#how-to-start) |
| **Retail Rocket**    | 4.5-month clickstream dataset with 2.76M events (views, carts, purchases) from 1.4M visitors across 417k items; includes a deduplicated version.                 | [Source](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset?select=events.csv) |
| **Google Merchandise** | 3 months obfuscated GA4 e-commerce data (Nov 2020-Jan 2021), traffic sources, content behavior, transaction data. Via BigQuery Public Datasets.                   | [Source](https://support.google.com/analytics/answer/7586738#)        |
| **Shopee**           | Dataset from Shopee's Code League competition in 2020.                                                                                                           | [Source](https://www.kaggle.com/datasets/davydev/shopee-code-league-20) |
| **Flipkart**         | Sales dataset from the Indian e-commerce platform Flipkart.                                                                                                      | [Source](https://www.kaggle.com/datasets/iyumrahul/flipkartsalesdataset?select=Sales.csv) |
| **Pakistan e-commerce**| Largest retail e-commerce dataset from Pakistan: 500k+ transactions (Mar 2016 - Aug 2018).                                                                       | [Source](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset) |
| **Instacart**        | 3.4M orders, 206k+ users, 49k+ products (134 aisles, 21 depts), order timing, prior orders. Avg reorder ~59%. (More detailed view).                               | [Source](https://mdporter.github.io/DS6030/other/instacart.html#:~:text=,measure%20of%20time%20between%20orders) |
| **YOOCHOOSE RecSys 2015** | Session-based click and purchase events from a European e-commerce retailer, used in the RecSys Challenge 2015 for session-based recommendation research. | [Source](https://www.kaggle.com/datasets/chadgostopp/recsys-challenge-2015) |
| **Open E-Commerce 1.0 (MIT)** | 1.8M Amazon purchase records with demographic attributes (age, gender, location), enabling research on consumer behavior across population segments. | [Source](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YGLYDY) |

---

## A/B Tests and Experiments

Datasets resulting from controlled experiments, often used for causal inference or evaluating interventions.

| Dataset                      | Description                                                                                                                                    | URL                                                                                |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| **Upworthy News Headlines**  | Largest public A/B testing repository: 32,487 headline/image experiments (2013-2015) on 538M participant assignments, including engagement metrics. | [Source](https://upworthy.natematias.com/)                                         |
| **ASSISTments Dataset**      | Data from the ASSISTments online tutoring platform, often used for educational data mining and A/B testing research.                             | [Source](https://sites.google.com/site/las2016data/home?authuser=0)                |
| **Gamified Learning**        | Dataset related to experiments on gamification in learning environments.                                                                         | [Source](https://www.sciencedirect.com/science/article/pii/S2352340917301646#s0010) |
| **Collection (GSB DBI)**     | A collection of datasets suitable for experimentation analysis maintained by Stanford GSB Data, Analytics & Research Computing.                 | [Source](https://github.com/gsbDBI/ExperimentData)                                 |
| **Athey's course**           | Datasets used in Susan Athey's course materials, often related to causal inference and experimental design.                                      | [Source](https://github.com/itamarcaspi/experimentdatar/tree/master)               |
| **Development (PEP)**        | Experimental research datasets focused on development economics from the Partnership for Economic Policy (PEP).                                  | [Source](https://www.pep-net.org/publications/datasets/experimental-research-datasets) |
| **Computational Neuroscience**| Datasets for computational neuroscience research, often involving experimental data from neural recordings or behavior.                         | [Source](https://crcns.org/)                                                       |
| **ASOS experiments**       | 99 real e-commerce experiments from ASOS with daily metric checkpoints (4 KPIs) and p-values, used for validating adaptive stopping rules.       | [Source](https://www.kaggle.com/datasets/marinazmieva/asos-digital-experiments-dataset?select=document.pdf) |

---

## Browsing and Search

Logs detailing user navigation, search queries, and clicks, potentially without purchase or price data.

| Dataset                       | Description                                                                                                                                         | URL                                                                          |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Amazon Sessions (KDD Cup 23)** | Multilingual Shopping Session Dataset: Sessions from 6 locales (DE, JP, UK, ES, FR, IT), ~40k-500k products per locale, rich product attributes.        | [Source](https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge) |
| **JD.com Search**             | 170,000 users' real search queries (2021-2022) with multi-channel interactions (clicks, carts, purchases), 987 categories, and exposed candidate lists. | [Source](https://github.com/rucliujn/JDsearch)                               |
| **JD-pretrain-data**          | Encoded search queries, item titles, categories for user intent detection and embedding retrieval (5 TSV files).                                      | [Source](https://github.com/jdcomsearch/jd-pretrain-data)                    |
| **BestBuy**                   | Mobile website clicks (~42k) for Xbox games: user IDs, queries, product IDs, timestamps, game attributes. ~3.8k unique queries after cleaning.        | [Source](https://www.kaggle.com/c/acm-sf-chapter-hackathon-big/data)         |
| **Rakuten**                   | E-commerce dataset provided for a SIGIR ecom workshop data task.                                                                                    | [Source](https://sigir-ecom.github.io/ecom2018/data-task.html)               |
| **Wayfair Search (WANDS)**    | Largest public e-commerce search relevance dataset: 233k human-annotated query-product judgments, 43k products with 40+ attributes (categories, ratings). | [Source](https://github.com/wayfair/WANDS)                                   |
| **Criteo Display Advertising**| Massive display ad dataset (24 daily files, 342GB total): click feedback, 13 integer features, 26 hashed categorical features.                           | [Source](https://ailab.criteo.com/ressources/)                               |
| **Avazu**                     | Dataset for predicting click-through rates (CTR) on mobile ad placements.                                                                           | [Source](https://www.kaggle.com/competitions/avazu-ctr-prediction/overview)  |
| **Yoyi**                      | Dataset related to computational advertising provided by Yoyi Digital.                                                                              | [Source](https://apex.sjtu.edu.cn/datasets/7)                                |
| **Ele Search**                | Search log dataset from Ele.me (Chinese food delivery platform).                                                                                    | [Source](https://tianchi.aliyun.com/dataset/120281)                          |
| **Ele Clickstream**           | Clickstream data from Ele.me.                                                                                                                       | [Source](https://tianchi.aliyun.com/dataset/131047)                          |
| **Alibaba Industrial Dump (150GB)** | Large-scale industrial dataset from Alibaba Cloud.                                                                                                | [Source](https://tianchi.aliyun.com/dataset/81505)                           |
| **Alibaba Fashion Combo**     | Dataset focusing on fashion item combinations from Alibaba.                                                                                         | [Source](https://tianchi.aliyun.com/dataset/131519)                          |
| **Alibaba Brick and Mortar (IJCAI-16)** | Combines online browsing/purchase data with offline check-ins/purchases from 1,000+ physical stores linked to Alibaba's O2O platform.       | [Source](https://tianchi.aliyun.com/dataset/53)                              |
| **Alibaba Mobile 2021**       | Mobile user behavior data from Alibaba for 2021.                                                                                                    | [Source](https://tianchi.aliyun.com/dataset/109858)                          |
| **Alibaba Clickstream 2018**  | Clickstream data from Alibaba users in 2018.                                                                                                        | [Source](https://tianchi.aliyun.com/dataset/56)                              |
| **Alibaba Cloud Theme**       | Themed dataset related to Alibaba Cloud services or usage.                                                                                          | [Source](https://tianchi.aliyun.com/dataset/9716)                            |
| **Alibaba Ads**               | Advertising-related dataset from Alibaba (distinct from IJCAI-18).                                                                                  | [Source](https://tianchi.aliyun.com/dataset/148347)                          |
| **Alibaba User Behavior 2018**| 649M user interactions (clicks, carts, buys) on 25M items over 9 days (2017), CTR, dwell times. (15 structured columns: user profiles, item positions, predicted metrics). | [Source](https://tianchi.aliyun.com/dataset/649)                             |
| **Alibaba Personalized Re-Ranking** | Mobile shopping user click data on recommended items (30 per instance), item features, user interactions.                                         | [Source](http://yongfeng.me/dataset/)                                         |
| **Online Shopping Intention** | 12,330 user sessions (1 year), 10 numerical (page metrics, bounce/exit rates, page values, special day proximity) & 8 categorical attributes (OS, browser, traffic type, visitor type, weekend flag, revenue). | [Source](https://www.kaggle.com/datasets/henrysue/online-shoppers-intention) |
| **Yandex Personalized Web Search** | Large-scale search log dataset with 35M queries from 5.7M users, featuring click-through data and user session information for personalized search ranking. | [Source](https://www.kaggle.com/c/yandex-personalized-web-search-challenge) |

---

## Video Search and Recommendation

User interaction data specifically related to online video platforms.

| Dataset       | Description                                                                                                                                                      | URL                                               |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| **MicroLens** | Micro-video recommendation dataset with 1 billion interactions from 34 million users on 1 million videos, including raw multimodal data (titles, audio, full videos). | [Source](https://github.com/westlake-repl/MicroLens) |
| **KuaiSAR**   | Unified Search And Recommendation dataset from Kuaishou: 5M search actions, 14.6M recommendation events from 25k users over 19 days (8 interaction types).        | [Source](https://kuaisar.github.io/)              |

---

## Video Engagement

Datasets measuring viewer engagement, attention, and emotional response to video content.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **System1's Video Advertisement** | 30K+ video ads with 2.3M emotional annotations across 8 categories, using 5-second clips analyzed for viewer-reported emotional engagement via sliding window techniques. | [Source](https://www.nature.com/articles/s41598-024-76968-9) |
| **Snapchat UGC Short Video** | 90K short videos with multi-modal features (visual, audio, text), measuring engagement via Normalized Average Watch Percentage and Engagement Continuation Rate. | [Source](https://arxiv.org/abs/2410.00289) |
| **Micro-video Engagement** | Large-scale dataset capturing user-video interactions with skip timestamps, providing fine-grained analysis of skip vs. non-skip behaviors on short video platforms. | [Source](https://fi.ee.tsinghua.edu.cn/~gaochen/papers/SIGIR2023.pdf) |
| **EEG-SVRec** | 3,657 user interactions combining EEG brain signals with engagement labels to study affective experiences during video recommendations. | [Source](https://arxiv.org/abs/2404.01008) |
| **Engagement for Online Meetings** | 24 long-form online meetings (~1.5 hours each) with facial recordings and physiological cues for analyzing participant engagement and group dynamics. | [Source](https://arxiv.org/html/2404.04394v1) |

---

## News and Media

Datasets related to news consumption, media recommendations, and content engagement.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **MIND (Microsoft News Dataset)** | Large-scale news recommendation dataset with 1M+ users and 160K+ English news articles, including click logs, impressions, and article content for personalization research. | [Source](https://msnews.github.io/) |
| **ContentWise Impressions** | Interaction logs from an OTT media service with 10M+ impressions, explicit and implicit user feedback, and recommendation context for evaluating recommendation algorithms. | [Source](https://github.com/ContentWise/contentwise-impressions) |

---

## Product and Reviews

Datasets containing product attributes (images, descriptions) and user reviews, often without user activity logs.

| Dataset                             | Description                                                                                                                                 | URL                                                                          |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Amazon Reviews (2023)**           | Expanded version: 571M reviews (1996-2023), 33 categories, 48M items, 30B metadata tokens, standardized splits for benchmarking LLMs.         | [Source](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews)     |
| **M5Product (Video, Audio, Text)**  | Large multi-modal e-commerce pretraining dataset: 5 modalities (image, text, table, video, audio), 6M+ samples, 6,232 categories, varied completeness. | [Source](https://xiaodongsuper.github.io/M5Product_dataset/index.html)       |
| **Tmall reviews**                   | Collection of product reviews from Tmall, Alibaba's B2C platform.                                                                           | [Source](https://tianchi.aliyun.com/dataset/140281)                          |
| **Home Depot Product Search**       | Product search relevance dataset: real customer search terms, products, human-rated relevance scores (1-3), product descriptions/attributes.   | [Source](https://www.kaggle.com/datasets/thedevastator/the-home-depot-products-dataset) |
| **Innerwear**                       | Data scraped from Victoria's Secret and other innerwear retailers.                                                                          | [Source](https://www.kaggle.com/datasets/PromptCloudHQ/innerwear-data-from-victorias-secret-and-others) |
| **Flipkart products**               | Product information scraped from Flipkart.                                                                                                  | [Source](https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products)    |
| **Stanford Datasets (Amazon/Beer)** | Collection including Amazon product data/metadata and BeerAdvocate reviews (ratings, text).                                                 | [Source](https://snap.stanford.edu/data/#amazon)                             |
| **Metacritic Video Games**          | Dataset related to video game reviews or metadata from Metacritic, hosted on Tianchi.                                                       | [Source](https://tianchi.aliyun.com/dataset/144719)                          |
| **Goodreads**                       | Datasets containing book information (metadata) and user reviews from Goodreads.                                                            | [Source](https://mengtingwan.github.io/data/goodreads.html#datasets)         |

---

## Sales and Forecasting

Datasets focused on individual or aggregate sales data, primarily for time-series forecasting tasks.

| Dataset             | Description                                                                                                  | URL                                                                                           |
|---------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| **Wallmart (M5)**   | Hierarchical sales data (unit sales) for 3,049 products across 10 Walmart stores (CA, TX, WI) used in the M5 forecasting competition. | [Source](https://www.kaggle.com/competitions/m5-forecasting-accuracy/)                         |
| **Ecuador Grocery** | Unit sales data (Corporacion Favorita, Ecuador), store/item metadata (type, cluster, family, perishable), transactions, oil prices, events. Favorita Grocery Sales Forecasting competition. | [Source](https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting/data)          |
| **Ukraine ecommerce** | E-commerce sales data from the Fozzy Group retail chain in Ukraine, used for Hack4Retail competition.      | [Source](https://www.kaggle.com/datasets/picklenik/fozzy-group-hack4retail/data)                |
| **Office Supplies** | Dataset related to office supply sales, used for a data mining workshop challenge (DMDA 2023).               | [Source](https://sites.google.com/view/dmdaworkshop2023/data-challenge)                         |
| **Brazilian Drugs** | Sales data for controlled substances (drugs) in Brazil, reported by ANVISA (National Health Surveillance Agency). | [Source](https://www.kaggle.com/datasets/tiagoacardoso/venda-medicamentos-controlados-anvisa) |
| **Indian Sales**    | Sales forecasting dataset for small basket items in India.                                                   | [Source](https://www.kaggle.com/datasets/girishvutukuri/sales-forecasting-for-small-basket?select=train.csv) |
| **Wallmart Sales**  | General sales data from Walmart stores including features like CPI, unemployment rate.                       | [Source](https://www.kaggle.com/datasets/yogesh174/wallmart-sales/data)                         |
| **Montgomery Liquor**| Warehouse and retail liquor sales data (volume, price) from Montgomery County, MD's Department of Liquor Control. | [Source](https://data.montgomerycountymd.gov/Community-Recreation/Warehouse-and-Retail-Sales/v76h-r7br) |
| **Iowa Liquor**     | Monthly Class E liquor sales data (Iowa): store, county (w/ population), item, volume, price, cost, revenue details. | [Source](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy/data)           |
| **Brazil Medical**  | Data on medicine sales in Brazil, potentially including industrialized medicines.                            | [Source](https://www.kaggle.com/datasets/tgomesjuliana/brazil-medicine-sales?select=EDA_Industrializados_202002.csv) |
| **Store Item**      | Demand forecasting dataset tracking sales of 50 items across 10 different stores over 5 years.                 | [Source](https://www.kaggle.com/c/demand-forecasting-kernels-only/)                             |
| **Italian Grocers** | Sales data (receipt-level) from Italian grocery stores for demand pattern analysis.                          | [Source](https://data.mendeley.com/datasets/s8dgbs3rng/1)                                     |

---

## Supermarkets and Grocery

Datasets containing prices and purchases from supermarkets or grocery stores, often with less granular detail.

| Dataset             | Description                                                                                              | URL                                                                                                     |
|---------------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Tesco Data**      | Grocery purchase data from Tesco stores, including loyalty card transactions over several months.          | [Source](https://figshare.com/collections/Tesco_Grocery_1_0/4769354)                                     |
| **Rossman Store**   | Historical sales data for 1,115 Rossmann drug stores across Germany, including promotional info and store details. | [Source](https://www.kaggle.com/c/rossmann-store-sales)                                                 |
| **Polish Grocery**  | Yearly sales data (2018) from a grocery shop in Poland.                                                  | [Source](https://www.kaggle.com/datasets/agatii/total-sale-2018-yearly-data-of-grocery-shop/data)      |
| **UK Gift Shop**    | Online retail transactions (2010-2011) from a UK-based non-store gift shop (UCI dataset).                  | [Source](http://archive.ics.uci.edu/dataset/352/online+retail)                                           |
| **Turkish Drugs**   | Drug sales data from Turkey, potentially monthly sales across provinces.                                   | [Source](https://www.kaggle.com/datasets/emrahaydemr/drug-sales-data)                                   |
| **NYC Shopping**    | Large sales dataset, potentially from retail locations in New York City.                                   | [Source](https://www.kaggle.com/datasets/pigment/big-sales-data)                                        |
| **Mexican Grocery** | Data from a grocery store in Mexico.                                                                     | [Source](https://www.kaggle.com/datasets/martinezjosegpe/grocery-store/data)                              |
| **Vietnam Supermarket** | Sales and inventory snapshot data from a supermarket in Vietnam.                                         | [Source](https://www.kaggle.com/datasets/tienanh2003/sales-and-inventory-snapshot-data)                 |
| **Indian Grocery**  | Transaction and product details for grocery items from Flipkart's Supermart.                               | [Source](https://www.kaggle.com/datasets/aryansingh95/flipkart-grocery-transaction-and-product-details?select=fact_sales_apr1.csv) |
| **Instacart (Market Basket)**| 3 million grocery orders from 200k+ Instacart users, detailing products purchased and sequence of orders. (Kaggle competition focus). | [Source](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)                     |
| **Israeli Grocery** | Grocery purchase data potentially from the Shufersal chain in Israel, possibly scraped product listings. | [Source](https://www.kaggle.com/datasets/arielpazsawicki/kimonaim?select=shufersalist.db)                 |
| **Brazilian store** | Sales data for a chain of stores in Brazil.                                                              | [Source](https://www.kaggle.com/datasets/marcio486/sales-data-for-a-chain-of-brazilian-stores)          |
| **Dominiks Soft drinks** | Weekly scanner data (prices, volume, display/feature ads) focusing on soft drink purchases from Dominick's Finer Foods (Chicago). | [Source](https://www.chicagobooth.edu/research/kilts/research-data/dominicks)                           |

---

## Financial Transactions

Datasets focusing on banking transactions or financial product purchases.

| Dataset                                       | Description                                                          | URL                                       |
|-----------------------------------------------|----------------------------------------------------------------------|-------------------------------------------|
| **Hashed Multimodal Banking Transactions**    | Dataset containing hashed banking transactions and product purchases. | [Source](https://github.com/dzhambo/mbd) |
| **IEEE-CIS Fraud Detection** | 590K+ payment transactions with identity and device features from the IEEE-CIS Kaggle competition for fraud detection research. | [Source](https://www.kaggle.com/competitions/ieee-fraud-detection) |

---

## Fashion

Datasets specific to the fashion industry, including products, styles, and user interactions.

| Dataset             | Description                                                                                                                 | URL                                                           |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| **Indonesian Fashion**| Dataset focusing on fashion items relevant to the Indonesian market or campuses, used for image classification tasks.     | [Source](https://www.kaggle.com/datasets/latifahhukma/fashion-campus) |
| **Diginetica Fashion**| Dataset used in a Codalab competition related to fashion e-commerce, likely involving clickstream or purchase data.       | [Source](https://competitions.codalab.org/competitions/11161) |
| **Dressipi Fashion**| Dataset from fashion styling service Dressipi used in the RecSys Challenge 2022, including session interactions and item features. | [Source](http://www.recsyschallenge.com/2022/dataset.html)     |
| **Fashion-MNIST**   | 70,000 28x28 grayscale images of 10 fashion categories (T-shirt, trouser, pullover, etc.), intended as a MNIST replacement. | [Source](https://github.com/zalandoresearch/fashion-mnist)    |

---

## Cars and Used Cars

Market-level or transaction data related to new and used automobiles.

| Dataset              | Description                                                                                                       | URL                                                                                                               |
|----------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **BLP US Car data**  | Classic dataset (1971-1990) used for estimating demand models (Berry, Levinsohn, Pakes) for US cars, includes prices, shares, attributes. | [Source](https://pyblp.readthedocs.io/en/stable/_notebooks/tutorial/blp.html)                                     |
| **European Car Market** | Dataset containing information (prices, attributes) on the European car market over several years (1970-1999). | [Source](https://sites.google.com/site/frankverbo/data-and-software/data-set-on-the-european-car-market?authuser=0) |
| **Russian Car Market** | Information on car sales in the Russian market.                                                                   | [Source](https://www.kaggle.com/datasets/ekibee/car-sales-information)                                            |
| **German Used Cars** | Dataset detailing used car listings or sales in Germany, often scraped from online platforms.                       | [Source](https://www.kaggle.com/datasets/gogotchuri/myautogecardetails)                                           |
| **Indian Automobiles**| Vehicle sales data for Telangana, India in 2023.                                                                  | [Source](https://www.kaggle.com/datasets/zubairatha/revving-up-telangana-vehicle-sales-2023)                      |

---

## Discrete Economic Choices

Datasets used in structural econometric models of discrete decision-making under uncertainty.

| Dataset              | Description                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Career Decisions of Young Men** | NLSY panel data tracking young men's educational and occupational choices over time, widely used for dynamic discrete choice estimation (Keane & Wolpin 1997). | [Source](https://github.com/lindamaok899/student-project-lindamaok899) |
| **Bus Engine Replacement Data** | Harold Zurcher's bus engine mileage and replacement decisions, the canonical dataset for dynamic discrete choice models (Rust 1987). | [Source](https://www.kaggle.com/datasets/erichschulman/bus1234.csv) |
| **The Discrete Choice Data Bank** | Curated collection of publicly available discrete choice datasets spanning transport, health economics, energy, and consumer behavior. | [Source](https://github.com/alvarogutyerrez/TheDiscreteChoiceDataBank) |

---

## Travel

Data related to travel bookings, transactions, delays, and recommendations.

| Dataset           | Description                                                                                         | URL                                                                 |
|-------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Fliggy Travel** | Travel-related dataset from Fliggy, Alibaba's online travel platform, potentially including bookings or user behavior. | [Source](https://tianchi.aliyun.com/dataset/113649)                 |
| **Fliggy Transfers**| Dataset focusing on transfer-related data within the Fliggy platform, such as connecting flights or ground transport. | [Source](https://tianchi.aliyun.com/dataset/140721)                 |
| **Expedia**       | Hotel booking or search data from Expedia, often used for recommendation or ranking tasks.          | [Source](https://www.kaggle.com/datasets/vijeetnigam26/expedia-hotel) |
| **Trivago Travel**| Dataset released for a RecSys challenge by Trivago, involving user interactions with hotel listings. | [Source](https://recsys.trivago.cloud/challenge/dataset/)           |
| **Airline delay** | Data on airline flight delays, including carriers, origins, destinations, and delay times.         | [Source](https://www.kaggle.com/datasets/sriharshaeedala/airline-delay) |
| **SwissMetro** | Stated preference survey of 1,192 respondents choosing between rail, car, and the hypothetical SwissMetro for intercity travel in Switzerland, a canonical dataset for discrete choice modeling. | [Source](https://biogeme.epfl.ch/data.html) |
| **LPMC (London Passenger Mode Choice)** | Revealed preference dataset of 81K+ trips in London with mode choices (walk, cycle, drive, bus, rail) and detailed trip attributes for transport demand modeling. | [Source](https://biogeme.epfl.ch/data.html) |
| **Chicago TNC Trips** | Publicly released ride-hailing trip records from the City of Chicago, including pickup/dropoff areas, timestamps, fares, and trip durations. | [Source](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p) |
| **Uber Movement** | Aggregated travel time and speed data across major global cities, derived from Uber trip data for urban transportation analysis and planning. | [Source](https://movement.uber.com/) |
| **TrajAir** | General aviation trajectory dataset capturing aircraft operations around a non-towered airport, with recorded trajectories and corresponding weather conditions. | [Source](https://theairlab.org/trajair/) |

---

## Music

Datasets focusing on music listening behavior, sales, and reviews.

| Dataset                 | Description                                                                                                                | URL                                                                 |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **NetEase Music**       | Dataset from NetEase Cloud Music, used in an INFORMS RMP data competition, likely involving listening history or user profiles. | [Source](https://connect.informs.org/rmp/awards/data-competition)   |
| **Spotify**             | Various datasets released by Spotify research, including the Million Playlist Dataset and challenge datasets.                  | [Source](https://research.atspotify.com/datasets/)                  |
| **Bandcamp Music sales**| Dataset containing music sales data (digital/physical) from the Bandcamp platform.                                         | [Source](https://components.one/datasets/bandcamp-sales)            |
| **Yahoo Music Reviews** | User ratings and play counts for musical tracks/artists from the Yahoo Webscope collection (e.g., 1 billion play counts).     | [Source](https://webscope.sandbox.yahoo.com/catalog.php?datatype=c) |

---

## Procurement and Online Auctions

Data from online auction platforms, public procurement processes, or tender databases.

| Dataset              | Description                                                                           | URL                                                                       |
|----------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Online Auctions**  | Collection of datasets related to various online auctions (e.g., eBay, experimental). | [Source](https://www.modelingonlineauctions.com/datasets)                 |
| **Crypto Art**       | Bids and transactions data from the SuperRare crypto art (NFT) platform.              | [Source](https://www.kaggle.com/datasets/franceschet/superrare?select=bids.csv) |
| **Ukraine Procurement**| Public procurement data (tenders, contracts, bidders) from Ukraine's ProZorro system. | [Source](https://www.kaggle.com/datasets/oleksastepaniuk/prozorro-public-procurement-dataset) |
| **Romania Tenders**  | Public tender data from Romania (2007-2016).                                          | [Source](https://www.kaggle.com/datasets/gpreda/public-tenders-romania-20072016) |
| **Art Auction**      | Data from the "Artists for Lahaina" benefit art auction in 2023.                       | [Source](https://www.kaggle.com/datasets/quillen/artists-for-lahaina-2023)  |
| **Used Car Auction** | Listings data from PakWheels, a Pakistani used car marketplace/auction site.          | [Source](https://www.kaggle.com/datasets/asimzahid/pakistans-largest-pakwheels-automobiles-listings) |
| **Bidoo**            | Data from closed penny auctions on the Bidoo platform.                                | [Source](https://www.kaggle.com/datasets/federicominutoli/bidoo-closed-auctions) |

---

## Display Advertising and Sponsered Search Auctions

Bidding logs and ad clickstream data from online advertising platforms.

| Dataset                 | Description                                                                                              | URL                                                                                                                                               |
|-------------------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Ipinyou**             | Real-time bidding (RTB) dataset from Ipinyou for CTR prediction and advertising research.                  | [Source](http://contest.ipinyou.com/)                                                                                                             |
| **Alibaba**             | Advertising dataset from Alibaba (potentially related to sponsored search or display ads).                 | [Source](https://tianchi.aliyun.com/dataset/148347)                                                                                               |
| **Adform**              | Display advertising dataset (impressions, clicks, auction details) hosted on Harvard Dataverse.            | [Source](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/TADBY7)                                                          |
| **Tencent**             | Advertising or algorithm competition data from Tencent (e.g., social ad CTR prediction).                   | [Source](https://algo.qq.com/index.html)                                                                                                          |
| **Outbrain**            | Click prediction dataset based on users' browsing history (page views, ad clicks) provided by Outbrain.    | [Source](https://www.kaggle.com/c/outbrain-click-prediction)                                                                                      |
| **Soso**                | Dataset from the KDD Cup 2012 Track 2, focusing on predicting click-through rates for Tencent Soso search ads. | [Source](https://www.kaggle.com/competitions/kddcup2012-track2/overview)                                                                           |
| **Yahoo**               | Advertising and search log datasets available via Yahoo Webscope (e.g., sponsored search clicks, ad impressions). | [Source](https://webscope.sandbox.yahoo.com/catalog.php?datatype=a)                                                                               |
| **Display Advertising** | Real-time advertiser auction dataset, likely containing bid requests and outcomes.                         | [Source](https://www.kaggle.com/datasets/saurav9786/real-time-advertisers-auction)                                                                |
| **ICPSR**               | Search results for auction-related studies within the ICPSR data archive.                                  | [Source](https://www.openicpsr.org/openicpsr/search/studies?start=0&ARCHIVE=openicpsr&sort=score%20desc%2CDATEUPDATED%20desc&rows=25&q=auction) |
| **Replication Data (Harvard)** | Search results for auction-related replication datasets on Harvard Dataverse.                          | [Source](https://dataverse.harvard.edu/dataverse/harvard?q=auction)                                                                             |
| **Multi-Region MMM eCommerce** | Synthetic multi-region marketing mix modeling dataset with channel spend, impressions, and sales outcomes for evaluating media attribution methods. | [Source](https://figshare.com/articles/dataset/Multi-Region_Marketing_Mix_Modeling_MMM_Dataset_for_Several_eCommerce_Brands/25314841) |
| **Criteo Counterfactual Learning** | 25M logged interactions with counterfactual propensity scores for offline policy evaluation and counterfactual reasoning in display advertising. | [Source](https://ailab.criteo.com/dataset-release-evaluation-counterfactual-algorithms/) |

---

## Healthcare

Datasets related to healthcare pricing, provider utilization, and organ allocation.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **CMS Hospital Price Transparency** | Machine-readable hospital pricing files mandated by CMS, containing negotiated rates, charges, and payer-specific information across US hospitals. | [Source](https://data.cms.gov/provider-characteristics/hospitals-and-other-facilities/hospital-price-transparency-enforcement-activities-and-outcomes) |
| **OPTN Organ Transplant** | Organ Procurement and Transplantation Network data on organ donation, waiting lists, and transplant outcomes across the US. | [Source](https://optn.transplant.hrsa.gov/data/) |
| **Medicare Provider Utilization** | CMS data on services and procedures provided by physicians and other healthcare professionals to Medicare beneficiaries, including utilization and payment information. | [Source](https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners) |

---

## Logistics

Supply-side data focusing on delivery operations, freight, and supply chain management.

| Dataset             | Description                                                                                                                             | URL                                                                                                          |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| **MSOM18**          | Logistics or supply chain dataset from the 2018 MSOM Data Driven Research Challenge (Cainiao Last-Mile Delivery, hosted on Tianchi).       | [Source](https://tianchi.aliyun.com/competition/entrance/231623/information)                                 |
| **MSOM20**          | Dataset from the 2020 MSOM Data Driven Research Challenge (JD.com Logistics, focus on e-commerce fulfillment).                             | [Source](https://connect.informs.org/msom/events/datadriven2020)                                             |
| **MSOM21**          | Dataset from the 2021 MSOM Data Driven Research Challenge (Dmall Fresh Food Delivery).                                                  | [Source](https://pubsonline.informs.org/page/msom/data-driven-challenge)                                     |
| **Amazon Last Mile**| 9,184 historical routes (2018) across 5 US metro areas; route, stop, package features; anonymized IDs/locations. From AWS Open Data challenges. | [Source](https://registry.opendata.aws/amazon-last-mile-challenges/)                                         |
| **LaDe Last-Mile Delivery** | 10.6M+ packages, 619k trajectories, 16.7M+ GPS pings (21k couriers) across 5 cities (6 months), pickup/delivery scenarios.      | [Source](https://arxiv.org/html/2306.10675v2)                                                                |
| **DataCo**          | Widely used synthetic supply chain dataset covering sales, orders, shipping, and returns across multiple regions.                         | [Source](https://tianchi.aliyun.com/dataset/89959)                                                           |
| **Drone Delivery**  | Dataset related to drone delivery logistics or operations, possibly route planning or scheduling (hosted on Tianchi).                   | [Source](https://tianchi.aliyun.com/dataset/89726)                                                           |
| **Brewery Operations**| Dataset covering brewery operations (production, inventory) and market analysis (sales, distribution).                                | [Source](https://www.kaggle.com/datasets/ankurnapa/brewery-operations-and-market-analysis-dataset)           |
| **Shipping and Pricing**| Supply chain data focusing on shipment modes, costs, and pricing across different routes and products (provided by DataCo Global). | [Source](https://catalog.data.gov/dataset/supply-chain-shipment-pricing-data-07d29#:~:text=This%20dataset%20provides%20supply%20chain,data%20are%20particularly%20valuable%20for) |

---

## Driving, Mobility, GPS Traces

Data related to vehicle movement, driving behavior, and GPS tracking.

| Dataset                     | Description                                                                                                                   | URL                                                                                                       |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| **Natural Driving in Ohio** | Data from vehicles equipped with Advanced Driver Assistance Systems (ADAS) recording naturalistic driving behavior and events. | [Source](https://data.transportation.gov/Automobiles/Advanced-Driver-Assistance-System-ADAS-Equipped-Si/iie8-uenj/about_data) |
| **NGSIM**                   | Detailed vehicle trajectory data (position, speed, acceleration) from US highways collected for traffic flow modeling.        | [Source](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj/about_data) |
| **Grab Driving GPS Traces** | GPS trace data (latitude, longitude, timestamp, accuracy) from drivers using the Grab ride-hailing platform in Southeast Asia. | [Source](https://engineering.grab.com/grab-posisi)                                                        |
| **HighD Dataset** | Naturalistic vehicle trajectory dataset recorded from German highways using drones, capturing 110K+ vehicles with high positional accuracy for traffic and lane-change analysis. | [Source](https://levelxdata.com/highd-dataset/) |
| **inD Dataset** | Naturalistic trajectory dataset of road users at German intersections captured by drones, including vehicles, bicyclists, and pedestrians with rich interaction data. | [Source](https://levelxdata.com/ind-dataset/) |
| **100-Driver Naturalistic Driving** | Large-scale naturalistic driving study tracking 100 drivers with continuous sensor data (GPS, accelerometers, cameras) capturing real-world driving behavior and safety events. | [Source](https://100-driver.github.io/) |
| **Round Dataset** | Drone-captured vehicle trajectory dataset from roundabouts in Germany for studying yielding behavior and gap acceptance in complex traffic situations. | [Source](https://levelxdata.com/round-dataset/) |
| **PishguVe Dataset** | Vehicle trajectory dataset providing positional data for driving behavior analysis including lane changes, acceleration, and braking in diverse traffic conditions. | [Source](https://github.com/TeCSAR-UNCC/PishguVe) |
| **T-Driver Dataset** | GPS trajectories of 10K+ taxis in Beijing over one week, widely used for urban computing, route planning, and traffic analysis. | [Source](https://www.kaggle.com/datasets/arashnic/tdriver) |
| **COMPASS Connected Car** | Connected vehicle telemetry data including GPS traces, speed, and driving events from real-world driving sessions in the UK. | [Source](https://data.cdrc.ac.uk/dataset/compass-connected-car-vehicle-trajectories-and-behaviours) |
| **Ithaca365** | Autonomous driving dataset collected along a 15 km route under diverse weather (snow, rain, sun), times (day/night), and traffic conditions with LiDAR and camera data. | [Source](https://ithaca365.mae.cornell.edu/) |
| **Mobile Century Experiment** | 8 hours of GPS data from 100 vehicles on a 10-mile stretch of I-880 in California, collected to validate mobile phone-based traffic monitoring systems. | [Source](https://github.com/ucbtrans/mcdata) |
| **Taxi Trajectory Dataset** | GPS trajectory data from taxi trips (e.g., Porto taxis from ECML-PKDD 2015), providing insights into urban mobility patterns and route optimization. | [Source](https://www.kaggle.com/datasets/crailtap/taxi-trajectory/data) |
| **Citi Bike NYC** | Trip-level data from New York City's bike-sharing system including station locations, trip durations, and user types, updated monthly. | [Source](https://citibikenyc.com/system-data) |

---

## Human Trajectories

Datasets tracking pedestrian and general human movement patterns across various environments.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **OpenTraj** | Benchmark aggregating multiple pedestrian trajectory datasets (ETH, UCY, Stanford Drone, etc.) in a unified format for trajectory prediction research. | [Source](https://github.com/crowdbotp/OpenTraj) |
| **trajdata** | Unified trajectory data loader and API by NVlabs supporting multiple trajectory datasets with consistent formatting for training and evaluating prediction models. | [Source](https://github.com/NVlabs/trajdata) |
| **GeoLife GPS Trajectory** | 17,621 trajectories from 182 users (2007-2012) in Beijing, capturing daily mobility patterns including commuting, shopping, and leisure over three years. | [Source](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/) |
| **GPS Trajectories with Transportation Mode Labels** | GPS trajectory dataset with manually labeled transportation modes (walk, bike, bus, car, subway) for movement pattern classification research. | [Source](https://www.microsoft.com/en-us/research/publication/gps-trajectories-with-transportation-mode-labels/) |

---

## Check-in and Location Data

Datasets capturing user check-ins and location-based interactions at venues and points of interest.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Foursquare Check-in Datasets** | Collection of Foursquare/Swarm check-in datasets including global check-ins (33M+ from 266K users at 3.6M venues), NYC/Tokyo city datasets, and long-term user activity logs for location-based recommendation and mobility research. | [Source](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) |

---

## Housing and Residential Prices

Data on property assessments, house prices, transactions, or rental bookings.

| Dataset     | Description                                                                                                                                     | URL                                                                                                  |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| **AirBnb**  | Global short-term rental listings (6M+), reviews (190M+), pricing, availability calendars, host info, and amenities data compiled by Inside Airbnb. | [Source](http://insideairbnb.com/explore)                                                             |
| **Chicago** | Public data catalog for Cook County, IL, including detailed property assessment values, characteristics, and sales data from the Assessor's Office. | [Source](https://datacatalog.cookcountyil.gov/)                                                      |
| **New York**| NYC Open Data portal, including the Rolling Calendar Sales archive with details on property sales transactions across the five boroughs.          | [Source](https://data.cityofnewyork.us/Housing-Development/NYC-Calendar-Sales-Archive-/uzf5-f8n2/about_data) |

---

## Research Datasets and Collections

Aggregated collections of datasets released by companies or researchers for academic use.

| Collection          | Description                                                                                                                               | URL                                                            |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| **Yahoo**           | Yahoo Webscope program: Diverse datasets including search logs, advertising data, ratings (e.g., music), news clicks, graph data for research. | [Source](https://webscope.sandbox.yahoo.com/)                  |
| **Yelp**            | Dataset including business attributes, millions of reviews, user data, check-ins, tips, and photos from Yelp's platform.                      | [Source](https://www.yelp.com/dataset)                         |
| **Yandex**          | Research datasets released by Yandex, often related to search ranking, translation quality, machine learning tasks, and user behavior.        | [Source](https://research.yandex.com/datasets)                 |
| **Facebook (Meta)** | Research datasets accessible via platforms like the Meta Content Library (1.1B+ public FB/IG posts, engagement metrics, API access) or specific requests. | [Source](https://fort.fb.com/researcher-datasets)              |
| **Microsoft**       | Collection of research tools and datasets released by Microsoft Research across various domains (ML, NLP, vision, systems).               | [Source](https://www.microsoft.com/en-us/research/tools/?)    |
| **Amazon AWS**      | Registry of Open Data on AWS, hosting a wide variety of public datasets across many fields, often analysis-ready.                         | [Source](https://registry.opendata.aws/)                       |
| **Netflix**         | Dataset from the Netflix Prize competition (2006-2009) containing 100M+ anonymous movie ratings from 480k users for 17k movies.           | [Source](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data) |
| **JD.com**          | Open dataset portal provided by JD.com's data science division, potentially including e-commerce, logistics, or advertising data.           | [Source](https://datascience.jd.com/page/opendataset.html)     |
| **Rakuten**         | Data releases from the Rakuten Institute of Technology, including e-commerce, advertising, and multimedia datasets.                         | [Source](https://rit.rakuten.com/data_release/#access)         |
| **IBM**             | Datasets provided by IBM, often related to AI, data science technologies, healthcare, or weather (e.g., IBM Debater, EHR data).            | [Source](https://developer.ibm.com/technologies/artificial-intelligence/data/) |
| **Baidu**           | Datasets released by Baidu Research, often related to AI, NLP (e.g., DuReader), computer vision, autonomous driving (ApolloScape).         | [Source](https://ai.baidu.com/broad/download)                  |
| **AirBnb (Direct)** | Direct link to download raw data files (listings, reviews, calendar) from the Inside Airbnb project.                                      | [Source](http://insideairbnb.com/get-the-data/)               |
| **Yongfeng**        | Personal collection of datasets curated by Yongfeng Zhang, including e-commerce (JD, Alibaba) and recommendation system data.               | [Source](https://www.yongfeng.me/dataset/)                     |
| **Julian McAuley**  | Collection of datasets curated by Julian McAuley's lab at UCSD, strong focus on reviews (Amazon, Yelp), recommendations, and social network data. | [Source](https://cseweb.ucsd.edu/~jmcauley/datasets.html)      |
| **Makridakis**      | Time series data used in the Makridakis Competitions (M1-M5) for benchmarking forecasting methods across various domains (economic, demographic, industry). | [Source](https://forecasters.org/resources/time-series-data/)  |
| **bayesm R Package Datasets** | Collection of marketing and choice datasets bundled with the bayesm R package, including scanner panel data, conjoint studies, and hierarchical Bayes examples. | [Source](https://cran.r-project.org/package=bayesm) |
| **AMiner DBLP Citation Network** | Large-scale academic citation network with 5M+ papers and 36M+ citation relationships extracted from DBLP, ACM, and MAG for bibliometric and network analysis. | [Source](https://www.aminer.org/citation) |
| **LIAR** | Benchmark dataset of 12.8K short political statements labeled with six fine-grained truthfulness ratings, speaker metadata, and context for fake news and fact-checking research. | [Source](https://huggingface.co/datasets/ucsbnlp/liar) |

---

## Competitions

Platforms and conferences hosting data science competitions, often providing unique datasets.

| Platform / Event   | Description                                                                                                       | URL                                                      |
|--------------------|-------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|
| **RecSys Datasets**| Collection of datasets used in the ACM Recommender Systems (RecSys) conference challenges over the years.           | [Source](https://github.com/RUCAIBox/RecSysDatasets)     |
| **NIPS (NeurIPS)** | Top-tier conference on Neural Information Processing Systems, often featuring competitions and benchmark datasets tracks. | [Source](https://nips.cc/)                               |
| **ICJAI**          | International Joint Conference on Artificial Intelligence, hosting various AI competitions and associated datasets. | [Source](https://www.ijcai.org/)                         |
| **MSOM**           | Manufacturing & Service Operations Management society, hosting annual Data Driven Research Challenges with unique industry datasets. | [Source](https://pubsonline.informs.org/journal/msom)    |
| **Data Mining Cups**| Competitions focused on data mining tasks, often sponsored by industry partners.                                    | [Source](https://www.data-mining-cup.com/reviews/)       |
| **KDD Cup**        | Prestigious annual data mining and knowledge discovery competition associated with the ACM SIGKDD conference.       | [Source](https://kdd.org/kdd-cup)                        |
| **Marketing Science**| INFORMS Marketing Science conference/journal, sometimes featuring datasets or data-focused competitions.          | [Source](https://pubsonline.informs.org/page/mksc/online-databases) |
| **Driven Data**    | Platform hosting data science competitions focused on social impact challenges using real-world data.               | [Source](https://www.drivendata.org/)                    |
| **Coda Labs**      | Open-source platform for running data science competitions, benchmarks, and reproducible research.                | [Source](https://codalab.lisn.upsaclay.fr/)              |
| **Open ML**        | Online platform for democratizing machine learning: sharing datasets, tasks, code, and experimental results.      | [Source](https://www.openml.org/)                        |

---

## Gaming

Datasets capturing player behavior, strategy, and engagement in digital games and sports analytics.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Basketball-U, Football-U, Soccer-U** | Player trajectory sequences with xy-coordinates (in yards) from 91 basketball, football, and soccer games each, for multi-agent behavior modeling and sports analytics. | [Source](https://arxiv.org/html/2405.17680) |
| **CS:GO Agent Data** | Gameplay data from Counter-Strike: Global Offensive capturing AI agent decision-making, enemy detection, and movement control for real-time FPS strategy research. | [Source](https://cs230.stanford.edu/projects_fall_2021/reports/102988723.pdf) |
| **StarCraftImage** | 3.6M images compiled from StarCraft II replays summarizing game states in RGB and grayscale formats for analyzing complex multi-agent behaviors in strategy games. | [Source](https://arxiv.org/abs/2401.04290) |
| **Awesome Game Datasets** | Curated list of game-related datasets spanning board games, video games, esports, and game analytics for machine learning research. | [Source](https://github.com/leomaurodesenv/game-datasets) |

---

## Others

Miscellaneous datasets or categories.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **AI4Animation** | Motion capture and physics-based character animation datasets and tools for training neural network controllers for virtual character movement. | [Source](https://github.com/sebastianstarke/AI4Animation) |

*To add a dataset email me.*
