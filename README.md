# 🎵Purple Review🎵

![purplereviewtitle](https://user-images.githubusercontent.com/70012637/186297625-66cf25a1-5e3f-46ec-9255-c245376a8234.png)

### 서비스 소개

컬리의, 컬리만을 위한 컬리 리뷰 서비스 퍼플 리뷰입니다.<br>
기존의 마켓컬리 상품 추천 개선에 관한 아이디어로써 상품 구매 후 키워드 기반 리뷰 작성 시스템을 도입했습니다.
<br>
- 사용자 리뷰 작성 URL : [kurlyreview.com](http://kurlyreview.com)
- 관리자 데이터 조회 URL : [kurlyreviewadmin.com](http:/kurlyreviewadmin.com)

### 프로젝트 상세

- 2022 Kurly Hack Festa 컬리 제 1회 입사 연계 특전 온라인 해커톤
- 프로젝트 개발 일정 : 2022년 8월 17일~8월24일(13일) 
- 8월 10일 : 브레인스토밍 - 8월 15일 : 해커톤 예선 기획서 제출 마감
- 8월 24일 : 본선 과제 제출 마감(개발 프로젝트 git repository 생성 및 PT Materials 완료)
<br>

## 🎨서비스 구성도
이미지를 누르시면 좀 더 자세하게 확인 할 수 있습니다.
<br>
|![서비스구성도](https://user-images.githubusercontent.com/70012637/186348047-cd677195-02f9-4692-9219-1e702576e1e0.png)|![관리자서비스구성도](https://user-images.githubusercontent.com/70012637/186348039-188665f8-d916-4613-bd86-aecf41c468b5.png)|
|-----|-------|

<br><br>

## 🛠기술 스택

| springboot                                                                                                           | react                                                                                                           | next                                                                                                           | aws                                                                                                           | maradb                                                                                                           |
| -------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| ![stringboot](https://user-images.githubusercontent.com/70012637/186303710-a5eac8c4-0f70-4ee0-8c0a-b100dafaf842.jpg) | ![react](https://user-images.githubusercontent.com/70012637/186303832-ed627bbe-2c88-4335-82ba-4177a180e522.png) | ![next](https://user-images.githubusercontent.com/70012637/186302791-df9259e1-5916-4f3c-8bc1-4f0ee88b7cbb.png) | ![aws](https://user-images.githubusercontent.com/70012637/186303378-10c8d21c-3427-42c2-a19d-040a62bc0841.png) | ![maradb](https://user-images.githubusercontent.com/70012637/186302785-b574dc4a-cddd-4b60-8dc4-d41d05d2ee0f.png) |
#### Back-End
- Spring Boot를 사용하여 Rest API 웹 어플리케이션 서버 구축 했습니다.
- spring data jpa(Hybernate)로 객체 지향적 데이터 로직을 구성했습니다.
- AWS EC2 가상 서버를 통해 서버를 배포하였습니다.
- Database AWS RDS의 mariadb를 사용했습니다.
#### Front-End
- NextJS SSG로 페이지를 구현하였습니다.
- 프론트엔드 배포는 AWS S3 버킷을 이용했습니다.

<br>

## 🎢향후 개발 계획

- TDD기반 클린코드 리팩토링 및 서비스 고도화 예정.
- git actions, jenkins를 통해 무중단 배포 CI/CD 구성 예정.
- 개발된 리뷰 서비스 로직을 이용한 AI 추천 서비스 구현 예청.

<br>

## 🐱‍🏍 팀원 소개

|                                   🧏🏻‍♀️[송재현](https://github.com/songgplant)                                    |                                     [손정호](https://github.com/otterp012)                                     |                                        [안유진](www.github.com/U-jjin)                                         |
| :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![재현](https://user-images.githubusercontent.com/70012637/186308596-0dde6861-465e-4a12-9208-e74308ac4f86.jpg) | ![정호](https://user-images.githubusercontent.com/70012637/186308581-ac1bb7ba-9677-435e-b803-a443171a214b.png) | ![유진](https://user-images.githubusercontent.com/70012637/186308590-eb714273-fbe0-4a86-b2e7-b7994e2fdccb.jpg) |
|                                              🐱‍👤기획,데이터분석                                              |                                                🐱‍💻프론트엔드                                                 |                                                  🐱‍🐉백엔드                                                   |
