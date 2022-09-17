# CS50

1. 2022.08.01 책에 있는 내용이 글로 읽기에는 벅차서 페어분이 소개해주신 강의를 들으면서 읽어가면 더 좋을 것 같아서 듣게 되었다.

2. 2022.08.03 오늘 들은 강의는 전에 책에서 봤던 ASCII코드와 유니코드에 대한 강의였고, 컴퓨터의 0과 1로 문자 표현 부터 ios의 기쁨의 눈물 이모지와 색상, 동영상을 표현하는 방식에 대한 설명이었다. RGB로 표현하는게 숫자로 이뤄진다는 점과 동영상이 사진의 모음인데 이것을 표현하기 위해 얼마나 많은 0과1이 필요한지 또 평상시 그냥 사용했던 이모지를 숫자로 나타내는 방식을 알고나니 기술이 엄청 발전한거구나 새삼 깨달았다.

3. 2022.08.05 오늘 강의 주제는 algorithm이었다. 알고리즘은 단순히 문제를 풀기위한 규칙들의 순서적 나열이며, 정확성과 효율성 두 가지 측면을 고려해서 작성해야한다. 이때 Pseudo Code를 작성하면 컴퓨터가 수행해야하는 일을 절차적으로 파악할 수 있게 도와준다. 강의 중에 책을 찢으셨는데 매우 인상적이었다.ㅋㅋ

4. 2022.08.07 오늘은 스크래치 기본편을 들었다. 스크래치는 스크래치블록을 통해 입력이 블록을 거쳐 출력되는 모습을 구현한 웹사이트이다. 알고리즘을 직접 짜보면서 눈으로 확인하는데 재밌었다.

5. 2022.08.08 오늘은 스크래치 심화편을 들었다. 이번에는 애니매이션의 효과를 내는 원리와, 조건문, 변수에 대한 내용이었고 마지막에 게임을 지원자를 받아서 진행하는걸 봤는데 재밌었다ㅋㅋㅋ 나도 케이크,,,

6. 2022.08.09 오늘 강의는 c언어 기초에 대해서 알려주셨다. 우리가 흔히 말하는 c언어, 자바,...의 언어들은 소스코드이고, 이를 컴퓨터가 이해할 수 있는 머신코드(0과1)로 바꿔야 하는데 이것을 해주는 프로그램이 컴파일러이고, 그 중 clang에 대해 알려주셨다. 그리고 샌드박스를 사용해 c언어 간단실습을 했다. #include <stdio.h> int main(void){printf("Hello world\n");} 라는 간단한 코드였고 옛날에 교양으로 배웠던 내용도 간간히 생각났다. stdio.h는 printf함수에 접근할 수 있도록 하는 것인데 저거 studio로 많이 쳐서ㅋㅋㅋㅋㅋ주의해야 했던 기억이랑 ; 적어주는거!!ㅋㅋㅋ

7. 2022.08.10 오늘은 문자열에 대해서 알아봤다. c언어에서는 변수를 선언할때 변수에 들어가는 값이 어떤 타입인지를 적어야한다. 샌드박스를 통해 실습했는데 터미널에서 make string 명령어를 사용하여 주어진 파일 안의 string 문자열 형식과 함수에 대해 코드를 컴파일 하고 실행하는걸 좀 더 간편히 할 수 있었다. 그리고 문자열을 받기 위해서 %s를 붙여 인자를 받아준다 이 때 s는 string의 s이다. 이렇게 사용하는 이유는 어떤 종류의 인자를 받는지 알려주기 위해서이다. c언어는 오래된 저수준의 언어라 내가 지금 배우고 있는 js와는 다르게 타입을 꼭 써주는등 규칙같은게 엄격한 느낌이 들었다. 그에 비하면 js는 굉장히 유연해보인다.

8. 2022.08.11 오늘 강의는 조건문과 루프!! 이 부분은 js와 크게 다른 건 없다. 가장 크게 다른 건 정수를 다루는 변수를 선언할 때 int 를 붙여 나타낸다는 점?? 그것말고는 while이나 for문으로 루프를 만드는 것과 무한루프를 만들지 않도록 조건을 잘 붙여줘야한다는 것을 알게됐다. 오늘은 굉장히 익숙한 내용이어서 무난했던 것 같다.

9. 2022.08.12 오늘 강의는 자료형,형식지정자,연산자에 대한 강의였다. %.2f를 사용하면 소수점 2번째 자리까지만 나타낼 수 있다. float가 필요한 이유는 소수점 표현이고, int가 있는데 long이라는 정수 데이터를 나타내는 데이터 타입을 쓰는 이유는 int는 40억까지 셀 수 있는 자료형이라 좀 더 큰 정수를 표현하기 위해서 long을 사용한다. char은 문자 하나를 표현하는 데이터 타입 연산자와 주석처리는 js와 거의 동일한 것 같다. 강의 중간에 python같은 경우는 ||을 or로 써도 된다고 하셔서 신기하다고 생각됐다.

10. 2022.08.13 오늘은 중첩루프와 사용자 정의 함수에 관련된 내용이었다. c 언어는 좌에서 우로 위에서 아래로 읽기 때문에 함수를 만들고 그 함수를 호출을 해야한다면 함수가 호출되기 전에 먼저 선언되어야한다. 하지만 프로토타입이라고 함수의 이름과 매개변수만 적은 코드를 윗쪽에 올려두고 세미콜론을 찍으면 눈속임?ㅋㅋ을 할 수 있어서 추상화를 하기 용이해진다. 중첩루프는 쉽게 말해 행과 열을 떠올리면 된다. 사용자 정의 함수는 사용자가 입력을 한 변수에 의해 출력 값이 함수 안의 식을 거쳐 나오는 것인데 이러한 사용자 정의 함수를 사용하면 장점이 코드의 재사용과, 유지보수에 유리함 즉 효율성이 좋아진다.

11. 2022.08.14 오늘은 메모리에 대한 수업이었다. 컴퓨터는 RAM이라는 물리적 저장장치를 포함하고, 우리가 작성한 프로그램은 구동 중 RAM에 저장되는데 이 때 RAM은 유한한 크기의 비트만 저장할 수 있기 때문에 그 유한한 비트를 넘어가면 오버플로우가 발생하게 된다. 이러한 문제는 실생활 속에서는 Y2K문제와 보잉 787에서 발생되었고, 이 문제를 해결하기 위해 많은 비용을 지불하게 됐다. 지금과 달리 옛날에는 메모리가 아주 값비싸서 설계 시 더 효율적이고 문제가 생기지 않는 방법을 위해 고군분투 했을 것 같다. 이와 관련된 문제를 어떻게 하면 좋을지 고민해보자라는 주제가 있었고, 메모리 사용에 대해 효율적으로 코드를 설계한다라고 생각했고, 다른 사람들의 의견 중에 오버플로우가 되기 전에 자동 초기화를 한다는 글도 봤는데 좋은 방법인 것 같아서 기록한다.

12. 2022.08.15 오늘은 컴파일이 주제였다. 컴파일링의 네가지 단계는 전처리,컴파일링,어셈블링,링킹이 있고, '전처리'에서는 #으로 시작되는 C소스 코드는 전처리기에 실질적 컴파일이 이뤄지기 전에 다른 파일의 내용을 포함시키라는 등을 알려준다. '컴파일'은 전처리한 소스 코드 생성 후 어셈블리라는 c언어보다 저수준의 언어로 변환시킨다 '어셈블'은은 어셈블리 코드를 오브젝트 코드로 변환 0과1로 바꿔주는 작업을 한다. 컴파일 되어야 할 파일이 여러개라면 다음 단계인 '링크'로 넘어가 여러개의 오브젝트 코드 파일을 실행가능한 하나의 오브젝트 코드 파일로 합쳐주고 이 단계들을 거치면 최종적으로 실행 가능한 파일이 완성된다!! 컴파일을 하는데 어셈블리 코드라는 과정을 한 번 더 거친다는 것이 신기했다 그동안 입력 컴파일 출력으로 생각하고 있어서 바로 0과1로 바꿀줄 알았는데 새롭게 알게된 내용이었다.

13. 2022.08.16 오늘 내용은 디버깅이었다. 버그는 코드에 들어있는 오류다. 디버깅(debugging)이라는 작업으로 버그를 식별하고 고친다. 프로그램은 일반적으로 빠른 속도로 연산을 수행하기 때문에 눈으로 실행과정을 직접 알아보고 싶다면 중지점을 사용하여 디버깅을 하면 된다. 콘솔에서도 이렇게 디버거를 넣고 하나씩 단계를 확인하면서 알고리즘을 풀었던 기억이 났다ㅋㅋㅋ 반복문등에서 매우 유용했다. 다른 방법으로는 이 강의에서 help50과 printf로 문제를 찾아가는 방법이 있었다. js로 비유하면 printf는 console.log()와 비슷한 것 같다.

14. 2022.08.17 오늘은 코드 정리에 대한 강의였다. 실습을 cs50 샌드박스로 하기 때문에 여기서 알려준 방법은 1. check50으로 코드가 잘 작동하는지 2. style50으로 코드가 심미적으로 괜찮은 코드인지 3. 고무오리에게 코드가 왜 잘 안짜지는지 약간 생각의자 + 걱정인형ㅋㅋ 이렇게 소개 시켜줬다. 그리고 강의 속 수강생들에게는 오리를 가져가도 좋다고 했다. 나도 오리 가져가고 싶다ㅋㅋㅋ 현실에 적용하려면 1. console.log나 debugger를 사용하여 코드가 잘 작동하는지 확인하거나 test를 위해 모카를 사용하는 등으로 적용하면 될 것 같고 2. 클린코드를 의미하는 듯 하다 리팩토링을 거쳐 클린코드를 만들도록 노력하거나 심미적인 부분에서 vscode에서는 prettier확장팩이나 정렬을 위한 단축키를 사용하면 도움이 될 것 같다. 3. 고무오리는 사실 이 강의를 듣기 전부터 강아지 인형이 있었다. 아직 그 인형을 보면서 고민해본적은 없지만 나중에 코드 짜면서 고민이 생기거나 생각할 일이 많으면 한 번 시도해보는걸로...

15. 2022.08.18 오늘은 메모리와 배열에 대한 학습을 했다. 각 데이터 타입마다 정해진 용량(예를 들면 char은 1바이트)이 있고, 컴퓨터 안에 RAM이라는 물리적 칩이 메모리의 역할을 하여 저장을 한다. 배열은 들어올 값의 갯수를 예측하기 어려울 때 혹은 여러 값들을 관리하기에 유용하게 사용할 수 있다. 오늘은 배열에 들어올 값을 정해두고 한정된 여러개의 값들을 정리하는 걸 배웠다. c언어에서 배열은 arr[n] n 부분에 들어올 값의 갯수를 적어주고 arr[0],...,arr[n-1]까지 적을 수 있고, 할당 시 arr[0] = 1 이렇게 적어주면 된다.

16. 2022.08.19 오늘은 배열과 루프, 전역 변수를 사용하여 좀 더 동적인 코드로 변환하는 강의를 들었다. c언어에서 숫자의 계산은 int/int=int가 나오므로 소수점을 고려한다면 float/float로 해주고 원하는 소수점 자리수 만큼 .nf를 해주면 된다. 루프 안에 사용자로부터 값을 입력 받는 함수를 작성한다면 값의 갯수에 상관 없이 값을 입력 받을 수 있다.

17. 2022.08.20 문자열의 배열에 대해서 학습하였다. 강의에서 문자열은 메모리에 문자 자료형 데이터들의 배열이라고 알려주고, 직접 인덱스를 통해 배열을 확인하는 시간을 가졌다. 이 때 형식 지정자는 문자 자료형을 출력하는 것이기 때문에 %s 대신 %c를 사용하였고, 문자열이 끝날 때 ₩n을 사용해주었다. 이 이유에 대해 생각해보자라는 글이 있어서 적어보자면 내 생각에는 각 문자열을 구분하기 위해 ₩n을 사용하는 것 같다. 그리고 댓글을 봤는데 나랑 비슷한 생각을 하신 분들이 대다수였다.

18. 2022.08.21 문자열의 활용에 대한 학습을 했다. 문자열의 길이를 구하는 함수와 그 함수를 이용하여 문자열에 있는 문자 하나 하나를 돌면서 다시 출력해보는 과정을 알려주었고, 이를 활용해 문자 하나 하나를 돌면서 소문자이면 대문자로 바꿔주는 과정도 배웠다. 소문자를 대문자로 변환해주는 함수도 있었고, 아스키 코드라는 점을 이용하여 모든 대문자와 소문자가 32 차이가 나고, 소문자 -32를 하면 대문자 변환이 된다는 것도 배웠다. 강의 중간에 키보드에 이런 대문자 처리하는 기능을 누르면 -32를 하여 대문자로 변환해준다고 하셨는데 평상 시 많이 쓰던 대소문자 변환이 이런 과정이었구나를 알게됐다.

19. 2022.08.22 오늘 강의는 명령행 인자에 대한 강의였다. c언어에서 main 함수에 받는 인자로 void가 아닌 명령행 인자인 argc, argv를 받을 수 있다. argc는 받을 인자의 수이고 argv는 받은 인자를 배열안에 넣는 명령행 메모리 목록이다. 이때 argc는 2개 이상일 때를 조건으로 걸어야 인자를 받았다고 하는 이유가 아무 인자를 넣지 않아도 argc 즉 argv[0]값은 파일명이 되기 때문에 다른 인자를 넣었다는 걸 argc 2개이상으로 처리하는 것이다. 이번 생각해보기는 명령행 인자를 사용했을 때 프로그램 확장성에 어떤 도움이 되는지 예시를 드는 것이었다. 코드가 간결해지는 것 외에는 잘 떠오르지 않았는데 다른 사람의 의견을 보니 코드 간결화랑, 프로그램 내부가 중도에 노출되더라도 인자로 사용된 데이터를 보호할 수 있다라는 의견도 있었다.

20. 2022.08.23 오늘부터는 ch.4 알고리즘이다. 오늘은 배열의 선형검색과 이진검색에 대하여 알아보았다. 선형 검색은 말 그대로 하나하나 자료를 살펴보는 것을 의미하며, 이진검색은 배열의 중간 인덱스부터 시작하여 찾는 값이 있으면 결과를 찾는 값이 없으면 조건에 따라 오른쪽 혹은 왼쪽으로 움직여 또 같은 작업을 반복하는 것이다. 자료가 정렬되지 않을 때와 정렬 됐을 때를 비교하여 정렬되었을 때는 이진검색이 훨씬 효율적이라는 점이 명확하였고, 이번 생각해보기 주제에서 나온 정렬되지 않은 상태에서는 어떤것이 더 효율적인가에 대한 나의 생각은 둘 다 무작위로 섞인 배열에서는 이진검색의 의미가 사라지는 것이므로 비슷할 것 같다고 생각했다.

21. 2022.08.24 오늘은 알고리즘 실행시간 표기법을 배웠다. 표기법에는 상한선인 Big O 와 하한선인 Big Ω가 있다. Big O는 최악의 경우 걸리는 실행시간이다. Big O는 O(n^2), O(n log n), O(n), O(log n), O(1)로 구분할 수 있다. 우리가 어제 배운 선형 검색은 O(n)이고, 이진 검색은 O(log n)이다. 반대로 Big Ω는 실행시간의 하한선이며, Ω(n^2), Ω(n log n), Ω(n), Ω(log n), Ω(1)이 있다. 이 때 이진 검색과 선형 검색은 운이 좋으면 한번에 바로 찾을 수 있으므로 Ω(1)에 해당된다. 배열 안에 존재하는 값의 개수 세기 같은 경우는 Ω(n)에 해당된다. 알고리즘 설계 시 둘 다 중요한 개념이지만 상한선인 Big O가 최악의 경우까지 고려한 실행시간이니 둘 중에서 중요도는 대부분 Big O이다. 이를 고려하여 설계하면 좋다.

22. 2022.08.25 오늘은 선형검색에 대한 강의였다. 찾고자 하는 자료를 검색하는데 사용되는 알고리즘 중 하나이며, 원하는 원소가 발견될 때까지 처음부터 마지막 자료까지 차례대로 검색하는 정확하지만 효율성에서 떨어지는 방법이다. 최악의 경우에는 자료 맨 끝부분에 원하는 값이 있거나, 아예 없는 경우에는 n번까지 찾아봐야하기 때문이다. 물론 최선의 경우에는 첫 번째에 원하는 값이 있을수도 있지만 보통 최악의 경우를 살펴보기 때문에 효율성이 매우 떨어진다고 할 수 있다. 이런 선형검색을 써야할 때는 자료가 정렬되지 않았거나, 그 어떤 정보도 없을 경우 무작위로 찾아보는 것보다 순서대로 찾는 것이 효율적이기 때문에 이럴 때 사용한다. 정렬이 된 상태라면 더 좋은 알고리즘 방법도 있을 수 있으니 항상 자료를 찾기 전 정렬을 할 수 있다면 해주는 것이 좋고, 오늘 강의에서 전화번호부(이름,전화번호)를 통해 정렬이 필요한 이유를 알게 됐고, 이와 비슷한 케이스로는 게임 유저들의 정보등이 있을 것 같다.

23. 2022.08.26 오늘은 버블 정렬에 대한 강의를 들었다. 버블 정렬은 두 개의 인접한 자료값을 비교하면서 위치를 교환하는 방식으로 정렬하는 방식이다. 버블 정렬은 단 두 개의 요소만 정렬해주기 때문에 너무 많이 교환하는 낭비가 생길 수 있다. 버블정렬의 실행시간은 O(n^2)이다. 이진탐색이 선형탐색보다 효율적이지만 정렬이 됐다는 조건 한이다. 버블 정렬을 하고 이진 탐색을 하는 방식이 어쩌면 더 시간이 걸리는 방법일 수 있으나 배열을 자주 반복해서 사용한다면 정렬을 해주는 것이 좋은 방법이라할 수 있다. 버블정렬이 효율적일때는 정렬해야 되는 과정이 적을 때이고 비효울적일때는 정렬 과정이 많을 때 인 것 같다.

24. 2022.08.27 오늘 강의는 선택 정렬이었다. 선택 정렬은 배열 중 가장 작은(혹은 큰) 값을 찾아 첫번째(혹은 마지막)위치의 수와 교환해주는 방식의 정렬이다. 선택 정렬은 교환 횟수를 최소화하는 방면 각 자료를 비교하는 횟수는 증가, 소요시간의 상한 O(n^2) 하한 Ω(n^2)로 버블 정렬과 같다. 이 선택 정렬을 좀 더 효율적으로 바꾸는 방법에 대해 물어보았는데 첨에 최소/최대 값을 기억하게 하면 되려나 싶었지만 어짜피 정렬을 하면서 기억을 하는게 아닌가라는 생각이 들었고, 댓글을 확인했는데 여러 의견이 나왔다. 그 중 인상적인 건 어짜피 선택 정렬은 정렬이 된 상태여도 무조건 끝까지 돌기 때문에 단축 시킬 수 없다는 글이었다.

25. 2022.08.28 오늘 강의는 정렬 알고리즘의 실행시간에 대한 강의였다. 어제까지 선택정렬과 버블정렬의 상,하한은 n^2이었는데 버블정렬의 경우 조건문으로 만일 교체가 이뤄지지 않는다면, 이미 정렬이 된 상태이므로 바깥쪽 루프에 교환이 일어나지 않을 때 까지만 안쪽 루프를 실행한다는 걸 걸어둔다면 실행시간의 하한이 Ω(n)으로 줄어드는 효율적인 방법도 있었다. 생각해보기에 선택 정렬도 이와 같이 하한을 줄일 수 있는 방법이 있을지 물어봐서 잠깐 고민했는데 어제 생각과 같이 딱히 없을 것 같았다.

26. 2022.08.29 오늘은 재귀에 대한 강의 였다. 사실 강의 듣기 전에 재귀를 공부해서 내용 자체의 큰 어려움은 없었지만 재귀를 직접 구현하기는 아직 익숙치 않다. 동일한 작업을 하는 걸 작게 쪼개서 recursive case로 만들고 base case 즉 이 반복이 끝나는 점을 조건문으로 걸어 계속해서 함수를 호출하는 것이다. 이론은 쉽지만 잘 쓰기 위해서는 엄청 반복적으로 학습해야겠다. 생각해보기에서 반복문을 쓸 수 있는데 재귀를 쓰는 이유에 대해 물어서 반복문보다 간결하게 사용할 수 있을 때 예를 들면 몇 번을 반복해야 할 지 모르는 문제에 사용하면 된다. 중첩된 배열 같은 경우가 해당된다. 이럴때 사용하면 굳이 몇번이 중첩됐는지 알지 않아도 되기 때문이다. 아 그리고 강의에서 recursion 구글에 치면 하드코딩한 유머?,,, 보여줬는데 뭔가 했다ㅋㅋㅋㅋ

27. 2022.08.30 오늘은 병합정렬에 대해 공부하였다. 병합정렬은 왼쪽을 정렬하고 오른쪽도 정렬한 뒤 합쳐서 또 정렬하는 방식이다. 병합정렬의 실행 시간의 상한은 O(n log n)이다. 숫자를 반으로 나누는데 O(log n), 반으로 나눈 부분들 다시 정렬해서 병합하는데 각각 O(n)의 시간이 걸리기 때문이다. 실행 시간의 하한도 Ω(n log n)이다. 숫자들이 이미 정렬되었는지 여부에 관계없이 나누고 병합하는 과정이 필요하기 때문이다. 선택정렬과 버블정렬과 비교 시 병합정렬의 내가 생각하는 장단점은 먼저 단점으로 정렬이 이미 된 상태일 때도 n log n이라는 시간이 걸린다는 점 정렬을 위해 메모리가 좀 더 필요한점이고, 장점은 최악도 최선도 n log n 이라 최악의 상황에서는 가장 시간이 절약된다는 점이다.

28. 2022.08.31 오늘은 16진수와 메모리에 대한 내용이었다. 16진수는 Hexadecimal이라 표현하고 2진수를 잘 표현할 수 있다. 그 이유는 2^4가 16이기 때문이다. 16진수와 10진수의 구분법은 16진수로 변환 후에 Ox를 붙여 뒤에 오는 문자들이 16진수임을 밝혀준다. 메모리 주소는 우리가 만약 정수를 선언했다면 우리 컴퓨터 메모리 어딘가에 4바이트만큼 자리를 차지하여 저장되어있다. 이때 이 주소값을 알고 싶다면 '&'연산자를 사용하고 이 주소로 가고 싶다면 '\*' 연산자를 사용한다.

29. 2022.09.01 오늘은 포인터에 대한 공부를 했다. 예시로 int n = 50, int \*p = &n 이라는 코드가 있을 때 '\*' 은 포인터 연산자이고, 주소를 가리키는 역할을 한다. 포인터의 크기는 운영체제의 bit 수에 따라 크기가 달라진다. 32비트/64비트 난 사실 이번 생각해보기는 잘 몰라서 댓글을 봤는데 그동안 봐왔던 운영체제의 비트가 이렇게 연관이 있구나 하고 알아갔던 하루였다.

30. 2022.09.02 오늘은 문자열에 접근하는 새로운 방식을 공부하였다. 그 동안 string자료형을 사용하여 문자열을 출력하였지만, 포인터를 이용해 'char \*변수'로 작성해주면 컴퓨터가 해당 메모리의 주소로 가서 문자열의 첫번째 요소의 주소를 읽고 출력해준다. 문자열의 두번째 요소와 첫번째 요소와의 주소 차이는 1바이트이다. string 자료형을 정의해서 사용했을 시 장점은 직관적이고, 추상화가 잘 되어있다는 점이다.

31. 2022.09.03 오늘은 문자열의 비교에 대해 배웠다. 각각 다른 변수에 할당한 같은 문자열을 주소를 통해 접근하게 된다면 같은 문자여도, 다른 주소에 해당하기 때문에 일치하지 않는다고 나온다. 생각해보기에서 그렇다면 문자의 비교는 어떻게 하면 좋을지에 대한 주제 나왔는데 주소가 아니라 결과를 비교 한다는 의견과 댓글을 보니 if(strcmp(a,b) == 0)이라는 strcmp함수를 사용하고 있었다.

32. 2022.09.04 오늘은 문자열의 복사에 대해 배웠다. 사용자에게 입력값을 받아 string s에 저장하고 string t를 s로 정의 후 t를 대문자로 변환 시키는 함수를 작성하면 s에게도 적용이 된다. 그 이유는 문자열이 있는 주소를 복사했기 때문인데 string = char \* 와 같다보면 된다. 고로 문자열만 복사하고 싶은 경우 t에 메모리 할당을 하고, s문자열의 문자를 하나하나 돌면서 카피를 하면 된다. 이 때 malloc이라는 함수를 사용한다 이 함수는 정해진 크기만큼 메모리를 할당하는 함수이다. 이 함수를 사용할 때 문자열은 널 종단문자가 있다는 사실을 기억해서 값을 할당해야 한다.

33. 2022.09.05 오늘은 메모리 할당과 해제 대한 강의를 들었다. malloc함수를 이용해 메모리 할당 후에는 free함수를 이용해 메모리 해제를 해줘야 메모리 누수가 생기지 않는다. valgrind라는 프로그램을 사용하면 코드에서 메모리와 관련된 문제가 있는지 확인 할 수 있다. 예를 들면 앞에서 설명한 메모리 누수나 버퍼 오버플로우 등등이 있다. 제한된 메모리를 가지고 프로그래밍 시 메모리 해제를 하지 않으면이라는 주제가 생각해보기였고, 아마 메모리의 낭비가 발생하여 효율이 좋지 않을 것 같다. 댓글에는 메모리 부족 현상이 나타날 수 있다고 적혀있었다.

34. 2022.09.06 오늘은 메모리 교환, 스택, 힙에 대해서 학습하였다. 교환을 할 때 변수에 할당된 값 자체를 복사해서 값을 교환하려고 하면, 실패한다.그 이유는 메모리 안의 데이터 저장 방식 때문인데 메모리는 위에서부터 머신코드영역, 글로벌 영역, 힙 영역, 스택 영역이 있고, 그 중 스택 영역은 밑에서 부터 저장을 하는데 이 때 값을 교환하고자 하는 변수와 값을 교환하기 위해 만든 함수의 매개변수 예를 들면 int x, int y와 swap(int a, int b)는 다른 메모리 주소에 저장되어서 실제 x,y의 값에는 영향을 미치지 않는다. 이 때 해결법으로는 포인터를 사용해 x와 y가 있는 주소 자체를 복사한 뒤 바꾸는 방법이 있다. 생각해보기에서 메모리 영역을 다양하게 나누는 이유에 대해 물었고, 메모리에 저장된 값의 중요도(쓰임새)나 메모리 할당 시 메모리의 크기가 정해진 값들도 있지만 정해지지 않은 값도 있기 때문에 크기에 따라서 나뉠 수 있을 것 같다. 댓글을 보니 효율적인 사용을 위해서라는 의견이 많았다. 유사한 성질의 데이터끼리 묶으면 데이터 관리가 용이하고 접근 속도도 향상되기 때문이다.

35. 2022.09.07 오늘은 파일쓰기에 대해서 배웠다. 일단 메모리 구조로 머신코드에는 프로그램 실행 시 프로그램이 컴파일된 바이너리가 저장, 글로벌 영역에는 프로그램 안에서 저장된 전역변수 저장, 힙 영역에는 malloc으로 할당된 메모리의 데이터가 저장, 스택에는 프로그램 내의 함수와 관련된 것들이 저장되는데 힙 영역에서는 malloc에 의해 메모리가 더 할당될수록 메모리의 범위가 아래로 점점 늘어나고, 스택영역에서도 함수가 더 많이 호출 될 수록 사용하는 메모리의 범위가 위로 점점 늘어난다. 제한된 메모리 용량에서 기존 값을 침범하는 상황도 발생할 수 있는데 이를 힙 오버플로우, 스택 오버플로우라고 말한다.scanf에 s가 아닌 &s로 주소를 입력하면 scanf 함수의 변수가 스택 영역 안에 s가 저장된 주소로 찾아가 사용자가 입력한 값을 저장한다. get_string은 scanf에 s를 그대로 입력하는데 이는 s의 크기를 char 자료형 배열로 정의하고 또한 clang컴파일러는 문자 배열의 이름을 포인터처럼 다뤄 scanf에 s라는 배열의 첫 바이트 주소를 넘겨준다. 파일쓰기는 사용자로부터 입력을 받아 파일에 저장하는 프로그램을 작성할 수 있는데 fopen이라는 함수로 파일을 FILE이라는 자료형으로 불러올 수 있다. fopen의 첫번째인자는 파일이름, 두번째 인자는 모드로 r은 읽기,w쓰기 a는 덧붙이기다. 사용자에게 값을 입력 받은 후 fprintf함수를 이용해 printf처럼 파일에 직접 내용을 출력할 수 있다. 작업이 끝난 후에는 fclose함수로 파일에 대한 작업을 종료해줘야 한다. get_long, get_float, ger_char도 비슷한 방식으로 직접 구현할 수 있는지가 생각해보기였다. 형식 지정자만 바꾸면 될 것 같다.

36. 2022.09.08 오늘은 파일 읽기에 대한 강의였다. 파일 읽기는 어제 말한대로 r을 두번째 인자에 넣어주면 된다. 만약 fopen에서 에러가 발생하면 null을 반환하므로 이와 관련된 조건문을 넣어줘 에러핸들링을 할 수 도 있다. 파일이 잘 열리면 크기가 3인 문자 배열을 만들어 fread함수를 이용해 파일에서 첫 3바이트를 읽어온다. fread(배열, 읽을 바이트 수, 읽을 횟수, 읽을 파일)안에 인자는 이렇게 작성해주면 된다. 이번에 읽을 파일은 jpeg였는데 jpeg의 경우 0xff, 0xd8, 0xff로 형식이 정해져있다. 이는 jpeg형식의 파일을 정의할 때 만든 약속으로 jpeg 파일의 시작점에 꼭 포함되어 있다. 따라서 이를 검사하면 jpeg파일인지를 확인할 수 있다. 생각해보기에 다른 파일도 그 형식임을 알려주는 약속이 있는지 물어봤고, 있을 것 같다.

37. 2022.09.09 오늘 강의는 malloc과 포인터 복습에 대한 강의였다. int *y를 선언한 뒤 malloc으로 메모리 할당을 안하고 바로  *y = 8 으로 할당하게 된 코드를 강의 예시로 들었다. 이 경우 포인터로 선언만 하고 어디를 가리킬지 정의를 하지 않은 즉 초기화 되지 않은 *y는 프로그램 어딘가를 임의로 가리키고 있을 수 있고 이로 인해 13을 할당하는 것이 오류를 발생 시킬 수 있다. 생각해보기에서 포인터를 초기화시키지 않고 값을 저장하면 어떤 오류가 발생할 수 있을지에 대해 물어보았고, 방금 썼던 것 처럼 예상치 못한 곳에 값을 할당해 오류를 발생시킬 것 같다.

38. 2022.09.10 오늘 강의는 배열의 크기 조정하기였다. 배열의 크기를 키우는 것은 생각보다 어려운 일이다. 이미 할당한 메모리 옆자리에 다른 값이 이미 있을 수 있기 때문이다. 이 때 배열의 크기를 조정하는 방법으로는 크기를 키운 배열을 malloc을 이용해 만든다음 배열을 복사하여 옮긴 후 크기를 키워야 한다. 이 작업은 O(n)만큼 걸리게 된다. 이런 작업을 realloc이라는 함수를 사용할 수도 있다. 이번 생각해보기는 이미 할당된 메모리의 크기를 조절할 때 임시 메모리를 새로 할당해줘야하는 이유였고, 앞서 말했다싶이 이미 메모리에 값이 있을 수도 있기 때문에 임시 메모리를 할당해줘야 된다고 생각한다.

39. 2022.09.11 이번 강의는 '연결리스트 : 도입' 에 대한 강의였다. 데이터 구조의 개념과 연결 리스트에 대해서 새롭게 배웠는데 데이터 구조는 컴퓨터 메모리를 더 효율적으로 관리하기 위해 새로 정의하는 구조체이고, 데이터 구조 중에서 연결리스트는 메모리상에서 배열의 값이 연이어 있지 않더라도 다음 값의 메모리 주소(포인터)를 기억해서 값을 연이어 읽는 방법을 의미한다. 마지막 값은 다음 주소가 없기 때문에 NULL(0x0)을 다음 값의 주소를 넣는 곳에 넣게 된다. 이번 생각해보기는 연결리스트를 배열과 비교했을 때의 장단점에 대해 물어보았다. 내가 생각 했을 때 장점은 배열의 크기 조정 시 굳이 메모리가 연이어 붙어있을 필요가 없으니 더 수월할 것 같고, 단점은 주소를 입력하는 메모리가 추가적으로 필요하기 때문에 이런 메모리 손실이 있다는 점 이다.

40. 2022.09.13 이번 강의 주제는 연결리스트: 코딩 이었다. node리스트를 연결하는 것을 알려줬는데 한 번에 이해가 가지는 않았다...ㅜㅜ 최근에 깊이 우선 탐색(DFS)과 너비 우선 탐색(BFS)애 대해 아주아주 살짝 알아간적이 있었는데 이 연결리스트를 좀 더 심층적으로 다룬게 DFS, BFS인 것 같고, 이 내용은 js로 해도 아직은 이해가 되지 않아서 그냥 c언어로의 연결리스트는 이렇게 작성하는거구나를 봤다. 이번 생각해보기에서 연결리스트의 중간에 node를 추가하거나 삭제하는 코드는 어떻게 작성할 수 있을까에 대해 물었고, 추가는 이전 노드의 포인터를 추가하려는 노드를 가리키게 하고 추가 노드의 포인터를 그 다음 노드를 가리키게 하면 될 것 같다. 삭제는 삭제하려는 노드 이전의 노드의 포인터를 삭제하려는 노드 이후 노드를 가리키게 하고, 삭제하려는 노드를 해제하면 될 것 같다.

41. 2022.09.14 이번에는 연결 리스트: 시연 이었다. 연결리스트는 배열과 다르게 새로운 값을 추가할 때 다시 메모리 할당을 하지 않아도 된다는 장점이 있지만 연결리스트에 값을 추가하거나 검색하는 경우에 해당 하는 부분까지 연결 리스트의 각 node를 따라 이동해야 하기 때문에 연결 리스트의 크기가 n일 때 실행 시간이 O(n)이 된다는 단점이 있다. 배열의 경우에는 정렬이 된 경우에 이진검색을 이용하면 O(log n)의 실행시간이 걸리는데 연결리스트는 이에 비하면 실행시간이 더 오래 걸린다. 다만 배열이 정렬되지 않은 경우에는 연결리스트나 배열이나 O(n)로 같게 되기 때문에 나중에 효율적인 알고리즘을 짤 때 잘 생각해봐야 한다.

42. 2022.09.15 이번 주제는 연결리스트:트리 였다. 트리는 연결리스트를 기반으로 한 새로운 데이터 구조다. 트리에서의 노드의 연결은 2차원적인 구성이다. 각 노드들은 일정한 층에 속하고 다음 층의 노드들을 가리키는 포인터를 가지게 된다. 가장 높은 층에서 트리가 시작되는 노드를 루트라고 한다. 루트 노트는 다음 층의 노드를 가리키게 되는데 이를 자식 노드라 한다. 이번 강의에서 나온 트리는 이진 검색 트리인데 하나의 노드는 두개의 자식 노드를 가지고, 왼쪽 자식 노드는 자신의 값보다 작고, 오른쪽 자식 노드는 자신의 값보다 크다. 이런 구조의 트리는 이진 검색을 할 때 유리하다. 이진 검색 트리를 활용하게 된다면 검색 실행 시간과 노드 삽입시간이 O(log n)이 되므로 기본 연결 트리에 비해 실행 시간이 단축된다는 장점이 있지만 기본 연결 리스트에 비해 메모리를 많이차지하게 된다는 단점이 있다.

43. 2022.09.16 오늘은 해시 테이블에 대해 배웠다. 해시테이블은 연결 리스트의 배열이고, 각 값들은 '해시 함수'라는 맞춤형 함수를 통해 어떤 바구니에 담기는 지가 결정된다. 각 바구니에 담긴 값들은 그 바구니에서 새롭게 정의되는 연결리스트로 이어진다. 연결 리스트가 담긴 바구니가 여러개 있는 것이 연결 리스트의 배열, 즉 '해시 테이블'이 된다. 해시 함수가 이상적이라면, 각 바구니에는 단 하나의 값들만 담기게 될 것이고, 검색 시간은 O(1)이 된다. 작동이 잘 되지 않는 최악의 상황이라면, 단 하나의 바구니에 모든 값들이 담겨서 O(n)이 될 수도 있다. 해시 함수를 만들때는 최대한 많은 바구니를 만들기 때문에 거의 O(1)에 가깝다. 해시 함수는 어떻게 만들 수 있을 지가 생각해보기였는데 가능한 경우의 수를 다 생각해서 만들면 될 것 같다. 뭔가 내가 알고리즘을 구현해야 한다면 작게 동일한 작업을 반복하는 일이라면 재귀함수를 사용해 만들 것 같다. 댓글을 보니 충돌이 일어나지 않게 분류를 한다는 의견이 많았다.

44. 2022.09.17 오늘은 트라이에 대한 강의였다. 트라이는 트리 형태의 자료 구조이며, 각 노드가 배열로 이뤄졌다는 특징이 있다. 맨 처음 노드를 루트라고 부르고 이름을 저장한다고 쳤을 때 예를 들면 james라면 j배열에서 다음 노드는 알파벳 배열 a-z까지 가진 배열을 가지게 되고 이 배열 중 a의 자식 노드로 들어가 또 a-z로 이뤄진 배열을 가지게 된다 이 과정을 이름의 길이만큼 반복하게 된다. 이러한 트라이에서 값 검색하는데 걸리는 시간은 문자열의 길이에 한정된다. 트라이가 해시 테이블에 비해 가지는 장점과 단점에 대해 생각을 해보라는 주제가 나왔고, 굳이 해시 함수를 만들지 않아도 된다는 장점이 있을 것 같고, 단점으로는 역시 메모리를 많이 차지하게 된다는 점일 것 같다. 댓글에서는 탐색 속도가 빠르다는 장점이 있다는 내용이 많았다.