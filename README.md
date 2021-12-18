# 2021-2 빅데이터 자료구조 웹스크래핑 과제

## 주제
Musinsa 아우터부분 랭킹에서 다른 변수들과 가격과의 관계

## 방법
* [무신사 페이지](https://search.musinsa.com/ranking/best?&mainCategory=002&page=1) - 랭킹 - 아우터부분
* 한 페이지 당 90개, 10페이지 가져오기
* 가격 변수와 다른 변수와의 상관성과 각 변수들의 분포, 브랜드의 독점성 등을 확인하고자 선택

# 과정
1. Webscraping - [관련코드](./12171930_HW_Webscraping.ipynb)
2. EDA - [관련코드](./12171930_HW_EDA.ipynb)

**변수**
|변수명|설명|
|---|--|
|goods|상품이름|
|brand|브랜드|
|price|가격|
|review_count|리뷰 수|
