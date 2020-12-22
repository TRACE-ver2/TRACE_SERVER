# 🏡트레이스 - 지역기반 자취방 후기 커뮤니티 플랫폼

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3aab6d14-d028-47c3-aa60-3cefbe81e002/5.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3aab6d14-d028-47c3-aa60-3cefbe81e002/5.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1923f145-f93a-479d-8c8d-a75d2728c5bc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1923f145-f93a-479d-8c8d-a75d2728c5bc/Untitled.png)

## 🤔서비스 소개

트레이스란 “자취(自炊)의 자취(Trace)”라는 의미로, 웹, 앱 기반 자취방 커뮤니티 및 플랫폼 서비스입니다. 트레이스는 대학생을 주요 대상으로 하고 학교를 거점으로 하며, 학교 주변 학생들의 투명하고 높은 질의 주거에 도움을 주고자 합니다. 저희 서비스가 제공하는 기능은 크게 두가지로 나뉩니다.

1) 정보제공기능

학생들이 집을 구할 때 직접 살아보지 않으면 알 수 없는 정보들(습기, 방음, 벌레 여부 등등) 과 건축물대장정보를 이용해 학교 주변 모든 건축물에 대한 기본 정보, 데이터분석을 이용한 적정 집값을 제공합니다. (필요한 경우 자취방 거래도 일부 보조합니다)

2) 커뮤니티 기능
학생 사용자들이 자유롭게 이용할 수 있는 커뮤니티 서비스 역시 제공합니다. 각자 자취를 하면서 얻은 노하우를 공유하거나 자취할 때 필요한 물품에 대한 정보를 자유롭게 공유할 수 있습니다. 또한, 이 커뮤니티를 통해 트레이스는 생필품, 식료품 등에 대해서 공동 구매를 편리하게 할 수 있는 서비스를 제공합니다. 

---

## 🔥SERVER - 이수영👨🏻‍💻 배준호👨🏻‍🔧 배지홍👨🏻‍🏫

### 🤼 역할 분담

- 이수영 : api 서버 구축 / id, password 기반 회원가입, 인증, 인가 처리 / ERD & Entity Class Diagram 작성 / API 설계 / AWS S3 버킷 연결
- 배준호 : AWS EC2 배포 환경 구축 / DNS 연결 / DB에 빌딩 데이터 INSERT
- 배지홍 : 공공 API를 통해 얻은 건물 정보 가공 및 데이터 분석

## ✨기술 스택

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/efb0e424-018f-4966-a5aa-5f08cdb36241/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/efb0e424-018f-4966-a5aa-5f08cdb36241/Untitled.png)

## 🏗️ 서버 아키택처

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eeed4a91-f205-4cd2-b0ad-82aeb9a6c0a8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eeed4a91-f205-4cd2-b0ad-82aeb9a6c0a8/Untitled.png)

## 📊 ERD & 엔티티 클래스 다이어그램

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9f2e875c-eeee-4f8d-813d-ae47a6cd8ed1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9f2e875c-eeee-4f8d-813d-ae47a6cd8ed1/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/761b0800-c16c-4656-a5ec-640486331a80/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/761b0800-c16c-4656-a5ec-640486331a80/Untitled.png)

## 🖨️API 명세서

### 스프레드 시트

- 이미지 첨부 예정

### API 명세서

[git book api 링크](https://syleemk.gitbook.io/trace/)