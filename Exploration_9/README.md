# Exploration 9
## 아이유 닮은 아티스트 찾기

이번에는 머신러닝 어플리케이션 중 가장 상업적인 성공을 거둔 것으로 평가받고 있는 추천시스템(Recommender System) 에 대해 학습해보자. 유튜브, 넷플릭스 등 동영상 플랫폼이 기가막히게 내가 좋아할 만한 콘텐츠를 찾아서 자동으로 플레이해 주고 있다. 
아마존, 쿠팡 온라인 쇼핑 사이트에서도 내 취향에 맞는 상품추천을 쉽게 접할 수 있다. 
페이스북, 인스타그램 같은 Social media와 뉴스나 광고까지도 추천시스템의 원리가 숨어있다.

추천시스템의 원리를 요약하자면, 나와 비슷한 다른 사용자들이 좋아하는 것과 비슷한 것을 내게 추천해 준다는 것이다.
- 어떤 사용자들이 나와 비슷한지를 어떻게 알 수 있을까? 
- 또 어떤 상품이나 정보가 서로 유사한지는 어떻게 알 수 있는 걸까? 

위의 두 물음은 이번 프로젝트에서 배울 수 있다.

[목표]
- 추천시스템의 개념과 목적을 이해
- Implicit 라이브러리를 활용하여 Matrix Factorization(이하 MF) 기반의 추천 모델을 만들어 보기
- 음악 감상 기록을 활용하여 비슷한 아티스트를 찾고 아티스트를 추천해 보기
- 추천 시스템에서 자주 사용되는 데이터 구조인 CSR Matrix을 익히기
- 유저의 행위 데이터 중 Explicit data와 Implicit data의 차이점을 파악하기
- 새로운 데이터셋으로 직접 추천 모델을 만들어 보기

[목차]
- 데이터 탐색하기와 전처리
- 사용자의 명시적/암묵적 평가
- Matrix Factorization(MF)
- CSR(Compressed Sparse Row) Matrix
- MF 모델 학습하기
- 비슷한 아티스트 찾기, 유저에게 추천하기


-------

[jupyter notebook Link](https://github.com/kalina007/AIFFEL_EXPLORATION/blob/main/Exploration_9/practice.ipynb)     
[Exploration 9 Link](https://github.com/kalina007/AIFFEL_EXPLORATION/blob/main/Exploration_9/exploration_9.ipynb)
