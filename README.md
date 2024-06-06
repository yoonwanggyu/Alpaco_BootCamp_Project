# 알파코 딥러닝 9기 프로젝트 

1. 텍스트 마이닝 프로젝트
    - 주제 : 백종원의 프렌차이즈 분석
    - 방향성 : 다양한 분야의 상인들에게 시장 분석과 성공 요인을 도출해 드리자
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/d04946eb-aa58-4225-a4bc-894bc0a8fc6b)
    - 데이터 : 유튜브/네이버 리뷰 셀레니움을 통해 크롤링
    - 한식/중식/양식/일식/카페 카테고리별 키워드 분석
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/4955a2c8-c53e-40e9-858b-f169e8ed4450)
    - 토픽 모델링(LDA)
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/5fb037fe-b127-4f7e-b9f3-0df817545ad6)


2. 자연어 처리 / 음성인식 프로젝트
    - 주제 : 도파밍된 현대인들에게 필요한 긴 영상에서의 자동 키워드/토픽 추출 프로세스
    - 방향성 : 음성 데이터 -> 텍스트 데이터로 변환 -> 자동 키워드 / 토픽 추출 서비스 예상
    - 데이터 : AI HUB (뉴스 음성/텍스트 데이터)
    - Faster_Whisper 이용해 텍스트로 변환
    - 키워드 VS 토픽
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/01b4cb75-d081-4e16-84b8-07152a249752)
    - 키워드 추출(with Attention / KeyBert)
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/df925252-1518-4869-998f-601b5ea56b16)
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/c0b35df6-5695-4bac-bec8-65e20955b528)
    - 토픽 모델링(BERTopic)
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/2d32674a-397a-4ce0-8cd1-902cd2731471)


4. 이미지 프로젝트
    - 주제 : 생성형 AI 작품을 구별하기 위한 50인 작가의 작품 분류 프로젝트
    - 방향성 : 데이터의 불균형 극복 및 모델 성능 향상
    - 데이터 : 캐글(https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time/data?select=artists.csv)
    - 데이터 불균형 해소를 위해 데이터 다양한 증강법 
      - ex) TrivialAugmentWide / Resige / RandomPerspective / CenterCrop / GaussianBlur / RandomHorizontalFlip / Normalize
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/638ff65a-4aed-4f52-b6cc-0c493dc2d200)
    - 클래스 가중치 사용
      - ex) CrossEntropyLoss 함수에 작품 개수에 대한 가중치 적용
    - 사용한 모델 : ResNet50 / ViT
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/392e9c0d-419c-4ed3-aac3-23075ac6a20a)
    - 결과
       ![image](https://github.com/yoonwanggyu/Alpaco_Project/assets/161268939/986e0fb2-262d-4168-b200-24fb4cf5e6eb)
    - Demo 활용



 
