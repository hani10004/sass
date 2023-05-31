 # sass 사용 거의 안함, scss를 사용 (사스라고 읽음)
![image](https://github.com/hani10004/sass/assets/129706997/b6f60a48-c329-4e2f-a30a-9caaf28dbab3)

--------------
 # scss 컴파일 
![image](https://github.com/hani10004/sass/assets/129706997/c870b8e4-690a-4e02-a5aa-4b72d81b88c9)

--------------
 # css 위치변경 
![image](https://github.com/hani10004/sass/assets/129706997/da8154b0-2b8b-4138-9f49-843f31f038c5)

--------------
  # savePath:null이면 scss파일과 같은 위치에 style.css가 생김 
![image](https://github.com/hani10004/sass/assets/129706997/7ad0fe93-936c-4c24-9a59-dc3c6ec9eafd)

--------------
# '~'은 style.scss를 의미, '/'는 style.scss가 있는 폴더
![image](https://github.com/hani10004/sass/assets/129706997/e7165610-cfa3-4c83-ad58-490d379ddca8)

--------------
 # scss파일이 있는 폴더의 상위요소에 생성 
![image](https://github.com/hani10004/sass/assets/129706997/64f1254e-01b7-4125-a9fb-ccfcc6c9a421)

--------------
# 주석처리방법 
## // : 라인주석처리는 css로 컴파일 되지 않는다
##  /* */ : 블록 주석처리는 css로 컴파일 됨 
![image](https://github.com/hani10004/sass/assets/129706997/5d81e5db-d5b3-48d3-9afd-795d12ff9f2f)

--------------
# 변수만들기 : $로 시작(영문, 숫자, -,_)만 사용가능 
![image](https://github.com/hani10004/sass/assets/129706997/cc652587-a5cf-42f9-8011-5cad18cdb40d)
![image](https://github.com/hani10004/sass/assets/129706997/b9421058-4f7f-4fbd-a92a-a8857060850e)

--------------
# Partials
  * Partials 의 파일명은 _ 로 시작하며
  * 불러들일때는 @import '파일명' 이때 파일명에 _ 는 포함시키지 않고, 확장명도 포함시키지 않는다.
  * Scc는 _ 로 시작하는 파일은 컴파일 하지 않는다 
  * ![image](https://github.com/hani10004/sass/assets/129706997/ebe203af-f407-4da9-ad71-dc4a24d64b5e)

--------------
# @import --> 변수가 중복될때는 아래의것이 적용된다
![image](https://github.com/hani10004/sass/assets/129706997/e8208bdd-8936-4a00-a32c-adac296f54c6)

--------------
# @use --> 변수이름이 같을 때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 "파일명.변수명"
![image](https://github.com/hani10004/sass/assets/129706997/3f7be0f9-c1e7-4eb7-b993-3e58dd5ed0ab)

--------------
#
https://github.com/understanding963852/sass/blob/main/README.md
--------------
#

--------------
#

--------------
