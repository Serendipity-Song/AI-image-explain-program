# AI-image-explain-program


이 프로젝트는 사용자로부터 제공받은 이미지를 기반으로 4가지 품목을 판단하고, 해당 품목에 대한 설명을 출력하는 웹/앱 애플리케이션입니다. 이를 통해 사용자는 사진 속의 물체에 대해 더 깊게 이해하고, 그 특징과 정보를 학습할 수 있습니다.

## 프로젝트 구조
```
.
├── my_model                   # 학습된 모델 파일
├── ecobyte.ipynb              # 모델 학습 및 테스트 코드
├── ML_dataset_crawling.ipynb  # 데이터셋 크롤링 코드
├── index.html                 # 웹 애플리케이션 메인 페이지
└── README.md                  # 프로젝트 설명 및 가이드
```
## 프로젝트 동작 화면

아무것도 물체를 보여주지 않았을 때 화면
 
![](https://images.velog.io/images/thdalwh3867/post/ba3e7806-f147-4471-b342-0caf87a967b3/image.png)
 
물병을 보여줬을 때 나타나는 설명
 
![](https://images.velog.io/images/thdalwh3867/post/441e4ae4-85d7-40a7-9451-d6d732d46058/image.png)
 
구강세척기를 보여줬을 때 나타나는 설명
 
![](https://images.velog.io/images/thdalwh3867/post/ba76da46-e404-48d5-acbc-33bc19c31713/image.png)


## 사용 방법
1. 먼저, 프로젝트를 로컬 시스템에 클론합니다.
2. 웹 브라우저에서 `index.html` 파일을 열어 애플리케이션을 실행합니다.
3. 애플리케이션에서 이미지를 업로드하면, 이미지가 분석되고 해당 품목에 대한 설명이 출력됩니다.

## 개발 정보
이 프로젝트는 웹/앱 프론트엔드로 HTML을 사용하였습니다. 뒷단에서는 Python을 사용하여 데이터셋을 크롤링하고 이미지 분석 모델을 학습하였습니다. 학습된 모델은 사용자로부터 입력받은 이미지를 분석하여 결과를 생성하는데 사용됩니다.
 
