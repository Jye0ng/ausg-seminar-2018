## 아키텍쳐 개요
이 모듈에서는 C9을 통하여 만든 프로젝트를 외부 인원과 공유하여 사용해봅니다. 
공유하기 이전에는 [IAM](http://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/introduction.html)을 사용하여 권한 정책을 사용자에게 부여할 수 있습니다.
![c9withfriend](./../images/c9withfriend.png)

## Chapter 3. C9 친구와 작업하기
1. 우측 상단 **Share** 버튼 클릭
1. **create a new user** 클릭
1. **사용자 이름** 에 `friend` 입력
1. **액세스 유형** 에 **AWS Management Console 액세스** 선택 -> **다음:권한** 선택
1. **그룹 생성** 선택
1. **그룹 이름** `cloud9user` 입력 -> **cloud9** 검색 -> `AWSCloud9User` 선택 -> **그룹 생성** 선택
1. **다음:검토** 선택 -> **사용자 만들기** 선택
1. **비밀번호** 를 복사 -> 이메일 전송 -> **로그인 URL**과 **사용자 이름** **비밀번호** 를 친구에게 알려주기
1. **친구는 이메일로 온 메일에 접속하여 비밀번호를 변경 후 접속해야 함**
1. **친구**는 **cloud9** 말고는 다른 리소스에 접근할 권한이 없음
1. 다시 콘솔에서 **Invite Member** 에 친구의 ID 입력-> **Invite**
1. 초대받은 친구는 Cloud 9 **좌측 탭**에서 **Shared with you** -> 이전에 만든 환경 c9 접속
1. 동시에 같은 프로젝트를 편집할 수 있음

실습이 완료되면 다음모듈인 [Chapter 4. Elastic BeanStalk](../4_eb) 으로 이동하십시오