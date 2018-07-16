---
layout: post
title: "Professional Experience"
description: "This is a post which shows the details of my professional experience including research and work internship."
---

Below are my main research experiences. The events are ranked in time order.

## APEX Lab

- time: Feb 2018 - July 2018
- Professor: Weinan Zhang
- Topic: Looking into the Future Directions: Deep Reinforcement Learning methods on Portfolio Management regard to Actor-Critic Framework
- Tag: Reinforcement Learning, Portfolio Management, Finance
- Background: Financial portfolio management is the art and science of making decisions about investment mix and policy, matching investments to objectives, asset allocation for individuals and balancing risk against performance. Based on the foundation of the reinforcement learning framework, the agent, which can adaptively explore the financial market environment without any assumptions  and knowledge on the distribution of the data, is able to manage the portfolio in order to achieve best return at the current time step. However, an intensive observation reveals that, if only concerning about the immediate return at the current time step, it will lead to the result of an unstable trading strategy, thus gaining high transaction cost and slippage in profits.
- Work:
  1. We propose an indicator optimization model to achieve better indicators’ performance by integrating stock-wise distinct properties.
  2. In order to represent stock with different properties, we learn the stock embedding based on the collective behaviors of the fund managers.
  3. We conduct experiments on real world stock data and evaluate the effectiveness of new indicator optimization approach by practical metrics employed in real investing strategies.

## Microsoft Research Asia

- time: Nov 2017 - Feb 2018
- Professor: Jiang Bian
- Topic: Individualized Indicator for All: Stock-wise Technical Indicator Optimization with Stock Embedding.
- Tag: Stock Embedding, Finance
- Background: In this paper, we propose a novel idea to optimize technical indicator with stock-wise properties. In particular, we design a Technical Trading Indicator Optimization(TTIO) framework that manages to optimize the original factor concerning stock’s specific properties. We propose a Skip-gram architecture to learn stock embedding from a valuable knowledge repository formed by fund manager’s collective investment behaviors. Based on the learned stock representation, we further propose to learn a rescaling network to optimize the indicator’s performance.
- Work:
  1. We propose a enhanced deep reinforcement learning model regard to Actor-Critic framework for portfolio management. The model is designed to obtain a robust trading strategy considering various challenges in financial market.
  2. A training algorithm based on deterministic policy gradient with the portfolio vector memory is introduced for explorations and maximizing returns.
  3. We conduct experiments on real world stock data and evaluate the effectiveness of our model framework. Compared with original model-based portfolio management strategies and existing reinforcement learning policies, the experiment results show that our proposed model can significantly improve the performance of the investment.

## Microsoft Research Asia

- time: July 2017 - Nov 2017
- Professor: Jiang Bian
- Topic: Confidence-based Dynamic Calibration of Investment Indicator for Portfolio
  Construction.
- Tag: Calibration, Finance
- Background:  In this paper, we propose a confidence based calibration approach for dynamic portfolio construction. The major intuition behind is to tune a more concentrated portfolio when the indicator yields higher confidence otherwise a relatively equal-weighted one. In order to seek a maximized long-term profit, we further propose to integrate learning the confidence (i.e., future effectiveness) of an indicator into a unified portfolio construction approach powered by a recurrent reinforcement learning framework.
- Work:
  1. To construct portfolios with dynamic concentration based on the indicator confidence, we design a
     confidence-based calibration approach specified by a soft-max operation for jointly adjusting the indicator scores of assets and generating the investment distribution accordingly.
  2. To predict the dynamic confidence of the indicator, we recognize historical effectiveness of the indicator as a golden mine to provide invaluable information. To better leverage such information, we propose a multi-layer perceptron based confidence prediction model by comprehensively considering multiple metrics of effectiveness in various time window.
  3. To integrate this confidence modeling into the unified optimization for consecutive portfolio constructions, we introduce a recurrent reinforcement learning framework to maximize the risk-adjusted return of the long-term investment, which can implicitly and simultaneously learn the unified optimal confidence as well as controls the transaction cost.

## Institute of Distributed Computing

- time: Mar 2017 - July 2017
- Professor: Ruonan Rao
- Topic: Stock Index Futures Predictions Based on Reinforcement Learning.
- Tag:Reinforcement Learning, Finance
- Background: Can we train the computer to beat experienced traders for financial asset trading? In this project, we try to adress this problem by introducing the Actor-Critic network for real time financial signal representation and trading.
- Work:
  1. Design the actor-critic reinforcement trading model representing the stock index futures’ rewarding and decision-making model.
  2. Implement the deep recurrent neural network mapped to time-sequence presented trading data.
  3. Fuzzy extensions to reduce certainties by importing the fuzzy sets. Different membership functions are confirmed through k-means clustering.

## Police Economic Investigation Station

- time: Oct 2016 - Mar 2017
- Professor: Xiaoying Gan
- Topic: An efficient parsing tools for cellphone files.
- Tag: Parsing, crawler, work internship
- Link:<https://github.com/Elitack/JZData>
- Background: There is a tool which can parse the contents of the cellphone into XML files. From the XML file we can get the data like: contacts, wechat chat log, etc. But in order to do the data analysis, first we need to parse the xml file and design a website that anyone from the branch of the police economic Investigation station can easily transfer the data and import the data into the database.
- Work:
  1. Design a basic crawler to crawl the needed information from the xml file.
  2. Use the django framework to develop a website:
     - Import the data into the database.
     - Transfer the data into a zip file and offer it to the person who uploads the file.
     - Present some useful information on the website.

## Intelligent Networking Center

- time: Oct 2016 - Mar 2017
- Professor: Xinbing Wang
- Topic: Designing the Paper Similarity Network Using the Meta-Path-Based Similarity Search.
- Tag:Similarity, Academy
- Link:[http://acemap.sjtu.edu.cn](http://acemap.sjtu.edu.cn/)
- Background: Paper Similarity can effectively reflect the relativity between 2 different papers. We define that 2 objects are similar if they are referenced by similar objects. In normal way, the similarity rank is achieved through SimRank, which cost a lot of time and space. However, the meta-path based method is proposed to solve this problem.
- Work:
  1. The conceptions of network schema are implemented to describe the meta structure of the paper network.
  2. Decrease the time complexity based on the random walk algorithm.
  3. Successfully applied Pathsim measuring the similarity in the heterogeneous network.

## Institute of Distributed Computing

- time: Oct 2016 - Mar 2017
- Professor: Ruonan Rao
- Topic: Highly Scalable Finance Data Acquisition System.
- Tag: Crawler, Distribute
- Link:<https://github.com/Elitack/Distributed-Crawler>
- Background: Equity analysis is pretty significant nowadays. So in oder to get enough data for equity analysis, we need to crawl the data from the financial website. But most of the financial websites have some anti-crawler measures. So we need to develop an efficient data acquisition system to crawl the needed data.
- work:
  1. Implement the crawling process based on phantomjs and webdriver due to the dynamic ajax website.
  2. Design the proxy pool by crawling some popular ip offered websites to avoid the image captcha. Refresh the whole proxy pool in a certain time at the backstage.
  3. Construct the distributed crawler based on the master-slave model. One machine functioned as master uses the redis database and schedule different crawling target websites to different slave machines. The slave machines grab the proxy ip and the target website then start crawling.

## Institute of Distributed Computing

- time: Apr 2016 - Oct 2016
- Professor: Ruonan Rao
- Topic: Agile Development of the Enterprise Movie Web Application based on Container Cloud.
- Tag: Web, Docker, Project
- Link: <https://github.com/elitack/MovieManagement>
- Background: Docker, as an efficient integration application, is suitable for many situations like crawler. Also varies types of movies are mixed together so that we need a strong and convenient movie manage platform .
- Work:
  1. Crawl the relevant website using the Scrapy framework.
  2. Implement the multi-process crawler by packing the crawler into docker.
  3. Build the website by using the Django back-end framework and the Bootstrap front-end framework.

## State Energy Smart Grid R&D Center

- time: Oct 2015 - Apr 2016
- Professor: Ping Yi
- Topic: Routing and Scheduling Renewable Energy in Electric Vehicle Energy Transmission Networks.
- Tag: Algorithm, Energy Internet, Research
- Background: Energy Internet is a hot topic aiming at constructing a network that enables the transmissions of the energy just like the internet. In the past years, many researchers develop some algorithms to properly distribute the energy. But in reality, some factors need to be considered like what if the energy is not sufficient. Also, all algorithms are proposed in a static distribution mode. But in fact, it should be a dynamic situation.
- Work:
  1. Introduce the electronic vehicle(EV) dynamic energy network under the background of energy internet.
  2. Develop a new algorithm termed *balanced stream algorithm* to schedule energy from sources to charge stations in no sufficient energy condition. The algorithm is compared with some other proposed algorithms. Simulations show that both algorithms have their effectiveness.
  3. Simulate and compare the balanced stream algorithm and the Multi-source shortest route algorithm by using transport data of Manhattan bus lines in New York and the bus map of the Pioneer Valley Transit Authority(PVTA).