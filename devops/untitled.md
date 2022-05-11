# DevOps 정의

## Wikipedia Document

{% hint style="info" %}
제품의 변경사항을 품질을 보장함과 동시에 반영하는데 걸리는 시간을 단축하기 위한 실천 방법의 모음
{% endhint %}

쉽게 말해 개발(Dev) + 운영(Ops)의 합성어로 분리되어 있던 개발 조직과 운영 조직의 경계를 허물고 하나의 팀으로 통합하고자 하는 문화이자 철학입니다.

![Dev + Ops](<../.gitbook/assets/CleanShot 2022-05-11 at 13.11.10@2x.png>)

## DevOps 개요

구글의 검색어 트렌드를 살펴보면 DevOps가 주목 받기 시작한 것은 2009년부터 입니다.

![DevOps Google Search Analytics](<../.gitbook/assets/CleanShot 2022-05-11 at 13.13.15@2x.png>)

소프트웨어 개발은 아래와 같은 라이프사이클을 가지고 있습니다.

설계 => 개발 => 테스트 => 배포 => 운영 => 피드백을 각 분리된 조직에서 처리를 하는 방식인데요,&#x20;

각 단계마다 분리된 조직이 있기에 의사소통에 어려움이 있고, 놓치는 경우가 생길 수 있습니다.

![Software Develop Life Cycle](<../.gitbook/assets/CleanShot 2022-05-11 at 13.23.44@2x.png>)

> 개발자는 작성한 코드를 스스로 테스트하고, 배포하고, 운영할 수 있으며 이에 대한 피드백을 전달받아 다시 코드를 작성할 수 있게 됩니다.

## AWS DevOps

Amazone Web Services는 6가지 데브옵스 모법 사례를 제시합니다.

### 1. 지속적 통합 (Continuous Integration)

개발자가 만든 변경 사항에 대해서 빌드 및 테스트를 진행해본 후에 중앙 리포지토리에 통합함으로써 신속하게 버그를 발견하고 제품의 품질을 개선하며, 새로운 변경 사항을 테스트 및 배포하는 데 걸리는 시간을 단축하는 것입니다.

![Continuous Integration](../.gitbook/assets/image.png)

### 2. 지속적 전달 (Continuous Delivery)

개발의 산출물을 프로덕션에 배포하기 위한 코드 변경이 자동으로 빌드, 테스트 되는 개발 방식입니다. 지속적 전달이 적절하게 구현되면, 개발자는 언제나 즉시 배포할 수 있게 됩니다.

![Continuous Delivery](<../.gitbook/assets/image (1).png>)

### 3. 마이크로 서비스 (Micro-Service)

마이크로 서비스 아키텍쳐(MSA)는 큰 서비스를 작은 서비스의 집합으로 구축하는 설계 방식입니다. 큰 서비스를 마이크로 서비스 없이 설계하게 된다면, 빌드 및 테스트에 많은 시간이 소요되고 병목 현상이 발생할 가능성이 높으며 발생 원인을 찾기도 힘듭니다.

![Micro-Service](<../.gitbook/assets/image (4).png>)

### 4. IaC (Infrastructure as Code)

인프라 구조를 코드로 관리하는 방식입니다. 개발자나 시스템 관리자가 수동으로 리소스를 설정 및 구성할 필요 없이 코드로 대규모 인프라와 상호 작용할 수 있습니다.

![Infrastructure as Code](<../.gitbook/assets/image (3).png>)

### 5. 모니터링과 로깅 (Monitoring & Logging)

개발자에게 제품의 지표와 로그를 중앙에서 모니터링할 수 있는 환경을 제공해주면, 직접 운영에 참여함으로써 제품에 문제가 발생하였을 때 빠르게 처리할 수 있습니다.

![Monitoring & Logging](<../.gitbook/assets/image (5).png>)

### 6. 커뮤니케이션 및 협업 (Communication & Collaboration)

조직 내에서 커뮤니케이션과 협업이 증가하는 것도 DevOps의 주요 문화입니다. Slack과 같은 메신저 시스템이나 JIRA 같은 이슈 관리 시스템, Confluence 및 Notion과 같은 위키 시스템을 잘 활용하는 것입니다.

![Communication & Collaboration](<../.gitbook/assets/image (2).png>)
