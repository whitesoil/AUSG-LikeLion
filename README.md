# 초보자를 위한 웹페이지 정복하기 - AWS로 웹페이지 서비스 해보기

### 본 실습 세션의 학습 목표는 아래와 같습니다.

- 내 도메인을 AWS Route 53 서비스에 연결해본다.
- S3를 이용해 HTML, JS, CSS 등 정적 웹사이트를 내 도메인으로 인터넷에 배포해본다. (HTTP)

#  필수 준비 사항

## 1. AWS 계정
- AWS 계정 만들기 [이동](https://aws.amazon.com/ko/)

본 가이드는 한명이 하나의 AWS 계정을 사용한다고 가정합니다. AWS Route 53, S3, CloudFront, Certification Manager에 접근할 수 있어야 하며, 다른 사람과 계정을 공유하게되면 특정 리소스에 대해 충돌이 발생하므로 권장하지 않습니다.

### [중요] 본 워크샵에서 사용하는 'Route 53' 서비스는 **과금**됩니다. 월 800원 (0.5$) 수준이니 실습이 끝나고 사용하지 않으신다면 바로 삭제하세요.

**Route 53을 제외한** 본 워크샵의 일환으로 시작하는 모든 리소스는 AWS 계정이 12개월 미만인 경우, 제공하는 AWS 프리티어로 충분히 가능합니다. 프리티어를 넘어서는 경우, 과금 될 수도 있습니다. 따라서, 새로운 실습용 계정을 만드시길 권장합니다. 자세한 내용은 [AWS 프리 티어 페이지](https://aws.amazon.com/free/)를 참조하세요.

## 2. 웹 브라우저
- Chrome 최신 버전 [다운로드](https://www.google.com/chrome/)
- Firefox 최신 버전 [다운로드](https://www.mozilla.org/ko/firefox/new/)

둘 중 원하시는 브라우저를 설치해주세요. (Internet Explorer는 AWS Web Console에서 문제가 발생 할 수 있습니다.)

# 자 그럼 이제 시작해볼까요?
1. [Freenom 가입 및 무료 도메인 등록](1_freenom)
2. [Route 53 Hosted Zone 등록](2_route53/)
3. [S3 정적 웹사이트 호스팅](3_s3/)
4. [Certification Manager로 인증서 만들기](4_certificate_manager)
5. [CloudFront로 CDN 구성하기](5_cloudfront/)
6. [삭제 가이드](8_Delete/)
