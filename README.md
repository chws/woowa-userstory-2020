# 1. 서비스 개요

## A. 주제

- 온라인 강의를 수강하는 학생들의 강의 수강 및 과제 트래킹 서비스

## B. 등장 배경 및 서비스 소개

- 코로나19사태의 향방이 불확실한 상황에서 대학생을 비롯한 학생들이 언제부터 오프라인으로 교육을 받을 수 있을 지 모르는 상황이다. 
- 온라인으로만 교육이 이뤄지고 있기 때문에 어떤 수업을 듣고 있는지, 들어야하는 동영상 강의가 얼마나 남았는지, 어느 과목이 어떤 과제가 있는지, 남아있는 과제가 며칠까지인지 등 대학생을 우선적인 타겟으로 하여 수강정보를 정리하고 기록할만한 강의 트래킹 어플리케이션을 제안한다.
- 코로나19 사태가 진정되고 오프라인 수업이 병행되어도 점차 온라인 비대면 수업을 늘려나가려는 정부의 방침으로 인하여 사용자 이탈을 막을 수 있다.


---

# 2. Persona 및 유저 스토리

## A. Persona

### 목적 정의

 - 강의/강의자마다 다른 출석체크 방식을 생각하지 않고 직관적으로 알고 싶다.
 - 학점을 어떻게 하면 잘 받을 수 있는지 한 눈에 파악하고 싶다.

### Persona 설명

| 학생A                                                        |
| ------------------------------------------------------------ |
| - 대학생<br />- 20대<br />- 온라인 수업 수강중<br /><br />**Needs**<br />- 수업 관련 챙겨야 하는 내용을 한 곳에 정리하여 한 눈에 파악하고 싶다.<br />- 알림을 받고싶다.<br /> |

## B. 시나리오

### 서비스 사용 전

우아대학교 학생A는 온라인으로 강의를 수강중이다. a 수업은 실시간 화상 강의로 진행되므로 교수가 호명하여 출석 체크를 하는데, 출석체크 방식을 착각하여 지각처리 되었다. 반면 b 수업은 수업 당일 아침에 강의가 사이버캠퍼스에 업로드 되고, 해당 강의에 대한 출첵퀴즈를 다음날까지 제출해야 하는데 날짜를 착각하여 결석처리 되었다. 출석체크만으로도 정신이 없는데, 한 학기에 2번 부과되는 큰 과제를 언제까지 제출해야 하는지 확인해야 한다. 출석 및 과제에서 잃어버린 점수를 만회하기 위해 학생A는 어떤 영역에서 점수를 더 얻으면 학점이 잘 나올지 고민하며 강의계획안 사이버캠퍼스에서 검색하여 컴퓨터에 다시 다운로드 받아 확인한다. 

### 서비스 사용 후

우아대학교 학생A는 온라인으로 강의를 수강중이다. a 수업은 실시간 화상 강의로 진행되므로 교수가 호명하여 출석 체크를 하는데, 앱으로부터 알림을 수업 시작 20분 전에 받아 제 시간에 출석할 수 있었다. 반면 b 수업은 수업 당일 아침에 강의가 사이버캠퍼스에 업로드 되고, 해당 강의에 대한 출첵퀴즈를 다음날까지 제출해야 하는데 그 사항을 앱에서 확인할 수 있었다. 시간을 계속 착각하는 학생A는 자신의 성격에 맞게 과제를 시간순으로 설정하여 당장 급한 과제가 무엇인지 알 수 있다. 중간고사를 치르고 난 뒤, 학생A는 자신이 어떤 영역에서 점수를 만회할 수 있는지 점수 체계 퍼센티지를 앱에서 쉽게 파악할 수 있었다. 



## C. 시나리오로부터 도출한 요구사항

- 강의별 출석 체크 방식을 설정할 수 있어야 한다.
- 과제 마감 날짜를 등록할 수 있어야 한다.
- 출석 및 과제 제출 시간이 다가오면 알림을 보내야 한다.
- 강의별 점수 체계 퍼센티지를 확인할 수 있어야 한다. 
