# 🛍️ 뷰티 이커머스 리텐션 분석을 통한 구매 유도 마케팅 전략 수립
**팀구성**
데이터리안 SQL 실전반 16기 4인팀
  
**담당 역할** 기여도 35%
- 인기제품 탐색
- 리텐션분석 쿼리 작성
- 리텐션 차트, 커브 시각화 

**사용 툴**
Colab, Pyspark, excel
<img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">:Pyspark Query
<img src="https://img.shields.io/badge/microsoftexcel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">


  **데이터 정보**
  - 출처: [Kaggle] [****eCommerce Events History in Cosmetics Shop****](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop)
  - 수집 기간 : 2019년 10월 ~ 2020년 2월 (5개월)
  - 구성 : 월별 총 5개의 테이블(2019-Oct, 2019-Nov, 2019-Dec, 2020-Jan, 2020-Feb)
  
**최종보고서** 
[[노션 보고서](https://www.notion.so/s-Portfolio-a1cfb21801e94a638b1614be7ad89487?p=c73f7ac7ea83424f8c1d0693da143567&pm=s)]

<aside>
💡 팀구성: 데이터리안 SQL 실전반 16기 4인팀

역할:  Retention 분석, 인기상품 리스트업 쿼리 작성, 결과 시각화, 보고서 작성

기여도: 35%

데이터 수집: 캐글 **[eCommerce Events History in Cosmetics Shop](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop)**

배운점

- 대량의 로그데이터를 다뤄볼 수 있었습니다.
- 문제를 정의하고 가설설정 후 검증하는 일련의 논리과정을 경험했습니다.
- 분석 결과 및 마케팅 전략 제안서를 효과적으로 작성하는 방법을 배웠습니다.
</aside>

  
### 1. **분석 기획 의도**
 N사는 네일 제품을 파는 코스메틱 온라인 쇼핑몰입니다. 2019년 10월 1일에 오픈하여 2020년 2월까지 5개월의 데이터를 수집했습니다. 서비스를 시작한 지 5개월이 지난 지금, 첫 구매 프로모션을 준비하고 기존 고객의 구매를 유도하기 위한 마케팅 전략을 수립하고자 합니다. 

### 2. 분석 목적

1. 전체 고객의 구매 현황을 파악하여 마케팅 타깃을 선정함.
2. 고객들의 구매 로그를 기준으로 구매 주기에 따른 리텐션 분석 진행함.
  
### 3. 보고서 
<img width="725" alt="스크린샷 2024-04-02 오후 9 40 52" src="https://github.com/KYK0328/ecommerce/assets/128811238/ad0698b9-068c-4088-96fb-3ae9a40f0a9a">
<img width="725" alt="스크린샷 2024-04-02 오후 9 41 03" src="https://github.com/KYK0328/ecommerce/assets/128811238/a5ad1b43-d7f9-4de4-8ec6-6c02d76935d5">
<img width="725" alt="스크린샷 2024-04-02 오후 9 41 20" src="https://github.com/KYK0328/ecommerce/assets/128811238/136273b6-33cb-40da-92e7-11b7f6c73dff">
<img width="725" alt="스크린샷 2024-04-02 오후 9 41 27" src="https://github.com/KYK0328/ecommerce/assets/128811238/e123364f-e1a0-4ddd-993e-eb740e4bae1d">
<img width="725" alt="스크린샷 2024-04-02 오후 9 41 37" src="https://github.com/KYK0328/ecommerce/assets/128811238/ae59d0ce-ae13-4892-8c64-5fb56b9653d5">
<img width="725" alt="스크린샷 2024-04-02 오후 9 43 02" src="https://github.com/KYK0328/ecommerce/assets/128811238/b38d7c8d-5a7c-4bb5-b8b6-8897dd254feb">
<img width="725" alt="스크린샷 2024-04-02 오후 9 43 13" src="https://github.com/KYK0328/ecommerce/assets/128811238/d6d10605-e8ce-401c-8b83-369730befd15">
<img width="725" alt="스크린샷 2024-04-02 오후 9 43 21" src="https://github.com/KYK0328/ecommerce/assets/128811238/0b1cb345-4bca-437b-a9c6-6c879df1ab65">
<img width="725" alt="스크린샷 2024-04-02 오후 9 43 30" src="https://github.com/KYK0328/ecommerce/assets/128811238/3944a2b4-8aef-4a6d-9152-1fa520ccc6fd">
