# KHUDA 4기 심화 Project - TEAM KHUPANG!

![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=Python&logoColor=white)
<img src="https://img.shields.io/badge/Jupyter%20notebook-F7931E?style=flat-square&logo=Jupyter%20Notebook&logoColor=white"/>
<img src="https://img.shields.io/badge/Kaggle-F9AB00?style=flat-square&logo=Kaggle&logoColor=white"/>
  
- <b> `프로젝트 명` : <고객 빅데이터를 기반한 인사이트 분석과 마케팅 기획> 팀 쿠팡!

- <b> `간단 소개`  : 저희는 "익히 들어 알고 있는 '기업'과 '브랜드'는 과연 ‘데이터 기반의 효율적이고 개인별 맞춤화 마케팅’을 제대로 수행하고 있을까?"라는 질문을 던진 채 프로젝트 구상하기 시작했습니다. 만약 유의미한 결과가 나온다면, 왜 그렇고, 어떻게 해결할 수 있으며, 누구(어떤 기업)와 함께 할 수 있는지를 고민했습니다. <br><br>   기업 데이터에는 상품, 고객, 매장 정보, 위치 등 다양한 특성이 반영되어야 합니다. 이번 프로젝트는 기업에서 제공하는 데이터들의 변수 관계를 파악하고, 여러 가지 분석 기법을 적용해보는데 목적이 있습니다. 따라서 당장에 어떤 결과물이나 내세울 만한 서비스는 없는 것이 현실입니다. 다만 그 '과정'과 '인사이트 도출'에 집중을 했습니다. <br><br> 대신 단순 기법만 적용해보는 건 재미가 없잖아요?? 그래서 저희는 적용한 분석 기법을 토대로 특정 마케팅 혹은 전략적 인사이트를 얻었다면, 이를 바탕으로 해당 기업에게 새로운 방식과 전략을 제안해보고자 합니다. 데이터 분석 분야에 관심이 많으신 분들이라면 한 번쯤 접할 법한 방법론들이고, 개발보다는 방법론 쪽에 치우쳐 있기 때문에, 장차 해당 분야에 진출하고자 하는 이들에게도 또다른 도움이 되리라 기대합니다!

- <b> `프로젝트 기간` :  2023.11.10 ~ 2023.12.05(대면 + 비대면 미팅 > 총 6회!)
  
<br> 

## ✍🏻 Code
![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=Python&logoColor=white) <br>

#### 이모지와 태그별 사용 경우
| Code | Description | Key analysis |
| :--: | :--: | :--: |
| KMeans | 고객 요인 별 segment 분류 | K-means clustering |
| RFM | 고객등급 별 segment 분류 | RFM 등급 분류 |
| ANOVA | 분산 분석 + 사후 분석 | 요일, 나이, 주문 수에 다른 ANOVA 분석 |

<br> 

## 🔍 Preview

#### 1. 기본 가설 설정
1) (TOTAL_ORDERS)주문 수가 많은 사람은 총 구매액 (REVENUE)이 높을 것이다.  
2) 마지막 주문으로부터 ##일 이상 지난 사람은 주문 수(TOTAL_ORDERS)가 적을 것이다.  
3) (AVGDAYSBETWEENORDERS) 평균 주문 간격이 짧은 사람은 주문 수(TOTAL_ORDERS)가 많을 것이다.  
4) 평균 배송 금액이 높을 수록 총 주문 수는 낮을 것이다.  

#### 요일별 가설 설정

주문과 매출의 요일별 양상은 똑같으며, 대략적으로    
(목 -> (금, 일) -> 수 -> 화 -> (월, 토)) 순으로 활발함  
1) 주문 빈도 or 총 주문액 or 주문 횟수가 많은 사람은 특정 요일에 더 많이 구매하는 경향이 있다. (+ 역)

### 주차별 가설 설정
1) 목요일의 높은 매출은 마지막 주의 높은 매출 때문이다. (월급날?)

![output](https://github.com/leejoon2067/TEAM-KHUPANG/assets/77916205/054c4348-52ae-4e6e-88f7-3045f47c037f)

![output](https://github.com/leejoon2067/TEAM-KHUPANG/assets/77916205/a9c27d70-f8fb-496b-917f-d424833fb9e4)


### dataset
[e_commerce_sales.zip](https://github.com/leejoon2067/TEAM-KHUPANG/files/13564162/e_commerce_sales.zip)

<br>

## 🙌 Welcome to Our Notion!
https://www.notion.so/KHUDA-KHUPANG-33be32cc5dee4455ba2b4c2aa4deed52?pvs=4

<br>

## 🧑🏻‍💻 역할 분배
---- Member List ---- <b>
#### 김기범, 김건형, 김채령, 이준혁, 조수현, 한채연 <br>

<br>

| NAME | github | Part |
| ------ | -------- | ----------------	|
| 이준혁 | [See GitHub Profile](https://github.com/leejoon2067) | 아이디어 빌딩, 데이터 마이닝, 최종 ppt, github 및 notion 운영(PM) |
| 김기범 | [See GitHub Profile](https://github.com/minpedco1) | 아이디어 빌딩, 데이터 전처리 및 시각화, 데이터 마이닝 |
| 김건형 | [See GitHub Profile](https://github.com/GU-0) | 아이디어 빌딩, 데이터 전처리, AirFlow 활용 크롤링, 데이터 마이닝 |
| 김채령 | [See GitHub Profile](https://github.com/riela77) | 아이디어 빌딩, 데이터 전처리 및 시각화, 발표 |
| 조수현 | [See GitHub Profile](https://github.com/SOOsuhyuncho) | 아이디어 빌딩, 데이터 전처리 및 시각화, ppt |
| 한채연 | [See GitHub Profile](https://github.com/chaeyeonni) | 아이디어 빌딩, 데이터 전처리 및 시각화, rfm 분석, 최종 ppt |

<br>

## reference
https://www.slideshare.net/leoyang991/ss-90038927?utm_source=br <br>
Ga-Eul Kim 외, "Marketing Strategy in The Era of Fourth Industrial Revolution: Amazon",2019.
Min JIHONG, "The Effects of Consumer's RFM Purchase History on the Next Purchase Timing in the e-business industry", 201.5

