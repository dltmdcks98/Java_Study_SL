============================
1.주차장 관리 프로그램
===========================
1-1 Park클래스
*Park 클래스에는 아래와 같은 멤버변수(fields)들어있다.
-차량번호
-들어온 시간(1234 라고 입력하면 12시 34분)

2.주차장은 5칸짜리 주차장이다. 칸은 ArrayList로 관리하게 된다.
3.무한반복문을 통해서 종료를 누르기 전까지 계속 실행된다.
4.프로그램 개요
4-1)차량입고 선택시
(1)주차장내에 빈칸이 있는지를 확인한다.
(2)차량이 입고된 기록이 있는지 찾는다. 있으면 잘못된 입력이라고 출력,
(3)차량이 입고된 기록이 없으면 시간을 기록한다.
시간은 int로 입력을 받으며, 잘못된 시간을 입력시 다시 입력하라고 지시
(4)차량번호와 시간 모두 사용자가 올바른 값을 입력할떄까지 다시 입력을 받는다.

4-2) 차량출고선택시
(1)주차장에 주차된 차량이 존재하는지 체크
(2)차량이 주차된 기록이 존재하면 사용자로부터 차량번호를 입력받는다.
(3)일치하는 차량을 찾으면 나가는 시간을 입력받는다.
(4)2,3번의 경우 사용자가 올바른 입력을 할때까지 다시 입력을 받는다.
(5)시간의 차이를 계산여 10분당 1000원의 요금을 적용
(6)차량이 나간 칸을 비워준다.
 
