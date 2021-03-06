# Project2

팀장

2018202064 손승현(sonshn)

팀원

2014722004 박경원(tomorrowith)

2018202006 최지원(cjw1359)

2018202001 염지원(xx10222)

---

### 파일 비교 프로그램 구현하기

##### Project2 - Git 공동작업에서 구현해야하는 프로그램은 우분투 18.04에서 만든 두 파일을 서로 비교하는 프로그램이며, 자세한 내용은 아래와 같다.

---
+ 저장소 이름 : Project2

+ 두 파일의 이름 : **text1, text2**

+ 구현해야하는 함수명 및 함수 설명

  + filestat1, filestat2: 우분투에서 생성한 text1과 text2의 **파일정보**를 가져오는 함수

  + filetime1, filetime2: text1과 text2의 **파일 시간 정보**를 가져오는 함수

  + sizecmp: 두 파일의 **크기**를 비교하는 함수

  + blockcmp: 두 파일의 **블럭 수**를 비교하는 함수

  + datecmp: 두 파일의 **수정 날짜**를 비교하는 함수

  + timecmp: 두 파일의 **수정 시간**을 비교하는 함수

+ 각 함수들은 모든 팀원들이 각각 두개씩 나누어서 구현하였으며, 각자 구현한 코드를 합칠 때는 이 저장소의 collaborator로 모든 팀원들을 등록시킨 후, master branch에 직접 push하지 **않고 git의 pull request를 이용하여 진행함**

+ Project_2_git.pdf의 **gitHub Scenario** 부분을 참조하여 **팀장을 포함한 팀원 모두가 각자 branch를 생성하고 checkout하여 코드를 작성한 후, pull request를 통해 코드를 merge함**(pull request 이력 참조)

+ pull request를 close하기 전에는 pull request를 close해야하는 팀원을 제외한 나머지 팀원들이 확인했다는 내용의 댓글을 남긴 것을 확인한 후에 close해야한다.

+ 구현해야하는 각 함수들에 맞게 적절한 milestone과 issue가 작성되어야 한다. 주의할 점은 모든 issue는 각각 적절한 milestone에 할당이 되어야한다는 점이며, issue에는 적절한 Assignee를 지정해야한다.  **또 1인당 최소 1개 이상의 milestone을 생성해야 한다.**
  + 자료를 참고하여 함수 관련 issue의 각 step은 기반 기술조사, 코드 작성, 코드 리뷰로 나누었다.
  + 상황에 따라 자유롭게 milestone이나 issue의 추가가 가능하다.
