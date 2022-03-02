# HTML, CSS, JavaScript

## HTML?
  - > 마크업 언어 <br> 
  내부 콘텐츠의 구조(골격)를 형성함.

## CSS?
  - > 스타일 시트 언어 <br>
  구조를 좀 더 보기 편하게 디자인을 입힘.

## JavaScript
  - > 프로그래밍 언어 <br>
  HTML, CSS 의 정적인 화면을 동적으로 만들어줌.

<br>
위의 삼위일체를 통해서 움직이며 보여지는 웹 환경을 만든다.

<br>

### - HTML 구조
  ```
  <!DOCTYPE html>
  <html>
    <head>
      <meta>
      <title></title>
    </head>
    <body>
    </body>
  </html>
  ```

  제일 상단의 !DOCTYPE html 은 html의 버전을,

  html 태그로 전체가 html임을 알리며, 내부에 head, body로 머리 몸통을 구성한다.<br>

  <br>

  - head
  
    head 태그는 title을 제외하고는 눈에 보이지 않으며 내부 정보에 대한 설정이나 설명을 담당한다.

  - body

    body 태그는 실제로 보여지는 태그이며 html의 골격이 나타나는 곳이며 요즘은 골격 형성 이후에 동적 화면 구성을 올리기 때문에 스크립트가 마지막에 오는 경우가 많다.

<br>

## 기본 문법
<br>

1. 요소
   
   요소는 시작 태그(여는 태그), 종료 태그(닫는 태그), 그 안의 내용으로 구성된다.

   ![요소의 형태](https://poiemaweb.com/img/tag.png)

    딱히 대소문자를 구분하지는 않지만 소문자를 추천하는 편이다.

    <br>

    1.1 요소의 중첩

    각 요소들 내에 다른 요소들이 배치될 수 있으며 그 배치 관계에 따라서 부모 자식의 관계가 생기며 그 포함관계에 따라서 정보를 구조화 할 수 있다.

    각 들여쓰기가 같은 위치면 형제관계
    다른 위치면 부모의 관계 혹은 자손 관계를 형성한다.

    ```
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="UTF-8">
        <title>Document</title>
      </head>
      <body>
        <header>
          <h1>제목</h1>
        </header>
        <footer>
        </footer>
      </body>
    </html>
    ```

    <br>

    1.2 빈 요소

    빈 요소는 그 자체만으로 완성되며 내용이 필요 없는 태그들을 말한다. 내부에 내용이 필요없기 때문에 닫는 태그도 필요없다.

    빈 요소

    - link
    - br
    - hr
    - input
    - meta
    - img
  
    <br>
    
    위의 태그들이 대표적인 빈 요소다.

    <br>

    1.3 어트리뷰트

    어트리뷰트는 각 요소들의 성질이나 특징을 정의한다. 추가적 정보를 주며 여는 태그에 위치하고, 어트리뷰트 명 = "값" 으로 주로 쌍을 이룬다.

    ![태그명](https://poiemaweb.com/img/html-attribute.png)

    - 글로벌 어트리뷰트
    
      글로벌 어트리뷰트는 모든 html 요소가 공통적으로 사용할 수 있는 어트리뷰트다.

      글로벌 어트리뷰트

      - id
      - class
      - lang
      - style

      <br>
      
      등이 대표적이다.
       
      단, 글로벌이 있으면 글로벌이 아닌 어트리뷰트들도 존재한다.
      그 속성들은 특정 태그에서만 유효한 속성이다.