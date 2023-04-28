#### 2023-04-26 회고

- 플러터 freezed, getx, http, data class 구성 작업 남았음
- 정리한 내용들은 많으나 말로 설명이 잘 안되는 것들이 아직 많음
- 개인 홈페이지 재작업 필요

#### 2023-04-19 회고

- 반응형 UI 적용했는데 관련 레퍼런스 소스코드의 동작을 모른채 기존 소스와 어떻게든 밎춰보려고 시도했는데 잘 안되서 솟
 분석이 조금 더 필요
- 소스코드 모듈화 작업을 하다보니 어디까지 쪼개는게 맞을지에 대해서 의문이 들었음
- 모듈화하다보니 필요한 객체들 사용을 위해 파리미터로 넘기거나 정의해야 되는 일이
많은데 오히려 더 복잡할까봐 걱정됨
- 현 시점에서 잠시 작업 중지하고 현재 흐름을 그려보는 작업이 필요할듯함
- 테이블 뷰, 우측 UI (이벤트에 대한 동작 없이), 드로어 UI 구성 계획 잡아야함

#### 2023-04-15 ~ 2023-04-18 회고

- 좋은 레퍼런스를 찾는 것이 중요, 개발 전 초기 리서치 기간을 앞으로 늘리는 방향이 좋을 것으로 생각
- 개발 해 본 결과 UI 코드 작성 속도는 플러터 > 안드로이드 > 리액트 > 바닐라 JS 순
- 중복되는 컴포넌트들에 대한 모듈화가 잘 되어 있는 상태에서 새로운 코드 적용이 가능

#### 2023-04-14 회고

- 개발 진행할 때 항상 숲에서 나무로의 접근을 해야 함
- 플러터 위젯들에 대한 컴포넌트화 작업은 리액트와 비슷한데 조금 더 수월한 것 같음
- 플러터 테스트 코드 작성법에 대해 공부가 필요
- Android, React-Native, React Web, Flutter, iOS로 TODO 앱 작성 프로젝트 시작 전 TODO 앱에 필요한 기능이 무엇인지 파악 필요
- 플러터 DI / Usecase / Repository 구성에 대한 예제 검토 필요

#### 2023-04-13 회고

- Flutter Webpage UI 골격 설계 / 구현함
- 생각보다 Widget 사용은 간편하고 리액트나 안드로이드를 해봤다면 대충 이렇게 쓰겠지라고 생각되는 부분들이 많음
- 리액트보다 빌드 환경 셋업이 간편한 것 같음
- 1차적으로 UI 코드 작성하고 보니 중복되거나 위젯안에 또다른 위젯 안에 또다른 위젯이 들어가는 경우가 상당수 있어서 리팩토링 불가피할 것으로 보임
- 플러터는 파일명 짓는 규칙이 일반 프로그래밍 언어와 다름. 소문자로 작성, 길어질 경우 소문자와 언더바 조합으로 작성
- 개념 스터디도 중요한데 가끔은 잘 짜여진 레퍼런스 코드 참고하면서 바로 구현을 하는게 도움이 되는 것 같음

#### 2023-04-12 회고

- Flutter 스터디 진행
- 스터디 진행 및 이슈 처리 작업으로 인해 최근 팀 내 공유할 문서 제작을 하지 못하고 있음

#### 2023-04-11 회고

- 공부는 계속 지속 중이나 얉고 넓게만 공부하는 문제점이 있음
- 업무가 곧 바빠질 예정이라 공부와의 밸런스를 어떻게 둘지 고민
- React Web Front-end 이슈 대응 건이랑 Flutter Web page 신규 구현 건이 같이 들어온 상태라 우선순위 정리 작업이 필요
- 그 동안 해왔던 공부 내용들 중에 아직도 이해가 잘 안되는 부분들이 상당수 있음
- 최근 코딩 문제 풀이를 못한지 3일이 넘었음
  - 막연한 혹시나 모를 미래 이직에 대한 준비 활동인데 못하고 있으니 상당히 정신적으로 괴로움
  - 아직도 자료구조 + 알고리즘에 대해 자신이 많이 없는 상태라 더 그런것은 아닌지?
- 리액트하다가 갑자기 플러터로 업무 방향이 바뀌는 바람에 그간 동영상 강의나 개인적으로 구현하고 있던 소스들에 대한 정리를 하지 못해서 찝찝한 상태
- 영어 공부에 대한 걱정
  - 진행하다가 중단되고를 반복하다보니 학습이 제대로 안됨 / 영어 공부하고 있으면 코딩 공부는 언제하지에 대한 걱정이 있음
- 번아웃은 아닌데 최근 업무 집중이 예전보다 떨어짐 (날씨때문인지 업무 방향 변경 때문인지)
- 평일날 매일 이분야 저분야 조금씩 조금씩 공부하는 방식을 택했었는데 차라리 이틀/삼일/일주일 간격으로 몰아서 공부하는게 더 효율적일지 아니면 이대로 할지에 대한 고민이 점점 커짐
  - 고민이 커지는데에는 무엇인가 이유가 있지 않을까라는 생각
- 지난 몇달간 작게 크게 진행했었던 앱 또는 웹 프론트 페이지 소스 리팩토링을 깔끔하게 해서 나의 소스로 만들어보고 싶은데 실천으로 옮기질 못하고 있음
- 공부든 업무수행이든 현시점에 야근을 하거나 아침 일찍 출근을 하던가 해야하는데 둘다 안하고 있음
- 현재까지의 나의 이력 (한글 / 영문)을 작성해보았는데 보완할 점들이 보임
  - 각 도메인별 포트폴리오 / 동작 원리 등에 대한 지식 정리 / 개발 환경 최적화 / 이력서 전체에 대한 재리뷰
- 리액트 웹 페이지 이슈 중에 데이터가 중복되어 쌓이는 이슈가 있는데 이 이슈는 과거 수정한 것으로 아는데 다시 재현되었다고 해서 스트레스 받음
  - 2주전에 배포한 Commit 내용 다시 확인 필요 / 소스 레벨 검토 / 검토 후 수정까지의 소요 예상 시간 공지 / 검토로 인한 플러터 앱 개발 일정 관련 전체 공지 필요
- 주력 스킬을 계속 안드로이드로 유지할지 아니면 리액트나 플러터로 할지 아니면 아예 다른 것으로 선택할 지 결정을 해야함
- 개발을 안한 상태 또는 많이 해보지 않은 분야에 대해서 일정 산출하는 요령 습득할 필요가 있음