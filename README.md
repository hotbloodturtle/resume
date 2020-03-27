
### 강해석
---

CAREER&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4년 (2016~)

BIRTH&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1987.12.21

ADDRESS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;서울시 금천구 독산동 한신아파트 8동 204호

PHONE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;010-5231-1994

EMAIL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bloodturtle@naver.com

BLOG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://kez1994.tistory.com

GITHUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://github.com/hotbloodturtle





### 간략한 자기소개

서비스 개발자 강해석입니다.
신뢰할 수 있는 task 수행, 경험에 대한 겸손과 존중을 지향합니다.





### 업무적 강점

웹서비스, 어플리케이션 서버 등 서비스 준비부터 오픈 운영까지 개발 경험 및 강한 서비스 마인드

웹서비스의 frontend, backend 경험

개발 및 업무적 dependency의 최소화






### 개발자로서 중요하게 생각하는 것
- 철저한 데드라인 준수
- 안정적인 서비스 배포 및 운영
- 긍정적인 커뮤니케이션
- 최소한의 데이터베이스 자원 사용
- 효율적인 개발 환경의 구축
- 반복적인 루틴에 대한 자동화
- 이유있는 코딩





### 경력 요약

2018.06 ~ 현재&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;펫닥&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;R&D 센터 개발팀 / 매니저

2017.12 ~ 2018.04&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;바이플러그&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;부설기술연구소 / 주임연구원

2016.07 ~ 2017.12&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;영우씨엔아이&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;부설기술연구소 / 사원

2015.12 ~ 2016.07&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;하루소프트&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;개발팀 / 사원





### 학력 사항

2006 ~ 2013&nbsp;&nbsp;&nbsp;&nbsp;가톨릭대학교 미디어콘텐츠기술 학사 전공





### 최근 프로젝트

##### (주)펫닥

##### 펫닥 맞춤형사료 추천 서비스 구축

반려동물 데이터 기반 사료 추천 웹/앱 서비스

 - 주요 업무
    - 프로젝트 리드 개발
    - 기획서 분석 및 데이터베이스 설계
    - api 서버 및 웹서버, 앱서버 backend 개발
    - pc 및 모바일 웹 frontend 개발
    - 서비스 배포
 - 개발환경
    - java, spring boot, jquery, mysql
 - 배포환경
    - aws ec2, elb, rds
 - 주요 성과
    - 서버인스턴스, 로드밸런서 무중단배포를 직접 구현하였고 vpc 서브넷으로 각 서버들의 접근 영역을 명확하게 나눴습니다. jenkins서버를 직접 구축하면서 배포자동화를 구성하였고 인증api서버, 인증웹서버, 서비스 api서버, app서버, 웹서버, jenkins 및 터미널서버 등 기능에 따른 서버를 분리한 MSA의 기본적인 부분을 경험했습니다.
    - ec2 redis 인스턴스 (개발용), elastic cache(배포용) 환경을 구성하여 반복되는 select 요청은 캐시 처리를 두어 데이터베이스 커넥팅을 최소화하였습니다.
    - 기획서 분석 단계부터 앱 클라이언트, 인증서버 개발 파트와 지속적인 미팅을 통해 미리 api 명세를 작성, 관리하여 전반적으로 효율적인 개발 프로세스를 정립할 수 있었습니다.



##### (주)펫닥

##### 펫닥 웹서비스 구축

수의사 기반 반려동물 토탈케어서비스 펫닥 웹

 - 주요 업무
    - 웹서버 backend 개발
    - pc 및 모바일 웹 frontend 개발
 - 개발환경
    - java, spring boot, jquery, postgresql
 - 배포환경
    - aws ec2, postgresql
 - 주요 성과
   - 기존 레거시 서버의 api 엔드포인트 일부를 새로운 서버로 옮기는 작업을 진행했습니다. 매번 앱을 업데이트하기란 불가능했기에 aws API Gateway를 통해 유연하게 api 이전 작업을 진행했습니다.
   - js 즉시실행함수를 활용한 global scope 변수 선언 방지, 랜더링에 대한 플래그 변수 등등 견고한 프론트엔드를 구성하도록 신경썼으며 backend의 cache 활용 및  frontend의 효율적인 element selector사용으로 구글 page speed insight 속도측정에서 최고 95점 이상을 기록했습니다.
   - 서비스 콘텐츠의 검색엔진 노출을 위해 각 리스트 페이지의 1페이지만 SSR을 진행했고 다른 부분은 ajax call로 동적 로딩을 구성하였습니다.
   - java/spring boot로 진행했던 첫 프로젝트이며 개발할 때 특정 언어와 프레임워크가 서비스를 결정짓는 요소가 아니란 것을 경험했습니다. 그동안 python/django로 개발 할 때와 비교해보며 스크립트와 컴파일 언어의 차이를 실제 경험으로 느끼게 되었고 spring과 django의 내부 기능을 비교해보며 서비스 개발에 대한 이해를 높이는 경험을 했습니다.



##### (주)펫닥

##### 펫닥 서버 고도화

수의사 기반 반려동물 토탈케어서비스 펫닥 어플리케이션

 - 주요 업무
    - 서버 개발 및 운영 배포 개선
 - 개발환경
    - python, django, postgresql
 - 배포환경
    - aws elastic beanstalk, docker, postgresql
 - 주요 성과
   - 최우선적으로 ORM의 쿼리 최적화를 진행하였고 캐시를 도입해 상당 부분의 서비스 속도를 개선했습니다. 전반적인 개선 후 상담서비스 리스트 페이지는 약 70% 정도 속도 개선을 이루었고 부하 테스트에서도 약 50% 정도 향상을 이끌었습니다.
   - admin 및 배치 기능의 서버를 따로 분리하여 필요한 부분의 배포를 독립적으로 이끌었고 dev, live 환경 외에 qa 환경을 두어서 실제 라이브에서 어떻게 동작하는지 테스트 가능하도록 구축했습니다. 그리고 위키를 통한 서버 포지션에 대한 문서화를 진행하였습니다.
   - api 각 기능에 대한 유닛테스트를 구성하였으며 jenkins를 활용해서 테스트 자동화를 적용했습니다. dev 브랜치 merge 완료 후 자동으로 테스트 빌드를 실행하며 테스트 실패 시 서비스팀 전체에 slack으로 알림을 발송하여 서버 이슈에 대해 공유했습니다. 이후로 반복되는 코드제거 및 타입을 표시한 변수 이름 선언등 가능한 명확한 코드를 작성하는데 시간을 기울였습니다.



##### (주)펫닥

##### 펫닥 서버 리뉴얼

수의사 기반 반려동물 토탈케어서비스 펫닥 어플리케이션

 - 주요업무
    - 서버 개발 및 운영 배포 구현
 - 개발환경
    - python, django, postgresql
 - 배포환경
    - aws elastic beanstalk, docker, postgresql
 - 주요 성과
   - 기존 데이터베이스의 마이그레이션 및 새로운 DB 설계를 참여했고 DRF를 활용한 전반적인 서버 api를 담당하였습니다.  aws beanstalk, docker로 배포 진행하였으며 aws sns 서비스를 사용하여 모바일 푸시 서비스를 구성하였으며 celery, redis로 비동기적 태스크를 구성, 대량 발송에 대응하였고 반복되는 루틴의 푸시알림은 admin에서 컨트롤 할 수 있도록 구성하였습니다.



##### (주)펫닥

##### 서울수의사회 웹사이트 구축

서울수의사회 소개 및 교육신청 관리 웹서비스

- 주요 업무
  - 웹구축 전반

 - 개발환경
    - python, django, postgresql,  jquery, html, css
 - 배포환경
    - aws elastic beanstalk, postgresql
 - 주요 성과
   - 웹사이트 전반을 담당하였습니다. 아임포트를 활용한 결제기능을 도입하였고 소규모 프로젝트였기 때문에 마크업도 담당하였습니다. 사이트 관리자의 편의성을 돕기 위해 이미지 업로드 시 리사이징 기능을 도입했으며 썸네일 라이브러리를 사용하여 초기 로딩을 단축했습니다.



##### (주)바이플러그

##### fadein 모바일 웹서비스 구축

목표관리 모바일 웹서비스 fadein

 - 주요 업무
    - 서비스 구축 전반
 - 개발환경
    - python, django, mysql, angular
 - 배포환경
    - aws ec2, mysql
 - 주요 성과
   - fadein 서비스 개발 및 유지보수



##### (주)영우씨엔아이

##### webtex3d, little smart, elite 웹서비스 구축

의상 시뮬레이션 및 코디네이트 웹서비스

 - 주요 업무
    - 프로젝트 리드 개발
 - 개발환경
    - python, django, jquery, postgresql
 - 배포환경
    - windows 물리서버, apache, uwsgi, postgresql
 - 주요 성과
   - 시뮬레이션, 코디네이트 웹서비스 개발 및 유지보수
