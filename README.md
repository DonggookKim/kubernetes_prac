# 목표
- kubernetes를 통해 간단한 spring boot 서버를 운영해보고, 이를 한번에 배포할 수 있는 파이프라인을 만든다
- spring boot 서버의 기능은 아래와 같아
    - PUT 1 : request 받은 문자열을 저장한다
    - PUT 2 : request 받은 이미지를 저장한다
- 필요 pod 
    - spring boot 서버 pod
    - persistent volume을 가진 mysql pod
    -
