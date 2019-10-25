# AWS, Terraform, Network 연습공간

#####  

#### AWS



##### s3 특징

- 저장 용량에 제한이 없어서 무제한으로 저장이 가능하다.
  - 단 지갑이 허용된 만큼

- 100% 가까운 내구성을 가진다.
  - 99.9999..%
- SSD 서비스(EBS) 보다 저렴하다.



##### 인터넷

[인터넷은 어떻게 동작하는가?](https://developer.mozilla.org/ko/docs/Learn/Common_questions/How_does_the_Internet_work)

[웹 작동 방식](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)



##### vpc

- 인터넷 서비스를 제공하려면 하나 이상의 서버가 필요하다.
- 각 서버를 연결하기 위한 사설 네트워크가 필요
- AWS VPC는 서비스를 위한 가상 사설 네트워크 제공
- AWS VPC는 인터넷과 연결되어 사용자에게 서비스 제공
  - VPC `subnet`으로 나뉘고 `ec2`는`subnet`과 연결

