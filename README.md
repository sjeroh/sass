# SASS 

SASS 사용안함. SCSS를 사용한다.(좀 쉽게 변한 scss를 주로 사용)

![image](https://github.com/sjeroh/sass/assets/36749506/95a52303-866d-4035-9035-2e7f5736e79d)
- mscode에서 추가로 설치

# SCSS 컴파일
![image](https://github.com/sjeroh/sass/assets/36749506/e6807fe8-826b-4c3a-80cd-305e957fc1fd)


scss파일 -> ![image](https://github.com/sjeroh/sass/assets/36749506/240e714a-2f87-4cf0-b0f3-2d1517a2a68e)

css 만들어짐

# css 위치 변경

![image](https://github.com/sjeroh/sass/assets/36749506/db3eca3b-4ef3-40e3-aa83-d7341ee30940)

# savePath:null 이면 scss 파일과 같은 위치에 style.css가 생긴다.

![image](https://github.com/sjeroh/sass/assets/36749506/a9b631e4-5ba1-4da3-9aed-75dcf92dae0a)

![image](https://github.com/sjeroh/sass/assets/36749506/868ae9cb-0c39-4921-8a57-6f53feb4177f)

# ~은 style.scss를 의미, / 는 style.scss 가 있는 폴더

![image](https://github.com/sjeroh/sass/assets/36749506/f79a4754-cc32-4db1-b8d6-b326d0ca10a1)

# scss 파일이 있는 폴더의 상위 요소에 생성

![image](https://github.com/sjeroh/sass/assets/36749506/b5941a9b-088d-403e-b978-2c61a4d99921)



2. savePath 설정
./ = 현재 파일의 위치
../ 현재 파일의 부모 폴더
~/ 현재 작성중인 Scss 파일의 위치
여기서 ./ 과 ~/이 헷갈릴 수 있는데
접근순서가 다르다.

# 주석처리 방법
# // 주석처리 방법은 css로 컴파일 되지 않는다
# /**/ css로 컴파일된다.
![image](https://github.com/sjeroh/sass/assets/36749506/0d3af72f-b79e-4aed-bf71-c43fe610b5fa)

scss 에서는 //
/* */ 이주석은 css에 나온다.


# 변수만들기 --> $ 로 시작함 (영문, 숫자, - , _) 만 사용할 수 있음. 숫자로 시작 할 수 없음!
> 호이스팅 안됨 상단에 나오도록 해야함.
> 세미콜론을 변수 만들고 꼭 붙여줘야한다.

![image](https://github.com/sjeroh/sass/assets/36749506/150da50d-7707-4be5-9069-25a56b6fc8c4)
안에서 & 넣으면 상위요소를 말함.

![image](https://github.com/sjeroh/sass/assets/36749506/a3f06c72-b65c-4a44-a62d-054a7428fc48)

띄워쓰기 되니 &로  after는 선택해줘야함
![image](https://github.com/sjeroh/sass/assets/36749506/71ce2516-fc46-4118-af0a-7176f1b661af)

