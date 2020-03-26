# portfolio




## [toy-personal-recommendation-system](https://github.com/kangheeyong/PROJECT-personal-recommendation-system-demo)
- 프로젝트명 : toy personal recommendation system 개발
- 기간 : 2020.3
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 개발(개인), 1인 / Backend AI 서비스 개발, linux(Ubuntu 16.04), Python(3.7.0), Kafka(2.4.1), MongoDB(4.2.3), docker, supervisord, API(google drive, slack), 개인용 library([LIB-Feynman](https://github.com/kangheeyong/LIB-Feynman))
- 요약
  - 본 프로젝트는 micro service architecture를 참고하여 실제 시스템과 유사하게 동작하게 만든 개인화 추천 시스템입니다. 실제 추천 시스템과 다른 점은 유저의 피드백을 확률적 그래프 모델로 설계하여 반응하게 만들었습니다. 시스템의 배포를 위하여 docker를 사용하였고, 안정적인 24시간 운용으 위하여 supervisord와 slack을 이용하여 관리할 수 있게 설계 했습니다. 이 시스템은 일간 이용자 수 20만명이 접속한다는 가정하여 설계하였고, 추천 알고리즘의 갱신 주기는 15초로 설정 했습니다. 


## [Fault Detection Project for OES](https://github.com/kangheeyong/2018-1-Deep-Learing-pc1/tree/master/2018-2/experiment_anoGANs_2)
- 프로젝트명 : anoGANs for PECVD Fault Detect using OES data 프로젝트
- 기간 : 2018.9 ~ 2018.12
- 소속회사명 : 대학원과정
- 주요사용기술 : 연구(팀장), 2인 / Fault Detection 알고리즘 연구, linux(Ubuntu 16.04), Python3(tensorflow for GPU 1.6.0), 딥러닝(CNN, GANs, anoGANs), MATLAB(신호 분석) 
- [연구 결과 링크](https://github.com/kangheeyong/2018-1-Deep-Learing-pc1/blob/master/2018-2/experiment_anoGANs_2/report.md)
- 요약
  - 본 연구는 "Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery" 논문에서 제한한 anoGANs을 단점을 보완하여, 반도체 공정과정에서 얻게 되는 OES(Optical Emission Spectroscopy) 센서 데이터를 가지고 이상패턴을 검출하는 알고리즘에 관한 연구입니다. 이 알고리즘의 가장 큰 특징은 정상데이터 만을 가지고 학습을 하고 테스트 단계에서 정상과 비정상 데이터를 구분하는 것입니다. 결과는 ROC curve가 0.99가 나왔으며, 실제 논문에서 0.89이라는 수치가 나왔습니다. 비록 두 연구에서 사용한 데이터 유형은 다르지만 높은 ROC curve 값이 의미하는 것은 의미하는 것은 OES 센서 데이터로 반도체 장비의 이상점 검출 가능성을 확인할 수 있는 연구였습니다.

## [GPU 프로그래밍](https://github.com/kangheeyong/2017-2-Deep-Learing-from-khy/tree/master/my_project_2017_1)
- 프로젝트명 : tensorflow 코드와 나의 cuda코드 비교 실험
- 기간 : 2017.9 ~ 2017.12
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 연구(개인), 1인 / linux(Ubuntu 16.04), Python3(tensorflow for GPU 1.6.0), 머신러닝(뉴럴네트워크), GPU(TITAN X Pascal 12GB), c/c++, cuda 9.0
- 요약
  - 본 프로젝트는 tensorflow(Python)를 사용하지 않고 직접 cuda로 프로그래밍을 해서 뉴럴네트워크 코드를 작성하는 것입니다. 본 프로젝트의 목적은 tensorflow로 작성한 코드와 직접 cuda로 작성한 것의 학습 속도를 비교하기 위함이었습니다. 결과는 제가 직접 작성한 cuda 코드가 속도와 메모리에서 약 10% 더 좋은 결과를 얻었지만, 생산성 측면에서는 tensorflow 코드가 훨씬 더 효율적이었습니다.

