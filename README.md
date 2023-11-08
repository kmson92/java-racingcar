# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)


# 3단계 - 자동차 경주

* [O] 사용자로부터 값 입력
* [] 전진 값을 가지고 있는 객체 필요
* [] 0 ~ 9사이의 random 값 생성
* [] random 값이 4 이상일 경우 전진
* [] 자동차 상태를 화면에 출력한다

# 2단계 - 문자열 덧셈 계산기 기능 요구사항 분리

* [O] "" => 0. null => 0    OK
* [O] "1" => 1
* [O] "1,2" => 3
* [O] "1,2,3" => 6
* [O] "1,2:3" => 6
* [O] "//;\n1;2;3" => 6
* [O] "-1, 1, 2" => RuntimeException 예외 throw
