# portfolio

## 최신 포르폴리오

simple example 위로 포트폴리오

- [study-about-programming](https://github.com/kangheeyong/STUDY-about-programming)
- [study-about-database](https://github.com/kangheeyong/STUDY-about-database)
- [study-about-webserver](https://github.com/kangheeyong/STUDY-about-webserver)

---

## 취업 이전 포트폴리오 

프로젝트 결과 위주 포트폴리오

- 파란색 글씨를 클릭하시면 git repository로 가실 수 있습니다.
- 이 프로젝트는 대학원이나 회사에서 한 내용이 아니라 개인적으로 진행한 프로젝트입니다.



## (개발)[PROJECT-ML-ENV-setting](https://github.com/kangheeyong/PROJECT-ML-ENV-setting)
- 프로젝트명 : ML/DL 연구/개발 환경 세팅
- 기간 : 2020.5
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 개발(개인), 1인 / nvidia-docker, docker,linux(Ubuntu 18.04), Python(3.7), tensorflow(2.1), GPU(cuda 10.1), supervisor
- 요약
  - 본 프로젝트는 ML/DL 연구/개발 환경을 docker를 통해 관리하고, 쉽게 그 환경을 설치할 수 있게 만드는 것이 목표입니다. docker를 이용해 연구/개발 환경을 관리하면 단순히 git으로 코드를 관리하는 것보다 일관성 있는 연구 결과를 재현할 수 있고, 또한 실제 머신러닝 백엔드 서버를 개발을 할 경우 검증된 GPU 세팅과 ML/DL 라이브러리가 설정된 docker가 있기 때문에 불필요한 시간을 줄일 수 있습니다. 
  

## (개발)[toy-async-web-server](https://github.com/kangheeyong/PROJECT-async-web-server)
- 프로젝트명 : toy async web server 개발
- 기간 : 2020.5
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 개발(개인), 1인 / async web server 개발, 웹 풀스택, linux(Ubuntu 16.04), Python(3.7.0), sanic, Docker, pytest, HTML, JavaScript, jQuery
- 요약
  - 본 프로젝트는 async web server 개발하는 것입니다. 이 웹서버는 unicode 이름을 검색하면 unicode 값을 web을 통하여 보여주는 것이 목적입니다.(toy project라서 서버의 목적 자체는 의미 없습니다.) 백엔드에서 유니코드 이름 검색을 위한 인덱스를 만들고 웹에서 검색을 하면 이 인덱스를 통하여 값을 반환합니다. 마지막으로 이 서버는 도커를 통하여 배포할 수 있게 만들었습니다.
  - 이 프로젝트의 목적은 [웹 풀스택 개발 과제]를 만들고 모범 답안을 만드는 것입니다. 막연하게 공부하는 것보다 특정 요구사항이 주어지면 그 요구사항에 맞춰서 개발하는 것이 개발자로서 성장에 많은 도움이 된다고 생각합니다. 하지만 초보 개발자가 어떤 toy project를 어떻게 시작하느냐를 생각하는 것은 개인적으로 초보가 할 수 있는 것이 아니라고 생각했습니다. 이러한 문제는 어느정도 경험이 있는 사람이 만드는 것이 맞다고 생각합니다. 저도 초보자지만 저의 경험을 참고하여 toy project 문제를 만들어 봤습니다.
  
    

## (개발)[toy-personal-recommendation-system](https://github.com/kangheeyong/PROJECT-personal-recommendation-system-demo)
- 프로젝트명 : toy personal recommendation system 개발
- 기간 : 2020.3
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 개발(개인), 1인 / Backend AI 서비스 개발, linux(Ubuntu 16.04), Python(3.7.0), Kafka(2.4.1), MongoDB(4.2.3), docker, supervisord, API(google drive, slack), 개인용 library([LIB-Feynman](https://github.com/kangheeyong/LIB-Feynman))
- 요약
  - 본 프로젝트는 micro service architecture를 참고하여 실제 시스템과 유사하게 동작하게 만든 개인화 추천 시스템입니다. 실제 추천 시스템과 다른 점은 유저의 피드백을 확률적 그래프 모델로 설계하여 반응하게 만들었습니다. 시스템의 배포를 위하여 docker를 사용하였고, 안정적인 24시간 운용으 위하여 supervisord와 slack을 이용하여 관리할 수 있게 설계 했습니다. 이 시스템은 일간 이용자 수 20만명이 접속한다는 가정하여 설계하였고, 추천 알고리즘의 갱신 주기는 15초로 설정 했습니다. 


## (연구)[Fault Detection Project for OES](https://github.com/kangheeyong/2018-1-Deep-Learing-pc1/tree/master/2018-2/experiment_anoGANs_2)
- 프로젝트명 : anoGANs for PECVD Fault Detect using OES data 프로젝트
- 기간 : 2018.9 ~ 2018.12
- 소속회사명 : 대학원과정
- 주요사용기술 : 연구(팀장), 2인 / Fault Detection 알고리즘 연구, linux(Ubuntu 16.04), Python3(tensorflow for GPU 1.6.0), 딥러닝(CNN, GANs, anoGANs), MATLAB(신호 분석) 
- [연구 결과 링크](https://github.com/kangheeyong/2018-1-Deep-Learing-pc1/blob/master/2018-2/experiment_anoGANs_2/report.md)
- 요약
  - 본 연구는 "Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery" 논문에서 제한한 anoGANs을 단점을 보완하여, 반도체 공정과정에서 얻게 되는 OES(Optical Emission Spectroscopy) 센서 데이터를 가지고 이상패턴을 검출하는 알고리즘에 관한 연구입니다. 이 알고리즘의 가장 큰 특징은 정상데이터 만을 가지고 학습을 하고 테스트 단계에서 정상과 비정상 데이터를 구분하는 것입니다. 결과는 ROC curve가 0.99가 나왔으며, 실제 논문에서 0.89이라는 수치가 나왔습니다. 비록 두 연구에서 사용한 데이터 유형은 다르지만 높은 ROC curve 값이 의미하는 것은 의미하는 것은 OES 센서 데이터로 반도체 장비의 이상점 검출 가능성을 확인할 수 있는 연구였습니다.

## (개발)[GPU 프로그래밍](https://github.com/kangheeyong/2017-2-Deep-Learing-from-khy/tree/master/my_project_2017_1)
- 프로젝트명 : tensorflow 코드와 나의 cuda코드 비교 실험
- 기간 : 2017.9 ~ 2017.12
- 소속회사명 : 개인 프로젝트
- 주요사용기술 : 연구(개인), 1인 / linux(Ubuntu 16.04), Python3(tensorflow for GPU 1.6.0), 머신러닝(뉴럴네트워크), GPU(TITAN X Pascal 12GB), c/c++, cuda 9.0
- 요약
  - 본 프로젝트는 tensorflow(Python)를 사용하지 않고 직접 cuda로 프로그래밍을 해서 뉴럴네트워크 코드를 작성하는 것입니다. 본 프로젝트의 목적은 tensorflow로 작성한 코드와 직접 cuda로 작성한 것의 학습 속도를 비교하기 위함이었습니다. 결과는 제가 직접 작성한 cuda 코드가 속도와 메모리에서 약 10% 더 좋은 결과를 얻었지만, 생산성 측면에서는 tensorflow 코드가 훨씬 더 효율적이었습니다.

