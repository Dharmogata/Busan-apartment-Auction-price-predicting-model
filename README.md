
# Tech chanllenge
# 부산 지역 아파트 경매가 예측 모델링
# Supervised Learning
## Project: Busan-apartment-Auction-price-predicting-model

### Overview
 

#### 1.Background

 


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

 


#### Description

 


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

Template code is provided in the `Predicting hammer price of apartment in Busan.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `auction_master_train.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for users to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `Predicting hammer price of apartment in Busan/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Predicting hammer price of apartment in Busan.ipynb
```  
or
```bash
jupyter notebook Predicting hammer price of apartment in Busan.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

You are provided about 2,700 auction apartments information for 2 years in Seoul and Busan, Korea. with various data tables,

including registration, rent, appraised price, number of miscarriage, location information, hammer price, etc.

The main mission(goal) is to predict the hammer price of given apartments.

 

* You can use external data(public data) that is not subject to legal restrictions such as ‘The Apartment Real Transaction Price of the Ministry of Land,

Infrastructure, and Transport’ (http://rt.molit.go.kr).

 

Submissions are evaluated with a cost function, using the following Root Mean Squared Error(RMSE). (Evaluations are based on provided datasets only.)

 


**code book**
1. Auction_master_train_en.csv – Basic information such as the location, appraiser, and the start/end date of the auction including the hammer price of the Seoul/Busan area (*last 2 years).

2. Auction_master_test_en.csv – Same with train.csv except for hammer price data. 

3. Auction_submission_en.csv – Fill in with predicting hammer price.

4. Auctiuon_regist_en.csv – a certified copy of the register on apartments.

 

*The registration information may be missing if any of the following occurs during an individual auction.


    a. If all registration of items are the same (only one is issued). 

b. If it is difficult to issue a copy of the registration due to excessive registration (for example, if you cannot issue a certified copy of the registration due to too many registered creditors, owners, etc.).

 

*Individual auction: Case of auction is held with multiple items for one event number.

 

*Excessive registration : Case of the number of registered persons exceeds 100. 

 

5. Auctiuon_result_en.csv – Auction date, appraised price, minimum sales price, auction result, etc.

6. Auctiuon_rent_en.csv – Data such as rent, transfer/ownership, deposit, and monthly rent, etc.

 

Term auction (Refer to below URL.)

(https://www.courtauction.go.kr/RetrieveAucTermInq.laf)


**features**


Auction_master_train.csv

Auction_key

경매 아파트 고유 키값

Auction_class

경매구분 강제경매 : 법원에 소송을 제기하여 판결을 얻은 후 집행권원에 따라 경매를 진행 임의경매 : 등기부등본 담보권(저당권, 가압류등)으로 경매를 진행 http://www.xn--289al3wfvfg7fo3dqso.com/?c=35/164/169/168&where=subject%7Ctag&keyword=%EC%9E%84%EC%9D%98&uid=913 http://www.goodmorningcc.com/news/articleView.html?idxno=50150

Bid_class

입찰구분(일반/개별/일괄)

Claim_price

경매 신청인의 청구 금액

Appraisal_company

감정사

Appraisal_date

감정일자

Auction_count

총경매횟수

Auction_miscarriage_count

총유찰횟수

Total_land_gross_area

총토지전체면적(㎡)

Total_land_real_area

총토지실면적(㎡)

Total_land_auction_area

총토지경매면적(㎡)

Total_building_area

총건물면적(㎡)

Total_building_auction_area

총건물경매면적(㎡)

Total_appraisal_price

총감정가

Minimum_sales_price

최저매각가격, 입찰 시 입찰인이 최저로 제시해야만 하는 금액

First_auction_date

최초경매일

Final_auction_date

최종경매일

Final_result

최종결과

Creditor

채권자, 경매 신청인

addr_do

주소_시도

addr_si

주소_시군구

addr_dong

주소_읍면동

addr_li

주소_리

addr_san

주소_산번지 여부(Y/N)

addr_bunji1

주소_번지1

addr_bunji2

주소_번지2

addr_etc

주소_기타주소

Apartment_usage

건물(토지)의 대표 용도

Completion_date

준공일

Preserve_regist_date

보존등기일, 건물을 신축하고 처음으로 등기

Total_floor

총층수

Current_floor

현재층수

Specific

기타_특이사항

Share_auction_YorN

지분경매 여부(Y/N), 하나의 부동산이 전체가 아닌 일부만 경매가 진행 (하나의 부동산의 공유자가 지분으로 소유권을 가지고 있을 때 그중 일부 지분만 경매가 진행)

road_name

도로명주소_도로명

road_bunji1

도로명주소_번지1

road_bunji2

도로명주소_번지2

Close_date

종국일자

Close_result

종국결과, 낙찰과 배당의 차이 : 경매 진행은 ①경매진행(낙찰) ▷ ②낙찰허가결정 ▷ ③대금납부 ▷ ④배당 후 종결 로 이뤄집니다. 낙찰자가 최고가로 입찰(①)해서 낙찰허가(②)를 받으면 대금납부기한 낙찰금을 입금(③)합니다. 법원은 납부된 낙찰금을 가지고 채권자에게 순위에 의한 배당(④)을 해주고 경매는 종결됩니다.

point.y

위도

point.x

경도

Hammer_price

낙찰가

Auction_result.csv

Auction_key

아파트 경매 물건 고유 키값

Auction_seq

키_Sequence

Auction_date

경매일자

Appraisal_price

감정가

Minimum_sales_price

최저매각가격, 입찰 시 응찰인은 최저매각가격 이상 제시

Auction_results

경매결과 변경 : 특별한 사유로 인하여 지정된 경매일에 경매를 진행 할 수 없을 때 법원이 직권으로 경매일정을 변경하는 절차 유찰 : 경매일에 낙찰되지 않음 낙찰 : 최고가 입찰 대납 : 낙찰 후 낙찰허가결정이 나면 대금을 납부 배당 : 납부된 대금으로 채권자의 순위에 따라 돈을 배당

낙찰과 배당의 차이 : 경매 진행은 ①경매진행(낙찰) ▷ ②낙찰허가결정 ▷ ③대금납부 ▷ ④배당 후 종결 로 이뤄집니다. 낙찰자가 최고가로 입찰(①)해서 낙찰허가(②)를 받으면 대금납부기한 낙찰금을 입금(③)합니다. 법원은 납부된 낙찰금을 가지고 채권자에게 순위에 의한 배당(④)을 해주고 경매는 종결됩니다.

Auction_regist.csv

Auction_key

경매 아파트 고유 키값

Auction_seq

키_Sequence

Regstration_type

등기종류(토지, 건물, 집합) 건물등기 : 일반부동산의 건물등기 토지등기 : 일반부동산의 토지등기 집합건물등기 : 아파트 등 집합건물의 등기 토지별도등기 : 집한건물은 토지와 건물이 일체가되어 거래되야하는데 건물을 짓기 전 토지에 저당권이 있을 경우 토지와 건물의 권리관계가 일치하지 않으므로 건물등기부에 “토지에 별도등기가 있다”는 표시를 하기위한 등기

Regstration_class

등기구분, 가등기 : 본등기의 순위보전을 위하여 하는 예비등기 보전처분 : 다툼이 있는 권리를 보전하기 위하여 소송이 확정되기 전 까지 법원에서 명하는 잠정적인 처분 가압류, 가처분: 보전처분으로 금액에 대한 강제처분을 가압류, 행위에 대한 강제처분을 가처분이라고 함 소유이전, 이전: 계약등의 이유로 소유권이 이전 압류 : 국가기관이 강제로 채무자의 재산처분이나 권리행살등을 못하게 하는 것. 예)체납 세금으로 인한 압류 예고등기 : 등기원인의 무효 또는 취소등으로 등기가 말소 또는 회복의 소가 제기된 경우 이를 제3자에게 경고하기 위하여 하는 등기 임의, 강제 : 임의경매나 강제경매 신청시 이뤄지는 등기 임차권 : 임차권등기명령으로 인한 임차 등기 저당 : 일반적으로 채권자가 부동산을 담보로 돈을 빌려줄 때 부동산에 하는 등기 전세권 : 전세권자가 하는 등기 질권 : 채권자가 채권의 담보로 받은 담보물권

Regist_date

등기일, 토지 별도 등기인 경우 99999999 코드로 분류

Creditor

등기부등본에 등재된 채권자

Regist_price

등기금액, 등기부등본 상의 부동산을 담보로 한 차입금

Auction_rent.csv

Auctiuon_key

경매 아파트 고유 키값

Rent_class

임대차구분, 전입 : (동사무소에)전입신고한 일자 점유 : 임대차기간이거나 실거주자가 있을 경우

Purpose_use

임차인의 임차 용도

Occupied_part

점유인의 점유부분

Rent_date

임차일자, 전입신고일, 점유일이 불확실할 시 11111111

Rent_deposit

임차금액(보증금)

Rent_monthly_price

임차금액(월세)

Specific

특이사항 조사서상: 법원 직원이 현상조사서, 물건명세서 작성한 서류상의 기록
