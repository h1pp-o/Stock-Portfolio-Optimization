# Stock-Portfolio-Optimization


## Objective
In this project, we will investigate investment strategies for stocks based on Modern Portfolio Theory (MPT) and momentum trading (MT). We will create a portfolio of stocks that appropriately balances the conflicting risk and profit and compare different investment strategies. 


## Background

#### Modern Portfolio Theory (MPT)
In MPT, our goal is to allocate money into stocks to maximize the expected return while accounting for your risk tolerance, which is measured by volatility. Unfortunately, we cannot optimize two conflicting quantities (profit and risk) simultaneously. Instead, we will take a piecewise approach: for each given risk tolerance ceiling (the max amount of risk we are willing to take on), we will maximize profit for that given risk level. So we will calculate one optimal mix of allocation of stocks that maximizes profit for each risk level; for example, if we evaluate 100 different risk levels, we will have 100 (potentially distinct) allocations. Low-risk levels will have well-balanced and diversified portfolios, but we will probably make less money. High-risk levels will have very skewed/narrow portfolio mixes (like only buying Tesla in our portfolio!), but this can be highly volatile. Our goal is to show the range of profit outcomes we could achieve for all risk levels (the efficient frontier).


#### Momentum trading (MT)
The MT strategy is based on the crossing points of the moving averages. Buy operations are triggered when the 9-day moving average becomes larger than the 21-day moving average, and sell operations are triggered when the 21-day moving average becomes larger than the 9-day moving average.

## Strategy
We will choose the following three sectors: Healthcare, Consumer Staples, Energy
From those sectors we will select three stocks each and create an optimal portfolio that narrows down into three stocks in total.

### Healthcare Sector

#### 1. Cigna (CI)
The Cigna Group is a health insurance and pharmacy benefits management(PBM) company headquartered in Connecticut, United States. The company's market capitalization is currently around 76.907 billion dollars, and its PBM services have been greatly expanded following its merger with Express Scripts in 2018.

#### 2. UnitedHealth Group (UNH)
UnitedHealth Group is a diversified healthcare company which is headquartered in Minnetonka, Minnesota with a market capitalization of 407.752 billion dollars. It provide four segments businesses: UnitedHealthcare, Optum Health, Optum Insight, and Optum Rx. It offers health benefit plans and services, pharmacy care services and programs, software and information products, and outsourcing contracts to various organizations.

#### 3. Abbott Lab (ABT)
Abbott Laboratories is a global healthcare company founded in 1888 and is based in North Chicago, Illinois with a market capitalization of 181.407 billion dollars. Abbott Lab develops and sells healthcare products. It has four segments: Established Pharmaceutical Products, Diagnostic Products, Nutritional Products, and Medical Devices.

### Consumer Staples sector

#### 1. COSTCO (CST)
Costco Wholesale Corporation is a retail company which is headquatered in Issaquah, Washington. COSTCO operates membership warehouses in multiple countries, offering a wide range of branded and private-label products in various merchandise categories. Its market capitalization is 219.466 billion dollars.

#### 2. Kraft Heinz (KHC)
The Kraft Heinz Company is a global food and beverage products manufacturers. Its products includes condiments, sauces, cheese and dairy products, meals, meats, refreshment beverages, coffee, and grocery products. The company is headquartered in Pittsburgh, Pennsylvania and its market capitalization is 48.215 billion dollars.

#### 3. Proctor and Gamble (PG)
Procter & Gamble is a global company that produces consumer packaged goods. Its products include personal care, beauty, grooming, healthcare, fabric and home care, and baby and family care. Its market capitalization is 356.523 billion dollars and is headquartered in Cincinnati, Ohio.

### Energy sector

#### 1. Halliburton (HAL)
Halliburton is a global oil and gas products and service provider in energy industry through two segments: Completion and Production, and Drilling and Evaluation. Halliburton also offers cloud-based digital services and artificial intelligence solutions for subsurface insights, integrated well construction, and reservoir and production management. The company is headquartered in Houston, Texas and its market caplization is 30.51 billion dollars.

#### 2. Baker Hughes Co(BKR)
Baker Hughes Company is a worldwide provider of energy and industrial technology and services, with two operating segments: Oilfield Services & Equipment and Industrial & Energy Technology. The company was incorporated in 2016 and is based in Houston, Texas and its current market capitaliztion is about 31.174 billion dollars.

#### 3. Chevron Corp (CVX)
Chevron Corporation is a US-based company engaged in the production and transportation of crude oil and natural gas, as well as the refining and marketing of petroleum products and chemicals. The company is headquartered in San Ramon, California and its current market capitaliztion is about 323.889 billion dollars.










