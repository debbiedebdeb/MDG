<!-- #🥇 Location Selection of IT Facility for Seniors -->



### 👩‍🎓 시니어 IT 지원 시설 도입 위치 선정 👨‍🎓
***

<br/>

과학기술정보통신부의 *[2021디지털정보격차 실태조사]*에 따르면 고령층(55세 이상)의 정보화 수준이 가장 낮습니다. 이를 통해 저희 조는 고령층이 급변하는 디지털 환경에 적응하지 못하고, 이는 디지털화되가는 실생활 서비스 및 문화 서비스 부분에서 시니어분들이 충분히 즐기지 못하고 있다 판단했습니다. 

서울시의  **시니어를 위한 복합 IT 체험존 현황의 경우**, 양천구 1개 & 서초구 5개 시설만이 설치되어있습니다. 2025년까지 체험존을 증대할 계획이라고 밝힌 서울시의 정책에 따라, 추후 IT체험존을 증대한다면, 서울의 어느 구, 어느 복지센터 및 주민센터에 설치해야하는지를 다양한 데이터들을 분석해 최적의 입지 선정을 해보았습니다.

<br/>

## 🗓 프로젝트 기간 

<br/>

- 2022.07.05 ~ 07.29 (1차) / 2022.08.22 ~ 09.06 (2차 본선) 
> - 07.29 1차 제출 
> - 08.18 본선 진출 확정
> - 09.04 새로 받은 data를 토대로 분석 재진행
> - 09.06 발표 
> - 09.16 3등 수상 
> - 11.10 시상
> <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/624d1773-b430-491c-813f-b2da4182550c/%EB%AC%B8%ED%99%94%EA%B2%BD%EC%A7%84%EB%8C%80%ED%9A%8C_%EC%83%81%EC%9E%A5.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221114%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221114T042301Z&X-Amz-Expires=86400&X-Amz-Signature=b1c3dfd4b00279e79c276bd938f5f654013a285106f59d4ac5392d7c8b688c9c&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22%25EB%25AC%25B8%25ED%2599%2594%25EA%25B2%25BD%25EC%25A7%2584%25EB%258C%2580%25ED%259A%258C%2520%25EC%2583%2581%25EC%259E%25A5.jpg%22&x-id=GetObject">

<br/> 

## 🙆 Skills

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4ed30666-82d8-4ef7-b859-870e6f12de8a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221114%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221114T041106Z&X-Amz-Expires=86400&X-Amz-Signature=af1fead109ad56b01394a7903a8fd885a6aae19d26f4010d126487a6d569c05f&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

<br/>


## 🙆 담당 역할
<br/>

- 공모전 **분석 주제 및 이유 선정**
- Selenium 을 통해 **주민센터 및 복지관 주소 데이터** 추출
- 행정동별 디지털 역량 파악을 위해 **<디지털 정보지수> 데이터** 선정 및 추출
- **교통시설 데이터(버스정류장, 지하철 역사) 데이터** 선정 및 추출
- **보행 노인사고 다발지역 데이터** 선정 및 추출 (* 2차 분석 과정에선 삭제 )
- **SPCA 차원축소** 선정
- **P-median 알고리즘** 선정

<br/>


## 👩🏻‍💻 분석 과정

### 🔧 데이터 선정 의사결정

| 데이터 | 사용처리 | 수집방법 |
| --- | --- | --- |
| 서울시 시니어 배움터 데이터 | 주민센터 및 복지관 주변 기존 시니어를 위한 배움시설 수를 파악하기 위해 사용  | 주최사 제공  |
| 서울시 공원 데이터  | 주민센터 및 복지관 주변 공원의 수를 파악하기 위해 사용  | 주최사 제공  |
| 대도시 내국인 보행/비보행 인구데이터 | 주민센터 및 복지관이 위치한 행정동의 유동인구 파악을 위해 사용 | 주최사 제공  |
| 서울시 주민등록인구 통계 | 행정동의 시니어 비율 및 시니어 인구 수 파악을 위해 사용  | 공공데이터 사이트 |
| 서울시 병원 데이터 | 주민센터 및 복지관 주변 병원 개수를 파악하기 위해 사용   | 공공데이터 사이트 |
| 서울시 공공도서관 현황 데이터 | 주민센터 및 복지관 주변 도서관 개수를 파악하기 위해 사용   | 공공데이터 사이트 |
| 서울시 지하철역주소 데이터 | 주민센터 및 복지관의 교통 편리성을 파악하기 위해 사용    | 공공데이터 사이트 |
| 서울시 버스정류장 좌표데이터 | 주민센터 및 복지관의 교통 편리성을 파악하기 위해 사용    | 공공데이터 사이트 |
| 디지털정보지수 | 행정동별 시니어분들의 평균 디지털 역량 지수를 파악하기 위해 사용 | 별도생성 |
| 서울시 주민센터 주소 데이터 | 주민센터 주소를 이용해 좌표변환 후 주변특성 데이터의 개수를 파악하기위해 사용 | 셀레니움 | 
| 서울시 노인복지관 주소 데이터 | 복지관 주소를 이용해 좌표변환 후 주변특성 데이터의 개수를 파악하기위해 사용 | 셀레니움 |
| 서울시 주민센터 연면적 데이터  | 주민센터 내 시설 도입 가능한 공간을 파악하기 위해 사용  | 기관에 전화 및 웹사이트 내 정보 이용 |
| 서울시 노인복지관 연면적 데이터  | 복지관 내 시설 도입 가능한 공간을 파악하기 위해 사용  | 공공데이터 사이트 |

<br/>

### 🔧 데이터 전처리 및 차원축소  
  
✅ **전처리** 

- **이상치 :** 존재 X
- **정규화 :** Standard Scale 방법 활용
- **차원축소 :** 일반 PCA보다 설명력(**누적 분산 비율**)이 더 높은 **SPCA로 선정**

✅ **모델링** 

- 실루엣 계수와 분산이 좋은 모델인 **K-means (n = 3) 방법**을 선정
- **군집별 features 평균**의 **상,중,하**를 파악해 점수화
- **고득점 Cluster**을 기준으로 최적의 주민센터or복지관 선택

✅ **최적의 입지 선정 고려요소** 

- P-median 알고리즘을 이용한 [총 이동거리] 기준으로 1차 선정
- 대중교통, 시설 연면적, 주변특성, 유동인구 순으로 수가 높거나, 해당 구의 평균 이상인 시설로 선정

<br/>
 
### 4. 분석 결과

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/93702baa-5a39-485e-8f64-8f02973548aa/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221114%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221114T041628Z&X-Amz-Expires=86400&X-Amz-Signature=672c48b5b12d68af1a3315ff1bf7879fb97e893ae50b59c9f9db03d37ebac20f&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject">

<br/>

## 💡 프로젝트 한계점

### 데이터 수집의 한계

분석에 필요하다고 생각했던 데이터들을 다 구하지 못한점이 가장 크게 아쉬웠습니다. 하지만 ‘구하지 못함’에서 끝내지않고, ‘대체 데이터로 무엇이 있을까?’에 대해 팀원들과 여러 생각을 공유하고 논의하며 합의점을 찾아가는 과정 또한 값진 경험이라 생각합니다.

- [❌구하지 못한 Data   ✅ 대체한 데이터] 는 아래와 같습니다.
    1. **시설 데이터** 
        
        ❌ 주민센터 & 복지관의 공실유무 
        
        ☑ (1차) 주민센터에서 운영중인 프로그램 수 & 최대 수용 인원 수 data   
        
        ✅ (2차) 주민센터 & 복지관의 연면적 data 
        
    2. **인구 특성 데이터**  
        
        ❌ 행정동별 시니어의 학력 수준 
        
        ✅ **[2021 연령대별 디지털 역량 수준 * 행정동의 연령대별 인구]**의 총 합 으로 대체 
        
<br/>

### 통계적 지식의 중요성

팀원 모두 비전공자 출신으로 시작했기때문에, 통계적인 관점과 지식으로 분석을 진행하지 못한점이 아쉬웠습니다. 이를 계기로 통계적 지식의 중요성을 크게 알게되었고, 기초 통계 공부를 하게 되는 계기가 되었습니다.
