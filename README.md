# Industry Datasets

A curated list of business datasets from the fields of Machine Learning, Marketing, Economics, Transporation, Operations, and Computer Science.

## Contents

- [General e-Commerce](#general-e-commerce)
- [A/B Tests and Experiments](#ab-tests-and-experiments)
- [Browsing and Search](#browsing-and-search)
- [Video Search and Recommendation](#video-search-and-recommendation)
- [Product and Reviews](#product-and-reviews)
- [Sales and Forecasting](#sales-and-forecasting)
- [Supermarkets and Grocery](#supermarkets-and-grocery)
- [Financial Transactions](#financial-transactions)
- [Fashion](#fashion)
- [Cars and Used Cars](#cars-and-used-cars)
- [Travel](#travel)
- [Music](#music)
- [Procurement and Online Auctions](#procurement-and-online-auctions)
- [Display Advertising and Sponsered Search Auctions](#display-advertising-and-sponsered-search-auctions)
- [Logistics](#logistics)
- [Driving, Mobility, GPS Traces](#driving-mobility-gps-traces)
- [Housing and Residential Prices](#housing-and-residential-prices)
- [Research Datasets and Collections](#research-datasets-and-collections)
- [Competitions](#competitions)
- [Others](#others)

---

## General e-Commerce

Datasets focusing on online retail transactions, customer behavior, and product information.

| Dataset              | Description                                                                                                                                                       | URL                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Brazilian eCommerce** | 100,000 orders (2016-2018) from Olist marketplaces across Brazil, structured in 9 relational tables (customers, orders, payments, products, geolocation, reviews). | [Source](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) |
| **Open CDP**         | Open-source Customer Data Platform by REES46 aggregating omnichannel interactions (web, app, POS) with AI-driven identity resolution and event tracking (14+ types). | [Source](https://rees46.com/en/datasets)                            |
| **JD.com 2014**      | E-commerce dataset from JD.com for the year 2014.                                                                                                                 | [Source](https://www.yongfeng.me/dataset/)                            |
| **JD.com 2020 (MSOM-20)** | Transaction-level data (March 2018) featuring 2.5M customers (457k purchasers) and 31,868 SKUs, emphasizing purchase conversion pathways.                     | [Source](https://connect.informs.org/msom/events/datadriven2020)    |
| **Alibaba Ads (IJCAI-18)** | 6 billion display ad/click logs over 8 days from 100 million users and 70 million items.                                                                     | [Source](https://tianchi.aliyun.com/dataset/147588)                 |
| **Alibaba Mobile (6GB)** | Mobile e-commerce dataset from Alibaba.                                                                                                                          | [Source](https://www.yongfeng.me/dataset/)                            |
| **Coveo Shopping (SIGIR-21)** | Session-based dataset with 30M+ browsing events, featuring query vectors, image vectors, and description embeddings for recommendation and purchase intent tasks. | [Source](https://github.com/coveooss/SIGIR-ecom-data-challenge#how-to-start) |
| **Retail Rocket**    | 4.5-month clickstream dataset with 2.76M events (views, carts, purchases) from 1.4M visitors across 417k items; includes a deduplicated version.                 | [Source](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset?select=events.csv) |
| **Google Merchandise** | Sample dataset from the Google Merchandise Store for Google Analytics analysis.                                                                                  | [Source](https://support.google.com/analytics/answer/7586738#)        |
| **Shopee**           | Dataset from Shopee's Code League competition in 2020.                                                                                                           | [Source](https://www.kaggle.com/datasets/davydev/shopee-code-league-20) |
| **Flipkart**         | Sales dataset from the Indian e-commerce platform Flipkart.                                                                                                      | [Source](https://www.kaggle.com/datasets/iyumrahul/flipkartsalesdataset?select=Sales.csv) |
| **Pakistan e-commerce**| Large dataset covering e-commerce transactions in Pakistan.                                                                                                       | [Source](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset) |
| **Instacart**        | Dataset containing order information from the Instacart grocery delivery service.                                                                                 | [Source](https://mdporter.github.io/DS6030/other/instacart.html#:~:text=,measure%20of%20time%20between%20orders) |

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
| **Amazon Sessions**           | Dataset from the Amazon KDD Cup 2023 challenge focusing on multilingual recommendations based on user sessions.                                      | [Source](https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge) |
| **JD.com Search**             | 170,000 users' real search queries (2021-2022) with multi-channel interactions (clicks, carts, purchases), 987 categories, and exposed candidate lists. | [Source](https://github.com/rucliujn/JDsearch)                               |
| **BestBuy**                   | Data from an ACM SF Chapter Hackathon involving BestBuy data.                                                                                       | [Source](https://www.kaggle.com/c/acm-sf-chapter-hackathon-big/data)         |
| **Rakuten**                   | E-commerce dataset provided for a SIGIR ecom workshop data task.                                                                                    | [Source](https://sigir-ecom.github.io/ecom2018/data-task.html)               |
| **Wayfair Search (WANDS)**    | Largest public e-commerce search relevance dataset: 233k human-annotated query-product judgments, 43k products with 40+ attributes (categories, ratings). | [Source](https://github.com/wayfair/WANDS)                                   |
| **Criteo Display Advertising**| Large datasets (including 1TB click logs) released by Criteo for research on computational advertising and click-through rate prediction.             | [Source](https://ailab.criteo.com/ressources/)                               |
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
| **Alibaba User Behavior 2018**| 649 million user interactions (clicks, carts, purchases) with 25 million items over 9 days in 2017, including click-through rates and dwell times.      | [Source](https://tianchi.aliyun.com/dataset/649)                             |
| **Online Shopping**           | Dataset focusing on online shoppers' intentions, potentially including browsing behavior and purchase outcomes.                                        | [Source](https://www.kaggle.com/datasets/henrysue/online-shoppers-intention) |

---

## Video Search and Recommendation

User interaction data specifically related to online video platforms.

| Dataset       | Description                                                                                                                                                      | URL                                               |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| **MicroLens** | Micro-video recommendation dataset with 1 billion interactions from 34 million users on 1 million videos, including raw multimodal data (titles, audio, full videos). | [Source](https://github.com/westlake-repl/MicroLens) |
| **KuaiSAR**   | Unified Search And Recommendation dataset from Kuaishou: 5M search actions, 14.6M recommendation events from 25k users over 19 days (8 interaction types).        | [Source](https://kuaisar.github.io/)              |

---

## Product and Reviews

Datasets containing product attributes (images, descriptions) and user reviews, often without user activity logs.

| Dataset                             | Description                                                                                                                                 | URL                                                                          |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Amazon Reviews**                  | Expanded 2023 version: 571M reviews (1996-2023), 33 categories, 48M items, 30B metadata tokens, with standardized splits for benchmarking LLMs. | [Source](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews)     |
| **Video, Audio, Text (M5Product)**  | E-commercial multi-modal pretraining dataset with video, audio, and text features for products.                                             | [Source](https://xiaodongsuper.github.io/M5Product_dataset/index.html)       |
| **Tmall reviews**                   | Collection of product reviews from Tmall, Alibaba's B2C platform.                                                                           | [Source](https://tianchi.aliyun.com/dataset/140281)                          |
| **Home Depot**                      | Dataset containing products sold by Home Depot.                                                                                             | [Source](https://www.kaggle.com/datasets/thedevastator/the-home-depot-products-dataset) |
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
| **Ecuador Grocery** | Sales data for grocery items sold at Corporación Favorita stores in Ecuador, used for forecasting competition. | [Source](https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting/data)          |
| **Ukraine ecommerce** | E-commerce sales data from the Fozzy Group retail chain in Ukraine, used for Hack4Retail competition.      | [Source](https://www.kaggle.com/datasets/picklenik/fozzy-group-hack4retail/data)                |
| **Office Supplies** | Dataset related to office supply sales, used for a data mining workshop challenge (DMDA 2023).               | [Source](https://sites.google.com/view/dmdaworkshop2023/data-challenge)                         |
| **Brazilian Drugs** | Sales data for controlled substances (drugs) in Brazil, reported by ANVISA (National Health Surveillance Agency). | [Source](https://www.kaggle.com/datasets/tiagoacardoso/venda-medicamentos-controlados-anvisa) |
| **Indian Sales**    | Sales forecasting dataset for small basket items in India.                                                   | [Source](https://www.kaggle.com/datasets/girishvutukuri/sales-forecasting-for-small-basket?select=train.csv) |
| **Wallmart Sales**  | General sales data from Walmart stores including features like CPI, unemployment rate.                       | [Source](https://www.kaggle.com/datasets/yogesh174/wallmart-sales/data)                         |
| **Montgomery Liquor**| Warehouse and retail liquor sales data (volume, price) from Montgomery County, MD's Department of Liquor Control. | [Source](https://data.montgomerycountymd.gov/Community-Recreation/Warehouse-and-Retail-Sales/v76h-r7br) |
| **Iowa Liquor**     | Data on liquor sales distributions in Iowa, including store, location, item, volume, and price details.      | [Source](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy/data)           |
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
| **Instacart (Supermarket)**| 3 million grocery orders from 200k+ Instacart users, detailing products purchased and sequence of orders. | [Source](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)                     |
| **Israeli Grocery** | Grocery purchase data potentially from the Shufersal chain in Israel, possibly scraped product listings. | [Source](https://www.kaggle.com/datasets/arielpazsawicki/kimonaim?select=shufersalist.db)                 |
| **Brazilian store** | Sales data for a chain of stores in Brazil.                                                              | [Source](https://www.kaggle.com/datasets/marcio486/sales-data-for-a-chain-of-brazilian-stores)          |
| **Dominiks Soft drinks** | Weekly scanner data (prices, volume, display/feature ads) focusing on soft drink purchases from Dominick's Finer Foods (Chicago). | [Source](https://www.chicagobooth.edu/research/kilts/research-data/dominicks)                           |

---

## Financial Transactions

Datasets focusing on banking transactions or financial product purchases.

| Dataset                                       | Description                                                          | URL                                       |
|-----------------------------------------------|----------------------------------------------------------------------|-------------------------------------------|
| **Hashed Multimodal Banking Transactions**    | Dataset containing hashed banking transactions and product purchases. | [Source](https://github.com/dzhambo/mbd) |

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

## Travel

Data related to travel bookings, transactions, delays, and recommendations.

| Dataset           | Description                                                                                         | URL                                                                 |
|-------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Fliggy Travel** | Travel-related dataset from Fliggy, Alibaba's online travel platform, potentially including bookings or user behavior. | [Source](https://tianchi.aliyun.com/dataset/113649)                 |
| **Fliggy Transfers**| Dataset focusing on transfer-related data within the Fliggy platform, such as connecting flights or ground transport. | [Source](https://tianchi.aliyun.com/dataset/140721)                 |
| **Expedia**       | Hotel booking or search data from Expedia, often used for recommendation or ranking tasks.          | [Source](https://www.kaggle.com/datasets/vijeetnigam26/expedia-hotel) |
| **Trivago Travel**| Dataset released for a RecSys challenge by Trivago, involving user interactions with hotel listings. | [Source](https://recsys.trivago.cloud/challenge/dataset/)           |
| **Airline delay** | Data on airline flight delays, including carriers, origins, destinations, and delay times.         | [Source](https://www.kaggle.com/datasets/sriharshaeedala/airline-delay) |

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

---

## Logistics

Supply-side data focusing on delivery operations, freight, and supply chain management.

| Dataset             | Description                                                                                                                             | URL                                                                                                          |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| **MSOM18**          | Logistics or supply chain dataset from the 2018 MSOM Data Driven Research Challenge (Cainiao Last-Mile Delivery, hosted on Tianchi).       | [Source](https://tianchi.aliyun.com/competition/entrance/231623/information)                                 |
| **MSOM20**          | Dataset from the 2020 MSOM Data Driven Research Challenge (JD.com Logistics, focus on e-commerce fulfillment).                             | [Source](https://connect.informs.org/msom/events/datadriven2020)                                             |
| **MSOM21**          | Dataset from the 2021 MSOM Data Driven Research Challenge (Dmall Fresh Food Delivery).                                                  | [Source](https://pubsonline.informs.org/page/msom/data-driven-challenge)                                     |
| **Amazon Last Mile**| Challenges and datasets related to Amazon's last-mile delivery routing and optimization (available on AWS Open Data).                   | [Source](https://registry.opendata.aws/amazon-last-mile-challenges/)                                         |
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

## Others

Miscellaneous datasets or categories.

*To add a dataset email me.*
