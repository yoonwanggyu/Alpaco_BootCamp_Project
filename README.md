# 알파코 딥러닝 9기 프로젝트 

1. 텍스트 마이닝 프로젝트
    - 주제 : 백종원의 프렌차이즈 분석
    - 유튜브/네이버 리뷰 셀레니움을 통해 크롤링
    - 한식/중식/양식/일식/카페 카테고리별 키워드 분석
    - 토픽 모델링(LDA)

2. 자연어 처리 / 음성인식 프로젝트
    - 주제 : 도파밍된 현대인들에게 필요한 긴 영상에서의 자동 키워드/토픽 추출 프로세스
    - AI HUB 데이터 활용(뉴스 음성/텍스트 데이터)
    - Faster_Whisper 이용해 텍스트로 변환
    - 키워드 추출(with Attention / KeyBert)
    - 토픽 모델링(BERTopic)

4. 이미지 프로젝트
    - 주제 : 생성형 AI 작품을 구별하기 위한 50인 작가의 작품 분류 프로젝트
    - 방향성 : 데이터의 불균형 극복 및 모델 성능 향상
    - 캐글 데이터 활용 (https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time/data?select=artists.csv)
    - 데이터 불균형 해소를 위해 데이터 다양한 증강법 
      - ex) TrivialAugmentWide / Resige / RandomPerspective / CenterCrop / GaussianBlur / RandomHorizontalFlip / Normalize
      - ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/638ff65a-4aed-4f52-b6cc-0c493dc2d200)
    - 클래스 가중치 사용
      - ex) CrossEntropyLoss 함수에 작품 개수에 대한 가중치 적용
    - 사용한 모델 : ResNet50 / ViT
      - ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/392e9c0d-419c-4ed3-aac3-23075ac6a20a)



 
