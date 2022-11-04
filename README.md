<!-- #🥇 Location Selection of IT Facility for Seniors -->



### 👩‍🎓 시니어 IT 지원 시설 도입 위치 선정 👨‍🎓
***

<br/>

각종 생활이 디지털화되는 현재, 많은 시니어가 겪는 어려움 중 하나가 바로 “디지털 소외감”입니다. 시니어의 74.1%가 키오스크부터 SNS,음식주문, 예매 및 예약, 금융 서비스 , 공공서비스 등 실생활과 밀접한 디지털 서비스에 어려움을 겪고 있습니다. 

키오스크 체험부터 디지털기기를 이용한 게임 그리고 1인 방송 스튜디오가 설치된 **시니어를 위한 복합 IT 체험존**이 현재 서울시에 6곳이 있으며 2025년까지 키오스크 체험존을 66대로 증대할 계획이라고 밝혔습니다.

하지만 높아지는 디지털 교육에 대한 수요, 그리고 점점 커져가는 “1인방송” 에 대한 관심에 비해 서울인구 대비 시니어 맞춤 it 체험존의 시설은 아직 현저히 부족한 현황입니다. IT 교육센터는 양천구와 서초구에만 설치되어있어, 다른 구에 거주중인 노인분들께선 서초구나 양천구로 직접 이동하셔야합니다. 

이에 저희 시소팀은 추후 it체험존을 증대한다면, 서울의 어느 구, 어느 복지센터 및 주민센터에 설치해야하는지를 다양한 데이터들을 분석해 최적의 입지 선정을 해보았습니다.

<br/>
<br/>

## 📪 주소
<br/>

- Data_process Git-hub : [Git Hub 링크 클릭](https://github.com/jennywoon/HomeComingDay.git)
- 브로셔 정리 : [Brochure 링크 클릭](https://neon-hub-f15.notion.site/Homecoming-Day-ef7d1c50568e4adc9ae05af11159197d)
> 브로셔에 뭐했는지 정리 
<br/>


## 🗓 프로젝트 기간 

<br/>

- 2022.07.05 ~ 07.29 (1차) / 2022.08.22 ~ 09.06 (2차 본선) 
> - 07.29 1차 제출 
> - 08.18 본선 진출 확정
> - 09.04 새로 받은 data를 토대로 분석 재진행
> - 09.06 발표 
> - 09.16 3등 수상 
> - 11.10 시상(예정)

<br/>
<br/>

## 🔔 기술 스택  

<br/>

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4ed30666-82d8-4ef7-b859-870e6f12de8a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T062328Z&X-Amz-Expires=86400&X-Amz-Signature=d9ca404bd0b60623358e8180a0642e9be1ad3a77bb304400d1c0fc0df4e4c897&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

<br/>

## 🙆 담당 역할(React)
<br/>

- 공모전 **분석 주제 및 이유 선정**
- Selenium 을 통해 **주민센터 및 복지관 주소 데이터** 추출
- 행정동별 디지털 역량 파악을 위해 **<디지털 정보지수> 데이터** 선정 및 추출
- **교통시설 데이터(버스정류장, 지하철 역사) 데이터** 선정 및 추출
- **보행 노인사고 다발지역 데이터** 선정 및 추출 (* 2차 분석 과정에선 삭제 )
- **SPCA 차원축소** 선정
- **P-median 알고리즘** 선정

<br/>


## 👩🏻‍💻 데이터 선정 및 모델링 과정

### 1. 분석 데이터 선정 및 이유

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8de73dfd-77c3-41dc-9e9d-75b13fb93264/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T080939Z&X-Amz-Expires=86400&X-Amz-Signature=fa07e4e28e1d7c808cded7f9da82933f8be030d64ad6c3375908530456ab1705&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

**[노년기 정보 활용 현황 및 디지털 소외 해소 방안 모색]** 논문을 참고해 **기존에 존재하는 노인복지관 및 주민센터라는 지역자원을 활용**하여 it 지원시설 및 교육을 확충하고자 주민센터 및 복지관의 위치데이터, 시설특성, 동별 주변특성을 반영한 다양한 데이터들을 분석해 최적의 입지선정을 진행했습니다.

- **주최사 제공 데이터**
    - 시니어 문화생활 정보 - 배움터 시설 목록 & 나들이 추천목록
    - 서울시 내국인 보행/비보행 인구데이터
    
- **외부 데이터 이용**
    
    ✔️ **정형데이터** 
    
    - 서울시 주민등록인구 통계 : 시설 이용자 수요 분석을 위해 이용
    - 서울시 병원 데이터 : 주민센터 & 복지관 내 편의시설 수 파악을 위해 이용
    - 서울시 공공도서관 현황 데이터 : 주민센터 & 복지관 내 편의시설 수 파악을 위해 이용
    - **서울시 지하철역주소 데이터** : 교통환경을 고려한 시설 선정 수행을 위해 이용
    - **서울시 버스정류장 좌표데이터** : 교통환경을 고려한 시설 선정 수행을 위해 이용
    - **디지털정보지수 :** 행정동별 디지털 역량수준을 파악하기 위해 선정
        - 2021년 연령대별 디지털 역량 지수 * 행정동 연령대별 인구
        
    
    ✔️ **비정형데이터 ( 셀레니움 )**
    
    - **서울시 주민센터 주소 데이터**
    - **서울시 노인복지관 주소 데이터**
    
    ✔️ **데이터에 대한 고민(❌구하지 못한 데이터 ✅ 대체한 데이터)**
    
    - **시설 데이터**
    > ❌ 주민센터 & 복지관의 공실유무   
    > ☑ (1차) 주민센터에서 운영중인 프로그램 수 & 최대 수용 인원 수 data     
    > ✅ (2차) 주민센터 & 복지관의 연면적 data  
      
    - **인구 특성 데이터**
    > ❌ 행정동별 시니어의 학력 수준   
    > ✅ **[2021 연령대별 디지털 역량 수준 * 행정동의 연령대별 인구]**의 총 합 으로 대체 


<br/>

### 2. 데이터 전처리 및 차원축소

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/97c4d25c-8f1c-4720-a174-da8b09e832f6/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T080826Z&X-Amz-Expires=86400&X-Amz-Signature=8886640f3297008330de910105a50f50d171fef9995d9691960d5f901f860b98&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- **위치 좌표 변환**
    - 시설 주변 대중교통시설 및 편의시설(공원, 배움터, 병원, 도서관) 개수 파악을 위해 주소를 이용해 UTMK 좌표계로 변환했습니다. 
    
- **정규화**
    - 최종 테이블의 데이터를 정규형에 가깝게 하기 위해 정규화를 실시했습니다.

<br/>

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c9e27535-5c4d-4f93-bed3-04a001379514/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T081035Z&X-Amz-Expires=86400&X-Amz-Signature=b2921779ee3ac2b37caa770df9cc67ba92a716444978fcba9960b088c91c891b&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- PCA로 차원축소한 결과(설명력)보다 SPCA(alpha = 0.01) 설명력이 더 좋은 이유로차원축소는 SPCA를 이용해 진행했습니다.

<br/>

### 3. 모델 & 알고리즘 선정

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/93ca97bb-25c7-49a9-8b78-fa4af64ebbb2/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T081039Z&X-Amz-Expires=86400&X-Amz-Signature=ad2c97a24df2bf7b53938098cd22a549e53cc8fddcf6a91bbe7a847bd1e3cb7f&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- SPCA의 주성분으로 2가지 군집화를 진행. 그 중 실루엣 계수와 분산이 좋은 모델을 선정했습니다.
<br/>

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a2e121b5-274a-4ef3-8bdc-ef65d1de6954/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T081140Z&X-Amz-Expires=86400&X-Amz-Signature=6119f042aae89447fcd894894817ae99d169e4a87622237b1e41e93276812f69&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- 군집별의 평균을 상&중&하 로 나누어 점수화. **가장 고득점을 받은 Cluster을 선택**했습니다.
<br/>

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/3ec53267-9614-45bd-8a13-760820218cb7/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T081204Z&X-Amz-Expires=86400&X-Amz-Signature=adf2a9669d020ded3479fd74f32915afa6c06a3bf51414e90adf7a24202b4486&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- [공공시설 입지 선정에 대한 선행 연구](2013)의 **“공공시설을 설치하기 위한 입지선정을 해결 & 거리 활용하는데 있어 P-median 이 최적이다”** 라는 내용에 따라 P-center , UFLP, CFLP 등 다양한 기법 중 P-median 을 선택해 이용했습니다.

<br/>

### 4. 분석 결과

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/93702baa-5a39-485e-8f64-8f02973548aa/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221104T081526Z&X-Amz-Expires=86400&X-Amz-Signature=c67b30441108dbd816b4e30a89cbfe027928af18ad4cc119f8db4120c2ed9f45&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

- 다음과 같은 기준을 통해 최종 선정을 진행했습니다.
    - 각 구에서 P-median의 결과값인 **총 이동거리**가 가장 낮은 곳 기준으로 1차 선정
    - **대중교통 > 시설 연면적 > 주변특성 > 유동인구** 우선 순으로 그 수가 높거나, 해당 구의 평균 이상인 시설로 선정
    - 각 시설 내 IT 지원시설을 설치할 유휴 공간에 대한 데이터가 부재해 **“연면적”데이터로 대체** **시설의 연면적이 크다는 것은 그만큼 추가 시설을 설치할 유휴공간이 있다고 가정*
