# js기초 강의 정리
#### 강의링크: https://www.youtube.com/watch?v=KF6t61yuPCY

## 1. let과 const
>let: 선언 후 값을 바꿀수 있음.    
>const:  절대 바뀌지 않는 상수를 선언할 때 사용 (PI, 최댓값, 생일 등)    
>팀 프로젝트일 경우 대문자로 선언하는게 좋음. (다른 개발자에게 절댓값이라는걸 알려주기위함

## 2. 알아두면 좋은 변수 규칙
>1. 첫글자는 숫자가 될 수 없다. -> 1Grade (X)
>2. 예약어는 사용할 수 없다. -> let let = 99; (X)
>3. const를 사용할 때는 대문자로 선언한다. -> const PI = 3.14;
>4. 변수명은 쉽게 이해할 수 있도록 선언한다. -> let a = 1;(X) || let userNumber= 1;(O)

## 3. 자료형
**String**
>1. 따옴표, 작은 따옴표, 백틱(`)으로 감싸주면 String형   
>2. 백틱(`)으로 감싸줄 경우 문자열에 함수를 포함시킬 수 있음.    
>![image](https://github.com/hwan06/jsStudy/assets/114748934/db1212fb-95ba-4018-a285-ae9390edd70f)

**Integer**
>1. 사칙연산 가능(+ - / * %) 순서대로 더하기, 빼기, 나누기, 곱하기, 나머지
>2. 만약 n/0을 한다면 값은 무한(Infinity)임.
>3. 문자열을 수로 나눈다면 값은 NaN임. Not a Number

## 4. typeof함수
>자료의 자료형을 구하는 함수   
>개인 프로젝트일 경우 사용하지 않지만 팀프로젝트일 경우 자료형을 알기위해 많이 사용함.   
>![image](https://github.com/hwan06/jsStudy/assets/114748934/109eeff4-a402-4615-8508-b4ac331c2bb6)

## 5. alrt, prompt, confirm
>1. alrt: 사용자에게 알리기 위함. (비밀번호 틀림, 회원가입 필수 입력 등)
>2. prompt: 사용자에게 입력받기 위함. (나이, 이름 등)
>3. confirm: 사용자에게 확인받기 위함. (성인인증 등)

**사용 예시**
>![image](https://github.com/hwan06/jsStudy/assets/114748934/39764a51-8be4-4b3d-a6a0-2438d7d907d1)     
>![image](https://github.com/hwan06/jsStudy/assets/114748934/26b05db6-99c7-43a0-9203-7765389a5642)    
>![image](https://github.com/hwan06/jsStudy/assets/114748934/5dc196a0-053a-4027-8c68-0b58358aca90)

**사용 예시**   
>확인 선택시 true, 취소 선택시 false   
>![image](https://github.com/hwan06/jsStudy/assets/114748934/3b0f8966-b1c0-4ebc-a24a-1c538deeae99)   
>![image](https://github.com/hwan06/jsStudy/assets/114748934/03dc6c00-c527-4e86-a7b5-79453b53cdbb)





