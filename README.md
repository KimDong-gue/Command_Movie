# ○ Subject: 개인별 맞춤 영화 추천 프로그램

# ○ Contributer

팀원|역할|
------------|-----------------------
김동신(팀장) | 사전기획 및 데이터 선정 
　　　　　　　| 데이터 수집 및 전처리   
심지영(팀원) | 데이터 전 처리         
　　　　　　　|  PPT 제작              
이선주(팀원) | 데이터 전처리 및 벡터화
　　　　　　　| 유사도 측정             
최수열(팀원) | 데이터 전처리(품사 태깅) 
　　　　　　　| 사용자 입력단 제작     

### ○ Skils: Vecterizing, TF-IDF, MeCab, Cosine similarity
### ○ DataSet: https://www.kmdb.or.kr/info/api/apiDetail/6 
### ○ Project Schedule : 23.8.24 ~ 23.9.5 (약 2주)


---

![image](https://github.com/KimDong-gue/Command_Movie/assets/116249934/c0ac7c8f-3452-4a97-ba79-78be0a91d7e2)


- 기획
  - 주제: 사용자에게 가장 적합한 영화 추천 뉴스레터 시스템을 개발하는 것을 목표로 함
  - 배경: 수많은 영화 중 어떤 영화를 선택해야 할지 결정하기 어려운 경우가 많음 
  - 기획의도: 사용자의 취향과 관심사를 고려한 개인 맞춤형 추천을 제공하여 이 문제를 해결
  - 기존의 서비스와의 차별점: 영화 시청 이력, 검색 기록 등 행동 기반의 추천을 하는 대부분의 서비스와 달리 사용자의 현재 취향과 관심사를 바탕으로 영화를 추천하는 방식임


---

- Flow Chart
  
![image](https://github.com/KimDong-gue/Command_Movie/assets/116249934/1dd41513-3f49-4c34-a3c2-fd64aa2c765c)

- 사용자 정보 입력 모듈 : 사용자에게 정보를 입력 받아 DB에 추가하고 해당 영화의 ‘키워드‘와 ‘줄거리＇를  추출하여 DB에 추가
- 데이터 전 처리 모듈 : DB내의  유용한 정보를 추출하고 품사 태깅, 벡터화 시킨다. 
- 유사도 측정 모듈 : ‘장르‘,’감독‘,’배우‘,’키워드‘,’줄거리‘ 각각 의 유사도를 측정하고 5개의 특징을 평균 내어 유사도의 순위를 매기는 방식

---
- 시연 영상

![image](https://github.com/KimDong-gue/Command_Movie/assets/116249934/d1185802-6236-412f-b15a-00428855b774)

---
