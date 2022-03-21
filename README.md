# 💧GoodPrice 
   #### 실시간으로 각 주유소별 요소수 재고량을 파악할 수 있는 공공 API를 활용한 JavaFX + SceneBuilder 기반 프로그램 
---

* ## __Description__
   요소수 대란으로 발생하는 사회적 이슈 및 불편 사항을 최소화하기 위한 목적으로,<br> 프로그램 사용자에게 각 주유소별 요소수 재고량을 실시간으로 파악할 수 있도록 함
   <br><br>
   ℹ️ 주요 기능
   *  지역별 주유소 검색 기능 
   *  요소수 최저 가격순 및 재고 여부 필터 적용 기능
   *  자주 가는 주유소를 즐겨찾기 목록에 추가할 수 있는 기능

* ## __Getting Started__
   ![Eclipse](https://img.shields.io/badge/Eclipse-6e6e6e.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
   ![Oracle](https://img.shields.io/badge/Oracle-6e6e6e?style=for-the-badge&logo=oracle&logoColor=white)

  1️⃣ 데이터베이스 테이블 생성 
   ```database
   create table urea_table(
   addr VARCHAR2(100),
   code VARCHAR2(100),
   inventory VARCHAR2(100),
   name VARCHAR2(100),
   openTime VARCHAR2(100),
   price VARCHAR2(100),
   tel VARCHAR2(100),
   regDt VARCHAR2(100)
   );

   create table favorite_table (
   addr varchar2(50),
   code varchar2(50),
   inventory varchar2(50),
   name varchar2(50),
   openTime varchar2(50),
   price varchar2(50),
   tel varchar2(50),
   regDt varchar2(50)
   );
   ```
   <br>
   2️⃣ GoodPriceUrea.exe 실행
