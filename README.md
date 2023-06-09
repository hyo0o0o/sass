# sass 사용안함. scss를 사용한다. scss-->샤스라고 읽음 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/dcc16513-559a-49dd-b6f6-31f2771e5c28)

----------------------------------------------------------

# scss 컴파일 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/23c40178-a6e7-4ac9-9729-09c454a5ac01)

----------------------------------------------------------

# css 위치변경 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/601529ba-dddb-4b02-81fe-86d63e3ea693)

----------------------------------------------------------

# savePath : null이면 scss파일과 같은 위치에 style.css가 생긴다 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/298d7aee-c0ae-4b5d-a1be-e4ddd626aece)

----------------------------------------------------------

# ~은 style.scss를  의미, / style.scss가 있는 폴더 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/320cbda3-dbe7-42f3-8c6c-9adc733e1010)
![image](https://github.com/hyo0o0o/sass/assets/129016961/6a3de466-7437-4177-b3cc-bf24667cf0bb)

----------------------------------------------------------

# scss파일이 있는 폴더의 상위요소에 생성 🎀

![image](https://github.com/hyo0o0o/sass/assets/129016961/84fd88a6-d470-49fa-bb1e-2c9d5fca1df0)
![image](https://github.com/hyo0o0o/sass/assets/129016961/06cac85b-35c9-45a3-baef-77ddd01ae3ad)

----------------------------------------------------------

# 주석처리 방법
# //주석처리 방법은 css로 컴파일되지 않는다.
# /* */ 주석처리방법은 css로 컴파일 된다.

![image](https://github.com/hyo0o0o/sass/assets/129016961/11cac9ea-4e66-4df0-96c7-5741d6eb54ad)

----------------------------------------------------------

# 변수 만들기 --> $로 시작함, (영문, 숫자, -, _)민 사용할 수 있다. ✔️숫자로 시작할 수 없음

![image](https://github.com/hyo0o0o/sass/assets/129016961/6eb40202-ccf2-4093-ae52-a5dc4a6f2bea)
![image](https://github.com/hyo0o0o/sass/assets/129016961/df8a8d23-2c8d-41e5-83a5-c3cac5ffe041)

----------------------------------------------------------

# Partials(파샬)
  -- 관련된 것 끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능
  
  * Partials의 파일명은 반드시 _(언더바)로 시작되어야 한다.
  * 불러들일때는 @import '파일명' 이때 파일명에 _(언더바)는 모함시키지 않고, 확장명도 포함시키지 않는다.


  ✔️ Scss는 _(언더바)로 시작하는 파일은 컴파일 하지 않는다.
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/a35c2698-07d7-42f9-910b-db09af45cf44)
  
  # @import --> 변수가 중복될때는 아래의 것이 적용된다. 🌐
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/c1131f14-8250-45c6-a2bb-66f1fe98a978)

  
  # @use --> 변수이름이 같을 때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 (파일명.변수명)이라 적어야한다. 🗂️
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/38e76a0c-3f2c-4628-a62b-203c365cc5b4)

  # as 뒤에 별명을 붙여서 사용할 수 있다. 🗂️
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/c9d1edcc-90ed-4c95-8e10-81175b4a59a4)

  # forward 는 파샬을 묶어줌 style.scss에서는 _index.scss를 호출하여 사용함 🗂️
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/25716980-2b1f-499d-ba63-a0b716084777)

  # *(와일드카드)를 붙이면 이름을 생략할 수 있다. ✡️
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/87c75de4-87e3-4ca5-b6fe-efa1e741810a)
  
  
  # 전역변수와 지역변수
  
  ![image](https://github.com/hyo0o0o/sass/assets/129016961/9901d164-8a88-4412-a2f5-ae8f74d47661)



