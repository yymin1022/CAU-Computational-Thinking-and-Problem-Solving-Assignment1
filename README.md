# 작성이 완료되지 않은 README.md입니다.
# Not completly written yet.

# 컴퓨팅적 사고와 문제해결 : 과제 1
## 중앙대학교 소프트웨어학부 19학번 유용민(391040342)

> 문제 1 : 절대값 출력하기 / [소스코드 열기](과제1.py)
![Code_Preview](/Images/과제1.jpg)
if-else 조건문을 통해 양수, 음수의 여부를 파악하고, 음수일 경우 입력된 값에 -1을 곱해 절대값을 구한 뒤 출력하는 코드입니다. 입력값이 0인 경우에는 프로그램을 종료합니다.

> 문제 2 : 리스트에서 데이터 찾기 / [소스코드 열기](과제2.py)
![Code_Preview](/Images/과제2.jpg)
주어진 동 요소들을 리스트로 선언합니다. 이후 입력값이 리스트 내에 존재하는 동일 경우 해당 동의 index값을 출력하고, 존재하지 않는 경우에는 append()함수를 이용해 리스트의 마지막 요소로 추가해줍니다.

> 문제 3 : 식당 메뉴표 / [소스코드 열기](과제3.py)
![Code_Preview](/Images/과제3.jpg)
Dictionary를 이용해 주어진 메뉴와 가격을 저장해둡니다. 프로그램 실행 시, Dictionary로부터 메뉴만을 추출해 String으로 변환하여 사용자에게 출력해줍니다. 입력받은 메뉴가 Dictionary에 존재하는 메뉴일 경우, 해당 메뉴의 가격을 불러와 출력하고, 존재하지 않는 경우에는 지정된 문구를 출력합니다.

> 문제 4 : 오름차순 출력 / [소스코드 열기](과제4.py)
![Code_Preview](/Images/과제4.jpg)
while 반복문을 이용해 사용자로부터 숫자를 입력받아 리스트로 저장하는 과정을 반복합니다. 입력값이 0인 경우에는 break함수를 호출해 반복문을 종료한 뒤 리스트를 sort()함수를 이용해 오름차순으로 정렬하여 출력합니다.

> 문제 5 : 구구단 / [소스코드 열기](과제5.py)
![Code_Preview](/Images/과제5.jpg)
시작단과 끝단의 숫자를 입력받되, 문제에서 지정된 조건에 따라 시작단과 끝 단 사이의 차가 3 이하가 되어야 합니다. 시작단과 끝단 사이의 차의 크기에 따라 출력시 간격이 달라지며, 이는 적절한 규칙성을 찾지 못해 String으로 하드코딩하였습니다. for 반복문을 이용해 각 단을 1부터 9까지 곱하는 작업을 반복 및 출력합니다.

> 문제 6 : 경주 게임 / [소스코드 열기](과제6.py)
![Code_Preview](/Images/과제6.jpg)
프로그램 시작시 먼저 두 플레이어의 이름을 입력받습니다. 이후 두 플레이어가 각각 주사위를 던지는 작업을 수행한 뒤 주사위 값 만큼 위치를 이동합니다. 위치가 30 이상인 경우 해당 플레이어가 이긴 것으로 처리하며, 동일 회차에 두 플레이어가 모두 30 이상의 위치에 도달한 경우는 무승부로 처리합니다.

> 문제 7 : 사인그래프그리기 / [소스코드 열기](과제7.py)
![Code_Preview](/Images/과제7.jpg)
sin()함수의 경우 각도를 Degree 단위가 아닌 Radian 단위로 입력해 주어야 합니다. sin 그래프의 한 주기는 0부터 2π까지로 이루어집니다. 20개의 \*을 이용해 그래프를 그리게 되므로, for 반복문에서 i값이 20일 때 2π가 되도록 sin() 함수의 파라미터 값을 수식으로 지정해줍니다. sin함수의 값은 -1부터 1까지의 값을 갖게되므로, 이에 10을 곱하면 -10부터 10이 되고, 이 값에 10을 더해주면 0부터 20 사이의 값을 갖습니다. 이 0부터 20이라는 값을 개수로 공백이 출력되도록 하고, 이 이후에 \*이 출력되도록 하면 sin그래프의 한 주기가 출력됩니다.
