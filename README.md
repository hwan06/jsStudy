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

## 6. 형변환
**자동형변환이란**
> "6" / "2" = 3 과 같이 문자열을 문자열로 나누었음에도 불구하고 정수형값이 반환된다.   
> 이처럼 자료형을 자동으로 변환해주는것.

**명시적형변환이란**
>String() Number() Boolean() 순서대로 문자열, 정수형, 참거짓   
>각각 괄호 안에 들어가는 값을 해당 자료형으로 변환한다.

**주의사항**   
><img src="https://github.com/hwan06/jsStudy/assets/114748934/ee98fd50-25a5-4547-bf44-a47ce802b19e.png" width="400" height="200"/>     
><img src="https://github.com/hwan06/jsStudy/assets/114748934/1f5403fe-2eb8-45cf-b2fd-ee8b29fce990.png" width="400" height="200"/>   

## 7. 동등연산자와 일치연산자
**동등연산자란**
> 등호(=)를 두개만 사용하는 방식으로 5 == 5 이런식으로 사용한다.   
> 하지만 5 == "5" 이 또한 true를 반환하기 때문에 문제가 있다.

**일치연산자란**
> 등호(=)를 세개를 사용하는 방식으로 5 === 5 이런식으로 사용한다.   
> 일치연산자는 5 === "5" 이를 false로 반환한다. 이처럼 일치연산자는 값의 자료형까지 구분해주는 연산자이다


