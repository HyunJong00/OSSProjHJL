# 프로젝트 명: 농작물 생산량 트렌드


## I. 프로젝트 수행팀 개요

* 수행 학기:  2024-1
* 프로젝트명: 농작물 생산량 트렌드 서비스
* Key Words : *농작물* | *생산량 예측* | *농업 지도* | *공시지가* | *농경지*
      
* 팀명: aha

구분 | 성명 | 학번 | 소속학과 | 연계전공 | 이메일
------|-------|-------|-------|-------|-------
팀장 | 이현종 | 2019111655 | 바이오환경과학과 | 융합SW연계전공 | hjong1010@dongguk.edu       
팀원 | 임형준 | 2019112520 | 산업시스템공학과 | 융합SW연계전공 | 2019112520@dongguk.edu        
팀원 | 이건희 | 2019110475 | 통계학과 | 융합SW연계전공 | ish8176@dgu.ac.kr        

* 지도교수 : 융합SW교육원 이길섭 교수님, 박효순 교수님

* 팀 구성원 또는 활동 사진  
    * *팀 자유 형식으로 작성*  

## II. 프로젝트 수행 결과  

### 1. 프로젝트 개요  

#### 1.1 개발 동기  

- 기후변화로 인해 농업 생태계가 어려움을 겪고 있으며 특히 작물에 따른 생산량 변동이 심화될 수 있음
- 농작물 생산량의 변동성이 커짐에 따라 생산 과잉은 악성 재고, 생산 부족은 가격 폭등을 유발하여 생산량 예측이 중요함

#### 1.2 개발 목표  

- 한국의 농업지도를 배경으로 기후변화에 따라 변화하는 지역, 작물의 생산량을 예측하여 정보를 제공하는 서비스 개발을 목표로 함

#### 1.3 최종결과물  
- http://34.47.70.11:8000/ 
* 웹 접속 초기 화면

  ![image](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/assets/143998370/55faf73a-d8bd-4247-b10c-724118d117fb)

* 작물/연도 선택란
  
  ![image](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/assets/143998370/29402e51-e8a5-4bde-b316-bb902b70bd4d)

* 지역 내 특정 위치 클릭 시 팝업창

  ![image](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/assets/143998370/d7fc9461-ef0e-4602-aab3-6961e4be837a)

#### 1.4 기대 효과  

- 농업을 처음 시작하는 사용자는 큰 시간과 비용을 들이지 않고 최적의 입지를 선정할 수 있음
- 농업에 종사중인 사용자는 생산량 예측을 통해 효율적인 공급, 재고 관리가 가능해 짐
- 사용자는 생산량 예측 결과를 사용자 친화적인 인터페이스로로 쉽게 조회할 수 있음

### 2. 프로젝트 수행 내용  

#### 2.1 프로젝트 진행과정 

[OSSP_WBS.pdf](https://github.com/user-attachments/files/15528554/OSSP_WBS.pdf)

#### 2.2 프로젝트 구현내용  

- *프로젝트 설계, 구현 등 구현과 관련된 내용을 기술*  

### 3. 프로젝트 자료  

#### 3.1 프로젝트 OSS 구성  

**오픈데이터**
- 기상청 기후변화아 시나리오에 따른 기상정보 예측 데이터
- [기상청 기후정보](http://www.climate.go.kr/home/CCS/contents_2021/35_download.php)
  
**오픈소스**
- v-world 공간 정보지도 공시지가 api
- [V-WORLD](https://www.vworld.kr/dtna/dtna_apiSvcFc_s001.do?apiNum=23)

#### 3.2 프로젝트 주요 문서 

- [수행계획서](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/blob/main/Doc/1_1_OSSProj_09_Aha_수행계획서.md)
- [중간보고서](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/blob/main/Doc/2_1_OSSProj_09_Aha_중간보고서.md)
- [최종보고서](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/blob/main/Doc/3_1_OSSProj_09_Aha_최종보고서.md)
- [회의록](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/blob/main/Doc/4_2_OSSProj_09_Aha_회의록.md)
- [이슈관리](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/issues?q=is%3Aissue+is%3Aclosed)
- [제품구성배포운영자료](https://github.com/CSID-DGU/2024-1-OSSProj-Aha-09/blob/main/Doc/4_3_OSSProj_09_Aha_제품구성배포운영자료.md)


#### 3.3 참고자료  

* 날씨마루 : https://bd.kma.go.kr/kma2020/fs/productionSelect1.do?pageNum=5&menuCd=F050102000
* USDA : https://www.nass.usda.gov/Charts_and_Maps/Crops_County/cr-pr.php
  
## Commit Convention
-   feat : 새로운 기능 추가
-   fix : 버그 수정
-   docs : 문서 수정
-   style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
-   refactor: 코드 리펙토링
-   test: 테스트 코드, 리펙토링 테스트 코드 추가
-   chore : 빌드 업무 수정, 패키지 매니저 수정

## 💡 PR Convetion

| 아이콘 | 코드                       | 설명                     |
| ------ | -------------------------- | ------------------------ |
| 🎨     | :art                       | 코드의 구조/형태 개선    |
| ⚡️    | :zap                       | 성능 개선                |
| 🔥     | :fire                      | 코드/파일 삭제           |
| 🐛     | :bug                       | 버그 수정                |
| 🚑     | :ambulance                 | 긴급 수정                |
| ✨     | :sparkles                  | 새 기능                  |
| 💄     | :lipstick                  | UI/스타일 파일 추가/수정 |
| ⏪     | :rewind                    | 변경 내용 되돌리기       |
| 🔀     | :twisted_rightwards_arrows | 브랜치 합병              |
| 💡     | :bulb                      | 주석 추가/수정           |
| 🗃      | :card_file_box             | 데이버베이스 관련 수정   |
