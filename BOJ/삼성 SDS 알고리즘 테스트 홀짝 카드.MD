시간제한 : 20 개의 input. 1초
메모리제한 : 전체 256MB (스택 1MB)

연아는 카드놀이를 좋아한다. 홀짝 카드놀이는 매우 쉬운 카드 놀이이다.

홀짝 카드놀이의 방법은 아래와 같다.

숫자가 적혀있는 짝수장의 카드를 숫자가 보이도록 테이블 위에 올려 놓는다.
연아가 2장의 카드를 고른다. (항상 연아가 고르며 상대방은 카드를 고르지 않는다.)
두 장의 합이 짝수인 경우, 골라진 두 장의 카드 중 한 장을 연아가 먼저 고른다.
두 장의 합이 홀수인 경우, 골라진 두 장의 카드 중 한 장을 상대방이 먼저 고른다.
모든 카드를 똑같이 나누어 가지게 되면 가져간 카드에 적힌 숫자의 합을 계산하여 더 높은 사람이 이기게 된다.
승부욕이 강한 연아는 이 게임에서 얻을 수 있는 최대 점수를 먼저 계산해 보려 한다.
카드의 정보를 받아 연아가 게임에서 받을 수 있는 최대 점수를 출력하는 프로그램을 작성하시오.


[제한조건]
카드의 수 NNN은 4 이상 10,000 이하이다.
카드에 적혀진 숫자는 1 이상 10,000 이하이다.
연아와 상대방은 두 장중 한 장을 고르게 되면 이기기 위해 노력한다. 즉, 일부러 적은 숫자를 고르거나 더 낮은 점수를 받는 카드를 고르지 않는다.
[입력]
맨 처음 테스트 케이스의 개수 TTT가 주어지며 그 다음 TTT개의 테스트 케이스가 주어진다. 각 테스트의 첫 줄에 카드의 수 NNN이 입력된다. 그 다음 줄에 NNN개의 카드에 적혀진 숫자가 공백으로 구분되어 입력된다.

[출력]
테스트 케이스 하나 당 한 줄씩 출력한다. 맨 처음 #x (x 는 테스트케이스 번호, 1부터 시작)을 출력하고 공백을 하나 둔 후 주어진 입력의 경우에서 연아가 받을 수 있는 최대 점수를 출력한다.

[입출력 예]
(입력)
3
8
1 4 4 12 3 17 18 4
10
17 11 16 1 19 18 13 12 8 13
20
3 3 5 14 5 11 17 18 1 5 13 14 3 14 18 6 2 7 13 13
Copy
(출력)
#1 50
#2 83
#3 129