# SASA_Visualization_Project  
Project related with 2019, SASA 정보과학프로젝트1 : Data Visualization Project (2019.05. ~ 2019.06.)  

## Information  
> #### 중증외상환자(Severe Trauma Patient)란  

> #### 이 프로젝트에서 이용하는 데이터(data)는  
- 기간 : 2014년~2017년(대부분 연도별)  
- 자료 구성 : [KOSIS(국가통계포털)](http://kosis.kr/statisticsList/statisticsListIndex.do?menuId=M_01_01&vwcd=MT_ZTITLE&parmTabId=M_01_01#SelectStatsBoxDiv)  
중증외상(ICISS_2008 기반) 환자 수(성별,연령별, 월별) & (시도별)  
중증외상(ICISS_2008 기반) 환자의 발병 후 응급실 도착 소요시간 현황 (성별, 연령별, 월별) & (시도별)  
중증외상(ICISS_2008 기반) 환자의 응급실 내원수단 현황(성별, 연령별) & (시도별)    
중증외상(ICISS_2008 기반) 환자의 응급진료 결과 현황(성별, 연령별) & (시도별)  
중증외상(ICISS_2015 기반) 환자의 병원 내 사망시점(성별, 연령별) & (시도별)  
중증외상(ICISS_2015 기반) 환자의 사망장소 (성별,연령별) & (시도별)  

> #### ICISS(ICD-9-based Injury Severity Score)란  
  ICISS는 국제표준질병사인분류(International Classification of Disease, ICD)를 기반으로 산출하며 국제표준질병사인으로
분류된 특정 손상환자 상병코드별(S, T code) 기대생존확률(Survival Rate Ratio, SRR)값을 곱하여 계산한다. 상병코드는
최대 10개까지의 손상진단을 곱하여 계산할 수 있다.  
![iciss](https://user-images.githubusercontent.com/42968884/58524880-acacda00-8204-11e9-8fd0-4df793d925d1.JPG)  
  ICISS 점수는 0부터 1까지의 범위를 가지며, 중증도가 낮은 손상은 높은 생존 확률 값을 갖고 중증도가 높은 손상은 낮은
생존 확률 값을 가져 중증도 지표뿐 아니라 손상환자 생존율 예측을 보여준다. 

*(출처: Introduction to the Tool to Classify the Severity Levels of Injury Patients 손상환자 중증도 분류를 위한 도구 소개_질병관리본부 질병예방센터)*

> #### 프로젝트의 목적은  
  우리나라의 중증외상환자에 대한 처우 및 관리는 매우 열악한 상태이다. 
구체적으로 보자면 의료진들에 대한 보호, 복지, 업무 관리도 열악한 상황이며 환자들을 충분히 수용하기 위한 시설이 마련되어있지 않고, 환자들을 이송하고 치료하는 과정 역시도 우리나라는 체계화되어있지 않다. 무엇보다도 가장 중요한 문제점은 이 모든 문제들이 복합적으로 나타나 선진국 기준 *"예방가능한 외상사망률"* 이 굉장히 높게 나타난다는 것이다.   
  이러한 문제점을 데이터 시각화를 통해 나타내고, 사용자 상호작용(User Interaction)을 통해서 심각성을 개인적인 자료의 형태로 전해주어 문제의 심각성을 경험의 형태로 드러나는 프로그램을 개발하고자 한다.   
  
## Project Plan  
![정과프](https://user-images.githubusercontent.com/42968884/58443468-03df7b80-812d-11e9-9bca-3ba169c12ce7.JPG)

## Records  
Date : 2019.05.28. (1hour)  
Edit :  
- Create repository  
- SetUp Plans  
--------------------------------  
Date : 2019.05.29. (class)  
Edit :  
- Add explanations(about ICISS)  
- Download Data (& add more datas than the original)  
