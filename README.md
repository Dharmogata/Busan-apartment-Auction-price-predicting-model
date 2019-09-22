
# chanllenge
# Supervised Learning
## Project: Busan-apartment-Auction-price-predicting-model

### Overview

Background

 

There are three main ways to buy a house in Korea.

The 1st way is to choose appropriate apartment through the real estate agents or

the 2nd is to buy an apartment from the constructor.

The 3rd way is to use the real estate auctions.

 

In general, Korean feel difficult it and they think that they cannot even begin to get started.

They are worried that if they make a reckless move without knowing the laws related to the analysis of rights and related to the laws,

they could lose their seed money.

 

Is the real estate auction really difficult and dangerous?

 

Yoon Soohyun(39 old) author of “the 365-month rent account”,

She said in an interview in the Hankook Daily(Korea newspaper) “It is just a misunderstanding and prejudice.”

 

The author argues that the more seed money is lacking, the more we should find a way at auction. 

- An excerpt from the Hankook Ilbo(Korea Newspaper).

 Challenge auction with seed money of 10 million won( 1130.56 won per 1$)... The Monthly Rent rich woman in only Three Years.

http://www.hankookilbo.com/News/Read/201804170416692333

 

Recently, various real estate related financial products such as real estate funds are actively being developed based on diverse data,

and expertise such as the development of high-yield investment products, trust in real estate investment,

evaluation of profitability and management of data is required.

 

The data for this contest was provided by a company that specializes in information services related to real estate auctions.
Infocare Auction(http://www.infocare.co.kr)

 

We hope many people will be interested in the data on apartment auction,

participate in the competition and realize your dream of own house.

 

Description

 

Existing financial institutions have conducted a review based on FICO scores and collateral oriented. On the other side,

The Korean FinTech company, TOGETHER FUNDING, 

predicts winning bid price and aims to provide financial opportunities for top winning bidders with low credit scores or with little collateral.

 

Please make a model to predict the apartment hammer price at this competition.

Together, we determine whether to lend or not based on the hammer price.

The more accurate the model is, the less the loss.

 

Order of auction procedure

flow

 

https://pds.joins.com/news/component/brandnews/201106/08/kumsol_813655_OEC3Kx.jpg


1. Background

 

집을 사는 방법엔 크게 세 가지가 있다. 부동산 중개업소에서 적당한 부동산을 고르거나 청약통장으로 아파트 분양을 받는 게 일반적인 방법이다. 

세 번째 방법은 부동산 경매를 이용하는 것이다. 하지만 부동산 경매는 어려울 것이라고 지레 겁먹고 시작할 엄두조차 내지 못하는 경우가 대부분이다. 

권리 분석과 관련 법규도 잘 모르는 상태에서 어설프게 나섰다간 오히려 종잣돈을 까먹을 수 있다는 우려 때문이다. 정말 부동산 경매는 어렵고 위험하기만 한 걸까. 

‘365 월세통장’의 저자 윤수현(39)씨는 지난10일 한국일보와의 인터뷰에서 “흔히 사람들은 경매에 대해 ‘어렵고 위험하다’고 말하는데 이는 경매에 대한 오해이자 편견일 뿐”이라고 강조했다.

 특히 종잣돈이 없을수록 경매에서 길을 찾아야 한다는것이 저자의 주장이다. -한국일보 인용

종잣돈 1000만원 들고 경매 도전…3년만에 ‘월세 부자’
http://www.hankookilbo.com/News/Read/201804170416692333
 

최근에는 다양한 데이터를 기반으로 부동산펀드 등 다양한 부동산 관련 금융 상품 개발이 활발히 개발되고 있으며, 

고수익 투자상품의 개발 및 부동산 투자신탁 등 전문성과 합리적인 Valuation, 수익방식에 의한 평가, 전문적인 자산관리 등 데이터 기반의 기술이 필요합니다.

 
이번 대회는 13년간 부동산 경매관련 정보서비스 전문 기업을 운영하는
 (주)인포케어옥션(http://www.infocare.co.kr)에서 유료 데이터를 제공하여 주셨습니다. 
많은 분들이 아파트경매 데이터에 관심을 가지고 대회 참여도 하시고 분석을 통해 내집 마련의 꿈을 이루기를 희망합니다.
 

2. Description

 

기존의 금융기관은 일반적으로 경매 낙찰인 대출 시 신용점수 또는 담보물 위주의 평가를 진행합니다. 

 

반면, 한국의 핀테크 기업인 투게더펀딩(TOGETHER FUNDING)은 낙찰가를 예측하여 신용 점수가 낮거나 담보를 가지지 못하는 우수 낙찰인들에게 금융 기회를 제공하려 합니다.

 

이번 대회에서 아파트 경매가를 예측하는 모델을 만들어주세요. 투게더펀딩에서는 낙찰가를 기반으로 대출 여부를 결정합니다. 모델이 정확할 수록 원금 손실이 줄어듭니다. 

 

3. 경매절차 순서도

flow

https://pds.joins.com/news/component/brandnews/201106/08/kumsol_813655_OEC3Kx.jpg

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Template code is provided in the `finding_donors.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `census.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**
- `age`: Age
- `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Number of educational years completed
- `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sex (Female, Male)
- `capital-gain`: Monetary Capital Gains
- `capital-loss`: Monetary Capital Losses
- `hours-per-week`: Average Hours Per Week Worked
- `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**
- `income`: Income Class (<=50K, >50K)
