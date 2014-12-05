# Scrum and XP from the Trenches

* Written by Henrik Kniberg on Jun 27, 2007
* Foreward by Jeff Sutherland
  * Ken Schwaber와 함께 scrum 창시자
* Foreward by Mike Cohn
  * 애자일 연합과 스크럼 연합의 창립 멤버
* Preface - Hey, Scrum worked!

## Introduction

### Disclaimer
### Why I wrote this
### But what is Scrum?

## How we do product backlogs

* product backlog
  * 우선순위가 매겨진 요구사항, 스토리, 기능 등의 목록
  * 고객의 용어로 기술
  * product owner가 관리
  * 비즈니스 목표에만 집중해서 관리, 문제 해결 방법은 팀이 수행
* backlog items, stories
  * id
  * name
  * importance
  * initial estimate (unit:story points, ideal man-day)
  * how to demo
  * notes
  * extra fields: track, component, requestor, bug id

### Additional story fields
### How we keep the product backlog at a business level

## How we prepare for Sprint planning

* sprint planning
  * product backlog ready! exist! product owner!
  * different importance ratings for only sorting

## How we do Sprint planning

* output of the sprint planning meeting
  * A sprint goal
  * A list of team members (and their commitment levels, if not 100%)
  * A sprint backlog(= a list of stories included in the sprint)
  * A defined sprint demo date
  * A defnied time and place for the daily scrum

### Why the product owner has to attend

* each story contains three variables
  * Scope (is set by the product owner)
  * Importance (is set by the product owner)
  * Estimate (is set by the team)
* 회의는 product owner가 스프린트 목표와 중요한 스토리를 요약하는 것으로 시작

### Why quality is not negotiable

* external quality : user가 느끼는 품질
* internal quality : 유지보수에 영향을 끼치는 품질
* 낮은 IQ에서 높은 EQ는 기대하기 어렵다
  * EQ를 scope의 범주로 보고 product owner가 판단한다
  * IQ는 논의대상이 될 수 없고 팀이 책임져야할 사항

### Sprint planning meetings that drag on and on...

* 스크럼에서 모든 것들은 timebox를 가진다

### Sprint planning meeting agenda

* planning meeting은 장시간을 요구하는 회의라서 agenda를 짜놓는게 중요
* example
  * 13:00 ~ 13:30 product owner가 sprint goal 검토, product backlog 요약, 데모 장소와 날짜, 시간을 결정
  * 13:30 ~ 15:00 팀이 시간을 추정, 필요에 따라 항목 세분화, product owner가 중요도 업데이트, 중요도가 높은 항목에는 데모 방법 기입
  * 15:00 ~ 16:00 팀이 스프린트에 포함시킬 스토리 선정, 속도 계산해서 실현 가능성 검토
  * 16:00 ~ 17:00 일일 스크럼 회의 시간과 장소 결정, 스토리를 작업 단위들로 세분화

### Defining the sprint length

* short sprint: 짭은 피드백, 잦은 출시, 잦은 고객 피드백, 잘못된 방향에 따른 시간 낭비 감소
* long sprint: 팀이 추진력을 얻기 위한 충분한 시간
* 권장 3주

### Defining the sprint goal

* 기술적인 용어가 아닌 비즈니스적인 말로 나타내야 한다
* 목표는 팀 외부로 공개하는게 효과적

### Deciding which stories to include in the sprint

* stories from the product backlog to copy to the sprint backlog
* product backlog 목록을 중요도에 따라 정렬하고 스토리 점수로 표현되는 시간 추정치가 반영되어 있고 팀의 추정 속도를 안다면, 다음 스프린트에서 완료할 수 있는 스토리가 (이상적으로) 결정된다
* 해당 스프린트에 얼마나 많은 스토리를 포함할지는 팀이 결정 (제품 책임자도 아님)

### How can product owner affect which stories make it to the sprint?

* 중요도에 따른 순서 재조정
* 스토리의 범위 변경
* 스토리 분할

### How does the team decide which stories to include in the sprint?

* 팀이 할 수 있는 기법은
  * 직감 - 작은 팀과 짧은 스프린트에 효과적
  * 속도 계산 - 추정 속도 정하고, 그 내에서 스토리를 얼마나 추가할 수 있는지 계산
    * 팀 이력을 보고 속도 추정
    * man-day & focus factor
      * 투입 자원(man-day) vs 스토리 점수상의 이상적인 man-day
      * 집중도 (focus factor) = (실제 속도) / (가능한 man-day)
      * 이번 스트린트 추정 속도 = (가능한 man-day) x (집중도)

### Why we use index cards

* 엑셀보면서 토의하는 것보다 index card가 낫다
* (아마도) 엑셀 형태로 되어있는 product backlog에 반영
* 시간 추정
  * 스토리를 작업 단위로 나누고 나면 쉽고 정확해짐 (task breakdowns)
* task breakdowns는 product backlog에 반영 안함
  * 일시적으로 만든거고 일하면서 빈번히 바뀔꺼고
  * 세부적인 사항을 굳이 넣을 필요는 없지

### Definition of “done”

* product owner와 team이 해당 sprint의 done에 대한 명확한 정의를 합의하는 것이 중요

### Time estimating using planning poker

* 팀원 전원 참여
  * 누가 어떤 스토리의 어느 부분을 구현할지 안 정했으니까
  * 스토리 구현을 위해서는 다양한 분야의 전문가 필요
  * 추정치 제시하기 위해서는 스토리가 어떤 것인지 어느 정도 이해할 필요가 있으니까
* planning poker
  * 0, 1/2, 1, 2, 3, 5, 8, 13, 20, 40, 100, ?, coffee
  * 20쯤 되면 너무 크다. 작게 만들어야 함

### Clarifying stories

* 스토리 점수로, 중대한 오해를 발견할 수 있음
* 스토리 데모로, 중대한 오해를 발견할 수 있음

### Breaking down stories into smaller stories

* 너무 작으면 안됨 - 미시적으로 관리한다는 얘기니까
* 너무 크면 안됨 - 계획하고 추정하기가 힘들어지니까
* 작게 나누더라도
  * 비즈니스 가치를 제공
  * 출시 가능한 단위인지 확인
* 2~8 man-day
* usually, 40~60 velocity

### Breaking down stories into tasks

* story vs task
  * story는 product owner가 care about하고 deliverable 한 것

### Defining time and place for the daily scrum

* 오전 스크럼 추천: 어제 뭐했냐 보다 오늘 무엇을 할지가 중요

### Where to draw the line

* 회의 내에서 결정되어야할 우선순위별 사항
  * 스프린트 목적과 데모 날짜
  * 이번 스프린트에 포함하기로 인정한 스토리 목록
  * 포함된 스토리에 대한 추정치
  * 포함된 스토리에 대한 데모 방법
  * 현실성 검증 차원에서, 속도 및 자원 계산
  * 일일 스크럼의 시간과 장소 결정
  * 스토리를 작업으로 나누기

### Tech stories

* 비기능적인 항목
  * product owner에게 직접적인 가치를 제공하는 것도 아니고 전달할 수 있는 것도 아니고 특정 스토리에 직접적으로 관련있지도 않는 기능
* 예
  * continuous build server
  * 시스템 설계 개요 작성
  * 리팩터링하기
  * jira 업데이트
* 어떻게 다루지?
  * 가능한 피하려고 해보고, 기존 스토리에 통합해보려고 하고
  * 별도의 목록으로 관리하고 product owner에게는 read-only로 보여주고
  * 이를 위한 투입률이나 집중도를 빼고 sprint planning meetting에서 계산

### Bug tracking system vs product backlog

* product owner가 우선운위가 높은 jira 항목을 가져와서 다른 스토리와 함께 다룬다
* product owner가 아예 스토리로 만들어온다
* 팀 집중도를 낮게 잡아서 스프린트 기간 내에 버그를 수정할만한 여력을 갖게 한다

### Sprint planning meeting is finally over!

## How we communicate Sprints

* 스크럼 마스터가 스트린트 정보 페이지 작성해서 메일로 배포
* 메일에 언급한 위키 페이지에 현재 진행중인 모든 스프린트 링크 나열
* 정보 페이지를 팀방 앞에 붙이기
* 데모 시일에 가까워올 때 확인 메일 보내기기

## How we do Sprint backlogs

### Sprint backlog format
### How the taskboard works

* 할일, 진행중, 완료, 스트린트 목표, 소멸차트, 계획에 없던 항목, 추가로 작업한 백로그 항목

### Example 1 – after the first daily scrum
### Example 2 – after a few more days
### How the burndown chart works

* 추정 속도가 보인다
* 일정 완수할 수 있을지 보인다

### Taskboard warning signs
### Hey, what about traceability?!
### Estimating days vs. hours

* days가 낫다. hours는 micromanaging이다

## How we arrange the team room

### The Design Corner
### Seat the team together!

* audibility
* visibility
* isolation

### Keep the product owner at bay
### Keep the managers and coaches at bay

* 이들은 개발 책임자, functional manager, scrum coach 등
* 초기에는 적극적, 그 후에는 간섭을 줄이고
* 개선 등의 의견 피력은 개별로 별개로 진행

## How we do daily Scrum

* 작업 현황판 업데이트
* 서서 15분

### How we update the taskboard

* 회의하면서 업데이트하기도 하고 미리 업데이트하기로 정하기도 한다
* 스크럼 마스터는 팀을 지원하고 장애물을 제거하는데 노력, 관리적인 수고는 줄여나가야함
* 팀원 전체 참가해서 기민하고 집중력을 높여야함

### Dealing with latecomers
### Dealing with “I don’t know what to do today”

## How we do Sprint demos

### Why we insist that all sprints end with a demo
### Checklist for sprint demos
### Dealing with “undemonstratable” stuff

## How we do Sprint retrospectives

### Why we insist that all teams do retrospectives

* 개선을 할 수 있는 최고의 기회

### How we organize retrospectives

* 일반적인 구성
  * 1~3시간
  * 스크럼 마스터는 스프린트 백로그를 보여주고, 스프린트 기간동안 어떤 중요한 사건과 결정사항 있었는지 요약
  * 한명씩 돌아가며 이야기하기 - 좋았던 거, 더 잘할 수 있었던 것, 다음 스프린트에서는 다르게 해보고 싶은 것
  * 추정 속도와 실제 속도 살펴보고 분석하기
  * 다음 스프린트를 잘 하기 위해 무엇을 할 수 있을지 구체적인 제안을 요약
* 화이트보드에는?
  * Good - 스프린트를 다시 한다고 하더라도, 이것들을 똑같이 반복할 것이다
  * Could have been better - 스프린트를 다시 한다면, 그것들을 다른 방법으로 할 것이다
  * Improvement - 향후 어떻게 개선할 수 있을지에 대한 구체적인 아이디어들
* 투표해서 다음 스프린트에서 적용해볼 것을 몇개 고른다 <- 스프린트마다 소수의 개선안에만 집중하라

### Spreading lessons learned between teams

* 스트린트 회고 회의록을 공유하라
* 누군가 한사람을 정해 모든 스프린트 회고에 참석하게 하여 지식의 교량 역할을 수행하게 한다. 비공식적으로.
  * 남의 말을 잘 듣는 사람
  * 활발한 토의를 위해 그런 질문을 던질 수 있는 사람
  * 모든 회고에 참석할만큼의 시간이 있는 사람
  * 팀이 직접 통제할 수 없는 개선 의견을 실행에 옮길 수 있는 사람

### To change or not to change

### Examples of things that may come up during retrospectives

## Slack time between Sprints

* 스프린트 데모와 회고를 끝낸 후에 팀과 제품책임자 모두에게는 정리할 정보와 아이디어들로 넘쳐날 것이다
* lab day

## How we do release planning and fixed priced contracts

### Define your acceptance thresholds

* 허용 기준 규칙
  * 중요도로 구분하게 할 수도 있다
    * >= 100: 반드시 포함
    * 50 ~ 99: 포함되어야하지만 다음 릴리스에 넣을 수 있다면 미룰 수 있다
    * 25 ~ 49: 필요하긴 하지만 다음 큰 릴리스에 끝낼 수 있다
    * < 25: 확실하지 않거나 필요하지 않을지도 모른다
  * 색깔도 칠한다
    * 빨강: 반드시 포함되어야 함 (>= 100)
    * 노랑: 포함되었으면 함 (50 ~ 99)
    * 녹색: 지연되어도 됨 (< 50)

### Time estimate the most important items

* 릴리스 계획을 하기 위해서는 제품 책임자가 적어도 계약서 상에 포함된 모든 스토리에 대해 추정을 해야한다
* 스프린트 계획을 할 때와 마찬가지로
  * 팀이 추정
  * 제품 책임자는 항목을 설명하며 질문에 답
  * 너무 많은 시간을 들이지 않게 하라
  * 시간 추정은 단순하고 완벽하지 않는, 단지 추정일 뿐이며 확정은 아니다라는 것을 이해시켜라

### Estimate velocity

### Put it together into a release plan

### Adapting the release plan

## How we combine Scrum with XP

* 스크럼은 주로 관리 및 조직적 실천법
* XP는 주로 실제 프로그래밍 실천법

### Pair programming

* 코드 품질 향상, 팀 집중력 상승
* 코드 리뷰는 짝 프로그래밍의 좋은 대안

### Test-driven development (TDD)

* 테스트 주도 개발은 자동화된 테스트를 하나 작성하고, 그 테스트를 딱 통과할만큼의 코드를 작성한 다음, 주로 가독성을 높이고 중복을 제거하기 위해 코드를 리팩터링하는 것
* TDD는 시스템 설계에 긍정적인 영향을 미친다
* 새 제품에 TDD가 제대로 돌아가기까지는 시간이 걸린다
* 도구 - junit / httpunit/ jwebunit / testng / selenium / hsqldb / jetty / cobertura / mockup

### Incremental design

* 설계를 단순히 유지하면서 지속적으로 개선해나가는 것을 의미
* 리팩토링

### Continuous integration

* 빌드와 모든 테스트 실행

### Collective code ownership

### Informative workspace

### Coding standard

### Sustainable pace / energized work




## How we do testing

### You probably can’t get rid of the acceptance test phase

* 여기서 인수 테스트 단계란, 실제 출시가 가능한 버전이 나올 때까지 테스트, 디버깅, 재출시를 하는 전체 기간을 의미

### Minimize the acceptance test phase

* 이 단계는 정말 애자일이 아닌 것처럼 느껴진다
* 방법
  * 스크럼 팀에서 전달되는 코드의 품질을 최고로 높이기
    * 테스터를 스크럼 팀에 포함시킨다
    * 스프린트 작업량을 줄인다
  * 수작업 테스트의 효율성을 최대화하기
    * 최고의 테스터를 동원
    * 최고의 도구를 제공
    * 자동화할 수 있는 낭비적인 작업들을 보고하도록 하는 것

### Increase quality by putting testers in the Scrum team

* 스크럼 팀에서는 역할을 구분하지 않기 때문에 오로지 테스터 역할만 하는 사람을 두어서는 안돼~
* 테스터는 개발 완료된 기능을 실제 테스트하고 해당 개발자와 함께 완료 체크리스트나 릴리스 노트가 있는지 여부를 확인하고 수행한다.
* 스프린트 데모를 준비하기에 최적인 인물
* 테스트할 게 없는 동안에, 테스터는 테스트 준비 작업이나 테스트 코드 짝 프로그래밍에 참여한다
* 비프로그래밍 작업에 크게 기여할 수 있는 확률도 있다
  * 테스트 환경 구축
  * 요구사항 명확화
  * 운영 팀과 배포에 관한 세부 사항 협의
  * 배포 문서 작업 (릴리스 노트,  RFC 혹은 여러분 조직에서 정한 산출물)
  * 외부 인력과의 미팅
  * 빌드 스크립트 개선
  * 스토리를 작업으로 더 나누기
  * 개발자들이 필요로 하는 핵심 의문을 파악하고 답 구하기

### Increase quality by doing less per sprint

### Should acceptance testing be part of the sprint?

스프린트는 기간이 고정되는 반면, 인수 테스트는 기간을 고정하기 힘들다. 그래서 수작업 인수 테스트를 별도로 남겨준다.

여러 스크럼 팀이 작업하는 경우에 결과물을 합쳐서 수작업 인수 테스트를 해야한다.

### Sprint cycles vs acceptance test cycles

스트린트 사이에 시간 제한이 없는 릴리스 기간을 추가하고 그 기간에는 제품으로 릴리스 할 수 있는 버젼을 만들 때까지 오직 테스트와 디버깅만 수행하는 방식이 일반적이나 규칙적인 스프린트 심장박동을 깨뜨린다. 어차피 이 기간 이후에 긴급 버그 리포트가 나타날 것이므로 이를 처리할 준비를 해야만 한다.

그래서 새로운 것을 만들 때가 되었더라도 이전 것을 제품화하는 것에 우선순위를 두는 식으로 하고 있다. 즉 계획 수립 회의에서 직전 스프린트로 인한 버그를 수정하는데 예상되는 전체 시간을 감안하여 집중도를 낮게 설정한다.

### Don’t outrun the slowest link in your chain

테스터가 턱없이 부족하거나 코드 품질이 낮아서 인수 테스트 기간이 너무 늘어지고 있다고 한다면..
* 테스트가 수월해지도록 도구나 스크립트를 개발하라
* 자동화된 테스트 코드를 더 많이 넣어라
* 개발자 몇 명이 개발 업무 대신 테스트 업무를 하게 하라
* 스프린트 길이를 늘여서 인수 테스트를 스프린트에 포함시켜라
* 때론, 테스트 스프린트로 정의해서 수행하라
* 테스터를 더 고용하라

### Back to reality

만족스러운 품질 보증 프로세스를 가졌다고 보기 어렵지만, 그럭저럭 해왔다는 것만으로 긍정적인 효과를 보았다고 생각한다.

## How we handle multiple Scrum teams

### How many teams to create

### Synchronized sprints – or not?

### Why we introduced a “team lead” role

### How we allocate people to teams

### Specialized teams – or not?

### Rearrange teams between sprints - or not?

### Part-time team members

### How we do Scrum-of-Scrums

### Interleaving the daily scrums

### Firefighting teams

### Splitting the product backlog – or not?

### Code branching

### Multi-team retrospectives

## How we handle geographically distributed teams

### Offshoring

### Team members working from home

## Scrum master checklist

### Beginning of sprint
### Every day
### End of sprint

## Parting words

## Recommended Reading

* this book is a example and best practice. Inspect and Adapt!
* http://www.crisp.se/konsulter/henrik-kniberg
* http://www.crisp.se/scrum/checklist
* https://www.scrum.org/Portals/0/Documents/Scrum%20Guides/2013/Scrum-Guide-KR.pdf
* http://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-KR.pdf#zoom=100
