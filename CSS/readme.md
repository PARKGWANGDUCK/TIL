[2022-07-12]

--------------------------------------------------------------




--------------------------------------------------------------
# CSS란?
Cascading Style Sheets의 약자로 문서의 콘텐츠와 레이아웃, 글꼴 및 시각적 요소들로 표현되는 문서의 외관(디자인)을 분리하기 위한 목적으로 만들어졌다.

* #### CSS를 적용하는 방법으로는 크게 3가지가 있다. 

      * 1.Inline Style
      * 2.Interal Style
      * 3.external Style
      
* Inline Style
Inline Style이란, HTML 태그안에서 Style속성을 설정.

* Internal Style
Internal Style이란, HTML 문서 내의 head 태그에 Style 요소들을 정의.

* External Style
외부CSS파일을 링크해서 사용(CSS 파일을 생성해서 불러옴)

# CSS 기본 문법
![image](https://t1.daumcdn.net/cfile/tistory/270CCE4255509FCB34)
* 선택자는 보통 스타일링하고 싶은 HTML요소나 부여한 ID 혹은 class가 위치한다.
* 선언부에 여러개의 속성과 속성값이 있을때는 ;(세미콜론)으로 구분한다.
* 각각의 선언은 속성과 속성값을 :(콜론)으로 구분한다.

# CSS 우선순위
CSS는 기본적으로 선언된 순서에 따라 적용되지만 각종 선택자와 삽입 위치에 따라 우선순위가 달라질 수 있다.

## 선택자 우선순위
    *!important > 인라인 스타일 > 아이디 선택자 > 클래스/속성/가상 선택자 > 태그 선택자 > 전체 선택자
경쟁 규칙이 같은 선택자 그룹에 속해 있다면 선택자의 종류와 수에 따라 우선순위가 결정된다. 즉 높은 우선순위의 선택자를 더 많이 사용한 규칙이 이긴다.