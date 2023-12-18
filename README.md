# Profile

## 보유 기술
C#(닷넷코어), AWS, 유니티


</br>
</br>
</br>


<img
    src = "img/극한직업 용사의 매니저편.png"
    width = 100
    height = 100
/>

## 극한직업 용사의 매니저 (라이브 중)
### 중도 참여
### 사용기술

#### 자바스크립트
- node.js

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3
- CloudWatch

### 작업 내용
- 모놀리식으로 운영되던 서버를 AWS의 Lambda에 MSA로 서비스되게 변경. 코드 관리 및 배포의 용이성 증가.
- Lambda에 개별 파일을 통해 배포.
- CloudWatch 경보를 통해 RDS 인스턴스의 CPU 사용률이 급격히 높아질 경우 메일로 알림을 보냄.
- 기존 ELB에 백업되던 유저들의 데이터를 S3로 마이그레이션.


</br>
</br>
</br>


<img
    src = "img/몬스터대마왕1호점.png"
    width = 100
    height = 100
/>

## 몬스터 대마왕 1호점 (서비스 종료)

### 사용기술

#### 자바스크립트
- node.js

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3
- DynamoDB

### 작업 내용
- Lambda에 개별 파일을 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- S3에 유저들의 데이터 백업.
- DynamoDB에 로깅.
- 길드 시스템 구현


</br>
</br>
</br>


<img
    src = "img/마계전자.png"
    width = 100
    height = 100
/>

## 마계전자 (라이브 중)

### 사용기술

#### 자바스크립트
- node.js
    - socket.io

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3
- EB
- CloudWatch
- Redis
- DynamoDB

#### 유니티
- 채팅 모듈

#### 웹
- 부트스트랩
- socket.io

### 작업 내용
- Lambda에 개별 파일을 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- S3에 유저들의 데이터 백업.
- CloudWatch 경보를 통해 RDS 인스턴스의 CPU 사용률이 급격히 높아질 경우 메일로 알림을 보냄.
- node.js로 채팅 서버를 구현. 각 언어에 맞게 채널을 구분.
- Redis를 통해 채팅 메시지를 임시로 저장하고 있다가 정해진 시간마다 S3에 백업.
- Redis를 통해 랭킹 컨텐츠의 순위를 저장.
- 유니티에 채팅 모듈을 구현함. UI를 통해 채팅 메시지를 띄우고, 채팅 메시지의 특정 부분 클릭 시 커스텀 태그 기능이 작동하도록 구현.
- 웹으로 어드민 페이지를 구현하여 채팅 메시지를 확인하고 유저 밴 처리와 우편 보내기 기능을 구현.
- DynamoDB에 서버 로깅.
- CloudWatch 이벤트를 통해 cron 시스템을 구현. 일정 기간마다 랭킹전 컨텐츠의 보스가 교체되도록 함.


</br>
</br>
</br>


<img
    src = "img/머지 드릴.png"
    width = 100
    height = 100
/>

## 머지 드릴 (서비스 종료)

### 사용기술

#### 자바스크립트
- node.js

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3

### 작업 내용
- Lambda에 개별 파일을 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- S3에 유저들의 데이터 백업.


</br>
</br>
</br>


<img
    src = "img/리버스 드라이브.png"
    width = 100
    height = 100
/>

## 리버스 드라이브 (서비스 종료)

### 사용기술

#### 자바스크립트
- node.js

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3

#### 유니티

### 작업 내용
- Lambda에 개별 파일을 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- S3에 유저들의 데이터 백업.
- 자사의 광고영상을 사전 다운로드하여 일정 조건마다 동영상 플레이어를 통해 재생.


</br>
</br>
</br>


<img
    src = "img/니트로 점프.png"
    width = 100
    height = 100
/>

## 니트로 점프 (서비스 종료)

### 사용기술

#### 자바스크립트
- node.js

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3

### 작업 내용
- Lambda에 개별 파일을 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- S3에 유저들의 데이터 백업.


</br>
</br>
</br>


<img
    src = "img/유니버스타.png"
    width = 100
    height = 100
/>

## 유니버스타 디펜스 (서비스 종료)

### 사용기술

#### C#
- asp.net
- 소켓

#### AWS
- Lambda
- API Gateway
- Route53
- RDS
- S3
- CDK
- EB
- CodeBuild
- CodePipeline
- CloudWatch

#### 유니티

#### Photon 엔진

### 작업 내용
- Lambda에 CDK를 통해 배포.
- 구글, 애플의 API를 통한 구매 영수증 검증.
- 풀 서버사이드로 구현. 모든 데이터를 서버단에서 처리. 기존 서비스와 달리 S3를 통한 데이터 백업 구현하지 않음.
- 중간에 asp로 서버 변경. EB를 통해 EC2 인스턴스에 서버 띄움. 이유는 Lambda의 콜드 스타트가 기존의 node.js보다 느리고 인스턴스가 내려가는 시간 이 더 빨랐기 때문.
- 소켓통신을 통해 pvp 대전 컨텐츠 구현. 개발 도중에 코드 폐기.
- CloudWatch를 통한 로깅.
- CodePipeline을 통한 코드 자동 배포.
- xml 코드를 제너레이터를 통해 통신 스펙 코드 자동 생성.
- 클라이언트용 통신 모듈(Sender, Receiver) 구현.
- MySQL 라이브러리를 사람이 사용하기 편하게 래핑.

### 서버 기능 구현 내용
- XUnit을 통해 모든 코드 테스트.
- RDB를 이용하여 로그인, 세션 ID를 구현. 동시접속을 막음.
- 배틀패스 기능 구현.
- 뽑기 픽업 기능 구현. 픽업을 유저가 바꿀 수 있음.
- 유닛 클래스, 레벨업 시스템 구현.
- 협업 컨텐츠 랭킹 구현. 2인 1조이기 때문에 팀원이 다르면 새로 업로드되게 함.
- 일일미션 시스템 구현.
- 일일 접속보상 시스템 구현.
- 유닛 덱 시스템 구현.
- 뽑기 구현.
- 공지사항 시스템 구현.
- 우편 시스템 구현