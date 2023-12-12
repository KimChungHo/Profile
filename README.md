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

## 극한직업 용사의 매니저
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
모놀리식으로 운영되던 서버를 AWS의 Lambda에 MSA로 서비스되게 변경.

Lambda에 개별 파일을 통해 배포.

CloudWatch 경보를 통해 RDS 인스턴스의 CPU 사용률이 급격히 높아질 경우 메일로 알림을 보냄.


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

### 작업 내용
Lambda에 개별 파일을 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증

S3에 유저들의 데이터 백업


</br>
</br>
</br>


<img
    src = "img/마계전자.png"
    width = 100
    height = 100
/>

## 마계전자

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

#### 유니티
- 채팅 모듈

### 작업 내용
Lambda에 개별 파일을 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증.

S3에 유저들의 데이터 백업.

CloudWatch 경보를 통해 RDS 인스턴스의 CPU 사용률이 급격히 높아질 경우 메일로 알림을 보냄.

node.js로 채팅 서버를 구현. 각 언어에 맞게 채널을 구분.

Redis를 통해 채팅 메시지를 임시로 저장하고 있다가 정해진 시간마다 S3에 백업.

Redis를 통해 랭킹 컨텐츠의 순위를 저장.

유니티에 채팅 모듈을 구현함. UI를 통해 채팅 메시지를 띄우고, 채팅 메시지의 특정 부분 클릭 시 커스텀 태그 기능이 작동하도록 구현.


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
Lambda에 개별 파일을 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증.

S3에 유저들의 데이터 백업.


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
Lambda에 개별 파일을 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증.

S3에 유저들의 데이터 백업.

자사의 광고영상을 사전 다운로드하여 일정 조건마다 동영상 플레이어를 통해 재생.


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
Lambda에 개별 파일을 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증.

S3에 유저들의 데이터 백업.


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

#### Photon 엔진

### 작업 내용
Lambda에 CDK를 통해 배포.

구글, 애플의 API를 통한 구매 영수증 검증.

풀 서버사이드로 구현. 모든 데이터를 서버단에서 처리. 기존 서비스와 달리 S3를 통한 데이터 백업 구현하지 않음.

중간에 asp로 서버 변경. EB를 통해 EC2 인스턴스에 서버 띄움.

소켓통신을 통해 pvp 대전 컨텐츠 구현. 개발 도중에 폐기.

CloudWatch를 통한 로깅.

CodePipeline을 통한 코드 자동 배포.