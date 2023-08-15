# 2023 0808

c언어 콘서트 37p
``` c
#include <stdio.h>

int main(void)
{
	printf("Hello World!");
		return 0;
}
```

c언어 콘서트 54p
``` c
#include <stdio.h>

int main(void)
{
	printf("Hello World!\n");
	printf("from ChulSoo\n");
		return 0;
}

```

c언어 콘서트 55p
```c
// 첫번째 프로그램 응용
#include <stdio.h>

int main(void)
{
	printf("3 x 1 = 3\n");
	printf("3 x 2 = 6\n");
	printf("3 x 3 = 9\n");
		return 0;
}
```

c언어 콘서트 56p

```c
// 두개의 숫자의 합을 계산하는 프로그램
#include <stdio.h>

int main(void)
{
	int x;
	int y;
	int sum;

	x = 100;
	y = 200;

	sum = x + y;
	printf("두수의 합 = %d\n", sum);
	
	return 0;
}
```

# 2023 0813

c언어 콘서트 44p

``` c
#include <stdio.h>

int main(void)
{
	printf("이름 : 홍길동\n");
	printf("나이 : 21살\n");
	printf("주소 : 서울 종로구 200번지");
	return 0;
}
```

c언어 콘서트 63p

``` c
//사용자로부터 입력받은 정수 2개의 합을 계산하여 출력
//비주얼 스튜디오 사용자라면 다음 문장이 필요
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int x; //첫번째 정수를 저장할 변수
	int y; //두번째 정수를 저장할 변수
	int sum; //2개의 정수 합을 저장할 변수

	printf("첫번째 숫자를 입력하시오:"); //입력 안내 메세지 출력
	scanf("%d", &x);         // 하나의 정수를 받아서 x에 저장

	printf("두번째 숫자를 입력하시오:"); //입력 안내 메세지 출력
	scanf("%d", &y);	 // 하나의 정수를 받아서 y에 저장

	sum = x + y;  //변수 2개 더한다.
	printf("두수의 합= %d \n", sum);	//sum의 값을 10진수 형태로 출력

	return 0;   // 0을 외부로 반환
}
```

c언어 콘서트 73p
```c
//비주얼 스튜디오 사용자라면 다음 문장이 필요
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int x; //첫번째 정수를 저장할 변수
	int y; //두번째 정수를 저장할 변수
	int result; //연산의 결과를 저장할 변수

	printf("첫번째 숫자를 입력하시오:"); //입력 안내 메세지 출력
	scanf("%d", &x);	 // 하나의 정수를 받아서 x에 저장

	printf("두번째 숫자를 입력하시오:"); //입력 안내 메세지 출력
	scanf("%d", &y);	 // 하나의 정수를 받아서 y에 저장

	result = x + y;	// 덧셈
	printf("두수의 합= %d \n", result);

	result = x - y;	// 뺄셈
	printf("두수의 차= %d \n", result);

	result = x * y;	// 곱셈
	printf("두수의 곱= %d \n", result);

	result = x / y;	// 나눗셈
	printf("두수의 몫= %d \n", result);

	return 0;
}
```

c언어 콘서트 74p
```c
//비주얼 스튜디오 사용자라면 다음 문장이 필요
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int a; //여행이 몇박인지 저장할 변수
	int b; //항공권 가격을 저장할 변수
	int c; // 호텔 1박 가격을 저장할 변수
	int d; // 하루에 필요한 용돈을 저장할 변수
	int result; //연산의 결과를 저장할 변수

	printf("여행은 몇박인가요?:"); //입력 안내 메세지 출력
	scanf("%d", &a);     // 하나의 정수를 받아서 a에 저장

	printf("항공권 가격:"); //입력 안내 메세지 출력
	scanf("%d", &b);  // 하나의 정수를 받아서 b에 저장

	printf("호텔 1박 가격:"); //입력 안내 메세지 출력
	scanf("%d", &c);  // 하나의 정수를 받아서 c에 저장

	printf("하루에 필요한 용돈:"); //입력 안내 메세지 출력
	scanf("%d", &d);     // 하나의 정수를 받아서 d에 저장

    
	result = b+(c)*a+(a+1)*d;  // 총여행비용= 항공권 가격+ (호텔1박가격)*박수+(박수+1)*용돈
	printf("총 여행 비용: %d ", result);

	
	return 0;
}
```

c언어 콘서트 75p
```c
//비주얼 스튜디오 사용자라면 다음 문장이 필요
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int x; //하나의 정수를 저장할 변수
	int y; //다른하나의 정수를 저장할 변수
	
	scanf("%d %d", &x, &y);
	printf("%d %d\n", y,x);

	return 0;
}
```

c언어 콘서트 77p
```c
#include <stdio.h>

int main(void)
{
	
	printf("#        #\n"); //8번 띄어쓰기
	printf("#        #\n"); //8번 띄어쓰기
	printf("#        #\n"); //8번 띄어쓰기
	printf("######    \n"); //
	printf("#        #\n"); //8번 띄어쓰기
	printf("#        #\n"); //8번 띄어쓰기
	printf("#        #\n"); //8번 띄어쓰기

	return 0;
}
```


# 2023 0816

c언어 콘서트 77p
```c
#include <stdio.h>

int main(void)
{
	
	printf("이름: 홍길동\n"); 
	printf("주소: 서울시 종로구\n");
	printf("전화번호: 111-2222\n");

	return 0;
}
```

c언어 콘서트 77p
```c
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	
	int price; //제품의 가격을 저장할 변수
	int a; //상품의 개수를 저장할 변수
	int sum; //제품의 합계를 저장할 변수

	printf("상품의 가격을 입력하시오:"); 
	scanf("%d", &price);

	printf("상품의 개수를 입력하시오:");
	scanf("%d", &a);

	sum = price * a;
	printf("총 가격은 %d 입니다.\n", sum);

	return 0;
}
```
c언어 콘서트 77p
```c
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	
	int age; //현제 나이
	int sum; //내년에 되는 나이

	printf("나이를 입력하시오: "); 
	scanf("%d", &age);

	sum = age +1;
	printf("내년이면 %d살이 되시는군요.\n", sum);

	return 0;
}
```
